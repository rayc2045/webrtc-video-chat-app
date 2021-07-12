# Video Chat App Build with WebRTC and Socket.io

[> Chat with friends online](https://rayc-video-chat.herokuapp.com/)

### Clone/Fork this repo
    git clone https://github.com/rayc2045/webrtc-video-chat-app.git
    npm i -g peerjs
    npm i
    npm run dev
    peerjs --port 3001

### 簡介
這次的專案以 WebRTC (Web Real-Time Communication) 網頁即時通訊技術為底，實現讓不同使用者在不安裝瀏覽器插件的前提下，能夠直接進行點對點 (peer-to-peer) 的語音、視訊通話以及資料傳輸。在缺乏中繼多媒體串流伺服器的情況下，人數限制應該會在十人左右，雖然沒有試過在線人數的上限，不過仍可作為簡單實用的多人視訊軟體。

### 使用方式
1. 前往網站 ([https://rayc-video-chat.herokuapp.com/](https://rayc-video-chat.herokuapp.com/))
2. 分享連結給朋友
3. 開始聊天，就這麼簡單 🙂