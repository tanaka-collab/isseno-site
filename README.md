# ISSENO 公開用サイト一式

このフォルダは、ビルド不要でそのまま Vercel にアップできる静的サイト一式です。

## 入っているもの
- `index.html` : トップページ
- `robots.txt` : クローラー向け設定
- `sitemap.xml` : サイトマップ
- `vercel.json` : Vercel 用設定

## 公開手順（いちばん簡単）
1. Vercel にログイン
2. `Add New` → `Project` → `Browse All Templates` ではなく、右上の `Import` か `Deploy` を選ぶ
3. このフォルダをアップロード
4. 公開URLが発行されたら表示確認

## 独自ドメインを付ける場合
1. Vercel の対象プロジェクトを開く
2. `Settings` → `Domains`
3. 取得したドメインを追加
4. Vercel が表示する DNS 設定を、ドメイン会社側で設定

## 公開後に必ず直すところ
独自ドメインや Vercel の URL が決まったら、次の2ファイル内の `https://example.com/` を実際のURLに置き換えてください。
- `robots.txt`
- `sitemap.xml`

例：
- `https://isseno.vercel.app/`
- `https://isseno.co.jp/`

## Google に載せる流れ
1. Google Search Console にサイトを登録
2. `sitemap.xml` を送信
3. トップURLのインデックス登録を申請

## 追加したほうがよい項目
- 正式な所在地（番地まで）
- 問い合わせ先メールアドレス
- プライバシーポリシー
- 採用情報ページ
- 実績 / 導入事例
