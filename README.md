# ISSENO Corporate Website

このフォルダは、株式会社ISSENOの静的コーポレートサイト一式です。

## 含まれるファイル
- `index.html` : トップページ
- `robots.txt` : 検索エンジン向け設定
- `sitemap.xml` : サイトマップ
- `vercel.json` : Vercel向け設定

## 公開方法
1. フォルダ内の中身を GitHub リポジトリ直下にアップロード
2. Vercel でそのリポジトリを Import
3. Framework Preset は `Other`
4. Build Command は空欄のまま Deploy

## 公開後に必ずやること
- `index.html` の `og:url`
- `robots.txt` の Sitemap URL
- `sitemap.xml` の URL

上記の `https://example.com/` を実際の公開URLまたは独自ドメインに変更してください。
