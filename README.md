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