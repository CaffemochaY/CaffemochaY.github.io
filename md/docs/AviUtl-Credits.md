# AviUtl-Credits

## 本体

- [AviUtlのお部屋](http://spring-fragrance.mints.ne.jp/aviutl/)
  - `AviUtl ver.1.10`
  - `拡張編集 ver.0.92`

## LuaJIT

- [LuaJIT](http://luajit.org/)からDLしてビルドする
- もしくはビルドしてくれている[ここ](https://scrapbox.io/ePi5131/LuaJIT)からDL
  - `LuaJIT-2.1.0-beta3`

## plugins

### in-out

- [x264guiEx](https://github.com/rigaya/x264guiEx)
  - `x264guiEx 3.09`
- [L-smash Works(Mr-Ojii版)](https://github.com/Mr-Ojii/L-SMASH-Works-Auto-Builds)
  - `L-smash Works Mr-Ojii r1086`
- [ffmpegOut](https://github.com/rigaya/ffmpegOut)
  - `ffmpegOut v1.01`
  - [FFmpeg](https://ffmpeg.org/)
    - `FFmpeg v5.0`
  - [ffmpegOut stg置き場](https://scrapbox.io/Mr-Ojii/ffmpegOut_stg%E7%BD%AE%E3%81%8D%E5%A0%B4)

### 必須枠

- [patch.aul](https://github.com/ePi5131/patch.aul)
  - `patch.aul r21`
    - <details><summary>r21-json-setting</summary>

      ```json
      {
        "console" : {
          "visible" : true,
          "rect" : [ -8, 499, 1425, 1047 ]
        },
        "theme_cc" : {
          "layer" : {
            "height_large" : 27,
            "height_medium" : 23,
            "height_small" : 19,
            "link_col" : "4040c0",
            "clipping_col" : "c04040",
            "lock_col" : [ "000000", "c04040" ],
            "hide_alpha" : 0.850000
          },
          "object" : {
            "media_col" : [ "10206c", "1830c0", "4080ff" ],
            "mfilter_col" : [ "106c10", "18c018", "40f040" ],
            "audio_col" : [ "6c1018", "c01820", "f83040" ],
            "afilter_col" : [ "6c6c10", "c0c020", "d8d840" ],
            "control_col" : [ "106c6c", "18c0c0", "40d8d8" ],
            "inactive_col" : [ "606060", "808080", "909090" ],
            "clipping_col" : "c04040",
            "clipping_height" : -3,
            "midpt_size" : [ 4, 3, 3 ],
            "name_col" : [ "ffffff", "a0a0a0" ]
          },
          "timeline" : {
            "scale_col" : [ "60a0ff", "204080" ],
            "bpm_grid_col" : [ "646464", "a0a0a0" ]
          }
        },
        "switch" : {
          "access_key" : false,
          "exo_aviutl_filter" : true,
          "exo_track_minusval" : true,
          "exo_sceneidx" : true,
          "exo_trackparam" : true,
          "exo_specialcolorconv" : true,
          "text_op_size" : true,
          "ignore_media_param_reset" : false,
          "theme_cc" : true,
          "exeditwindow_sizing" : true,
          "settingdialog_move" : true,
          "undo" : true,
          "undo.redo" : true,
          "undo.redo.shift" : false,
          "console" : true,
          "console.escape" : true,
          "console.input" : false,
          "console.debug_string" : true,
          "console.debug_string.time" : true,
          "lua" : true,
          "lua.env" : false,
          "lua.rand" : true,
          "lua.randex" : true,
          "lua.getvalue" : true,
          "lua.path" : true,
          "fast" : true,
          "fast.cl" : true,
          "fast.exeditwindow" : true,
          "fast.exeditwindow.step" : 0,
          "fast.settingdialog" : true,
          "fast.radiationalblur" : true,
          "fast.polortransform" : true
        }
      }
      ```

      </details>
  - `patch.aul r32`
    - <details><summary>r32-json-setting</summary>

      ```json

      {
        "console" : {
          "visible" : false
        },
        "theme_cc" : {
          "layer" : {
            "height_large" : 27,
            "height_medium" : 23,
            "height_small" : 19,
            "link_col" : "4040c0",
            "clipping_col" : "c04040",
            "lock_col" : [ "000000", "c04040" ],
            "hide_alpha" : 0.850000
          },
          "object" : {
            "media_col" : [ "10206c", "1830c0", "4080ff" ],
            "mfilter_col" : [ "106c10", "18c018", "40f040" ],
            "audio_col" : [ "6c1018", "c01820", "f83040" ],
            "afilter_col" : [ "6c6c10", "c0c020", "d8d840" ],
            "control_col" : [ "106c6c", "18c0c0", "40d8d8" ],
            "inactive_col" : [ "606060", "808080", "909090" ],
            "clipping_col" : "c04040",
            "clipping_height" : -3,
            "midpt_size" : [ 4, 3, 3 ],
            "name_col" : [ "ffffff", "a0a0a0" ]
          },
          "timeline" : {
            "scale_col" : [ "60a0ff", "204080" ],
            "bpm_grid_col" : [ "646464", "a0a0a0" ]
          }
        },
        "redo" : {
          "shift" : false
        },
        "fast_exeditwindow" : {
          "step" : 0
        },
        "fast_text" : {
          "release_time" : 120
        },
        "switch" : {
          "access_key" : false,
          "exo_aviutlfilter" : true,
          "exo_sceneidx" : true,
          "exo_trackparam" : true,
          "exo_track_minusval" : true,
          "exo_specialcolorconv" : true,
          "tra_aviutlfilter" : true,
          "text_op_size" : true,
          "ignore_media_param_reset" : false,
          "theme_cc" : true,
          "exeditwindow_sizing" : true,
          "settingdialog_move" : true,
          "undo" : true,
          "undo.redo" : true,
          "console" : true,
          "console.escape" : true,
          "console.input" : false,
          "console.debug_string" : true,
          "console.debug_string.time" : true,
          "lua" : true,
          "lua.env" : false,
          "lua.path" : true,
          "lua.getvalue" : true,
          "lua.rand" : true,
          "lua.randex" : true,
          "fast" : true,
          "fast.exeditwindow" : true,
          "fast_settingdialog" : true,
          "fast.text" : true,
          "fast.cl" : true,
          "fast.radiationalblur" : true,
          "fast.polortransform" : true,
          "fast.flash" : true
        }
      }

      ```

      </details>
- [InputPipePlugin](https://www.nicovideo.jp/watch/sm35585310)
  - `InputPipePlugin v1.8`

  ---

- [export2clipboard](https://scrapbox.io/ePi5131/export2clipboard)
  - `export2clipboard`
- [Aulsメモリ参照プラグイン(1.10対応版)](https://scrapbox.io/ePi5131/Aulsメモリ参照プラグイン)
  - `Aulsメモリ参照プラグイン`
- [AulsPNG出力(修正版)](https://scrapbox.io/ePi5131/AulsPNG出力_バグ修正)
  - `AulsPNG出力 バグ修正`

  ---

- [波形プレビュー](https://www.nicovideo.jp/watch/sm39258128)
  - `WaveformPreview v0.3.0`
- [改変版Auls終了確認](https://scrapbox.io/karoterra/%E6%94%B9%E5%A4%89%E7%89%88Auls%E7%B5%82%E4%BA%86%E7%A2%BA%E8%AA%8D)
  - `改変版Auls終了確認 v1.2`
- [上限確認](https://github.com/karoterra/aviutl_ShowLimit)
  - `上限確認 v0.2.0`

  ---

- [ショートカット追加](https://auls.client.jp/)
  - `ショートカット追加`

  ---

- [フィルタドラッグ移動](https://github.com/hebiiro/AviUtl-Plugin-DragFilter)
  - `フィルタドラッグ移動 v9.0.0`
    - <details><summary>ini-setting</summary>

      ```ini
      [TargetMark]
      alpha=0
      penColor=0,0,0,0
      penWidth=0
      brushColor=255,255,255,255
      base=0
      width=0
      fontName=Segoe UI
      fontSize=32
      rotate=0
      beginMoveX=0
      beginMoveY=0
      ```

      </details>
- [お気に入りフォント選択](https://github.com/hebiiro/AviUtl-Plugin-SelectFavoriteFont)
  - `お気に入りフォント選択 v5.2.1`
    - <details><summary>xml-setting</summary>

      ```xml
      <?xml version="1.0" encoding="UTF-16" standalone="no"?>
        <settings>
          <setting x="2753" y="191" w="295" h="499" labelFormat="%ws --- %ws" separatorFormat="----------"/>
          <preview enable="YES" left="YES" itemWidth="400" itemHeight="20" textFormat="Sample(%s)" fillColor="#ffffff" textColor="#000000"/>
          <favorite>
            <font alias="よく使うフォント" expand="YES">
              <font name="けいふぉんと"/>
              <font name="ラノベPOP v2"/>
              <font name="Klee One"/>
              <font name="チョーク体"/>
              <font name="Stick"/>
              <font name="チョークS"/>
              <font name="Reggae One"/>
              <font name="ロックンロール One"/>
              <font name="クラフト明朝"/>
              <font name="ぽーら H"/>
              <font name="こまどり mini"/>
              <font name="851チカラヅヨク-かなA"/>
              <font name="851チカラヨワク"/>
              <font alias="Zen" expand="YES">
                <font name="Zen Antique"/>
                <font name="Zen Antique Soft"/>
                <font name="Zen Old Mincho"/>
                <font name="Zen Old Mincho Black"/>
                <font name="Zen Kaku Gothic New Light"/>
                <font name="Zen Kaku Gothic New"/>
                <font name="Zen Kaku Gothic New Medium"/>
                <font name="Zen Kaku Gothic New Black"/>
              </font>
            </font>
            <font alias="ゴシック体">
              <font name="けいふぉんと"/>
              <font name="ラノベPOP v2"/>
              <font name="モボ"/>
              <font name="モッチーポップ One"/>
              <font name="モッチーポップ P One"/>
              <font name="零ゴシック"/>
              <font name="なごみ極細ゴシック ExtraLight"/>
              <font alias="Zen Kaku Gothic New">
                <font name="Zen Kaku Gothic New Light"/>
                <font name="Zen Kaku Gothic New"/>
                <font name="Zen Kaku Gothic New Medium"/>
                <font name="Zen Kaku Gothic New Black"/>
              </font>
              <font alias="游ゴシック">
                <font name="游ゴシック"/>
                <font name="游ゴシック Light"/>
                <font name="游ゴシック Medium"/>
              </font>
              <font alias="源ノ角ゴシック">
                <font name="源ノ角ゴシック Code JP EL"/>
                <font name="源ノ角ゴシック Code JP L"/>
                <font name="源ノ角ゴシック Code JP N"/>
                <font name="源ノ角ゴシック Code JP R"/>
                <font name="源ノ角ゴシック Code JP M"/>
                <font name="源ノ角ゴシック Code JP H"/>
              </font>
              <font alias="マメロン">
                <font name="マメロン 3 Hi Regular"/>
                <font name="マメロン 3.5 Hi Regular"/>
                <font name="マメロン 4 Hi Regular"/>
                <font name="マメロン 5 Hi Regular"/>
              </font>
              <font alias="コーポレート・ロゴ">
                <font name="コーポレート・ロゴ ver2 Medium"/>
                <font name="コーポレート・ロゴ ver2"/>
              </font>
              <font alias="Mplus 1p">
                <font name="Mplus 1p Thin"/>
                <font name="Mplus 1p Light"/>
                <font name="Mplus 1p"/>
                <font name="Mplus 1p Medium"/>
                <font name="Mplus 1p Bold"/>
                <font name="Mplus 1p ExtraBold"/>
                <font name="Mplus 1p Black"/>
              </font>
            </font>
            <font alias="明朝体">
              <font name="Zen Antique"/>
              <font name="Zen Antique Soft"/>
              <font name="Zen Old Mincho"/>
              <font name="Zen Old Mincho Black"/>
              <font name="ほのか明朝"/>
              <font name="ほのか新明朝 Light"/>
              <font name="装甲明朝"/>
              <font name="馬酔木明朝 Light"/>
              <font name="はれのそら明朝"/>
              <font alias="游明朝">
                <font name="游明朝"/>
                <font name="游明朝 Light"/>
                <font name="游明朝 DemiBold"/>
              </font>
              <font alias="しっぽり明朝">
                <font name="しっぽり明朝"/>
                <font name="しっぽり明朝 Medium"/>
                <font name="しっぽり明朝 SemiBold"/>
                <font name="しっぽり明朝 ExtraBold"/>
                <font name="しっぽり明朝B1"/>
                <font name="しっぽり明朝B1 Medium"/>
                <font name="しっぽり明朝B1 SemiBold"/>
                <font name="しっぽり明朝B1 ExtraBold"/>
              </font>
              <font alias="錦明朝かな">
                <font name="錦明朝かな"/>
                <font name="錦明朝かな Light"/>
                <font name="錦明朝かな Medium"/>
                <font name="錦明朝かな SemiBold"/>
              </font>
              <font alias="夜永オールド明朝">
                <font name="夜永オールド明朝 Regular"/>
                <font name="夜永オールド明朝 Bold"/>
                <font name="夜永オールド明朝 Black"/>
              </font>
            </font>
            <font alias="特殊">
              <font name="Klee One"/>
              <font name="チョーク体"/>
              <font name="Stick"/>
              <font name="チョークS"/>
              <font name="Reggae One"/>
              <font name="ロックンロール One"/>
              <font name="クラフト明朝"/>
              <font name="ぽーら H"/>
              <font name="しあさって"/>
              <font name="こまどり mini"/>
              <font name="かなりあmini mini"/>
              <font name="やわらかドラゴン mini mini"/>
              <font name="851チカラヅヨク-かなA"/>
              <font name="異世明"/>
              <font name="異世ゴ"/>
              <font alias="トガリテ">
                <font name="トガリテ"/>
                <font name="トガリテ Thin"/>
                <font name="トガリテ Light"/>
                <font name="トガリテ Medium"/>
                <font name="トガリテ Heavy"/>
                <font name="トガリテ Black"/>
              </font>
              <font alias="JKゴシック">
                <font name="JKゴシックL"/>
                <font name="JKゴシックM"/>
                <font name="JK丸ゴシック Medium"/>
              </font>
            </font>
            <font alias="英文フォント">
              <font name="Challenge Shadow"/>
              <font name="CounselorScript"/>
              <font name="Vaderlands"/>
              <font name="Script"/>
            </font>
            <font alias="手書き">
              <font name="Yomogi"/>
              <font name="あずきフォント"/>
              <font name="あずきフォントP"/>
              <font name="あんずもじ"/>
              <font name="あんずもじ等幅"/>
              <font name="うずらフォント"/>
              <font name="ちはや純"/>
              <font name="アイシングソーダ"/>
              <font name="アイシングソーダ濃"/>
              <font name="花鳥風月"/>
              <font name="春夏秋冬Ⅱ"/>
            </font>
          </favorite>
        </settings>
      ```

      </details>
- [エディットボックス最適化](https://github.com/hebiiro/AviUtl-Plugin-OptimizeEditBox)
  - `エディットボックス最適化 version 7.1.1`
    - <details><summary>ini-setting</summary>

      ```ini
      [Settings]
      optimizeTimeLine=1
      editBoxDelay=250
      usesUnicodeInput=1
      usesCtrlA=1
      usesSetRedraw=1
      usesGradientFill=0
      innerColorR=0xff
      innerColorG=0xff
      innerColorB=0xff
      innerEdgeWidth=0
      innerEdgeHeight=0
      outerColorR=0xf0
      outerColorG=0x80
      outerColorB=0x40
      outerEdgeWidth=1
      outerEdgeHeight=0
      selectionColor=-1
      selectionEdgeColor=-1
      selectionBkColor=-1
      layerBorderLeftColor=-1
      layerBorderRightColor=-1
      layerBorderTopColor=-1
      layerBorderBottomColor=-1
      addTextEditBoxHeight=60
      addScriptEditBoxHeight=100
      ```

      </details>
- [イージング選択](https://github.com/hebiiro/AviUtl-Plugin-SelectEasing)
  - `イージング選択 version 4.2.0`
- [オブジェクトエクスプローラ](https://github.com/hebiiro/AviUtl-Plugin-ObjectExplorer)
  - `オブジェクトエクスプローラ version 2.0.2`
- [フィルタのコピペ](https://github.com/hebiiro/AviUtl-Plugin-CopyFilter)
  - `フィルタのコピペ 1.0.0`
- [カラーコード追加](https://github.com/hebiiro/AviUtl-Plugin-AddColorCode)
  - `カラーコード追加 v1.1.0`

  ---

- [設定ダイアログ画面サイズ固定化](https://www.nicovideo.jp/watch/sm36085428)
  - `設定ダイアログ画面サイズ固定化 v2.6`
    - <details><summary>ini-setting</summary>

      ```ini
      [Config]
      cyScrollLine=60
      cyMargin=120
      bAlwaysRestoreScrollPos=false
      [Window]
      top=-2
      left=1912
      right=2429
      bottom=1049
      ```

      </details>

  ---

- [拡張ツールバー](https://aoytsk.blog.jp/aviutl/1644995.html)
  - `拡張ツールバー v0.3.6`
- [ウィンドウマネージャー](https://aoytsk.blog.jp/aviutl/1470428.html)
  - `ウィンドウマネージャー v0.4.0`
- [シークバー＋](https://aoytsk.blog.jp/aviutl/613302.html)
  - `シークバー＋ v0.3.1`
- [シーン切替](https://aoytsk.blog.jp/aviutl/1769130.html)
  - `シーン切替 v0.2.0b`

  ---

- [真・グループ制御](https://www.nicovideo.jp/watch/sm39776727)
  - `真・グループ制御 v1.1.0`
- [イージング設定時短](https://github.com/kumrnm/aviutl-easing-quick-setup)
  - `easing_quick_setup v1.0.0`
- [マウスオペレーション改](https://github.com/kumrnm/aviutl-advanced-mouse-operation)
  - `マウスオペレーション改 v1.0.0`

  ---

- [カメラ補助](https://www.nicovideo.jp/watch/sm39701988)
  - `カメラ補助プラグイン v1.7`

  ---

- [PSDToolKit](https://github.com/oov/aviutl_psdtoolkit)
  - `PSDToolKit v0.2beta56`
- [ごちゃまぜドロップス](https://github.com/oov/aviutl_gcmzdrops)
  - `ごちゃまぜドロップス v0.4.0beta4`
  - (PSDToolKitの中に入っているファイルを上書き)
- [拡張編集RAMプレビュー](https://github.com/oov/aviutl_rampreview)
  - `拡張編集RAMプレビュー v0.3rc7`
  - (PSDToolKitの中に入っているファイルを上書き)
- [音量測定用プラグイン](https://www.nicovideo.jp/watch/sm34877728)
  - `loudness v0.1`
- [テキスト編集補助](https://github.com/oov/aviutl_textassist)
  - `テキスト編集補助 v0.3.4`
- [aviutl_browser](https://github.com/oov/aviutl_browser)
  - `aviutl_browser v0.4.1`
- [bridge.dll](https://github.com/oov/aviutl_bridge)
  - `bridge.dll v0.14.0`

  ---

- [rikky module&memory](https://hazumurhythm.com/a/a2Z/)
  - `rikky_module v1.4b`
  - `rikky_memory v0.6a`
- [カラーパレット](https://hazumurhythm.com/a/Y3c/)
  - `カラーパレット v2.1+`
  - [ユニバーサルデザイン推奨配色セット](https://renhagu.net/downloads/)
- [相対パス保存](https://hazumurhythm.com/a/3Av/)
  - `relative v0.9e`
- [オブジェクト名変更](https://hazumurhythm.com/a/G8o/)
  - `オブジェクト名変更`
- [スクリプト並べ替え管理](https://hazumurhythm.com/a/Di0/)
  - `スクリプト並べ替え管理 v2`

  ---

- [JPEG 3点セット](http://auf.jpn.xxxxxxxx.jp/)
  - `JPEG 3点セット v0.3.1`
- [虫眼鏡プラグイン](http://auf.jpn.xxxxxxxx.jp/)
  - `虫眼鏡プラグイン r8`

  ---

- [VSTホストプラグイン](https://www.nicovideo.jp/watch/sm29926034)
  - `VSTホストプラグイン v0.1`

  ---

- [色調補正・改](https://aji0.web.fc2.com/)
  - `色調補正・改 v2.0`

  ---

- [MotionTracking_MKII_Plus](https://github.com/Mr-Ojii/MotionTracking_MKII_Plus)
  - `MotionTracking_MKII_Plus r41`

  ---

## ini_edit

- [aviutl.ini 編集](https://github.com/hebiiro/AviUtl-Tool-aviutl.ini.gui)
  - `aviutl.ini 編集 v1.0.0`
- [patch.aul.json 編集](https://github.com/hebiiro/AviUtl-Tool-patch.aul.json.gui)
  - `patch.aul.json 編集 v30.0.0`

---

## scripts

### [Aodaruma](https://github.com/Aodaruma)

- 3DObject
- CameraDisplays
- ClipFigures
- CycleAffect
- DelayBuffer
- FlatShadow
- kerning
- light&shadow
- LoopTextures
- MaskingSlider
- Modulator
- OriginalToon
- ParallelCamera
- Partition&Flex
- Repeater
- RepeatingClip
- RikkyReflection
- SphereMaterialTest
- Trackers
- UVmapping(beta)
- VariableTrack
- WipeClipping
- キャッシュ保存RM
- グラデーションマップ(Re)
  - [グラデーションマッププリセット](https://www.nicovideo.jp/watch/sm30253109)
  - [Lejeグラデーションマップセット](https://twitter.com/rezile_ExThin/status/1181524102693081088)
- 簡易Glitch++(派生)

### [Auls](https://auls.client.jp/)

- Aulsアニメーション効果

### [button](https://www.nicovideo.jp/user/97204971)

- BPM同期
- 音量変化
- 中心座標移動B
- 髪飾り反転

### [CaffemochaY](https://www.nicovideo.jp/user/95423040)

- [ソフトフォーカス](https://www.nicovideo.jp/watch/sm40105334)
- [グラデーション縁取り＋](https://www.nicovideo.jp/watch/sm40105334)
- [ディフュージョン](https://www.nicovideo.jp/watch/sm40317056)
- [コントラスト比自動計算](https://www.nicovideo.jp/watch/sm40317056)
- [任意番号個別エフェクト](https://twitter.com/CaffemochaY/status/1524698397952909312)

### [ePi](https://scrapbox.io/ePi5131/)

- BChromakey
- [ease](https://scrapbox.io/ePi5131/ease)
- gaincol
- [koma](https://scrapbox.io/ePi5131/koma.anm)
- yca
- [斜](https://scrapbox.io/ePi5131/AviUtl_任意の角度がついた斜体を作ろう)
- [汎用トラックバー](https://scrapbox.io/ePi5131/汎用トラックバー)
- [aulut](https://scrapbox.io/ePi5131/aulut)
  - [35 Free LUTs for Color Grading Videos](https://www.rocketstock.com/free-after-effects-templates/35-free-luts-for-color-grading-videos/)

### [gometh](https://www.nicovideo.jp/user/4739587)

- [ドカベンスクリプト](https://www.nicovideo.jp/watch/sm30220788)
- [グラフ描画](https://www.nicovideo.jp/watch/sm32069730)
- [音MAD五線譜](https://www.nicovideo.jp/watch/sm34892254)
- [タイムラインオブジェクト](https://www.nicovideo.jp/watch/sm34953829)
- [蜘蛛の巣](https://www.nicovideo.jp/watch/sm34953916)
- [電光掲示板](https://www.nicovideo.jp/watch/sm34953926)
- [クリッピングして登場](https://www.nicovideo.jp/watch/sm34953935)
- [角丸ライン](https://www.nicovideo.jp/watch/sm34953940)
- [満ち欠け円](https://www.nicovideo.jp/watch/sm37269786)
- [非弾性衝突](https://www.nicovideo.jp/watch/sm37269815)
- [任意軸回転](https://www.nicovideo.jp/watch/sm37269841)
- [パチンコ風文字](https://www.nicovideo.jp/watch/sm37635423)
- [角丸正多角形](https://www.nicovideo.jp/watch/sm38077066)
- [ひらがな小さ](https://www.nicovideo.jp/watch/sm38454622)
- [ハーフトーン](https://www.nicovideo.jp/watch/sm38565819)
- [ベベルとエンボス](https://www.nicovideo.jp/watch/sm39006767)
- [漫画化エフェクト](https://www.nicovideo.jp/watch/sm39560082)
- [滑らか立体化](https://www.nicovideo.jp/watch/sm40545139)

### [kaisatsu](https://twitter.com/i/events/950334056461344768)

- [減衰振動](https://twitter.com/kai_satsu/status/933298940987846656)
- [スケールワイプ](https://twitter.com/kai_satsu/status/906772065813803009)
- [なめらか縁取り](https://twitter.com/kai_satsu/status/874996715496984577)
- [光彩](https://twitter.com/kai_satsu/status/874996715496984577)

### [Karoterra](https://www.nicovideo.jp/user/17745173)

- [3次ベジェ曲線イージング](https://www.nicovideo.jp/watch/sm38463837)
- [動く多角形](https://www.nicovideo.jp/watch/sm38752367)
- [曲げKR](https://www.nicovideo.jp/watch/sm39711773)
- [MarkdownEX](https://www.nicovideo.jp/watch/sm38814110)
- [油絵](https://www.nicovideo.jp/watch/sm39051118)

### [Legendtomo](https://twitter.com/Legendtomo_)

- [rounded_circle](https://twitter.com/Legendtomo_/status/1061908978576195584)

### [madeinpc](https://madeinpc.blog.fc2.com/)

- [トーンカーブRGB改](https://madeinpc.blog.fc2.com/blog-entry-1146.html)
- [トーンカーブHSV改](https://madeinpc.blog.fc2.com/blog-entry-1148.html)
- [RGB順序入れ替え(DLL)](https://madeinpc.blog.fc2.com/blog-entry-1311.html)

### [mes](https://www.nicovideo.jp/user/56278)

- [Unmult](https://github.com/mes51/AVIUtl_Unmult)

### [mina](https://www.nicovideo.jp/user/117083491)

- [雑縁取り](https://www.nicovideo.jp/watch/sm39488375)
- [中間点毎に表示(個別)](https://www.nicovideo.jp/watch/sm39316703)
- [FlatShadow_V](https://www.nicovideo.jp/watch/sm39170222)
- [BPM同期効果処理](https://www.nicovideo.jp/watch/sm38516538)

### [moll](https://twitter.com/moll_movie)

- [BoundingBox](https://twitter.com/moll_movie/status/1512825847195275267)
- [簡易色変更](https://twitter.com/moll_movie/status/1508386616544403464)
- [指定フレームのみ適用](https://twitter.com/moll_movie/status/1516782562739650569)
- [色破壊](https://twitter.com/moll_movie/status/1504460643151544325)
- [等速移動](https://twitter.com/moll_movie/status/1490230925707587586)
- [破壊](https://twitter.com/moll_movie/status/1506290812124123136)
- [崩落](https://twitter.com/moll_movie/status/1516673075194245121)

### [Mr-Ojii](https://github.com/Mr-Ojii)

- [ImageLoader_M](https://github.com/Mr-Ojii/ImageLoader_M)
- [Bevel_And_Emboss_M](https://github.com/Mr-Ojii/Bevel_And_Emboss_M)

### [Respectrum93](https://www.nicovideo.jp/user/188248)

- DelayMove ([修正参考](https://scrapbox.io/ePi5131/LuaJIT))
- DelayDraw
- MultiSlicer
- ベジエ軌道Ｔ+
- マルチベジェ軌道
- 偽被写界深度2

### [rikky](https://www.nicovideo.jp/user/14059878)

- [立体化(R)](https://hazumurhythm.com/a/1Sm/)
- [カメラ手ぶれ(R)](https://hazumurhythm.com/a/2Nr/)
- [合成モード拡張](https://hazumurhythm.com/a/w2C/)
- [パーツ分割](https://hazumurhythm.com/a/pA2/)
- [タイピング](https://hazumurhythm.com/a/4sI/)
- [グループアニメーションGA](https://hazumurhythm.com/a/1Ga/)
- [カケアミ](https://hazumurhythm.com/a/62Nf/)
- [乙女ゲームの破滅フラグしかない悪役令嬢に転生してしまったED風](https://hazumurhythm.com/a/5fYN/)
- [パーティクル(R)](https://hazumurhythm.com/a/Ba6/)
  - [パーティクル(R)カスタムオブジェクト](https://hazumurhythm.com/a/Te1/)
- [グラデーション(R)](https://hazumurhythm.com/a/5Yb/)
- [シーンチェンジアニメ](https://hazumurhythm.com/a/E1g/)

### [SEED264](https://github.com/SEED264)

- [PixelSorter_s](https://github.com/SEED264/PixelSorter_s)
- [RadialWipe_s](https://github.com/SEED264/RadialWipe_s)
- [OpticsCompensation_s](https://github.com/SEED264/OpticsCompensation_s)

### [tim](https://www.nicovideo.jp/user/1366031)

- [ライン抽出T](https://www.nicovideo.jp/watch/sm38701215)
- [カスタムフレア](https://www.nicovideo.jp/watch/sm17476172)
  - [カスタムフレア・プリセット+](https://www.nicovideo.jp/watch/sm21519868)
- [ひび割れガラスT](https://www.nicovideo.jp/watch/sm38361197)
- [罫線T](https://www.nicovideo.jp/watch/sm38304163)
- [低解像度T](https://www.nicovideo.jp/watch/sm37665554)
- [注ぎT](https://www.nicovideo.jp/watch/sm37665519)
- [ジグザグ塗りT](https://www.nicovideo.jp/watch/sm36355165)
- [バーコードT](https://timnoheya.fc2.net/blog-entry-10.html)
- [色調調整セットver6](https://www.nicovideo.jp/watch/sm35722623)
- [カメレオン効果](https://www.nicovideo.jp/watch/sm34225787)
- [縁取りT](https://www.nicovideo.jp/watch/sm33598259)
- [ブロックラスターT](https://www.nicovideo.jp/watch/sm33598240)
- [ぷよぷよT](https://www.nicovideo.jp/watch/sm30453564)
- [網点分解T](https://www.nicovideo.jp/watch/sm30453526)
- [集中線T](https://www.nicovideo.jp/watch/sm26938922)
- [マルチラインT](https://www.nicovideo.jp/watch/sm22974710)
- [リール回転T](https://www.nicovideo.jp/watch/sm22528296)
- [風揺れT](https://www.nicovideo.jp/watch/sm21864731)
- [ストロークT](https://www.nicovideo.jp/watch/sm21475670)
- [twitchっぽいものT](https://www.nicovideo.jp/watch/sm21060861)
- [ライントーン＆ハーフトーン](https://www.nicovideo.jp/watch/sm20946264)
- [ラフエッジ](https://www.nicovideo.jp/watch/sm20763137)
- [透明度指定](https://www.nicovideo.jp/watch/sm20729870)
- [モーションタイル](https://www.nicovideo.jp/watch/sm20729858)
- [フィルターセット](https://www.nicovideo.jp/watch/sm20550446)
- [透明塗り](https://www.nicovideo.jp/watch/sm20426178)
- [簡易モーフィング](https://www.nicovideo.jp/watch/sm20358620)
- [色抽出](https://www.nicovideo.jp/watch/sm20237800)
- [燃焼](https://www.nicovideo.jp/watch/sm20042712)
- [ワイヤー3D](https://www.nicovideo.jp/watch/sm20001035)
- [TrackingラインEasy](https://www.nicovideo.jp/watch/sm19924144)
- [オーラ放出](https://www.nicovideo.jp/watch/sm19868761)
- [シーンチェンジセット](https://www.nicovideo.jp/watch/sm19788901)
- [スターバースト](https://www.nicovideo.jp/watch/sm19745635)
- [砕け散るパズル](https://www.nicovideo.jp/watch/sm30452741)
- [スカイドーム](https://www.nicovideo.jp/watch/sm19465675)
- [虹色グラデーション](https://www.nicovideo.jp/watch/sm19425542)
- [色収差](https://www.nicovideo.jp/watch/sm19417956)
- [領域枠](https://www.nicovideo.jp/watch/sm19322302)
- [二十六面体](https://www.nicovideo.jp/watch/sm19110075)
- [放射分布 変色パーティクル](https://www.nicovideo.jp/watch/sm19109766)
- [曲面変形](https://www.nicovideo.jp/watch/sm18731596)
- [な～さりい☆らいむ風TA](https://www.nicovideo.jp/watch/sm18731552)
- [輝度ワイプ](https://www.nicovideo.jp/watch/sm18581114)
- [グリッドワイプ](https://www.nicovideo.jp/watch/sm18581033)
- [ツイスター](https://www.nicovideo.jp/watch/sm18580953)
- [色付きエッジ抽出](https://www.nicovideo.jp/watch/sm18348885)
- [つまむ](https://www.nicovideo.jp/watch/sm18114436)
- [インク（＋ひょうたん）](https://www.nicovideo.jp/watch/sm17999314)
- [スプリット](https://www.nicovideo.jp/watch/sm17935960)
- [蜂の巣モザイク](https://www.nicovideo.jp/watch/sm17848725)
- [はためき](https://www.nicovideo.jp/watch/sm14441618)
- [オートターゲット](https://www.nicovideo.jp/watch/sm16555929)
- [回転ブラー](https://www.nicovideo.jp/watch/sm31700000)
- [バニシングポイント](https://timnoheya.fc2.net/blog-entry-8.html)
- [多角錐変形](https://www.nicovideo.jp/watch/sm20483016)
- [簡易リピーター](https://www.nicovideo.jp/watch/sm19322190)
- [簡易ワープ(改)](https://www.nicovideo.jp/watch/sm19322218)
- [輪郭追跡](https://www.nicovideo.jp/watch/sm18259978)
- [正多面体](https://www.nicovideo.jp/watch/sm17765571)
- [ランダムブラー](https://www.nicovideo.jp/watch/sm17348356)
- [フィルム焦げ](https://www.nicovideo.jp/watch/sm17192955)
- [ゆらめき](https://www.nicovideo.jp/watch/sm17156271)
- [斜めブラインド(改)](https://www.nicovideo.jp/watch/sm17155254)
- [極座標変換＋ぼかしミラー](https://www.nicovideo.jp/watch/sm17154269)
- [小物(カメラデータコピー等)](https://www.nicovideo.jp/watch/sm16943422)
- [稲妻](https://www.nicovideo.jp/watch/sm16931205)
- [砕けたガラス](https://www.nicovideo.jp/watch/sm16763314)
- [MMDカメラデータ読込](https://www.nicovideo.jp/watch/sm16630776)
- [ライトバースト](https://www.nicovideo.jp/watch/sm16497408)
- [バニシングポイント2](https://www.nicovideo.jp/watch/sm16461298)
- [任意多角形カット](https://www.nicovideo.jp/watch/sm16326102)
- [任意多角形カスタムオブジェクト](https://www.nicovideo.jp/watch/sm16109364)
- [泡](https://www.nicovideo.jp/watch/sm16108745)
- [一時保存読込](https://www.nicovideo.jp/watch/sm15784672)
- [多色グラデーション](https://www.nicovideo.jp/watch/sm15604220)
- [砕け散る球](https://www.nicovideo.jp/watch/sm15498968)
- [エンボスタイル](https://www.nicovideo.jp/watch/sm15248261)
- [砕け散る(改)](https://www.nicovideo.jp/watch/sm15221902)
- [簡易モーションパス(パス数無制限版)](https://www.nicovideo.jp/watch/sm15039124)
- [歯車変形](https://www.nicovideo.jp/watch/sm14632269)
- [直方体展開](https://www.nicovideo.jp/watch/sm14573964)
- [ルービックキューブ配置](https://www.nicovideo.jp/watch/sm14573891)
- [レンズフレア](https://www.nicovideo.jp/watch/sm14199347)

### [UndoFish/あんどぅ](https://www.nicovideo.jp/user/26576669)

- [トラックバー対応イージングスクリプト 2020版](https://www.nicovideo.jp/watch/sm37721332)
- [文字輪郭追跡](https://www.nicovideo.jp/watch/sm21828818)

### [さつき](https://bowlroll.net/file/3777)

### [シケロマ](https://www.nicovideo.jp/user/20276333)

- [テキストグリッド配置](https://www.nicovideo.jp/watch/sm34664063)
- [レーダーチャート](https://www.nicovideo.jp/watch/sm34460814)
- [作戦図](https://www.nicovideo.jp/watch/sm34460836)

### [しゅう](https://shummg.work/downloads)

- BufferMask
- SquareAdvanced
- モザイクとノイズ
- 明度着色

### [スノスク](https://www.nicovideo.jp/user/16086289)

- [拡大縮小ランダム配置](https://www.nicovideo.jp/watch/sm37678490)

### [ちくぼん](https://www.nicovideo.jp/user/14280641)

- [直線](https://www.nicovideo.jp/watch/sm38380577)
- [割合斜めクリッピング](https://www.nicovideo.jp/watch/sm38605865)

### [ちはユキ](https://www.nicovideo.jp/user/92595139)

- [自動呼吸アニメーション](https://www.nicovideo.jp/watch/sm37438844)
- [補助線スクリプト](https://www.nicovideo.jp/watch/sm37066079)

### [はち](https://www.nicovideo.jp/user/621156)

- [中心座標移動](https://www.nicovideo.jp/watch/sm32870150)

### [てつ(XIAO)](https://www.nicovideo.jp/user/2358792)

- [OpenCV_anm](https://www.nicovideo.jp/watch/sm32520048)

### [プリンカ](https://www.nicovideo.jp/user/29980050)

- [本当のブロックノイズ](https://www.nicovideo.jp/watch/sm26857840)

### [マタタビ](https://twitter.com/matatabi1120)

- [Fractal](https://bowlroll.net/file/230162)
- [PatternCollection](https://bowlroll.net/file/253069)

### [ゆーひま](https://twitter.com/i/events/1316391623589130241)

- [内側縁取り](https://twitter.com/YuHima_03/status/1343483111019974656)
- [内側シャドー](https://twitter.com/YuHima_03/status/1343460865224237056)
- [ずらし縁取り](https://twitter.com/YuHima_03/status/1298226973630533632)
- [簡易テキスト背景](https://twitter.com/YuHima_03/status/1264558442934460418)

### [ゆゆ](https://www.nicovideo.jp/user/46794622)

- [Blessing風TA](https://www.nicovideo.jp/watch/sm40029878)
- [XYランダム](https://www.nicovideo.jp/watch/sm40029878)
- [縦書き中央寄せ](https://www.nicovideo.jp/watch/sm40029878)

### [高橋 直哉](https://www.nicovideo.jp/user/16350045)

- [アスキーアート化](https://www.nicovideo.jp/watch/sm35637238)
- [ドット絵化](https://www.nicovideo.jp/watch/sm39554686)

### [糖衣月餅](https://www.nicovideo.jp/user/48182904)

- [明度・コントラスト補正+](https://www.nicovideo.jp/watch/sm37189836)

### [白い豚(赤)](https://www.nicovideo.jp/user/453050)

- [動く曲線_FrontLine](https://www.nicovideo.jp/watch/sm34885270)
- [レイヤーミラー](https://www.nicovideo.jp/watch/sm34925665)

### [白水](https://purinka.work/download/hksy.html)

- @hksy
- DLL使用アニメーション効果
- MIDIFileReader

### [連結歯車](https://www.nicovideo.jp/user/84530131)

- [長方形角取り](https://www.nicovideo.jp/watch/sm34542414)

---

## Transition

- [MORGUE](https://nega.client.jp/)
- [吉里吉里Z](https://krkrz.github.io/)
- [256じゃんくヤードMELT!](http://jym.if.land.to/game/trans/index.html)

---

## Other-Tools

- [.aupExportTool](https://share-aup.com/download/aup_exp_tool)
- [AupInfo](https://github.com/karoterra/AupInfo)
