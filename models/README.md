# face-api.js 模型

將 face-api.js 權重檔放在此資料夾（或改變 index.html 的 MODEL_URL 指向權重位置）。

建議檔案：
- tiny_face_detector_model-weights_manifest.json (+ 對應 shard 檔案)
- face_landmark_68_model-weights_manifest.json (+ 對應 shard 檔案)

下載來源範例：
- https://github.com/justadudewhohacks/face-api.js/tree/master/weights

上傳到 GitHub Pages 時，請將整個 models 資料夾 commit 到 main 分支，這樣頁面上的 MODEL_URL='/models' 才能正常抓取權重。
