# Todo List

這是一個基於 React 框架的網頁版待辦事項，提供新增、編輯、刪除、完成標記、依日期排序及依優先順序排序的功能。

## 專案架構

todo-list/
├── public/               # 靜態資源
├── src/                  # 源碼
│   ├── App.js            # 主應用程式
│   ├── App.css           # 應用程式樣式
│   ├── index.js          # 入口文件
├── package.json          # 專案配置
└── README.md             # 專案說明文件

## 功能特色

- **基本功能** : 查看/新增/刪除待辦事項，並可以標記完成/取消標記完成待辦事項
- **進階功能-設定待辦事項**：輸入待辦事項內容時可以選擇優先順序（普通件、急件、超急件）。
- **進階功能-編輯待辦事項**：未完成待辦事項可修改內容，已完成待辦事項僅可刪除。
- **進階功能-排序待辦事項**：
  - 依日期排序：按新增日期排序。
  - 依優先順序排序：按優先級（超急件 > 急件 > 普通件）排序。
- **本地儲存**：透過 `localStorage` 保存待辦事項，重新整理頁面後資料不會丟失。
- **動畫效果**：勾選或取消勾選時，待辦事項有淡入淡出的動畫效果。

## 使用技術

- **React**：用於構建使用者介面。
- **CSS**：用於設計明亮且繽紛的樣式。
- **localStorage**：用於保存待辦事項資料。
