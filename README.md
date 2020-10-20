# WellComp LP

## 公開手順
GitHub Actions(CI/CD)が設定されているため`master`に`push`すれば自動的に公開されます。  
変更を確認する際ブラウザーのキャッシュを消すように。

##### 手動 (ht.sfc.keio.ac.jp)
CIが壊れた場合のみ
1. daliにssh
2. rootに切り変える `su -`
3. `/home/www/public_html/rgs/wellcomp`へcd
4. `git pull origin master`

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
