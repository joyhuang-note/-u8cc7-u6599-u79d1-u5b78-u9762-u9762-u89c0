# 資料科學面面觀：理論、案例及企業導入方法 #

- Origin: [資料科學的第一堂課: 心法、案例分析與團隊建立 ](http://www.slideshare.net/swchen11/ss-52517363)
- Issue: [https://github.com/joyhuang9473/event-list/issues/3](https://github.com/joyhuang9473/event-list/issues/3)

## 心得 ##

資料科學面面觀，從 3V 面向來定義 Big Data ，使得這個 term 變得明朗些，其中在 variety 的定義裡，多領域、結構、非結構性資料的分類方式令人印象深刻。

探討國外在資料特徵放大、推薦系統等 Computer Vision 的應用案例，驚嘆之餘，講者也讓我們思考，在國內多數的人們是否還不清楚資料可以做些什麼，或說，被某種框架限制了發想。

”分析開放的資料來得到肉眼看不到的資訊”，藉由網路這個 scale lab ，人機的互動、FB 用戶按讚的行為，使得獲取 social pattern 和 personality prediction 成為可能。

在分析線上遊戲的應用案例上，預測玩家留存率和上癮指數，來量化一個遊戲到底有多”黏”，這可能是身邊開發遊戲的朋友們最受用的主題吧。

“將非結構性資料轉為結構性資料” 從遊戲的服裝銷售預測到釣魚網站的 URL 判別，feature 分析的妙用讓人遠離那華麗但無用的統計報表。

資料素養，為一位資料科學家最需要的能力特質，“不只依靠數據回答問題”、“資料的相關不代表實際的因果關係”、“知道什麼樣的問題適用數據回答”。

## Quick Note ##

### Big Data ###

3V 定義

1. volume: 1 - 2 TB
2. velocity: 即時處理、串流資料
3. variety: 資料多樣性（多領域、結構、非結構性資料）

### Computer Vision 應用 ###

1. 資料（特徵）放大
2. 心跳偵測
3. 推薦系統
  - 串流資料
  - 瀏覽網頁 -> 廣告推播
  - 先前購買的商品 -> 判斷是否為孕婦

講：（多數人還不清楚資料可以做到哪些事）

### Data Discovery ###

1. 發現產品問題 -> 藉由資料做決策

講：（Big Data 未來將不再被強調，因為它只是個 term）

=> Big Data 只有某些工具能處理，因此才產生 "Big Data" term 與 "Small Data" 區別

講：（分析資料得到肉眼看不到的資訊）

### Case Studies ###

1. 計算社會學
2. 遊戲外掛偵測
3. 遊戲玩家忠誠度分析
4. 線上遊戲市場表現預測
5. 未知號碼該不該接
6. 有沒有人偷用你的臉書
7. 釣魚網頁偵測
8. 如何輔助線上遊戲虛寶銷售

### Social Pattern: （人機互動、會議名牌） ###

- 分析社會互動、結構

### Social Dataset ###

- 用字遣詞 -> 判斷 性別、年齡、個性 ...

### Internet is a scale lab ###

- FB 實驗正面或負面文字文章對人的影響
  - 影響人的情緒
  - 影響人的投票意願
  - 藉由文字預測人的健康狀態
  - Personality Prediction

- AppleDaily 弱勢關懷專欄
  - 捐款金額分佈（受 登報時間點、家庭成員組成、個人身心特質等因素影響）

講：（文字影響人的 decision）

### CrowdSourcing（群眾外包）：群眾智慧 ###

- [Bounty Worker 平台](http://bountyworkers.net/index)：人工編碼

講：（資料科學家花 60% - 70% 時間收集、分析資料）

（認知偏差）

### 線上遊戲 ###

- 預測玩家留存率和未來離開遊戲的時間點
  - 魔獸世界 福克斯大神
- 遊戲“生存”時間（多久）
  - 如何量化一個遊戲有多“黏”
  - 上癮指數

（未知電話）

（講者工具：awk + php + R）

### 將非結構性資料轉為結構性資料 ###

- 方法：？（下 tag ?）
- 遊戲服裝銷售預測
  - 不同玩家族群對於商品外觀之偏好
  - SI 值 -> 做 regression
- 偵測釣魚網站
  - 分析 URL（非結構性資料）：符號、怪異文字等 feature

### 養成 ###

- 資料工程師
  - programming
  - DBMS
  - Data crawling
  - Data visualization

- 資料科學家
  - 統計、統計工具
  - Machine Learning
  - **Domain knowledge** (the most important thing i think)
  - Data visualization

講：（不能只依據數據回答問題）

講：（相關不等於因果關係）

講：（知道什麼樣的問題該用數據回答）

[眼鏡蛇效應](https://zh.wikipedia.org/wiki/%E7%9C%BC%E9%95%9C%E8%9B%87%E6%95%88%E5%BA%94)

培養創意：[魔島理論](http://wiki.mbalib.com/zh-tw/%E9%AD%94%E5%B2%9B%E7%90%86%E8%AE%BA)
