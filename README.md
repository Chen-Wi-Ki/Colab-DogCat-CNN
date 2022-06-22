# 本專案是經典的電腦視覺用於貓狗判斷這種二值辨識系統的研究

系統實現於Colab上,使用了Tensorflow2.x

本專案僅用來快速理解CNN二值問題的邏輯要領與快速實作之簡易程序

# 關於DogCatCNNAlgorithm.ipynb

經典範例--貓狗判斷程式(僅100張的訓練)

來源:https://www.kaggle.com/code/uysimty/keras-cnn-dog-or-cat-classification/notebook

僅使用貓狗圖各50張的訓練。

**小結:結果是難以實現辨識,這可能需要千張或萬張以上才可能實現判別功能...**

# 關於Sin Test for CNN 2Value Verify.ipynb

我利用了sin波做二值辨識測試,用處是驗證CNN系統在限制許多條件後能否以少量圖實現辨識能力？

分別有1.5Hz(2周波/3秒)與3Hz(1周波/3秒)兩種sin波各5張的訓練。

**小結:辨識能力良好，比貓狗的CNN系統更容易實現二值判別。**

# 關於Sin Test for CNN 2Value Verify2.ipynb

同理於Sin Test for CNN 2Value Verify，只是再把圖切成10份當作訓練圖。

第1份訊號作為平移訊號作用,本專案做成了3份有延遲(0秒/1秒/2秒)的訊號數據。

所以單一筆數據共9張圖，做了3種平移，所以1值數據共27張灰階圖做訓練。

依不同頻率做了2值判斷訓練集共54張灰階圖。

**小結:辨識能力良好，比貓狗的CNN系統更容易實現二值判別。**
