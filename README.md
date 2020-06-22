# R_finalProject
R語言程式設計 期末作業

1. 篩選從1980 到 2017 NBA球員的利用以下數據找出每個年代的最佳五人

    Age: 年紀
    G   : 出賽場次
    GS  : 先發場次
    MP  : 平均每場時間
    PER : [（得分+籃板+助攻+搶斷+封蓋）-（出手次數-命中次數）-（罰球次數-罰球命中次數）-失誤次數]/球員上場比賽的場次 可以綜合判斷球員良性表現
    WS  : 勝利貢獻值
    STL : 抄截
    FG  : 投籃進球數
    FGA : 投籃次數
    FG. : 投籃命中率
    X3P : 三分進球數
    X3PA: 三分次數
    X3P.: 三分命中率
    eFG.: 有效命中率 eFG%乘以出手數再乘2(eFG% × FGA × 2 = 得分)
    FT  : 罰球進球數
    FTA : 罰球次數
    FT. : 罰球命中率
    TRB : 總籃板(進攻+防守)
    AST : 助攻
    STL : 抄截
    BLK : 阻攻
    PTS : 總得分
    
 
2. 資料集是從Kaggle網頁中的NBA球員資料 https://www.kaggle.com/drgilermo/nba-players-stats#player_data.csv

3.套件1:dplyr

   函數:filter()

   函數簡介: 在 filter() 函數中我們輸入要篩選的資料框，以及依據什麼判斷條件進行篩選
   
  套件2:ggplot2

   函數:qplot()

   函數簡介: 在 qplot() 函數中我們輸入要畫出的X Y 軸資訊 以及圖樣類型 
   
