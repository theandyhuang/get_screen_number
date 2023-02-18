# 透過螢幕截圖擷取畫面資訊，低成本整合不同系統資訊

實時截圖判別程式如下，可存成CSV檔或存入mongoDB，其抓出來的結果如CSV檔
https://github.com/theandyhuang/get_screen_number/blob/main/screen_shot_realtime.ipynb

這是用截圖下來的圖片做的，下方演示效果是用這支程式做的
https://github.com/theandyhuang/get_screen_number/blob/main/screen_shot_organized.ipynb

演示: 如下圖，偵測圖片中某區塊包含0的座標，並將其框出來
![alt text](https://github.com/theandyhuang/get_screen_number/blob/main/GetNumber.png)

技術: OpenCv，並可透過拖拉Bar的方式自訂threshold
