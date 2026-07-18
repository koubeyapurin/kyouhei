# ヤング人材センター

奥池地区向けのお手伝いサービスを案内する、静的な1ページサイトです。

## 公開方法（GitHub Pages）

1. GitHubで新しいリポジトリを作成します。
2. このフォルダーの内容を `main` ブランチへpushします。
3. リポジトリの **Settings → Pages** を開きます。
4. **Build and deployment** のSourceを **Deploy from a branch** にします。
5. Branchで **main** と **/(root)** を選び、保存します。

数分後、GitHub Pagesに表示されるURLからサイトを閲覧できます。

## ローカル確認

`index.html` をブラウザで直接開くか、ローカルHTTPサーバーで確認できます。

```powershell
python -m http.server 8000
```

起動後、`http://localhost:8000` を開いてください。

## 公開前の確認事項

このサイトには氏名、顔写真、電話番号、メールアドレス、LINEのQRコードが含まれています。公開すると誰でも閲覧できるため、掲載内容に問題がないことを確認してください。

公開URLが決まったら、SNS共有時の表示を整えるため `index.html` の `<head>` に `og:url` と `og:image` を追加できます。

## 権利

掲載している文章・画像の無断転載を禁止します。
