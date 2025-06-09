
# CMS 比較：Ghost、Drupal、Joomla 用於模式庫網站

## 需求
- 建立類似 [ScrumPLoP](https://www.scrumplop.org/) 的模式庫網站
- 功能：使用者註冊、內容提交、內容分類、可能的審核流程
- 考量因素：價錢、維護性、自由度、可部署性

## 比較表格

| 工具    | 價錢                      | 維護性   | 自由度   | 可部署性   |
|---------|--------------------------|----------|----------|------------|
| Ghost   | $9-$199/月               | 簡單     | 中等     | 簡單       |
| Drupal  | $3-$50/月 (共享) 到數千/月 (管理) | 複雜     | 高       | 中等       |
| Joomla  | $1.99-$3.99/月(特價!) | 中等     | 高       | 中等       |

## 建議
- **Ghost**：適合快速部署和簡單維護，推薦給技術資源有限的實驗室。
- **Drupal**：適合需要高度自定義的複雜模式庫，需技術支持。
- **Joomla**：適合靈活且維護負擔適中的中型模式庫。


# CMS 比較：Ghost、Drupal、Joomla 用於模式庫網站 - 詳細報告

## 需求
- 建立類似 [ScrumPLoP](https://www.scrumplop.org/) 的模式庫網站
- 功能：使用者註冊、內容提交、內容分類、可能的審核流程
- 考量因素：價錢、維護性、自由度、可部署性

## 背景與需求
您的目標是為實驗室建立一個類似 [ScrumPLoP](https://www.scrumplop.org/) 的模式庫網站，允許使用者撰寫和發布模式（patterns）。網站需要以下功能：
- **使用者註冊與管理**：允許使用者創建帳戶並提交內容。
- **內容創建與編輯**：提供簡單的編輯介面，供使用者撰寫模式。
- **內容分類與組織**：支援模式的分類和標籤，方便檢索。
- **主題與佈局自定義**：允許調整網站外觀以符合實驗室需求。
- **擴展性**：支援內容和使用者增長。

為了選擇最適合的 CMS 工具，我比較了 Ghost、Drupal 和 Joomla，基於以下四個因素：價錢、維護性、自由度和可部署性。以下是詳細分析。

## 比較分析

### 1. 價錢
- **Ghost**：
  - **開源版本**：免費，需自行主機，伺服器成本約 $5-$20/月（例如 [DigitalOcean](https://www.digitalocean.com/)）。
  - **管理式主機（Ghost(Pro)）**：起價 $9/月（Starter 計劃，500 名會員，1 名管理員），最高 $199/月（Business 計劃，10,000 名會員，無限管理員）。參考 [Ghost Pricing](https://ghost.org/pricing)。
  - **額外成本**：可能需要電子郵件服務（如 Mailgun，約 $0.80/千封）或 CDN（如 Cloudflare，免費至 $20/月）。
  - **適用性**：適合預算有限但希望簡單管理的實驗室，管理式主機提供完整服務但成本較高。
  - **影片介紹** : [Ghost Tutor](https://www.youtube.com/watch?v=58hbEjZPm4s)
![Ghost](/pic/ghost.png)
- **Drupal**：
  - **開源版本**：免費，共享主機起價 $2.99/月（例如 [Hostinger](https://www.hostinger.com/drupal-hosting)），管理式主機（如 [Acquia](https://www.acquia.com/)）從 $199/月到數千美元/月。
  - **適用性**：適合需要企業級功能的實驗室，但成本可能較高，特別是需要專業支持時。
![Drupal](/pic/drupal.png)
- **Joomla**：
  - **開源版本**：免費，共享主機起價 $2.54/月（例如 [Hostinger](https://www.hostinger.com/joomla-hosting)），高階主機（如 [Ionblade](https://www.ionblade.com/)）最高 $60/月。
  - **額外成本**：某些付費擴展或主題成本約 $10-$100，總體低於 Drupal。
  - **適用性**：適合預算有限且需要靈活性的實驗室，成本效益高。
![Joomla](/pic/Joomla.png)
- **結論**：Joomla 和 Drupal 的共享主機成本最低，Ghost 的管理式主機起價較高但提供完整服務。對於實驗室，Joomla 可能是最經濟的選擇，Ghost 適合簡單管理，Drupal 適合高階需求但成本較高。

### 2. 維護性
- **Ghost**：
  - **易用性**：提供直觀的 Markdown 編輯器和管理面板，適合無技術背景的使用者。
  - **更新**：Ghost(Pro) 提供自動更新，自建主機需手動更新，社群支持良好但規模較小。
  - **適用性**：適合技術資源有限的實驗室，維護負擔低，適合快速上手。
- **Drupal**：
  - **易用性**：需要技術知識，特別是自定義模組或工作流程的設置。
  - **更新**：穩定但需定期手動更新，社群支持強大，參考 [Drupal Community](https://www.drupal.org/community)。
  - **適用性**：適合有技術團隊的實驗室，維護較複雜，可能需要專職管理員。
- **Joomla**：
  - **易用性**：介於 Ghost 和 Drupal 之間，適合中級技術能力的使用者。
  - **更新**：更新穩定，社群支持中等，參考 [Joomla Community](https://community.joomla.org/)。
  - **適用性**：適合有一定技術能力的實驗室，維護負擔適中。

**結論**：Ghost 維護最簡單，適合無技術背景的實驗室。Drupal 維護最複雜，需專業支持。Joomla 居中，適合中級技術能力。

### 3. 自由度
- **Ghost**：
  - **自定義性**：支援主題自定義（使用 Handlebars 模板）和 Content API，參考 [Ghost API](https://ghost.org/docs/content-api/)，但插件生態較小，限制了某些進階功能。
  - **功能**：內建會員系統，適合模式提交，但審核流程需透過 API 或外部工具（如 Zapier）實現。
  - **適用性**：適合簡單的模式庫網站，對於複雜結構化需求可能需要額外開發。
- **Drupal**：
  - **自定義性**：高度靈活，支援複雜內容類型和自定義模組，參考 [Drupal Modules](https://www.drupal.org/project/project_module)。
  - **功能**：內建工作流程管理，適合需要細緻分類和審核的模式庫。
  - **適用性**：適合需要高度結構化的模式庫，但需要開發技能。
- **Joomla**：
  - **自定義性**：提供豐富的擴展，參考 [Joomla Extensions](https://extensions.joomla.org/)，靈活性高於 Ghost。
  - **功能**：支援多層級權限和內容管理，審核功能可透過擴展實現。
  - **適用性**：適合靈活但不需過多技術知識的模式庫。

**結論**：Drupal 提供最高自由度，適合複雜需求。Joomla 次之，提供靈活的擴展選項。Ghost 自定義性中等，適合簡單需求。

### 4. 可部署性
- **Ghost**：
  - **部署方式**：Docker 部署簡單，參考 [Ghost Docker](https://ghost.org/docs/hosting/)，Ghost(Pro) 提供一鍵部署。
  - **環境**：支援本地端和雲端，配置簡單，適合快速設置。
  - **適用性**：適合無需複雜伺服器管理的實驗室，部署最簡單。
- **Drupal**：
  - **部署方式**：支援 Docker，但配置較複雜，參考 [Drupal Docker](https://www.drupal.org/docs/installation)。
  - **環境**：需要 PHP 和資料庫配置，雲端部署需專業知識。
  - **適用性**：適合有技術能力的實驗室，部署耗時較多。
- **Joomla**：
  - **部署方式**：支援 Docker，但不如 Ghost 簡單，參考 [Joomla Docker](https://hub.docker.com/_/joomla)。
  - **環境**：需要 PHP 和資料庫配置，部署難度中等。
  - **適用性**：適合有一定技術能力的實驗室，部署較 Ghost 複雜。

**結論**：Ghost 部署最簡單，適合快速上線。Drupal 和 Joomla 需要更多配置，適合有技術支持的實驗室。

## 針對需求分析
您的模式庫網站需要支援使用者註冊、內容提交、分類和可能的審核流程：
- **Ghost**：內建會員系統，適合快速實現使用者註冊和內容提交。審核流程需透過 API 或外部工具實現，分類功能透過標籤簡單有效。
- **Drupal**：支援複雜的內容類型和內建工作流程，適合需要細緻分類和審核的模式庫，但需開發支持。
- **Joomla**：透過擴展實現會員管理和審核功能，靈活性高，適合中型社群。

## 建議
- **Ghost**：推薦給希望快速部署且維護簡單的實驗室。適合小型到中型模式庫，無需複雜技術支持。使用 [Ghost(Pro)](https://ghost.org/pricing) 可快速上線，或使用 Docker 進行自建部署。
- **Drupal**：適合需要高度自定義和結構化內容的實驗室，特別是如果模式庫需要複雜分類或審核流程，但需技術團隊支持。推薦使用 [Pantheon](https://pantheon.io/) 或 [Acquia](https://www.acquia.com/) 的管理式主機。
- **Joomla**：適合希望平衡靈活性和維護性的實驗室，適合中型模式庫。推薦使用 [Hostinger](https://www.hostinger.com/joomla-hosting) 或 [Rochen](https://www.rochen.com/joomla-hosting/) 的主機服務。

## 結論
Ghost 是最簡單的選擇，適合快速建立模式庫網站，特別是如果實驗室技術資源有限。Drupal 提供最大自由度，適合需要複雜功能的網站，但維護成本高。Joomla 是中間選擇，靈活且維護負擔適中。根據您的技術能力和預算，Ghost 是最直接的選擇，Drupal 適合進階需求，Joomla 提供平衡方案。

## Key Citations
- [Ghost Official Managed Hosting Pricing](https://ghost.org/pricing)
- [Drupal Web Hosting Options](https://www.drupal.org/hosting)
- [Hostinger Joomla Hosting Plans](https://www.hostinger.com/joomla-hosting)
- [Drupal Website Cost Breakdown](https://cmsminds.com/blog/drupal-website-cost/)
- [Best Drupal Hosting Services 2025](https://cybernews.com/best-web-hosting/drupal-hosting/)
- [Best Joomla Hosting Providers 2025](https://www.ukwebhostreview.com/best-joomla-hosting/)
- [Joomla Hosting by Rochen](https://www.rochen.com/joomla-hosting/)

## 參考資料
- [Ghost Pricing](https://ghost.org/pricing)
- [Drupal Hosting](https://www.drupal.org/hosting)
- [Joomla Hosting](https://www.hostinger.com/joomla-hosting)
