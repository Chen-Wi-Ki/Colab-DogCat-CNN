# 本專案是經典的電腦視覺用於貓狗判斷這種二值辨識系統的研究

系統實現於Colab上,使用了Tensorflow2.x

本專案僅用來快速理解CNN二值問題的邏輯要領與快速實作之簡易程序

# 關於DogCatCNNAlgorithm.ipynb

經典範例--貓狗判斷程式(僅100張的訓練)

來源:https://www.kaggle.com/code/uysimty/keras-cnn-dog-or-cat-classification/notebook

小結:若貓狗圖各50張的訓練,結果是難以實現辨識,這可能需要千張或萬張以上才可能實現的功能...

# 關於Sin Test for CNN 2Value Verify.ipynb

我利用了sin波做二值辨識測試,用處是驗證CNN系統在限制許多條件後能否以少量圖實現辨識能力？

小結:分別有1.5Hz(2周波/3秒)與3Hz(1周波/3秒)兩種sin波各5張的訓練,結果是可辨識的。
