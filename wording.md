---
title: Foobar
separator: <!--s-->
verticalSeparator: <!--v-->
# theme: simple
theme: moon
highlight-theme: github
revealOptions:
  transition: 'fade'
---


# 2022 Resume

<!--v-->

## Index

- Intro
- Professional Skill
- Attitude
- Show Works

<!--s-->

## Intro

劉冠林 (JasonXDDD / Lawry / 罐罐XD)

### 學歷
淡江大學 資訊工程 學士 <br/>
台北教育大學 玩具與遊戲設計 碩士<br/>

### 資歷
**獨立接案** (2015-2020)<br />
**MyProGuide**：Web Developer (2017-2019)<br/>
**Leadtek**：Engineer (2019-2022)<br/>

### 活動
創辦 EXD FrontEnd 讀書會<br />
2019 Apple 應用創新賽 一等獎、最佳展演<br />
建立 Leadtek 讀書會, CI/CD 文化<br />

### 證照
Apple iOS Developer with Swift - L1

<!--v-->

## 技能點 Professional Skill
- Web Frontend Framework： `Angular v4+`, `Vue v2` / `Nuxt`, `React.js` / `Next.js`
- Web Backend Framework: `Koa.js + MySQL`, `JAVA Spring Boot + MariaDB / HANA`
- Mobile APP: `PWA (WebApp)`, `React Native (Hybrid App)`
- Styling Tool: `Bootstrap.css 4+`, `Tailwind.css 2+`, `SASS/SCSS (CSS Preprocessor)` ...
- Other Web Topics: `Web Vitals`, `SEO`, `Data Visuallization`, `UI/UX Design Flow`, `OAuth`, `Payment` ...
- Other Skills: `Git`, `DevOps (CI/CD)`, `Scrum` ...

---
## 工作態度 Attitude
- KISS (Keep It Simple, Stupid)
- YAGNI (You Aren't Gonna Need It)
- Clean Code
- Code Quality

<!--s-->

## Show Works

### MyProGuide 產品體系
作為公司的首席工程師，主要負責所有電商產品的網站開發及使用者體驗分析，
網站主要由我與兩位後端工程師負責，為期一年半。

使用 GitHub 來管理 source code，
利用 Webhooks 推到 AWS 上的 Code Pipeline 來做 build process，
所有服務都放在 AWS EC2 上。

團隊開發以 Scrum 來 run，每週一次 sprint 來開發。

開發成品：
- MyProGuide 主網站 (Angular)
  - 入口網站、導遊個人履歷
  - 技術：SEO、i18n、RWD、Google 結構化資料、OAuth、金流 (Paypal, Ecpay)

- Tour 電商平台 (Vue/Nuxt)
  - 定點旅遊購物、合作夥伴行程購物、國外旅遊服務
  - 技術：SEO、i18n、PWA、全球化、Google 結構化資料、OAuth、金流 (Paypal, Ecpay)

- Blog (Wordpress)
  - 官方旅遊介紹、各地區導遊景點介紹
  - 技術：wordpress、SEO、i18n

- Customized Tour (Angular)
  - 客製私人導遊服務、專屬客製化行程安排
  - 技術：i18n、RWD

- Dashboard (Angular)
  - 管理後台、個人資料、認證導遊審核機制、網站管理、權限控管、訂單管理、各類報表
  - 技術：i18n、RWD、資料視覺化、File Export

事件：
- 參加世界範圍的 Web Summit 年會，曾與國外的 partner 共同開發一段時間


### Leadtek 專案及產品
作為部門的主要前端工程師，接手大部分部門的專案及產品開發，
大部分案子都是做 Dashboard 及大數據 AI 呈現數據，所以有很多屬於資料視覺化的技術內容。

由於之前公司沒有版控及開發流程，導入使用 Git Flow，
並架設 GitLab 及 GitLab CI ...等 DevOps，並協同 Slack, Jira 使用。


開發成品：
- 教育局倉儲平台 (Vue/Nuxt)
- 情資分析平台 (Vue)
- ProfitPoint (Vue/Nuxt)
- 教育資料倉儲分析產品 (Vue)

事件：
- 協助導入開發工具，建立開發流程及 DevOps
- 新辦技術分享會、Side Project Hackthon
- 協助部門通過三張資安 ISO 認證


### 個人接案
自 2015 年開始接案來做練手，至目前都偶爾有組隊接案。
雖然案子類型主要是網站建置，但是都是來自各行各業，有著不同的需求，這是蠻有趣的地方。

開發成品：
- SOGO 世芥蘭業 (Angular)
  - 追蹤各個品種的蘭花，追蹤生長過程及品種紀錄，提供各地的培植場使用。

- Taipower 台電供電線路智慧故障定位系統 (Angular)
  - 透過分析電譯數據，定位出故障的路燈座標，以及即時通知修復狀況。

- 奇異科技 自動化工廠 (React)
  - 協助將工廠內的機器導入物聯網，製作網路平台呈現數據。

- TOFAS 台灣骨科足踝醫學會 (Vue/Nuxt)
  - 幫助台北榮總骨科建立協會官網。


### 其他
其餘個人的 Side Porject 及 參賽得獎作品。

#### BottleNeko 貓罐子
一款紙牌 TCG 遊戲的輔助工具，幫助玩家製作牌組及檢索想要的牌。
原本想說當成 Side Project 幫助我玩遊戲使用，
如今平台已登入帳號已高達 3k+，每月高達 2w 的使用者使用，包含香港、馬來西亞、日本、美國...等地區。

整個專案由我一人架設，包括：
- 爬資料 (python, node.js)
- 伺服器 (Koa.js + MySQL)
- 網站 (Vue/Nuxt)
- APP (PWA WebApp)
- 社群經營

另一個 V2 網站：
- 伺服器 (Koa.js + MySQL)
- 網站 (React/Next)

網站原本放在 Google Firebase (GCP)上，但後來使用者越來越多，就搬移至 AWS EC2 上。
技術：SEO、i18n、PWA、爬蟲、OAuth、金流 (Ecpay)


#### 從前從前
2019 Apple 應用創新賽，在台灣取得第一名後，代表台灣參加中華區比賽，取得一等獎及最佳展演獎。
這款 APP 是希望親子共同遊玩，藉由靈活簡單的擺放角色、場景，並錄製過程，來啟發小朋友創作故事。
APP 以 React Native + Swift 來開發。