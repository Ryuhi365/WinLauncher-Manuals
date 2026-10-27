# WinLauncher Standard

毎日の Windows 作業を、`Alt+Space` から始める。

WinLauncher Standard は、よく使うファイル、フォルダ、Webページ、OneNote、SharePoint、共有フォルダ、定型文をすばやく呼び出すための Windows 実務用ランチャーです。

Launcher は「探す・開く」を減らします。

Snippets は「書く・貼る・思い出す」を減らします。

## 最初の10分
最初から完璧に整理する必要はありません。

まずは、毎日使うものを3つだけ登録してください。

おすすめ:
- 毎日開くファイル
- よく使う共有フォルダまたはWebページ
- よく貼る定型文

使う中で「また探している」「また同じ文を書いている」と感じたものを、少しずつ追加していきます。

## 配布内容
販売版 zip には、以下が入っています。日本語と英語で1つのファイルです。

- `WinLauncher.exe`
- `README_FIRST.txt`
- `ChangeLog.md`
- `ja` フォルダ（`README.md` / `LICENSE.txt` / `WinLauncher_Manual_JA.pdf` / `sample`）
- `en` フォルダ（English versions of the same set）

`ja\sample` フォルダには、最初に何を登録すればよいかをイメージするための参考用CSVが入っています。

サンプルCSVは自動では読み込まれません。内容を参考にして手動登録するか、`CSV取込` で試す場合は、必要に応じてパスやURL、文面を自分用に書き換えてください。

## 起動方法
1. zip を任意のフォルダへ展開します。
2. `WinLauncher.exe` を起動します。
3. `Alt+Space` で WinLauncher を表示します。
4. まずは毎日使うファイル、共有フォルダ、定型文を3つ登録してみてください。

## 表示言語の切り替え
タスクトレイの WinLauncher アイコンを右クリックし、`Language / 言語` から `日本語` または `English` を選びます。

切り替えたあと、いったん WinLauncher を終了して起動し直すと反映されます。設定は保存され、次回起動時も維持されます。

はじめて起動したときは、お使いの Windows の表示言語に従います。

販売版は、.NET ランタイムを別途インストールしなくても起動できる self-contained 形式で配布しています。

動作環境:
- Windows 10 / 11、64ビット環境
- Webページを開く機能やWeb検索を使う場合は、インターネット接続が必要です。

注意:
- 初回起動時に SmartScreen やセキュリティソフトの警告が表示される場合があります。
- 会社PCで利用する場合は、所属組織のルールに従ってください。

## 使い始め

### Step 1: 毎日使う場所を登録する
毎日開く Excel ファイル、共有フォルダ、SharePoint の業務ページ、OneNote の業務ノートなどを登録します。

まずは1つだけでも大丈夫です。

### Step 2: `Alt+Space` から開く
Explorer やブラウザから探す代わりに、`Alt+Space` で WinLauncher を呼び出して開いてみます。

### Step 3: よく使う文面を Snippets に登録する
メール返信文、チャット連絡、作業記録テンプレ、入力テンプレなど、何度も使う文章を登録します。

Snippets はコード片だけでなく、定型文、作業メモ、入力テンプレ、チェックリストにも使えます。

### Step 4: 少しずつ育てる
仕事中に「また探している」「また同じ文を書いている」と感じたものを追加していきます。

WinLauncher は、最初から完成した整理棚を作るより、日々の仕事に合わせて少しずつ育てる使い方に向いています。

## できること

### よく使う場所をすぐ開く
毎日使うファイル、フォルダ、Webページ、OneNote、SharePoint、共有フォルダなどを登録して、`Alt+Space` からすばやく呼び出せます。

URLとして開けるものや、Windowsで開けるパスであれば、Launcherの登録対象として扱えます。

登録例:

| 種類 | 例 |
| --- | --- |
| Webページ | ChatGPT、YouTube、Amazon、社内ポータル |
| Teams | Teamsのチャネル、グループチャット、会議リンク |
| Microsoft 365 | Outlook Web、Microsoft 365、SharePointのページ |
| ファイル | Excel、PowerPoint、PDF、Word、OneNote |
| フォルダ | PC内フォルダ、共有フォルダ |
| WebDAV形式のフォルダ | Windowsのエクスプローラーで開けるSharePoint上のフォルダ |

### 登録した項目を検索する
登録した項目は、名前やタグで絞り込めます。

Explorer の階層をたどったり、ブラウザのお気に入りを探したりする時間を減らせます。

### 定型文をすぐ使う
メール返信、チャット連絡、問い合わせ対応文、作業記録、入力テンプレ、チェックリスト、コード片などを Snippets として保存できます。

必要なときに検索して、クリップボードへコピーできます。

### Web検索を補助的に使う
検索欄の文字列を使って、必要なときに Web検索を開けます。

これは主機能ではなく、作業中の小さな補助機能です。

### 検索モードで切り替える
検索欄の先頭または末尾に `/` を付けると、モード名の候補が出ます。
`/モード名 キーワード` でも `キーワード /モード名` でも切り替えられるので、通常の検索で目的のものが出ないときは、末尾に付け足すだけで他のモードへ移れます。

| モード | 検索対象 |
| --- | --- |
| `/Everything` | PC内のファイル（Everything(voidtools) 経由） |
| `/Edge` | Microsoft Edge のブックマーク |
| `/Search` | Google AI、Amazon、楽天市場などの検索先を選ぶ |
| `/ConvSPLink` | SharePoint の UNC パスと URL を相互変換する |
| `/Recent` | Windows が記録した最近使ったファイル |
| `/Snippet` | 保存済みの Snippets |
| `/DropDest` | Drops の「登録済みフォルダへコピー」で使う登録先フォルダ |

`/Everything` は Everything(voidtools) が入って動いている場合に使えます。必須ではありません。未導入なら、そのモードだけ0件になり、他の機能は通常どおり動きます。

### Drops でドロップして処理する
Launcher の横に出る小さなウィンドウに、2つのドロップ枠があります。

- **PDF化 (ppt/word)** — PowerPoint / Word ファイルをドロップすると、同じフォルダへ PDF を出力します。PowerPoint / Word が必要です。
- **登録済みフォルダへコピー** — ファイルやフォルダをドロップすると、`/DropDest` で登録したフォルダへコピーします。コピー時に名前を変えられます。Outlook メールの添付ファイルを直接ドロップすることもできます。

### Tasks で作業中の小さなタスクを持つ
Launcher の横に置ける、軽いタスク一覧です。初回起動時は畳んであります。`Alt+Shift+3` で表示でき、その設定は保存されます。

意図的に小さく作ってあります。通知なし、繰り返しタスクなし、チーム共有なし、クラウド同期なし。本格的なタスク管理が必要なら、本格的なツールを使ってください。

### CSVで出し入れする
Launcher の項目と Snippets は、どちらも CSV で書き出し・取り込みができます。

### 細かい便利機能
- `Alt+K`: Kind ごと（Snippets では Type ごと）の色マーカーを設定
- `Alt+R`: 並び順の切替
- `Alt+Z`: アプリ全体を 130% 表示に切替
- `Alt+S`: 検索欄の文字列で Google 検索

## こんな人に向いています
- Excel、OneNote、SharePoint、共有フォルダを毎日使う。
- よく使うファイルやWebページを探す時間が多い。
- メール、チャット、記録入力でよく使う文章がある。
- ブックマークや共有フォルダの場所を毎回探している。
- 大げさな自動化ではなく、日々の操作を少しずつ軽くしたい。
- Windows 標準機能だけでは、仕事の導線が足りないと感じている。

## 向いていない使い方
- すべての作業を自動化したい。
- クラウド同期や複数端末同期を前提にしたい。
- 法人向けの管理機能や配布統制が必要。
- Mac やスマートフォンでも同じ体験を使いたい。

## 基本操作

### 呼び出し
- `Alt+Space`: WinLauncher を表示
- `Esc`: 非表示

### Launcher
- `Ctrl+Enter`: 選択中の項目を開く
- `Alt+Shift+Space`: Explorerなどで選択中の項目を登録
- `Alt+N`: 手動登録
- `Alt+V`: クリップボードのURLやパスを登録
- `Alt+Enter`: 編集
- `Alt+Delete`: 削除
- `Alt+C`: パスやURLをコピー
- `Alt+O`: 親フォルダを開く
- `Alt+R`: 並び順切替
- `Alt+S`: Web検索補助

### Snippets
- `Alt+2`: Snippets へ移動
- `Ctrl+Enter`: 選択中の Snippet をコピー
- `Alt+N`: 新規登録
- `Alt+V`: クリップボードから登録
- `Alt+Enter`: 編集
- `Alt+Delete`: 削除

### 連動ウィンドウ
- `Alt+Shift+3`: Tasks の表示 / 非表示
- `Alt+Shift+4`: Drops の表示 / 非表示

ショートカットの一覧は、常にウィンドウ下部に表示されています。枠線が濃いチップにはツールヒントが付いているので、マウスを乗せると詳しい説明が出ます。

## サンプル設定
配布物の `ja\sample` フォルダには、架空の Launcher サンプルCSVが入っています。

このCSVは、最初に何を登録すればよいかをイメージするための参考用です。

含まれるファイル:
- `ja\sample\Launcher_Sample_JA.csv`
- `ja\sample\Snippets_Sample_JA.csv`
- `ja\sample\README_JA.txt`

注意:
- サンプルCSVは自動では読み込まれません。
- ChatGPT、YouTube、Amazon などの一般的なURLは `Browser`、フォルダは `Dir`、Officeファイルは `Excel` / `PowerPoint` / `PDF` / `OneNote` として入れています。
- Teams のチャネルとグループチャットは、追加の例として `Teams` にしています。
- Snippets には、メール返信、チャット連絡、会議メモ、作業ログ、SQL、Power Query などの定型文例を入れています。
- 架空のファイルパスは、そのままでは開けません。自分のPCや会社環境に合わせて書き換えてください。
- `CSV取込` で試す場合は、既存データと混ざるため、必要に応じて先にバックアップしてください。

## データ保存場所
WinLauncher のデータは、基本的に `%LocalAppData%\WinLauncher` 配下に保存されます。

主な保存先:
- Launcher: `%LocalAppData%\WinLauncher\commands.json`
- Snippets: `%LocalAppData%\WinLauncher\snippets.json`
- Snippet Type色設定: `%LocalAppData%\WinLauncher\snippet-type-colors.json`
- Launcher実行ログ: `%LocalAppData%\WinLauncher\launcher_runlog.json`
- Kind色設定: `%LocalAppData%\WinLauncher\kind-colors.json`
- Drops の登録先フォルダ: `%LocalAppData%\WinLauncher\drop-destinations.json`
- Tasks: `%LocalAppData%\WinLauncher\Tasks.json`
- Tasks / Drops の表示設定: `%LocalAppData%\WinLauncher\task-window-mode.json` / `drop-window-mode.json`
- 表示言語: `%LocalAppData%\WinLauncher\ui-language.txt`

## バックアップ
重要な登録データは、定期的にバックアップしてください。

最低限バックアップしたいもの:
- `%LocalAppData%\WinLauncher\commands.json`
- `%LocalAppData%\WinLauncher\snippets.json`

必要に応じてバックアップするもの:
- `%LocalAppData%\WinLauncher\kind-colors.json`
- `%LocalAppData%\WinLauncher\snippet-type-colors.json`
- `%LocalAppData%\WinLauncher\drop-destinations.json`
- `%LocalAppData%\WinLauncher\Tasks.json`

## 更新
更新前には、WinLauncher を終了し、必要なデータをバックアップしてください。

基本手順:
1. WinLauncher を終了する。
2. `%LocalAppData%\WinLauncher` の必要ファイルをバックアップする。
3. 新しい WinLauncher に差し替える。
4. 起動して、登録済みデータが表示されることを確認する。

## 注意事項
- WinLauncher は個人開発の Windows アプリです。
- 会社PCで利用する場合は、所属組織のルールに従ってください。
- セキュリティソフトや社内ポリシーにより、実行が制限される場合があります。
- SmartScreen などの警告が表示される場合があります。
- 重要な業務データの管理やバックアップは、利用者自身の責任で行ってください。
- クラウド同期や複数端末同期は提供しません。
- BOOTHで購入したダウンロード商品は、BOOTHの仕様上、購入後のキャンセル・返金ができません。
- 購入前に、対応環境・注意事項・サポート範囲をご確認ください。

## 使用許諾・再配布禁止
- 購入1件につき利用者1名（ギフトの場合は受取人1名）が利用できます。
- 個人利用・業務利用のどちらでも使用できます。
- アプリ、ZIP、説明書、サンプルファイル、ダウンロードリンクの第三者への共有、再配布、転売、再許諾、貸与、アップロード、転載、ミラー、同梱、譲渡を禁止します。
- 利用者ごとに個別に購入してください。
- 詳細は同梱の `ja\LICENSE.txt` をご確認ください。

Copyright © 2026 Ryuhi. All rights reserved.

## サポート範囲

### 対応できること
- 基本的な使い方の案内
- インストール・更新手順の案内
- 既知の不具合の共有
- 可能な範囲での不具合修正

### 対応できないこと
- 個別企業環境に合わせた導入支援
- 社内セキュリティ設定の変更
- 業務データの復旧保証
- 個別カスタマイズ開発
- 法人向け管理機能の提供

### 問い合わせについて
BOOTHの決済・購入処理については BOOTH の案内をご確認ください。

WinLauncherの使い方や不具合については、商品ページ記載の問い合わせ先へご連絡ください。

購入済みファイルを取得できない、またはダウンロードしたファイルが破損している場合は、BOOTHメッセージからご連絡ください。確認のうえ、ダウンロード案内の復旧または正常なファイルの再提供で対応します。この対応は返金を意味するものではありません。

## FAQ

### Q. 何のアプリですか？
よく使うファイル、フォルダ、Webページ、OneNote、SharePoint、共有フォルダ、定型文を `Alt+Space` からすばやく呼び出す Windows 実務用ランチャーです。

### Q. 最初に何を登録すればよいですか？
まずは、毎日開くファイル、よく使う共有フォルダ、よく貼る定型文を3つ登録するのがおすすめです。

### Q. Snippets はコード用ですか？
コードだけでなく、メール返信文、チャット連絡、作業メモ、入力テンプレ、チェックリストなどにも使えます。

### Q. インターネット接続は必要ですか？
基本機能はローカルで使う想定です。Web検索補助など、外部Webページを開く操作にはインターネット接続が必要です。

### Q. 会社PCで使えますか？
会社PCで利用できるかは、所属組織のルールやセキュリティ設定によります。利用前に社内ルールを確認してください。

### Q. サブスクですか？
いいえ。買い切りです。

### Q. 複数PCで同期できますか？
できません。クラウド同期や複数端末同期は提供していません。

### Q. Teams や SharePoint も登録できますか？
URLとして開ける Teams のチャネル、グループチャット、会議リンク、SharePoint ページなどは登録できます。

また、Windowsのエクスプローラーで開けるWebDAV形式のSharePointフォルダも、Launcherの登録対象として扱えます。

ただし、会社やMicrosoft 365環境の設定によっては、登録しても開けない場合があります。

### Q. PC内を検索しますか？
それ自体はしません。WinLauncher は、あなたが登録したものを表示します。Everything(voidtools) を入れて `/Everything` モードを使った場合だけ、Everything 経由でPC内のファイルを検索します。これは任意で、他の機能は Everything に依存しません。

### Q. Tasks や Drops は使えますか？
使えます。Tasks は初回起動時は畳んであり、`Alt+Shift+3` で表示できます。Drops は最初から表示され、「PDF化 (ppt/word)」と「登録済みフォルダへコピー」の2つの枠があります。PDF化には PowerPoint / Word が必要です。

### Q. データはバックアップできますか？
はい。`%LocalAppData%\WinLauncher` 配下の JSON ファイルをバックアップしてください。
