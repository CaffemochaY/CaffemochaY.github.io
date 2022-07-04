# かんしくん 設定

- [setting.txt](#settingtxt)
- [genexo.lua](#genexolua)

`setting.txt` から `genexo.lua` に値を持っていっているので、 `genexo.lua` はそこまでいじらない方が良いと思う

## setting.txt

```ini

# 文字コード : UTF-8

# [wiki](https://github.com/oov/forcepser/wiki/設定について(0.1beta15以降))
# [かんしくん設定ファイル作成ツール](https://oov.github.io/forcepser/)

# -- グローバルセクション / 全体の設定 --

  basedir = 'D:\_exported_voices'
  deletetext = false
  destdir = '%PROJECTDIR%\voices'
  filemove = 'move'
  freshness = 60.0
  padding = 650 # (ms)
  sort = 'name'
  sortdelay = 2.0


# -- [[rule]] セクション / 個別の設定 --

# VOICEVOX

  # VOICEVOX 四国めたん

    [[rule]] # VOICEVOX 四国めたん（ノーマル）
      layer = 1
      filere = '^.+?_四国めたん（ノーマル）_.*?\.[Ww][Aa][Vv]$'
      dir = '%BASEDIR%\VOICEVOX'
      encoding = 'sjis'
      modifier = '''
        filename = "V" .. filename
        execute("C:\\ffmpeg\\bin\\ffmpeg.exe", "-i", "%BEFORE%", "-af", "volume=5.7dB", "%AFTER%")
      '''

    [[rule]] # VOICEVOX 四国めたん（あまあま）
      layer = 1
      filere = '^.+?_四国めたん（あまあま）_.*?\.[Ww][Aa][Vv]$'
      dir = '%BASEDIR%\VOICEVOX'
      encoding = 'sjis'
      modifier = '''
        filename = "V" .. filename
        execute("C:\\ffmpeg\\bin\\ffmpeg.exe", "-i", "%BEFORE%", "-af", "volume=5.0dB", "%AFTER%")
      '''

    [[rule]] # VOICEVOX 四国めたん（ツンツン）
      layer = 1
      filere = '^.+?_四国めたん（ツンツン）_.*?\.[Ww][Aa][Vv]$'
      dir = '%BASEDIR%\VOICEVOX'
      encoding = 'sjis'
      modifier = '''
        filename = "V" .. filename
        execute("C:\\ffmpeg\\bin\\ffmpeg.exe", "-i", "%BEFORE%", "-af", "volume=7.0dB", "%AFTER%")
      '''

    [[rule]] # VOICEVOX 四国めたん（セクシー）
      layer = 1
      filere = '^.+?_四国めたん（セクシー）_.*?\.[Ww][Aa][Vv]$'
      dir = '%BASEDIR%\VOICEVOX'
      encoding = 'sjis'
      modifier = '''
        filename = "V" .. filename
        execute("C:\\ffmpeg\\bin\\ffmpeg.exe", "-i", "%BEFORE%", "-af", "volume=4.8dB", "%AFTER%")
      '''

  # VOICEVOX ずんだもん

    [[rule]] # VOICEVOX ずんだもん（ノーマル）
      layer = 2
      filere = '^.+?_ずんだもん（ノーマル）_.*?\.[Ww][Aa][Vv]$'
      dir = '%BASEDIR%\VOICEVOX'
      encoding = 'sjis'
      modifier = '''
        filename = "V" .. filename
        execute("C:\\ffmpeg\\bin\\ffmpeg.exe", "-i", "%BEFORE%", "-af", "volume=8.6dB", "%AFTER%")
      '''

    [[rule]] # VOICEVOX ずんだもん（あまあま）
      layer = 2
      filere = '^.+?_ずんだもん（あまあま）_.*?\.[Ww][Aa][Vv]$'
      dir = '%BASEDIR%\VOICEVOX'
      encoding = 'sjis'
      modifier = '''
        filename = "V" .. filename
        execute("C:\\ffmpeg\\bin\\ffmpeg.exe", "-i", "%BEFORE%", "-af", "volume=8.3dB", "%AFTER%")
      '''

    [[rule]] # VOICEVOX ずんだもん（ツンツン）
      layer = 2
      filere = '^.+?_ずんだもん（ツンツン）_.*?\.[Ww][Aa][Vv]$'
      dir = '%BASEDIR%\VOICEVOX'
      encoding = 'sjis'
      modifier = '''
        filename = "V" .. filename
        execute("C:\\ffmpeg\\bin\\ffmpeg.exe", "-i", "%BEFORE%", "-af", "volume=7.8dB", "%AFTER%")
      '''

    [[rule]] # VOICEVOX ずんだもん（セクシー）
      layer = 2
      filere = '^.+?_ずんだもん（セクシー）_.*?\.[Ww][Aa][Vv]$'
      dir = '%BASEDIR%\VOICEVOX'
      encoding = 'sjis'
      modifier = '''
        filename = "V" .. filename
        execute("C:\\ffmpeg\\bin\\ffmpeg.exe", "-i", "%BEFORE%", "-af", "volume=8.1dB", "%AFTER%")
      '''

  # VOICEVOX 春日部つむぎ

    [[rule]] # VOICEVOX 春日部つむぎ（ノーマル）
      layer = 3
      filere = '^.+?_春日部つむぎ（ノーマル）_.*?\.[Ww][Aa][Vv]$'
      dir = '%BASEDIR%\VOICEVOX'
      encoding = 'sjis'
      modifier = '''
        filename = "V" .. filename
        execute("C:\\ffmpeg\\bin\\ffmpeg.exe", "-i", "%BEFORE%", "-af", "volume=7.9dB", "%AFTER%")
      '''

  # VOICEVOX 雨晴はう（ノーマル）

    [[rule]] # VOICEVOX 雨晴はう（ノーマル）
      layer = 4
      filere = '^.+?_雨晴はう（ノーマル）_.*?\.[Ww][Aa][Vv]$'
      dir = '%BASEDIR%\VOICEVOX'
      encoding = 'sjis'
      modifier = '''
        filename = "V" .. filename
        execute("C:\\ffmpeg\\bin\\ffmpeg.exe", "-i", "%BEFORE%", "-af", "volume=7.2dB", "%AFTER%")
      '''

  # VOICEVOX 波音リツ（ノーマル）

    [[rule]] # VOICEVOX 波音リツ（ノーマル）
      layer = 5
      filere = '^.+?_波音リツ（ノーマル）_.*?\.[Ww][Aa][Vv]$'
      dir = '%BASEDIR%\VOICEVOX'
      encoding = 'sjis'
      modifier = '''
        filename = "V" .. filename
        execute("C:\\ffmpeg\\bin\\ffmpeg.exe", "-i", "%BEFORE%", "-af", "volume=8.2dB", "%AFTER%")
      '''

  # VOICEVOX 玄野武宏（ノーマル）

    [[rule]] # VOICEVOX 玄野武宏（ノーマル）
      layer = 6
      filere = '^.+?_玄野武宏（ノーマル）_.*?\.[Ww][Aa][Vv]$'
      dir = '%BASEDIR%\VOICEVOX'
      encoding = 'sjis'
      modifier = '''
        filename = "V" .. filename
        execute("C:\\ffmpeg\\bin\\ffmpeg.exe", "-i", "%BEFORE%", "-af", "volume=5.8dB", "%AFTER%")
      '''

  # VOICEVOX 白上虎太郎（ノーマル）

    [[rule]] # VOICEVOX 白上虎太郎（ノーマル）
      layer = 7
      filere = '^.+?_白上虎太郎（ノーマル）_.*?\.[Ww][Aa][Vv]$'
      dir = '%BASEDIR%\VOICEVOX'
      encoding = 'sjis'
      modifier = '''
        filename = "V" .. filename
        execute("C:\\ffmpeg\\bin\\ffmpeg.exe", "-i", "%BEFORE%", "-af", "volume=4.5dB", "%AFTER%")
      '''

  # VOICEVOX 青山龍星（ノーマル）

    [[rule]] # VOICEVOX 青山龍星（ノーマル）
      layer = 8
      filere = '^.+?_青山龍星（ノーマル）_.*?\.[Ww][Aa][Vv]$'
      dir = '%BASEDIR%\VOICEVOX'
      encoding = 'sjis'
      modifier = '''
        filename = "V" .. filename
        execute("C:\\ffmpeg\\bin\\ffmpeg.exe", "-i", "%BEFORE%", "-af", "volume=2.0dB", "%AFTER%")
      '''

  # VOICEVOX 冥鳴ひまり（ノーマル）

    [[rule]] # VOICEVOX 冥鳴ひまり（ノーマル）
      layer = 9
      filere = '^.+?_冥鳴ひまり（ノーマル）_.*?\.[Ww][Aa][Vv]$'
      dir = '%BASEDIR%\VOICEVOX'
      encoding = 'sjis'
      modifier = '''
        filename = "V" .. filename
        execute("C:\\ffmpeg\\bin\\ffmpeg.exe", "-i", "%BEFORE%", "-af", "volume=6.7dB", "%AFTER%")
      '''

  # VOICEVOX 九州そら

    [[rule]] # VOICEVOX 九州そら（ノーマル）
      layer = 10
      filere = '^.+?_九州そら（ノーマル）_.*?\.[Ww][Aa][Vv]$'
      dir = '%BASEDIR%\VOICEVOX'
      encoding = 'sjis'
      modifier = '''
        filename = "V" .. filename
        execute("C:\\ffmpeg\\bin\\ffmpeg.exe", "-i", "%BEFORE%", "-af", "volume=7.0dB", "%AFTER%")
      '''

    [[rule]] # VOICEVOX 九州そら（あまあま）
      layer = 10
      filere = '^.+?_九州そら（あまあま）_.*?\.[Ww][Aa][Vv]$'
      dir = '%BASEDIR%\VOICEVOX'
      encoding = 'sjis'
      modifier = '''
        filename = "V" .. filename
        execute("C:\\ffmpeg\\bin\\ffmpeg.exe", "-i", "%BEFORE%", "-af", "volume=6.9dB", "%AFTER%")
      '''

    [[rule]] # VOICEVOX 九州そら（ツンツン）
      layer = 10
      filere = '^.+?_九州そら（ツンツン）_.*?\.[Ww][Aa][Vv]$'
      dir = '%BASEDIR%\VOICEVOX'
      encoding = 'sjis'
      modifier = '''
        filename = "V" .. filename
        execute("C:\\ffmpeg\\bin\\ffmpeg.exe", "-i", "%BEFORE%", "-af", "volume=7.4dB", "%AFTER%")
      '''

    [[rule]] # VOICEVOX 九州そら（セクシー）
      layer = 10
      filere = '^.+?_九州そら（セクシー）_.*?\.[Ww][Aa][Vv]$'
      dir = '%BASEDIR%\VOICEVOX'
      encoding = 'sjis'
      modifier = '''
        filename = "V" .. filename
        execute("C:\\ffmpeg\\bin\\ffmpeg.exe", "-i", "%BEFORE%", "-af", "volume=6.7dB", "%AFTER%")
      '''

    [[rule]] # VOICEVOX 九州そら（ささやき）
      layer = 10
      filere = '^.+?_九州そら（ささやき）_.*?\.[Ww][Aa][Vv]$'
      dir = '%BASEDIR%\VOICEVOX'
      encoding = 'sjis'
      modifier = '''
        filename = "V" .. filename
        execute("C:\\ffmpeg\\bin\\ffmpeg.exe", "-i", "%BEFORE%", "-af", "volume=7.0dB", "%AFTER%")
      '''

# COEIROINK

  # COEIROINK つくよみちゃん

    [[rule]] # COEIROINK つくよみちゃん（れいせい）
      layer = 11
      filere = '^.+?_つくよみちゃん（れいせい）_.*?\.[Ww][Aa][Vv]$'
      dir = '%BASEDIR%\COEIROINK'
      encoding = 'sjis'
      modifier = '''
        filename = "C" .. filename
        execute("C:\\ffmpeg\\bin\\ffmpeg.exe", "-i", "%BEFORE%", "-af", "volume=0.3dB", "%AFTER%")
      '''

    [[rule]] # COEIROINK つくよみちゃん（おしとやか）
      layer = 11
      filere = '^.+?_つくよみちゃん（おしとやか）_.*?\.[Ww][Aa][Vv]$'
      dir = '%BASEDIR%\COEIROINK'
      encoding = 'sjis'
      modifier = '''
        filename = "C" .. filename
        execute("C:\\ffmpeg\\bin\\ffmpeg.exe", "-i", "%BEFORE%", "-af", "volume=1.0dB", "%AFTER%")
      '''

    [[rule]] # COEIROINK つくよみちゃん（げんき）
      layer = 11
      filere = '^.+?_つくよみちゃん（げんき）_.*?\.[Ww][Aa][Vv]$'
      dir = '%BASEDIR%\COEIROINK'
      encoding = 'sjis'
      modifier = '''
        filename = "C" .. filename
        execute("C:\\ffmpeg\\bin\\ffmpeg.exe", "-i", "%BEFORE%", "-af", "volume=-1.9dB", "%AFTER%")
      '''

  # COEIROINK MANA

    [[rule]] # COEIROINK MANA（のーまる）
      layer = 12
      filere = '^.+?_MANA（のーまる）_.*?\.[Ww][Aa][Vv]$'
      dir = '%BASEDIR%\COEIROINK'
      encoding = 'sjis'
      modifier = '''
        filename = "C" .. filename
        execute("C:\\ffmpeg\\bin\\ffmpeg.exe", "-i", "%BEFORE%", "-af", "volume=-1.0dB", "%AFTER%")
      '''

    [[rule]] # COEIROINK MANA（いっしょうけんめい）
      layer = 12
      filere = '^.+?_MANA（いっしょうけんめい）_.*?\.[Ww][Aa][Vv]$'
      dir = '%BASEDIR%\COEIROINK'
      encoding = 'sjis'
      modifier = '''
        filename = "C" .. filename
        execute("C:\\ffmpeg\\bin\\ffmpeg.exe", "-i", "%BEFORE%", "-af", "volume=-1.2dB", "%AFTER%")
      '''

  # COEIROINK おふとんP

    [[rule]] # COEIROINK おふとんP（のーまる）
      layer = 13
      filere = '^.+?_おふとんP（のーまる）_.*?\.[Ww][Aa][Vv]$'
      dir = '%BASEDIR%\COEIROINK'
      encoding = 'sjis'
      modifier = '''
        filename = "C" .. filename
        execute("C:\\ffmpeg\\bin\\ffmpeg.exe", "-i", "%BEFORE%", "-af", "volume=0.3dB", "%AFTER%")
      '''

    [[rule]] # COEIROINK おふとんP（ナレーション）
      layer = 13
      filere = '^.+?_おふとんP（ナレーション）_.*?\.[Ww][Aa][Vv]$'
      dir = '%BASEDIR%\COEIROINK'
      encoding = 'sjis'
      modifier = '''
        filename = "C" .. filename
        execute("C:\\ffmpeg\\bin\\ffmpeg.exe", "-i", "%BEFORE%", "-af", "volume=1.2dB", "%AFTER%")
      '''

  # COEIROINK ディアちゃん

    [[rule]] # COEIROINK ディアちゃん（のーまる）
      layer = 14
      filere = '^.+?_ディアちゃん(?:|（.+?）)_.*?\.[Ww][Aa][Vv]$'
      dir = '%BASEDIR%\COEIROINK'
      encoding = 'sjis'
      modifier = '''
        filename = "C" .. filename
        execute("C:\\ffmpeg\\bin\\ffmpeg.exe", "-i", "%BEFORE%", "-af", "volume=-0.1dB", "%AFTER%")
      '''

  # COEIROINK アルマちゃん

    [[rule]] # COEIROINK アルマちゃん（のーまる）
      layer = 15
      filere = '^.+?_アルマちゃん(?:|（.+?）)_.*?\.[Ww][Aa][Vv]$'
      dir = '%BASEDIR%\COEIROINK'
      encoding = 'sjis'
      modifier = '''
        filename = "C" .. filename
        execute("C:\\ffmpeg\\bin\\ffmpeg.exe", "-i", "%BEFORE%", "-af", "volume=-1.8dB", "%AFTER%")
      '''

# A.I.VOICE

  [[rule]] # A.I.VOICE 結月 ゆかり
    layer = 16
    filere = '^.+?_結月 ゆかり(?:| - .+?)_.*?\.[Ww][Aa][Vv]$'
    dir = '%BASEDIR%\AIVOICE'
    encoding = 'sjis'
    modifier = '''
      filename = "A" .. filename
    '''

  [[rule]] # A.I.VOICE 結月 ゆかり（雫）
    layer = 17
    filere = '^.+?_結月 ゆかり（雫）(?:| - .+?)_.*?\.[Ww][Aa][Vv]$'
    dir = '%BASEDIR%\AIVOICE'
    encoding = 'sjis'
    modifier = '''
      filename = "A" .. filename
    '''

  [[rule]] # A.I.VOICE 琴葉 茜
    layer = 18
    filere = '^.+?_琴葉 茜(?:| - .+?)_.*?\.[Ww][Aa][Vv]$'
    dir = '%BASEDIR%\AIVOICE'
    encoding = 'sjis'
    modifier = '''
      filename = "A" .. filename
    '''

  [[rule]] # A.I.VOICE 琴葉 茜（蕾）
    layer = 19
    filere = '^.+?_琴葉 茜（蕾）(?:| - .+?)_.*?\.[Ww][Aa][Vv]$'
    dir = '%BASEDIR%\AIVOICE'
    encoding = 'sjis'
    modifier = '''
      filename = "A" .. filename
    '''

  [[rule]] # A.I.VOICE 琴葉 葵
    layer = 20
    filere = '^.+?_琴葉 葵(?:| - .+?)_.*?\.[Ww][Aa][Vv]$'
    dir = '%BASEDIR%\AIVOICE'
    encoding = 'sjis'
    modifier = '''
      filename = "A" .. filename
    '''

  [[rule]] # A.I.VOICE 琴葉 葵（蕾）
    layer = 21
    filere = '^.+?_琴葉 葵（蕾）(?:| - .+?)_.*?\.[Ww][Aa][Vv]$'
    dir = '%BASEDIR%\AIVOICE'
    encoding = 'sjis'
    modifier = '''
      filename = "A" .. filename
    '''

  [[rule]] # A.I.VOICE 紲星 あかり
    layer = 22
    filere = '^.+?_紲星 あかり(?:| - .+?)_.*?\.[Ww][Aa][Vv]$'
    dir = '%BASEDIR%\AIVOICE'
    encoding = 'sjis'
    modifier = '''
      filename = "A" .. filename
    '''

  [[rule]] # A.I.VOICE 紲星 あかり（蕾）
    layer = 23
    filere = '^.+?_紲星 あかり（蕾）(?:| - .+?)_.*?\.[Ww][Aa][Vv]$'
    dir = '%BASEDIR%\AIVOICE'
    encoding = 'sjis'
    modifier = '''
      filename = "A" .. filename
    '''

  # CoeFont

  [[rule]] # CoeFont アリアル
    layer = 24
    filere = '^.+?_アリアル.*?_.*?\.[Ww][Aa][Vv]$'
    dir = 'C:\Users\caffemocha\Downloads'
    encoding = 'utf8'
    modifier = '''
      filename = "F" .. filename
    '''

  [[rule]] # CoeFont ミリアル
    layer = 25
    filere = '^.+?_ミリアル.*?_.*?\.[Ww][Aa][Vv]$'
    dir = 'C:\Users\caffemocha\Downloads'
    encoding = 'utf8'
    modifier = '''
      filename = "F" .. filename
    '''

```

## genexo.lua

```lua

local P = {}

function P.gen2(proj, file, text, rule)
  local ai = getaudioinfo(file)
  local length = math.ceil(ai.samples / ai.samplerate * proj.video_rate / proj.video_scale)
  local lpp = math.ceil((ai.samples / ai.samplerate + rule.padding * 0.001) * proj.video_rate * proj.video_scale)
  local mexo = [[
[exedit]
width=]] .. proj.width .. "\r\n" .. [[
height=]] .. proj.height .. "\r\n" .. [[
rate=]] .. proj.video_rate .. "\r\n" .. [[
scale=]] .. proj.video_scale .. "\r\n" .. [[
length=]] .. lpp .. "\r\n" .. [[
audio_rate=]] .. proj.audio_rate .. "\r\n" .. [[
audio_ch=]] .. proj.audio_ch .. "\r\n" .. [[
[0]
start=1
end=]] .. length .. "\r\n" .. [[
layer=1
group=1
overlay=1
audio=1
[0.0]
_name=音声ファイル
再生位置=0.00
再生速度=100.0
ループ再生=0
動画ファイルと連携=0
file=]] .. file .. "\r\n" .. [[
[0.1]
_name=標準再生
音量=100.0
左右=0.0
[1]
start=1
end=]] .. lpp .. "\r\n" .. [[
layer=2
group=1
overlay=1
camera=0
[1.0]
_name=テキスト
サイズ=1
表示速度=0.0
文字毎に個別オブジェクト=0
移動座標上に表示する=0
自動スクロール=0
B=0
I=0
type=0
autoadjust=0
soft=0
monospace=0
align=4
spacing_x=0
spacing_y=0
precision=0
color=ffffff
color2=000000
font=MS UI Gothic
text=]] .. toexostring('<?s=[==[\r\n' .. text .. '\r\n]==];require("PSDToolKit").prep.init({ls_mgl=0,ls_mgr=0,st_mgl=0,st_mgr=0,sl_mgl=0,sl_mgr=0,},obj,s)?>') .. "\r\n" .. [[
[1.1]
_name=アニメーション効果
track0=0
track1=0
track2=0
track3=0
check0=0
type=0
filter=2
name=口パク準備@PSDToolKit
param=file="]] .. string.gsub(file, "\\", "\\\\") .. "\"" .. "\r\n" .. [[
[1.2]
_name=標準描画
X=0.0
Y=0.0
Z=0.0
拡大率=100.00
透明度=0.0
回転=0.00
blend=0
]]

  return tosjis(mexo), lpp
end

return P


```
