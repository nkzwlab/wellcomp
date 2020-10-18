# WellComp LP

## 公開手順
今の所、CIがないため、手動でpullする必要があります  
##### ht.sfc.keio.ac.jp
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
