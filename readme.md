# 自製的日期選擇器
## 變數說明
1. maxDays: 最大可選天數
2. canSelect: 是否可以選日期的操作變數。
  如果起始日期與結束日期有設定，而只是用於展示日期那就要把這個變數設 false，這樣就無法選日期。
3. bookingList: 放已經被選，要變成不能夠被選的樣式，disabled 的日期。
  如果外部資料是一個日期區間，把起始日期與結束日期變成一個陣列放在 bookingList
  如果發現 bookingList 中有陣列是記錄日期區間，會在一起始就轉換成單日
4. 其餘的請見 js 檔中的說明
5. [示意網址](https://idben.github.io/datepicker3/)