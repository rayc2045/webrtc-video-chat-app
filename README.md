# Video Chat App Build with WebRTC and Socket.io

[![Photo](https://raw.githubusercontent.com/rayc2045/webrtc-video-chat-app/main/public/cover.png)](https://rayc-video-chat.herokuapp.com/)

[> Chat with friends online](https://rayc-video-chat.herokuapp.com/)

### Clone/Fork this repo
    git clone https://github.com/rayc2045/webrtc-video-chat-app.git
    cd webrtc-video-chat-app
    npm i
    npm run dev

### 簡介
這次的專案以 WebRTC (Web Real-Time Communication) 網頁即時通訊技術為底，實現讓不同使用者在不安裝瀏覽器插件的前提下，能夠直接進行點對點 (peer-to-peer) 的語音、視訊通話以及資料傳輸。在缺乏中繼多媒體串流伺服器的情況下，人數限制應該會在十人左右，雖然沒有試過在線人數的上限，不過仍可作為簡單實用的多人視訊 App。

### 使用方式
1. 前往網站 [https://rayc-video-chat.herokuapp.com/](https://rayc-video-chat.herokuapp.com/)
2. 分享連結給朋友
3. 開始聊天，就這麼簡單 🙂

### 開發紀錄
- 開發中使用 [Nodemon](https://github.com/remy/nodemon) 即時更新 Node.js 專案的改動
- 使用 Node.js Web 應用程式架構 [Express](https://expressjs.com/zh-tw/) 開發伺服器執行環境
- 使用通用唯一辨識碼 UUID 作為聊天室位址
- 透過 [PeerJS](https://peerjs.com/) 實現 WebRTC P2P 通訊
- 透過 [Socket.IO](https://socket.io/) 實現即時雙向通信
- 使用嵌入式 JavaScript 模板引擎 [EJS](https://ejs.co/) 產生網站模板
- 使用 [Heroku](https://www.heroku.com/) 部署專案