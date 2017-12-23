# Computer Graphics


## Index page - [link](https://bevis00.github.io/ComputerGraphics/index.html)


### Homework 1 : [time-based animation](https://bevis00.github.io/ComputerGraphics/hw1.html)
- 技術要求
  - 模型建構 : [指針](https://i.imgur.com/1ASPrjI.png)與[背板](https://i.imgur.com/EsHmKKz.png)，選擇合適的配色，XY plane、初始在+Y方向
  - 運動 : 依real-time順時針旋轉，使用於60秒內之計時
  - 不同display style : 扇形
- 功能
  - 三個按鈕可切換 Analog、Sector、Quartz 顯示方式
  - 可以由按鈕暫停(PAUSE, RESTART)


### Homework 2 : [git & github](https://github.com/bevis00/ComputerGraphics)
- 技術要求
  - 將課堂作業的資料夾建成Repository並建立index.html，為本學期作業做一個title page，並上傳到github上
  - 參考[Markdown files的格式](https://help.github.com/articles/basic-writing-and-formatting-syntax/)，為homework repository加上合適的README.md


### Homework 3 : [Hierarchical Model](https://bevis00.github.io/ComputerGraphics/hw3.html)
- 技術要求
  - 建構坦克模型：
    - 正確的機構(kinematic)模型，以及合理的joint angle limits
    - 架設合適的燈光，設定合適的顏色
  - 砲彈發射：
    - 初始位置：砲口 發射方向：砲管方向 發射速率：固定
    - 砲彈打到地面(y = 0)即停止。停止後，才可以發射下一發砲彈。
    - [雜研與專題生] write "class" for cannonball, 使得可以發射多發砲彈, [reference](https://docs.google.com/presentation/d/17tTiIvHCruuUXcSnboq1dPTnf0tQtg53xqUdj3nE2zw/edit#slide=id.p)
  - 簡單遊戲：
    - 坦克在中線(x = 0)上前後運動
    - 地圖的兩端(x = 100, x = -100)隨機產生標靶
    - 操作坦克，將標靶擊落
    - [bonus] 分隔畫面: god's eye view 以及 坦克操作員視角（以便瞄準）


### Homework 4 : [OBJ loader, drive](https://bevis00.github.io/ComputerGraphics/hw4.html)
- 技術要求
  - 在網路上找合適的車輛模型 (OBJ/MTL format)
  - 利用合適的loader將其匯入three.js 場景中，以適當大小呈現
  - 運用課堂上所教的“kinematic drive"，以鍵盤控制車輛
  - 在場景中佈置大小不同的圓形障礙物。可以用threejs所提供的geometry, 或是使用circular billboard (with cut-out texture)
  - 實作collision detection程式，使得車輛與障礙物相撞時立即停止。使用者須自行將車輛駛出。請務必在所錄的animated.gif中示範此效果
  - 螢幕分割成左右兩viewports: 一邊為上帝視角 (god's eye view), 一編為駕駛的第三人稱視角 (third person view)
    

### Homework 5 : [Class, Raycaster, Shadow Map](https://bevis00.github.io/ComputerGraphics/hw5.html)
- 技術要求
  - 在網路上找合適的檯燈模型 (OBJ/MTL format)
  - 利用合適的loader將其匯入three.js 場景中，以適當大小呈現
  - 利用BoxGeometry以及合適的材質做出電腦桌
  - 書桌上放置檯燈，燈光遙控器，以及筆筒(內有筆)
  - 遙控器上有至少兩個按鈕，以控制檯燈以及室內燈光
  - 開關須以class實作，由滑鼠點按觸動