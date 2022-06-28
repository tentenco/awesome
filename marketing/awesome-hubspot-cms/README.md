# HubSpot CMS Boilerplate

<p對齊=“中心”>
  在 HubSpot CMS 上構建出色網站的直接起點。
</p>

<p對齊=“中心”>
  <a href="https://github.com/HubSpot/cms-theme-boilerplate/wiki">文檔</a> |
  <a href="https://boilerplate.hubspotcms.com/">演示網站</a> |
  <a href="https://github.com/HubSpot/cms-theme-boilerplate/blob/main/CONTRIBUTING.md">貢獻</a>
</p>

[![當前版本](https://img.shields.io/github/v/release/HubSpot/cms-theme-boilerplate)](https://github.com/HubSpot/cms-theme-boilerplate/releases )
[![最新提交](https://img.shields.io/github/last-commit/HubSpot/cms-theme-boilerplate)](https://github.com/HubSpot/cms-theme-boilerplate/commits /主要的）
[![貢獻者](https://img.shields.io/github/contributors/HubSpot/cms-theme-boilerplate?logo=blue)](https://github.com/HubSpot/cms-theme-boilerplate/圖表/貢獻者）
[![GitHub 觀察者](https://img.shields.io/github/watchers/HubSpot/cms-theme-boilerplate?style=social)](https://github.com/HubSpot/cms-theme-boilerplate /觀察者）
[![GitHub 星星](https://img.shields.io/github/stars/HubSpot/cms-theme-boilerplate?style=social)](https://github.com/HubSpot/cms-theme-boilerplate /觀星者）
[![GitHub 分叉](https://img.shields.io/github/forks/HubSpot/cms-theme-boilerplate?style=social)](https://github.com/HubSpot/cms-theme-boilerplate /網絡/成員）
[![HubSpot 網站評分](https://img.shields.io/badge/HubSpot%20website%20grader%20score-97-brightgreen)](https://website.grader.com/tests/boilerplate.hubspotcms .com)
[![Google Lighthouse 桌面性能得分](https://img.shields.io/badge/Google%20Lighthouse%20desktop%20performance%20score-98-brightgreen)](https://developers.google.com/web/工具/燈塔）
[![Google Lighthouse SEO 得分](https://img.shields.io/badge/Google%20Lighthouse%20SEO%20score-100-brightgreen)](https://developers.google.com/web/tools/lighthouse )
[![Google Lighthouse 可訪問性評分](https://img.shields.io/badge/Google%20Lighthouse%20accessibility%20score-100-brightgreen)](https://developers.google.com/web/tools/lighthouse )
[![許可證](https://img.shields.io/badge/license-Apache%20Version%202.0-red)](https://github.com/HubSpot/cms-theme-boilerplate/blob/main/執照）

＃＃ 目的

[HubSpot CMS Boilerplate](https://designers.hubspot.com/docs/building-blocks/themes/hubspot-cms-boilerplate) 旨在為開發人員在網站構建過程中提供先機。雖然 HubSpot CMS 樣板代表了 HubSpot 固執己見的最佳實踐，但我們打算從類似的項目和反饋中學習。我們希望它為所有網站項目提供靈感和實用性！

＃＃ 入門

### 使用 HubSpot CMS CLI 下載 HubSpot CMS 樣板：

在開始之前，您需要安裝 [Node.js](https://nodejs.org)、[HubSpot CMS CLI](https://developers.hubspot.com/docs/cms/guides/getting- started-with-local-development#install-dependencies) 已安裝，我們強烈建議您為您的質量保證/測試環境。

1. 導航到您要用於項目的目錄
2. 運行 `hs create website-theme <directory>` 從 HubSpot CMS Boilerplate 創建一個項目
3. [配置](https://developers.hubspot.com/docs/cms/guides/getting-started-with-local-development#configure-the-local-development-tools) 門戶的本地開發工具( s) 你想用於你的項目。
4. 運行`hs watch --portal=<portal> src <directory> --initial-upload`上傳項目中的所有文件並【關注變化】（https://developers.hubspot.com/docs/ cms/developer-reference/local-development-cms-cli#watch) 到 `src` 目錄中的文件

請參考我們的_[在 HubSpot CMS 上開發的快速入門指南](https://developers.hubspot.com/docs/cms/guides/getting-started)_ 和我們的_[本地開發入門](https: //designers.hubspot.com/tutorials/getting-started-with-local-development)_ 文章了解更多信息。

### 要使用 GitHub 和 GitHub Actions 在項目中使用版本控制：

1. [Fork](https://help.github.com/en/github/getting-started-with-github/fork-a-repo) HubSpot CMS Boilerplate 存儲庫和[clone](https://help. github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository) 你的分叉存儲庫到你的計算機
2. [在您的分叉存儲庫中設置 GitHub 機密以加密敏感信息以防止公開顯示](https://help.github.com/en/actions/configuring-and-managing-workflows/creating-and-storing-encrypted-秘密）用於`HUBSPOT_PORTAL_ID`和`HUBSPOT_PERSONAL_ACCESS_KEY`
3. 在 `.github/workflows/deploy.yml` 文件中更新您將在設計管理器中部署到的目錄的名稱（當前默認的 `dest_dir` 是 `cms-theme-boilerplate`）
4. 通過推送到你的分叉存儲庫的“主”分支，將更改部署到你的設計管理器

請參考我們的 [_HubSpot CMS 部署 GitHub 操作頁面_](https://github.com/marketplace/actions/hubspot-cms-deploy) 和_[使用 GitHub 操作文章設置與 GitHub 存儲庫的持續集成](https:// /designers.hubspot.com/tutorials/github-integration)_ 了解更多信息。

＃＃ 時尚指南

有關 HubSpot CMS Boilerplate 推薦的最佳實踐和代碼格式的詳細信息，請參考我們的 [樣式指南](https://github.com/HubSpot/cms-theme-boilerplate/blob/master/STYLEGUIDE.md)。

## 貢獻

如果您有興趣為 HubSpot CMS 樣板做出貢獻，請閱讀 [CONTRIBUTING.md](https://github.com/HubSpot/cms-theme-boilerplate/blob/master/CONTRIBUTING.md) 和 [STYLEGUIDE.md ](https://github.com/HubSpot/cms-theme-boilerplate/blob/master/STYLEGUIDE.md) 了解如何報告問題、提出功能請求或提出拉取請求。

## 版本控制

以前的版本及其文檔可用於 [下載](https://github.com/HubSpot/cms-theme-boilerplate/releases)。為了提供對未來版本的透明度，我們創建了一個項目板，記錄我們為每個 [即將到來的主要和次要版本]（https://github.com/HubSpot/cms-theme-boilerplate/projects）做準備的計劃。

＃＃ 社區

您可以在 [HubSpot Developer Slack] (https://designers.hubspot.com/slack) 的 #hs-cms-boilerplate 頻道中了解 HubSpot CMS 樣板的更新和討論。

＃＃ 執照

該代碼可在 [Apache 許可證，版本 2.0](https://github.com/HubSpot/cms-theme-boilerplate/blob/main/LICENSE) 下獲得