PST 郵件檢視器 1.0.0

1.0.0 為原 v6.9 的正式發行版。

本版內容：
1. 修復 UI 圖示：改用內嵌 SVG，不再依賴容易顯示成方框/亂碼的 Unicode 符號。
2. 郵件本文區放大：寄件者/收件者/副本資訊改成可滾動區。
3. 三欄可拖曳調整：資料夾、郵件清單、郵件本文之間皆有拖曳分隔線。
4. 郵件標頭與本文間也可上下拖曳調整；尺寸會儲存在瀏覽器 localStorage。
5. 修復部分 HTML 郵件亂碼：直接讀取 PST 的原始 HTML bytes，依 BOM、HTML meta charset、Internet Codepage、Message Codepage 自動解碼，並加入 UTF-8/Big5/GB18030/Shift-JIS/EUC-KR/Windows codepage 後備判斷。
6. HTML 解碼後統一以 UTF-8 srcdoc 顯示，避免瀏覽器再次依錯誤 charset 解讀。
7. 保留 RTF / HTML / 純文字手動切換與附件/內嵌圖片功能。
8. PST 清單可依名稱（A→Z、Z→A）或檔案最後修改時間（新→舊、舊→新）排序。

使用方式：直接開啟「PST郵件檢視器_1.0.0.html」，按「選擇 PST 資料夾」。
