# skill-sheet
ITに関するスキルの網羅表

## 静的HTML公開（GitHub Pages）

このリポジトリでは、リポジトリルート配下の `site/` フォルダの中身をそのまま GitHub Pages に公開する設定にしています。

### 使い方

1. 公開したい静的ファイル（`index.html`、CSS、JS、画像など）を `site/` 配下に配置する
2. 変更をコミットして `main` ブランチに反映する
3. GitHub の `Settings > Pages` で `Build and deployment` の `Source` を `GitHub Actions` にする

### 公開先フォルダを変えたい場合

`.github/workflows/deploy-static-html.yml` の `PUBLISH_DIR` を希望フォルダ名に変更してください。  
そのフォルダ配下がそのまま公開されます。
