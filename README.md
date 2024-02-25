# 国土交通省 Project PLATEAU リンク集

> Awesome PLATEAU

- 一般・自治体・官公庁・企業の方からの情報の追加・修正、リンク切れの報告等を歓迎しています。[Issues](https://github.com/japan-opendata/awesome-plateau/issues) または [Pull Requests](https://github.com/japan-opendata/awesome-plateau/pulls) からお送りください。

### GitHub

<https://github.com/japan-opendata/awesome-plateau>

### 目次

- [3D都市モデルデータ](#3d都市モデルデータ)
    - [公式データ配布](#公式データ配布)
    - [派生データ配布・構築](#派生データ配布構築)
    - [ファイル形式の情報](#ファイル形式の情報)
- [コミュニティ](#コミュニティ)
- [イベント・コンテスト](#イベントコンテスト)
    - [PLATEAU AWARD 2023](#plateau-award-2023)
    - [PLATEAU AWARD 2022](#plateau-award-2022)
- [アプリケーション/ツール/ライブラリ](#アプリケーションツールライブラリ)
    - [ビューア](#ビューア)
    - [ArcGIS](#arcgis)
    - [Blender](#blender)
    - [C#](#c)
    - [Cities:Skylines](#citiesskylines)
    - [FME](#fme)
    - [JavaScript/TypeScript](#javascripttypescript)
    - [Minecraft](#minecraft)
    - [OpenStreetMap](#openstreetmap)
    - [Python](#python)
    - [Rust](#rust)
    - [Unity](#unity)
    - [Unreal Engine](#unreal-engine)
    - [VRChat](#vrchat)
- [手引き・学習](#手引き学習)
    - [全般](#全般)
    - [開発者向け](#開発者向け)
- [事例](#事例)
- [記事・レポート](#記事レポート)
- [企業・法人](#企業法人)
- [制度・事業](#制度事業)
- [関連プロジェクト](#関連プロジェクト)
- [関連リンク](#関連リンク)
    - [PLATEAU](#plateau)
    - [全般](#全般-1)

## 3D都市モデルデータ

### 公式データ配布

- [Open Data | 3D都市モデルオープンデータ](https://www.mlit.go.jp/plateau/open-data/) - 公式サイト内の都市別一覧
- [3D都市モデル（Project PLATEAU）ポータルサイト](https://www.geospatial.jp/ckan/dataset/plateau) - データが実際に配布されている[G空間情報センター](https://www.geospatial.jp/)内の都市別一覧

### 派生データ配布・構築

- [pacificspatial/flateau](https://github.com/pacificspatial/flateau) - GeoParquet形式に変換したデータセット
- [Project-PLATEAU/plateau-streaming-tutorial](https://github.com/Project-PLATEAU/plateau-streaming-tutorial/) - 「PLATEAU配信サービス」として3DTiles形式/MVT形式でデータを提供 (公式)
- [ESRIジャパン ファイル ジオデータベースでの公開](https://3d-city-model.esrij.com/) - ESRIジャパン社が提供するファイル ジオデータベース形式のデータ
- [OpenStreetMap Japan](https://openstreetmap.jp/node/993) - OpenStreetMapへのPLATEAU 3D建物データのインポート作業に関する情報
- [indigo-lab/plateau-tokyo23ku-building-mvt-2020](https://github.com/indigo-lab/plateau-tokyo23ku-building-mvt-2020) - CityGMLの建築物 (bldg:Building) データを Mapbox Vector Tile (MVT) 形式に変換したデータセット (東京23区、2020年度版)
    - [indigo-lab/plateau-lod2-mvt](https://github.com/indigo-lab/plateau-lod2-mvt) - LOD2対応版

### ファイル形式の情報

- CityGML
- GeoTIFF
- FBX
- OBJ
- FGDB

## コミュニティ

- PLATEAU Slackコミュニティ ([FAQ内の案内](https://www.mlit.go.jp/plateau/faq/)) - 公式サイト内の[問い合わせフォーム](https://www.mlit.go.jp/plateau/contact/)から参加申請が可能
- [PLATEAUコンソーシアム](https://www.mlit.go.jp/plateau/consortium/) - 産学官連携のための公式コンソーシアム

## イベント・コンテスト

> イベント毎の詳細の作成・アップデートにぜひご協力ください

- [PLATEAU AWARD](https://www.mlit.go.jp/plateau-next/award/) - 公式コンテスト (2022年度–)
- [PLATEAU STARTUP Pitch](https://www.mlit.go.jp/plateau-next/#plateau-startup-pitch)
    - PLATEAU STARTUP Pitch 02 [アーカイブ配信](https://www.youtube.com/watch?v=Pk1gh_689dE)
    - PLATEAU STARTUP Pitch 01 [アーカイブ配信](https://www.youtube.com/watch?v=fytNa-rdvgQ)
- [PLATEAU Accelerator](https://www.mlit.go.jp/plateau-next/#plateau-accelerator)
    - 成果報告会 (2023年度) [アーカイブ配信](https://www.youtube.com/watch?v=C7pzMnSibwk)
- [TOKYO NODE XR HACKATHON powered by PLATEAU](https://tokyonode.jp/sp/xrhackathon2023) - PLATEAUが共催する虎ノ門ヒルズ[TOKYO NODE](https://www.tokyonode.jp/)のイベント (2023年)
- [PLATEAU Hack Challenge](https://www.mlit.go.jp/plateau-next/#plateau-lt) - 公式ハッカソン
- [PLATEAU LT](https://www.mlit.go.jp/plateau-next/#plateau-lt) - 公式LT
- [PLATEAU Hands-on](https://www.mlit.go.jp/plateau-next/#plateau-hands-on) - 公式ワークショップ
- [PLATEAU Kids Challenge](https://www.mlit.go.jp/plateau-next/#plateau-hands-on) - 子供向け公式イベント

**こちらも参照:**

- [PLATEAU NEXT](https://www.mlit.go.jp/plateau-next/) - 最新の公式イベント情報
- [公式サイト内 Journalページ](https://www.mlit.go.jp/plateau/journal/) - 過去のイベントレポート等

### PLATEAU AWARD 2023

**ファイナリスト作品**

- Machi Plus
    - Web: <https://orchid966621.studio.site/>
- PlateauKit + PlateauLab
    - Web: <https://ozekik.github.io/plateaukit/>
    - GitHub: [ozekik/plateaukit](https://github.com/ozekik/plateaukit)
- 安全運転学習用 Unity版ドライビングシミュレータ 「ぷらっとドライブ in 沼津」
    - Web: <https://ss1.xrea.com/gosystems.s223.xrea.com/plateaudrive/>
- Echoes of the PLATEAU
    - YouTube: <https://youtu.be/9mcQf88XtfI>
- ぐりぐりインフォメーション
    - Web: <https://www.three-works.jp/>
- 観光ルート作成ゲーム 「Kyoto Itinerary」
    - Web: <https://matsudasu.itch.io/kyotoitinerary>
- PLATEAU Window:Horizon
- Scaling up PLATEAU
- 360°歩行映像のPLATEAUへの動的なプロジェクションと洪水可視化-Floodeau-への応用
- スカイランナー　高層の冒険者
- Beat Running over the city
- PLATEAU DIPS-4D

**奨励賞作品**

- NIIGATA XR プロジェクト
- ARCade ~月島・西仲通り商店街の ARアプリ製作~
- AI Texture Generator
    - GitHub: [tatsuya1970/AiTextureGenerator](https://github.com/tatsuya1970/AiTextureGenerator)
- 地球観察機
- TOKYO GOURMET "Cyber Navigate 360"
- 体感型地理学習ゲーム「PLATEAUビー玉転がし」
- URBAN THERMO PAINTER　- PLATEAU を用いたまちづくり支援のための屋外熱環境シミュレーションツール -
- でべごっこ
- PLATEAU Sky Printing
- 中目黒高架下 施設MAP
    - Web: <https://touyoko-nakamegurokoukashita.jp/>

### PLATEAU AWARD 2022

- [「PLATEAU AWARD 2022」初代グランプリは実在の街をスノードームで楽しむ『snow city』 | Journal](https://www.mlit.go.jp/plateau/journal/j029/) - 開催レポート

**ファイナリスト作品**

- Snow City [発表スライド](https://speakerdeck.com/toshiseisaku/no-dot-8-snow-city)
    - Web: <https://snow-city.vercel.app>
- 情報加算器 [発表スライド](https://speakerdeck.com/toshiseisaku/no-dot-4-qing-bao-jia-suan-qi)
    - Web: <https://info-adder.web.app>
    - GitHub: [SohMitian/info_adder_API](https://github.com/SohMitian/info_adder_API)
- 都市の分布を見る [発表スライド](https://speakerdeck.com/toshiseisaku/no-dot-2-du-shi-nofen-bu-wojian-ru)
    - Web: <https://www.estie.jp/blog/entry/2022/08/10/110801>
    - GitHub: [johntronik/blog_plateau_polar_plot](https://github.com/johntronik/blog_plateau_polar_plot)
- 点群×PLATEAU [発表スライド](https://speakerdeck.com/toshiseisaku/no-dot-3-dian-qun-xplateau)
    - YouTube: <https://youtu.be/tpz72maKBIw>
- Plateau Blender Importer [発表スライド](https://speakerdeck.com/toshiseisaku/no-dot-5-plateau-blender-importer)
    - [Blender](#blender)内 Plateau Blender Importer 参照
- PLATEAU CityGML LOD1をOpenStreetMapにインポートしてみた！ [発表スライド](https://speakerdeck.com/toshiseisaku/no-dot-6-plateau-citygml-lod1-wo-openstreetmap-niinpotositemita)
    - [派生データ配布・構築](#派生データ配布構築)内の「OpenStreetMap Japan」も参照
- Own東京 [発表スライド](https://speakerdeck.com/toshiseisaku/no-dot-12-owndong-jing)
    - Web: <https://tokyo.owntwin.com>
    - GitHub: [owntwin/owntwin](https://github.com/owntwin/owntwin)
- 世界初の位置情報と連携した3Dキャプチャー作品コンテスト みんキャプ [発表スライド](https://speakerdeck.com/toshiseisaku/no-dot-13-osoraku-shi-jie-chu-nowei-zhi-qing-bao-tolian-xi-sita3dkiyaputiyazuo-pin-kontesuto-minkiyapu)
    - Web: <https://minc.app>
- PLATEAU Tools
- PLATONE
- VARAEMON
- PLATEAU Window
- すPLATEAU～ん
- SUNABA MAP MR
- TOKYO 昭和97年
- PLATEAUで日本全国の自動運転シミュレーションを可能にする
- キッズ向けさいがいMAP

## アプリケーション/ツール/ライブラリ

**こちらも参照:**

- [イベント・コンテスト](#イベントコンテスト)
- [公式GitHub](https://github.com/Project-PLATEAU)

### ビューア

- [PLATEAU VIEW 2.0](https://plateauview.mlit.go.jp/) - ブラウザ上でPLATEAUの3D都市モデルを閲覧できる公式Webアプリ
- [PLATEAU VIEW 3.0 Design & Technology Preview](https://plateau.takram.com/) - 次期PLATEAU VIEWのプレビュー版 (Takram社)

### ArcGIS

- [EsriJapan/3D-CityModel-ConversionTools-for-ArcGIS-v2](https://github.com/EsriJapan/3D-CityModel-ConversionTools-for-ArcGIS-v2) - ESRI社ArcGIS用のデータ変換ツール

### Blender

- [nneri-hin/Plateau-Blender-Importer](https://github.com/nneri-hin/Plateau-Blender-Importer) -  PlateauのCityGMLファイルをBlenderにインポートするツール

### C\#

- [ksasao/PlateauCityGmlSharp](https://github.com/ksasao/PlateauCityGmlSharp) - Project PLATEAU の CityGML を .obj に変換するツール

### Cities:Skylines

- [Project-PLATEAU/SkylinesPLATEAU](https://github.com/Project-PLATEAU/SkylinesPLATEAU) - 3D都市モデルを都市育成シミュレーションゲーム"Cities:Skylines"にインポートするMOD

### FME

> 情報募集中

### JavaScript/TypeScript

- Cesium Ion

### Minecraft

- [Project-PLATEAU/plateau2minecraft](https://github.com/Project-PLATEAU/plateau2minecraft) - 3D都市モデルをマインクラフトに取り込み可能なデータ形式に変換するためのツール

### OpenStreetMap

- [yuuhayashi/citygml-osm](https://github.com/yuuhayashi/citygml-osm) - CityGMLデータをOSMデータに変換するツール (Javaで動作)

### Python

- [raokiey/plateau-geo-tools](https://github.com/raokiey/plateau-geo-tools) - CityGML形式のデータをGeoJSONなどのGISファイルフォーマットに変換したり情報を補完するためのツール
- [ozekik/plateaukit](https://github.com/ozekik/plateaukit) - PLATEAU都市モデルを利用するためのPythonライブラリおよび変換ツール
- [AcculusSasao/plateaupy](https://github.com/AcculusSasao/plateaupy) - PLATEAU CityGMLのPython版パーサおよびビューア用モジュール
    - [rhenerose/plateaupy](https://github.com/rhenerose/plateaupy) - 機能追加版フォーク

### Rust

- [geolonia/jp_plateau_tool](https://github.com/geolonia/jp_plateau_tool) - PLATEAUデータを処理するツール集

### Unity

- [PLATEAU SDK for Unity](https://github.com/Project-PLATEAU/PLATEAU-SDK-for-Unity) - 3D都市モデルデータをUnityで扱うためのツールキット

### Unreal Engine

- [PLATEAU SDK for Unreal](https://github.com/Project-PLATEAU/PLATEAU-SDK-for-Unreal) -  3D都市モデルデータをUnreal Engineで扱うためのツールキット

### VRChat

> 情報募集中

## 手引き・学習

### 全般

- [公式サイト内 Learningページ](https://www.mlit.go.jp/plateau/learning/) - PLATAU都市モデルを利用したアプリ開発のチュートリアル等
- [公式サイト内 Start Guide](https://www.mlit.go.jp/plateau/start-guide/) - PLATEAUのデータ概要と利用案内
- [ユースケース開発ガイド – 自治体編](https://www.mlit.go.jp/plateau/learning/ucg00/) - 公式サイト内の自治体向けガイド

### 開発者向け

- [PLATEAUタグが付けられた記事一覧 (Qiita)](https://qiita.com/tags/plateau)
- [PLATEAUタグが付けられた記事一覧 (Zenn)](https://zenn.dev/topics/plateau)

## 事例

- [公式サイト内 Use Caseページ](https://www.mlit.go.jp/plateau/use-case/) - 3D都市モデルを活用したソリューション開発の事例紹介

## 記事・レポート

- [公式サイト内 Journalページ](https://www.mlit.go.jp/plateau/journal/)
- [PLATEAUに関する記事一覧 (ASCII STARTUP)](https://ascii.jp/featuredarticles/3000732/)

## 企業・法人

- [パートナー企業・団体の一覧](https://www.mlit.go.jp/plateau/about/#partners) - 公式サイト内
- [ESRIジャパン 国土交通省 3D都市モデル 「Project PLATEAU」の活用](https://3d-city-model.esrij.com/) - ツールやデータの配布、事例紹介

## 制度・事業

- [大都市圏整備：都市空間情報デジタル基盤構築支援事業 (PLATEAU補助制度)](https://www.mlit.go.jp/toshi/daisei/plateau_hojo.html)

## 関連プロジェクト

- [東京都デジタルツイン実現プロジェクト](https://info.tokyo-digitaltwin.metro.tokyo.lg.jp/) - 東京都デジタルサービス局
- [国土交通省 スマートシティ官民連携プラットフォーム](https://www.mlit.go.jp/scpf/)
- [国土交通データプラットフォーム](https://www.mlit-data.jp/)

## 関連リンク

### PLATEAU

- [Project PLATEAU公式サイト](https://www.mlit.go.jp/plateau/)
- [Project PLATEAU公式X (旧Twitter)](https://twitter.com/ProjectPlateau)

### 全般

- [日本のオープンデータ情報一覧・まとめ](https://japan-opendata.github.io/awesome-japan-opendata/)

---

_Contributors_: [@ozekik](https://github.com/ozekik/)
