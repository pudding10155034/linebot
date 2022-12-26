# linebot
## 創立主旨

天氣與人們生活息息相關，因此，為了人們可以更方便的查詢目前天氣資訊，與幫助評估當下是否為出門好時機，才產生了這隻機器人。

## 介紹
### 基本資訊
名稱：weather

首先先幫我加入一下好友

可以使用搜尋ID(記得要打"@")或掃QR Code

ID：@287mwgze

![](https://imgur.com/m8ity4v.png)

### 功能
這是它的選單
![](https://i.imgur.com/9xl8U9a.png)

1. 它可以查詢即時匯率
2. 它可以查看最近三個月/兩週的趨勢圖
3. 它可以幫你判斷現在值不值得換日幣

+ 透過「介紹與說明」，可以查看教學與功能提醒
![](https://i.imgur.com/gAe92Yj.png)

+ 透過「即時查詢」，可以看到即時的現金與匯率之買入賣出值
![](https://i.imgur.com/ETZQzxg.png)

+ 透過「近期趨勢圖」，可以開啟趨勢圖的區間選單
![](https://i.imgur.com/VRY0trM.png)

+ 選擇「最近三個月」，會顯示最近三個月以來的匯率變化
![](https://i.imgur.com/53RtTUm.png)

+ 選擇「最近兩週」，會顯示最近兩週以來的匯率變化
![](https://i.imgur.com/yEeQ5RE.png)

+ 透過「推薦與否」，可以幫助計算即時匯率是否為近期低點
  (是否最近三個月的最低5個數值/最近兩周的最低3個數值)
  推薦程度與是否為低點有關，若都不是最低點則推薦度為「低」
  其中一項是則推薦度「中」，兩者皆是則推薦度「高」
  ![](https://i.imgur.com/zp6IZtn.png)


## Fsm 結構圖
![](https://i.imgur.com/zEHiCcn.png)


