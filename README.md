# Vue 後台管理系統模板

一個專為後台管理系統設計的 Vue 2 自定義模板，集成了 Vuetify 2、Vuex、Vue Router 等常用工具，幫助您快速開發高效、美觀的管理介面。

## 特色功能

- 🎨 基於 Vuetify 2 的 UI 界面
- 📊 使用者管理範例頁面
- 🌐 API 請求封裝與錯誤處理
- 🌍 多環境配置（開發、測試、生產）
- 🔄 全局錯誤日誌收集與展示

## 快速開始

### 安裝前提

確保已安裝最新版本的 Vue CLI：

```bash
# 使用 npm 全局安裝 Vue CLI
npm install -g @vue/cli

# 從模板創建新專案
# 使用模板創建專案
vue create --preset M4ORE/vue2-template 新專案名稱

# 如果是私有倉庫，請使用
vue create --preset M4ORE/vue2-template --clone 新專案名稱
```

### 啟動新專案

```bash
# 進入專案目錄
cd 新專案名稱

# 安裝依賴
npm install

# 啟動開發服務器
npm run serve
```

## 環境相關命令

```bash
# 開發環境啟動服務
npm run serve

# 使用 production 環境啟動服務
npm run pro-serve

# 使用 m4ore 環境啟動服務
npm run m4ore-serve

# 編譯與打包代碼用於生產環境
npm run build

# 編譯與打包代碼用於 m4ore 環境
npm run pro-build
```

## 專案架構

```
├── public/                 # 靜態資源
├── src/
│   ├── api/                # API 請求模組
│   ├── assets/             # 資源文件
│   ├── components/         # 全局組件
│   ├── layout/             # 頁面布局
│   ├── libs/               # 工具庫
│   ├── plugins/            # 插件配置
│   ├── router/             # 路由設置
│   ├── store/              # Vuex 狀態管理
│   ├── utils/              # 工具函數
│   ├── views/              # 頁面視圖
│   ├── App.vue             # 主應用組件
│   ├── main.js             # 應用入口
│   └── errorPlugin.js      # 錯誤處理插件
├── .env.development        # 開發環境變數
├── .env.m4ore             # m4ore 環境變數
├── .env.production         # 生產環境變數
├── babel.config.js         # Babel 配置
└── vue.config.js           # Vue CLI 配置
```
