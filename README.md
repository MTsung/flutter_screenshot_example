# Flutter Screenshot Example

在 Flutter 中利用 `RepaintBoundary` 和 `GlobalKey` 將 **Widget 截圖轉成圖片 (PNG)**。  
轉成 `Uint8List` 後，就可以做到：

- **顯示**：使用 `Image.memory` 預覽  
- **儲存**：透過 [gal](https://pub.dev/packages/gal) 套件存入相簿  
- **分享**：透過 [share_plus](https://pub.dev/packages/share_plus) 分享到其他 App  
- **上傳**：透過 [dio](https://pub.dev/packages/dio) 傳到伺服器  

---

## 功能
App 內提供四個按鈕，對截圖結果進行操作：

- **顯示** – 在 Dialog 中預覽截圖  
- **儲存** – 存到相簿  
- **分享** – 呼叫系統分享功能  
- **上傳** – 透過 API 上傳到後端  

---

## 使用場景
- **問題回報** – 回報錯誤時附帶螢幕截圖，方便除錯  
- **邀請卡片** – 自動生成含 QR Code 的分享卡片  
- **簽名截圖** – 將手寫簽名或筆跡存成圖片
- **輸出海報** – 將動態組合的 Widget 輸出成 PNG 分享  

---

This project demonstrates **how to capture a Flutter widget as an image (PNG)** using `RepaintBoundary` and `GlobalKey`.  
Once the widget is converted to `Uint8List`, you can easily:

- **Preview** it with `Image.memory`  
- **Save** it to the gallery with [gal](https://pub.dev/packages/gal)  
- **Share** it with [share_plus](https://pub.dev/packages/share_plus)  
- **Upload** it to a server with [dio](https://pub.dev/packages/dio)  

---

## Features
The app includes four built-in actions for the captured image:

- **Preview** – show the screenshot in a dialog  
- **Save** – store the image in the photo gallery  
- **Share** – share the image with other apps  
- **Upload** – send the image to a backend via API  

---

## Use Cases
- **Bug reporting** – attach a screenshot when submitting issues  
- **Invitation cards** – generate a shareable card with QR code  
- **Signature capture** – save handwritten signatures as images  
- **Poster generator** – export dynamically built widgets as PNGs to share  
