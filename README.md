# WellComp LP

## 公開手順 (jn.sfc.keio.ac.jp)
変更を確認する際ブラウザーのキャッシュを消すように。
1. JNNET VPNに接続
2. `jn.sfc.keio.ac.jp`にssh
3. `/srv/www/wellcomp`へcd
4. `git pull origin master` (sudoが必要です)

## メンテナンス
#### メンバー追加
1. 250x334の画像を用意
2. `assets/images/members/` に入れる
3. `index.html`のmembers sectionを編集

#### プロジェクト追加
1. 720x480の画像を用意
2. `assets/images/` に入れる
3. `index.html`のprojects sectionを編集
4. 多言語対応するため文書は`<body>`タグの下にある`<script>`から変更

#### 多言語対応
`i18next`フレームワークを使用しています
