# Legend of YMIR — シーズン3「競争のシーズン」クラン資料

クランメンバー向けのシーズン情報ページです。
イベント製作レシピ、火種の狩り場、バルザグルズ湧き場所MAPをまとめています。

データ出典：[7月14日パッチノート](https://www.legendofymir.com/ja/news/release/746673)／[7月14日イベント案内](https://www.legendofymir.com/news/notice/746645)

## GitHub Pages で公開する手順

1. GitHubで新しいリポジトリを作成（例：`ymir-season3`。クラン外に見せたくない場合は注意 — GitHub Pagesは無料プランではPublicリポジトリのみ公開可能）
2. このフォルダの中身（`index.html`、`images/`、`README.md`）をリポジトリにアップロード
   - Webからでも可能：リポジトリページ →「Add file」→「Upload files」
3. リポジトリの **Settings → Pages** を開く
4. 「Build and deployment」→ Source を **Deploy from a branch**、Branch を **main / (root)** に設定して Save
5. 数分後、`https://<ユーザー名>.github.io/ymir-season3/` でページが公開されます

このURLをクランのDiscord/LINEに固定しておけば全員がいつでも参照できます。

## MAPスクショの追加方法

`images/maps/` に以下のファイル名で画像を置くだけで、ページに自動で表示されます（未登録の枠は「スクショ募集中」の点線表示になります）。

| 出現地域 | ファイル名 |
|---|---|
| ラグナロクの谷 | `ragnarok-valley.png` |
| ラグナロクの分かれ道 | `ragnarok-crossroads.png` |
| 世界樹の峡谷 深層部 | `worldtree-deep.png` |
| ニザヴェッリル峡谷 | `nidavellir-canyon.png` |
| ヒルドの迷宮 | `hilder-labyrinth.png` |

- 湧き位置に○や矢印などの印をつけたスクショ推奨
- GitHub Webからのアップロード：`images/maps/` フォルダを開く →「Add file」→「Upload files」
- `.jpg` を使いたい場合は `index.html` 内の該当ファイル名の拡張子を `.jpg` に変更してください

## メモの更新方法

各MAPカードの「メモ：」欄や「クラン内メモ欄」は `index.html` を直接編集して追記できます。
GitHub Web上でも `index.html` を開いて鉛筆アイコン（Edit）から編集 → Commit で反映されます。

## 主要な期限

| 内容 | 期限 (UTC+8) |
|---|---|
| 製作イベント「燃え上がる競争の火種」 | 2026/8/11 07:00 |
| イベントコレクション「勝者の記章」登録 | 2026/8/18 07:00 |
| シーズン3 終了 | 2026/9/8 メンテ前 |
| ⚠ 黄金の角笛 +10未満は削除 | シーズン終了時 |
