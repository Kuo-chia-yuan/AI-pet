# AI-pet

## 動機：
創造一隻能陪伴主人，和主人互動的AI寵物

## 實作過程：
1. 利用pytorch實作，透過CNN訓練如何分辨人類口音，並將其分類成8種人類情緒。
2. 將寵物會做出的回應(gif檔)分成8種類型，對應到人類的8種情緒。
3. 寵物將根據主人傳達的語音，準確辨識出其情緒，並從該種類中多個gif檔隨機挑選一個，回覆主人。
4. 主人能選擇給予寵物獎勵，或者繼續與寵物對話。

![image](https://user-images.githubusercontent.com/56677419/204785761-d2667fcd-17a3-40b5-8dba-cc13ff4cd119.png)

## 遇到困難：
1. 中文語音的training data不容易蒐集。
2. 語音辨識的準確程度，會受周遭噪音影響而降低。
3. 比較SGD與Adam的優劣(用於AI pet時)

![image](https://user-images.githubusercontent.com/56677419/204790052-1eb452a0-b33b-4d95-8748-07005fd74a5a.png)

![image](https://user-images.githubusercontent.com/56677419/204789996-3838b11d-6cd1-4775-a1d8-bc2597c369f9.png)

## 運用技術：
1. CNN
2. SGD & Adam
3. Classifier
4. 情緒辨識
