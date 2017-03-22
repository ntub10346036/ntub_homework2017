##1.Ruby 跟 Rails 之間的關係，如果打個比方的話，就像樂高（Lego）積木，Rails 就像是一塊一塊的積木，可以讓你很快的把城堡蓋起來，而 Ruby 則像是積木的原料（塑膠），沒有原料就不會有這個積木。意思是說Rails是Ruby建構起來的
##2.一開始輸入網址連到自己的網站，透過路徑Rails會從controller找出需對應的action，Action 決定要做什麼事，若是Action要求找目前的產品項目， 它就會去請 Model 幫忙要資料，Model本身不是資料庫，它的作用可以使人所輸入的資料庫語法，轉換成資料庫看得懂的語言，透過資料庫查詢語言，Model 從資料庫那邊取得資料，Model再把這包資料交回 Controller/Action 手上。雖然 Controller/Action 有資料了，但這包東西還沒美化、整理過，不適合給使用者看，所以Controller/Action 需要跟 View 借一下畫面，讓資料更適合閱讀。最後Controller/Action 把資料跟 View 的畫面組合，呈現給使用者看。