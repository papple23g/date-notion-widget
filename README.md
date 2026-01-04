# 數位時鐘 Widget

這是一個美觀的數位時鐘 widget，設計風格參考 Notion 的時鐘卡片介面。

## 功能特色

- ✅ **即時更新**：每秒自動更新時間
- ✅ **12 小時制**：顯示 AM/PM
- ✅ **日期顯示**：顯示當天日期和星期
- ✅ **響應式設計**：適應不同螢幕尺寸
- ✅ **3D 視覺效果**：卡片帶有輕微的 3D 傾斜和陰影效果
- ✅ **純 HTML/CSS/JS**：無需額外依賴

## 使用方式

1. 直接在瀏覽器中開啟 `index.html` 檔案
2. 或將其嵌入到您的網頁中作為 iframe

## 顏色配置

根據原始設計圖片分析得出的色彩：

- **背景色**：`#E8E5DF` （米白色）
- **卡片背景**：`#FAFAFA` （淺灰白色）
- **文字顏色**：`#9B1B30` （深酒紅色）

## 技術細節

- HTML5
- CSS3（Flexbox、Transform、Box-shadow）
- Vanilla JavaScript（Date API、setInterval）
- 響應式設計（Media Queries）

## 瀏覽器支援

- ✅ Chrome/Edge (最新版)
- ✅ Firefox (最新版)
- ✅ Safari (最新版)

## 自訂調整

如需調整顏色、大小或樣式，請編輯 `index.html` 中的 `<style>` 區塊。

主要可調整的 CSS 變數：
- `.big-number` 的 `font-size`：調整數字大小
- `.label` 的 `font-size`：調整標籤大小
- `color` 屬性：更改文字顏色
- `background` 屬性：更改背景顏色

