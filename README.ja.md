# xrgourmet - XRグルメ

ARやVRアプリケーションで利用できる、3Dスキャンされたグルメ系モデルのオープンデータコレクションです。

## XR Gourmetギャラリー

ブラウザ上で3Dグルメモデルの全コレクションを閲覧できます。

**[ライブデモを表示](https://code4fukui.github.io/xrgourmet/)**

ギャラリーでは、各モデルを以下の方法で表示できます:
*   **AR (拡張現実):** 対応デバイス（iPhoneやiPadなど）では、モデルの画像をクリックすると直接ARで表示されます。
*   **VR/3Dビューア:** その他のデバイスでは、A-FrameやThree.jsなどの技術で構築されたウェブベースの3D/VRビューアが起動します。
*   **直接ダウンロード:** `.glb`や`.usdz`形式のモデルファイル本体をダウンロードできるリンクを提供しています。

![ステーキ、たこ焼き、カレー、パフェなど、3Dスキャンされた様々なグルメモデルのギャラリー画像](https://code4fukui.github.io/xrgourmet/mutsunohana-steak.jpg)

## 収録モデル例

コレクションの一部を紹介します。各項目には、料理名、提供元、モデルの表示やダウンロード用のリンクが含まれています。

| プレビュー | 料理名 | 提供元 | リンク |
| :--- | :--- | :--- | :--- |
| <img src="https://code4fukui.github.io/xrgourmet/lejardin-waton.jpg" width="150"> | 和豚料理 | [Le Jardin](https://lejardin-fukui.com/) | [APP](https://code4fukui.github.io/xrgourmet/lejardin-waton.html) / [USDZ](https://code4fukui.github.io/xrgourmet/lejardin-waton.usdz) / [GLB](https://code4fukui.github.io/xrgourmet/lejardin-waton.glb) |
| <img src="https://code4fukui.github.io/xrgourmet/takoyaki-takobei.jpg" width="150"> | たこ焼き | [蛸べえ](https://www.hotpepper.jp/strJ000985159/) | [APP](https://code4fukui.github.io/xrgourmet/takoyaki-takobei.html) / [USDZ](https://code4fukui.github.io/xrgourmet/takoyaki-takobei.usdz) / [GLB](https://code4fukui.github.io/xrgourmet/takoyaki-takobei.glb) |
| <img src="https://code4fukui.github.io/xrgourmet/kosen-dago.jpg" width="150"> | 高専ダゴ | [高専ダゴ](http://www.kousendago.com/) | [APP](https://code4fukui.github.io/xrgourmet/kosen-dago.html) / [USDZ](https://code4fukui.github.io/xrgourmet/kosen-dago.usdz) / [GLB](https://code4fukui.github.io/xrgourmet/kosen-dago.glb) |
| <img src="https://code4fukui.github.io/xrgourmet/salice-ichigo-pafrait.jpg" width="150"> | いちごティラミスパフェ | [Sweets Bar Salice](https://www.instagram.com/salicefukui_pr/) | [APP](https://code4fukui.github.io/xrgourmet/salice-ichigo-pafrait.html) / [USDZ](https://code4fukui.github.io/xrgourmet/salice-ichigo-pafrait.usdz) / [GLB](https://code4fukui.github.io/xrgourmet/salice-ichigo-pafrait.glb) |
| <img src="https://code4fukui.github.io/xrgourmet/echizen-seikogani.jpg" width="150"> | 越前せいこがに | (なし) | [APP](https://code4fukui.github.io/xrgourmet/echizen-seikogani.html) / [USDZ](https://code4fukui.github.io/xrgourmet/echizen-seikogani.usdz) / [GLB](https://code4fukui.github.io/xrgourmet/echizen-seikogani.glb) |

## 使い方

### 閲覧する場合
[XR Gourmetギャラリー](https://code4fukui.github.io/xrgourmet/)にアクセスするだけで、デスクトップやモバイルデバイスからモデルを閲覧・操作できます。

### 開発者向け
独自の3D、AR、VRプロジェクトで利用する場合は、このリポジトリをクローンするか、`.usdz`および`.glb`ファイルをダウンロードしてください。HTMLファイルは、これらのモデルをウェブ上で表示するための簡単な実装例となっています。

## コントリビューション

コントリビューションは大歓迎です！3Dスキャンしたグルメモデルを追加したい場合は、以下の手順でお願いします:
1.  リポジトリをフォークします。
2.  `.glb`、`.usdz`ファイルと、プレビュー用の`.jpg`ファイルを追加します。
3.  HTMLビューアページを作成します（既存のファイルをテンプレートとして利用できます）。
4.  `index.html`のリストにモデルを追加します。
5.  変更を含めたプルリクエストを送信します。

## ライセンス

データは[CC BY](https://creativecommons.org/licenses/by/4.0/)ライセンスの下で提供されています。ご利用の際は[Code for FUKUI](https://github.com/code4fukui/xrgourmet)のクレジット表記をお願いします。
