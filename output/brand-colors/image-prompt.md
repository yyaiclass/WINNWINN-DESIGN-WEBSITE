# 色票圖生成記錄

工具：內建 image_gen。

參考網站：https://www.felixmillory.com/ 。本色票為雙囍國際的設計提案，並非該參考網站的官方色票。

原始色票：專案根目錄的「色票.png」。

建議視覺比例：主要背景 55%、區塊與卡片 20%、文字與主體 15%、功能輔助 7%、強調點綴 3%。此比例用於視覺配置，依頁面內容調整。

## 最終生成提示詞

```text
Use case: infographic-diagram.
Asset type: a finished Traditional Chinese brand color-system poster for the interior architecture and commercial renovation company 雙囍國際 / WINNWINN DESIGN.
Primary request: Create one beautifully typeset, high-resolution vertical editorial infographic, approximately 2048 by 2560 proportions, with structured sections, very clear flat color swatches with exact Hex labels, an accurate color usage chart, and small website UI examples. This is a proposed brand interpretation inspired by the restrained architectural presentation and material atmosphere of https://www.felixmillory.com/, NOT that studio's official palette.
Art direction: warm architectural minimalism, quiet luxury, generous cream negative space, fine charcoal typography, delicate stone-gray dividers, precise Swiss editorial grid, refined Traditional Chinese typography. Strong clear hierarchy and enough type size to read every Hex code. Flat matte swatches with no gradients so swatch colors match their labels. A small abstract vignette of warm limestone and walnut with soft natural light may occupy a modest part of the header, but most of the poster must be functional charts and color blocks. No blue, violet, saturated green, neon, watermark, or third-party logo.
Exact header: "雙囍國際" and "網站色彩策略與品牌一致性". Secondary line: "WINNWINN DESIGN · COLOR SYSTEM". Small inspiration credit: "視覺靈感：Felix Millory Architecture".
Section 01 title: "色彩策略"
Exact strategy text: "暖白建立安定與留白，石米色傳遞材質溫度；木炭灰穩定資訊層級，胡桃棕與黃銅金引導行動。"
Small mood words: "極簡 / 建築感 / 溫潤 / 專業".
Section 02 title: "核心色票"
Six generous primary swatch cards in an orderly grid with these EXACT labels and EXACT Hex codes:
"暖白" "#F6F3EE" "主要背景"
"淺石米" "#DED6CA" "區塊與卡片"
"柔霧灰褐" "#B6A996" "輔助與層次"
"胡桃棕" "#7B6858" "主按鈕"
"木炭灰" "#2D2B28" "標題與導覽"
"墨黑" "#111111" "強調文字"
Three secondary / accent swatches:
"黃銅金" "#B28F60" "按鈕懸停與點綴"
"鼠尾草灰綠" "#8A9281" "狀態與輔助圖示"
"霧灰" "#C8C6C1" "邊框與分隔線"
A small text note with two extra labeled chips: "內文 #5A5A5A" and "卡片白 #FFFFFF".
Section 03 title: "建議配色比例"
Create ONE accurate horizontal stacked bar with segment widths EXACTLY 55%, 20%, 15%, 7%, 3%, totaling 100%. Color its five segments respectively #F6F3EE, #DED6CA, #2D2B28, #7B6858, #B28F60; outline the pale segments subtly for visibility. Put the percentages and captions beneath in an easily readable legend, so the narrow 3% segment is not forced to contain text:
"55% 主要背景"
"20% 區塊與卡片"
"15% 文字與主體"
"7% 功能輔助"
"3% 強調點綴"
Small note: "全站視覺配置建議，依頁面內容彈性調整。"
Section 04 title: "網站應用"
Provide tasteful small UI samples:
A default CTA filled #7B6858 with white label "預約諮詢" and caption "預設狀態";
a hover CTA filled #B28F60 with #111111 label "預約諮詢" and caption "懸停狀態";
a card with #FFFFFF surface, charcoal headline and #5A5A5A text against the warm background;
a dark footer strip filled #2D2B28 with #F6F3EE text and #7B6858 divider.
Closing sentence: "同一套色彩，貫穿背景、內容、互動與頁尾。"
All Chinese must be accurate Traditional Chinese. Preserve exact brand name 雙囍國際 (囍, not 喜). Do not invent additional Hex codes or present these as official Felix Millory colors.
```
