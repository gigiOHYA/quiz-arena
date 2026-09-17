# 問答擂台 Quiz Arena

課堂分組問答遊戲：左右兩隊在同一畫面上各自限時作答，答對得分，全部答完自動結算比分。

- **線上網址**：`https://<你的 GitHub 帳號>.github.io/quiz-arena/`（第一次部署完成後補上實際網址）
- **規格文件**：[SPEC.md](./SPEC.md)
- **測試清單**：[TESTING.md](./TESTING.md)
- **部署方式**：push 到 `main` 分支後，GitHub Actions 會自動跑測試並部署到 GitHub Pages（見 [.github/workflows/deploy.yml](./.github/workflows/deploy.yml)），不需要手動操作。第一次啟用前，要先到 repo 的 **Settings → Pages → Build and deployment → Source** 選成 **GitHub Actions**。
