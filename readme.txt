GitHub Pages架設靜態網站並綁定網域: https://www.youtube.com/watch?v=bU0f1IvUcZA, https://medium.com/@NorthBei/%E4%B8%8D%E7%94%A8%E6%87%82git%E4%B9%9F%E8%83%BD%E7%94%A8github-pages%E6%9E%B6%E8%A8%AD%E9%9D%9C%E6%85%8B%E7%B6%B2%E7%AB%99%E4%B8%A6%E7%B6%81%E5%AE%9A%E7%B6%B2%E5%9F%9F-c60c02bc470c
NCTU Domain免費網域申請教學: https://medium.com/@NorthBei/nctu-domain%E5%85%8D%E8%B2%BB%E7%B6%B2%E5%9F%9F%E7%94%B3%E8%AB%8B%E6%95%99%E5%AD%B8-b629fdaaad90


網站規劃
menu: comic， article， store，序號兌換，我的最愛(comic， article，商品)，搜尋功能
(1)每一頁的首頁顯示排行榜；顯示所有商品小圖示，預設以XXX分類排序；搜尋功能
(2)可以選擇依分類排序:熱門、....
(3)點圖示可進去詳細介紹頁面，(顯示集數:for comic, article使用；未購買圖片下面顯示加入購物車；購買完圖示下面顯示瀏覽:導至每集的sub)
在每一集被使用者點擊時記錄點擊次數(一個ip只能點一次)=>排行榜使用
記錄每個使用者對每一集的點擊總次數
(4)點store圖示可進去列出店家販賣商品:顯示所有商品小圖示，預設以熱門商品排序，可以選擇依分類排序

後台:
(1)如果身分為superuser:則多了會員管理
(2)會員中心:
文章分類管理(新增、修改分類)、文章管理(新增、修改內容、...)
comic分類管理(新增、修改分類)、comic管理(新增、修改內容、...)
商品圖片上傳、內容修改
遊戲區:會員等級達成則顯示可玩(有次數限制)，否則顯示灰
紅利點數區:顯示目前擁有紅利
消費紀錄
序號兌換紀錄
訂單管理
