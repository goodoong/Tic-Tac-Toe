# tic-tac-toe
tic-tac-toe 게임을 구현

![Image](https://github.com/user-attachments/assets/016273b0-725a-4fbe-8086-79d2a539eaca)

## 목적
state 활용 공부 목적

## 폴더구조
```
📦src
 ┣ 📂assets
 ┃ ┗ 📜react.svg
 ┣ 📂components
 ┃ ┣ 📜GameBoard.jsx
 ┃ ┣ 📜GameOver.jsx
 ┃ ┣ 📜Log.jsx
 ┃ ┗ 📜Player.jsx
 ┣ 📜App.jsx
 ┣ 📜index.css
 ┣ 📜index.jsx
 ┗ 📜winning-combination.js
```

폴더명|폴더 설명
---|---|
GameBoard|틱택토 게임 보드판/알맞는 행과 열에 플레이어의 상징을 나타내어 게임상황을 볼 수 있게 한다.|
GameOver|게임의 승패 표시 & 다시 시작 버튼|
Log|게임 진행상황을 기록하여 표시|
Player|플레이어 이름 설정 & 수정|
App|player, gameturn 등 상태 관리, 승패 로직|
