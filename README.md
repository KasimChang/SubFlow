SubFlow - Professional Subtitle Engine | 專業字幕批量轉換工具
SubFlow is a precision-driven subtitle processing engine designed for professional video editors. By implementing unique 1:1 line normalization logic, this tool eliminates synchronization drift commonly found when importing VTT files into non-standard editing software like DaVinci Resolve.
SubFlow 是一款專為影視剪輯師設計的「精準字幕處理引擎」。本工具透過獨創的 1:1 行數校正技術，徹底解決了將 VTT 檔案導入 DaVinci Resolve 等剪輯軟體時常見的時間軸偏移與格式不相容問題。

🚀 核心功能 | Core Features

精準同步校正 | Precision Sync Normalization

1:1 Line Alignment (1:1 行對齊): Automatically inserts placeholder lines to ensure VTT headers and SRT indexes are perfectly parallel.
自動插入補位行，確保 VTT 標頭與 SRT 序號行在視覺上絕對平行對應。

Header Correction (標頭修正): Rigorously handles WEBVTT headers and metadata to prevent cumulative vertical offset.
嚴謹處理 WEBVTT 標頭與元數據，防止累積性的垂直偏移導致比對失準。

Tag Cleaning (標籤清洗): Automatically strips technical tags (e.g., [source: x]) for a clean, professional output.
自動清除技術性標籤，確保輸出結果乾淨、專業。

互動式對比預覽 | Interactive Comparison

Synchronized Scrolling (同步滾動): A real-time lock mechanism that aligns the target SRT scroll position with the source VTT instantly.
具備即時鎖定機制，開啟時可瞬間將兩側捲動位置強制回正。

Side-by-Side View (雙欄對比): Visual verification of timestamps and text content before finalizing the batch.
在批量導出前，透過雙欄視窗直觀驗證時間戳與文本內容。

Fluid Layout (流動式佈局): Responsive design with adjustable font sizes for detailed inspection across devices.
響應式設計並支援字級調整，滿足不同螢幕下的細節檢查需求。

高效批量工作流 | High-Efficiency Workflow

Instant Batch Conversion (極速批量): Processes hundreds of VTT files in milliseconds using browser-side sandboxing.
利用瀏覽器沙盒技術，在毫秒間完成數百個字幕檔案的格式轉化。

ZIP Packaging (一鍵打包): Automatically zips all converted SRT files for a seamless transfer to your editing workstation.
自動將所有轉換後的 SRT 檔案打包為 ZIP，優化素材導入流程。

📈 處理邏輯 | Technical Concept

為確保兩側內容在滾動時絕對對準，SubFlow 採用了對稱補位演算法：
$$L_{VTT\_aligned} \equiv L_{SRT\_standard}$$

$L$: 每組字幕塊的總佔用行數。
確保 VTT 側的「時間戳行」與 SRT 側的「序號+時間行」在垂直空間上達到平衡。

🛠 技術棧 | Tech Stack
Frontend: HTML5, Tailwind CSS (Modern UI/UX)
Icons: Lucide-React (Vector Visualization)
Library: JSZip (Client-side Compression)
Typography: JetBrains Mono (Precision Code Font)

📖 使用方式 | Getting Started
Github page : https://kasimchang.github.io/SubFlow/ (直接開啟互動網頁)

Step 1: Drag & Drop your .vtt files into the upload zone. (拖放 VTT 檔案至上傳區)

Step 2: Preview content using sync-scroll for accuracy check. (利用同步滾動進行準確性檢查)

Step 3: Click "Start Batch Conversion" and download the results. (點擊開始轉換並下載成果)

✍️ 作者 | Author
kasimchang Precision Pricing Engine Creator GitHub Profile

📜 版權聲明 | Copyright & License
All Rights Reserved. This project is currently not open for licensing. No part of this software may be reproduced, modified, or distributed without written permission from the author.
版權所有，翻印必究。 本專案目前不開放授權使用。未經作者書面許可，請勿擅自轉載、修改、散佈或用於商業用途。
