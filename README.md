# MICO 動作訓練場 v0.1

純 HTML / CSS / JavaScript Canvas 2D，無 npm、無外部 CDN、無伺服器需求。手機建議橫向，支援多點觸控。雙擊 index.html 或使用 GitHub Pages。

操作：左／右或 A/D 移動；上或 Space 跳躍；下或 S 蹲下；按住 Shift 或奔跑鍵並移動；J 揮劍；K 技能。左上顯示能量與寶石，右上暫停、重置與全螢幕（視瀏覽器支援）。可跳上平台、練習打擊木樁並收集五顆寶石。

部署：將 index.html、assets 資料夾及 README.md 放在儲存庫 main 分支根目錄，Settings > Pages > Deploy from a branch > main > /(root)。

素材：使用本次對話生成的雙耳直立 MICO 角色素材表及遊戲場景示意圖，擷取可用幀。原始素材解析度有限，動畫為測試版；左右部分幀使用鏡像，因此非對稱裝甲方向可能翻轉。揮劍及技能效果使用 Canvas 繪製；不是最終精緻的逐幀戰鬥素材。場景為原示意圖的裁切及石塊材質重組。
