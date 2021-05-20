# Yolov4_Colab_User_Datasets
Google Colab範例，使用Yolov4(darknet)對自定義資料集進行訓練及推論  

yolov4_training_test.ipynb 為主程式，包含Yolov4預訓練測試、自定義資料集訓練及推論測試  
my_dataset.zip 包含100張影像及Yolo格式標註檔(＊.txt)  
Annotation 檔案夾為100張影像VOC標註檔(＊.xml) (原則上可不使用，僅供參考)  
my_obj.data 為資料集設定檔  
my_obj.names 為資料集分類標籤名稱  
my_yolov4_custom.cfg 為自定義模型及相關參數  
my_train.txt 為自定義資料訓練集檔案名稱列表  
my_test.txt 為自定義資料驗證集檔案名稱列表
test01.jpg, test02.jpg 為測試用影像  
