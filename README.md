# 第一章問題定義

## 1.1業務調查

　　隨著社會的發展和人民生活水平的提高，買車成為了人們奮鬥目標之一，當然已經有很多人買了車。可是隨著車輛的增加，車輛的停泊問題也隨之出現。人們的生活方式發生看深刻的變化。城市的交通用即便是這種變化所引起的現象之一。城市由於交通設施的增加造成的交通擁擠甚至混亂給人們的生活帶來了極大的不便，這種不便迫使人們尋求高技術的有效手段去解決這種不便，這就使得各個停車場需要更加先進，更加完善的車輛管理系統，為車主帶來方便，使停車場的管理系統化，因此開發了停車場管理系統。

## 1.2需求陈述


1)車主進入停車場：當車主在停車場外時，停車場外的顯示屏將顯示空餘停車位的數量。若有空餘車位，車主來到擋車器前，系統自動識別車牌號，記錄車輛進入停車場的時間與車牌號，擋車器放行，車主進入停車場。若因某些原因系統無法識別，例如車輛尚未上牌或使用臨時車牌，此時由管理員負責手動輸入車輛信息（車牌號、進入時間、特殊情況備註：未上牌或臨時牌），若無特殊情況則不需要備註。

2)車主離開停車場：車主再次來到擋車器前，系統自動識別車牌號，記錄車輛離開停車場的時間，並計算停車費用。車主完成支付後，擋車器放行，車主離開停車場。若出現以上特殊情況，則由管理員手動處理輸入信息，費用則由系統完成計算。

3)管理員查看車輛信息：管理員登入系統後，能夠對車輛信息（車牌號、進出時間、停車費用、特殊情況備註）進行管理，可查詢車輛信息、添加車輛信息、刪除車輛信息。

## 1.3 業務模型

### 1.3.1 業務模型 
<br />
![IMAGE](https://github.com/Fangani141/-final_Pexam/blob/main/other/%E6%A5%AD%E5%8B%99%E7%AE%A1%E7%90%86.drawio.png)

### 1.3.2 車主業務活動圖
<br />
![車主業務 drawio](https://github.com/Fangani141/-final_Pexam/assets/91513082/4a9aa54e-fbce-4867-bc79-eb94649f23c4)
### 1.3.3 管理員業務活動圖
<br />
![管理員業務 drawio](https://github.com/Fangani141/-final_Pexam/assets/91513082/912de2d5-ee33-4bbe-8848-00a70f5a1220)
# 第二章 需求分析

## 2.1 系統用例建模（根據對1.2的分析進行系統用例建模）

### 2.1.1 參與者概述

1)車主—— 停車服務

2)管理員—— 管理車輛進出的相關信息

### 2.1.2 用例概述

1)車主來到有空餘車位的停車場，進入停車場停車，支付停車費用後離開停車場

2)管理員輸入正確的帳號和密碼登入系統，管理車輛進出的信息，包括車牌號、進出時間、停車費用。

### 2.1.3 用例關係
正在上傳，重新上傳取消
<br />
![用例關係 drawio](https://github.com/Fangani141/-final_Pexam/assets/91513082/a60e851d-4017-46bd-9bd0-02f780ea1c1e)

## 2.2用例規約說明
<br />

表2-1 "進入停車場"用例規約
<br />
![image](https://github.com/Fangani141/-final_Pexam/assets/91513082/b3bec189-6759-4835-ad99-2d9672dcad89)


表2-2 "進入停車場"用例規約
<br />
![image](https://github.com/Fangani141/-final_Pexam/assets/91513082/aba58e87-4a1b-48b2-b5a8-c72efd2da4e7)


表2-3 "支付費用"用例規約
<br />
![image](https://github.com/Fangani141/-final_Pexam/assets/91513082/38c6dce9-8046-4c70-9e49-4e734fe4cee7)


表2-4 "離開停車場"用例規約
<br />
![image](https://github.com/Fangani141/-final_Pexam/assets/91513082/144a6fff-ee7c-4331-bfec-3b933247d3d6)


表2-5 "登陸"用例規約
<br />
![image](https://github.com/Fangani141/-final_Pexam/assets/91513082/88bd0bd2-b3dd-4cd5-904f-85c6a85e15a4)


表2-6 "查看車輛信息"用例規約
<br />
![image](https://github.com/Fangani141/-final_Pexam/assets/91513082/ac305945-b7bb-45c5-ad76-14412f4090e1)


表2-7 "查詢車輛信息"用例規約
<br />
![image](https://github.com/Fangani141/-final_Pexam/assets/91513082/42c364a7-7db9-4c7a-8699-5db09793a9b9)


表2-8 "導入車輛信息"用例規約
<br />
![image](https://github.com/Fangani141/-final_Pexam/assets/91513082/1cc4e714-6e35-4f6a-b994-71ef5835ca0e)


表2-9 "刪除車輛信息"用例規約
<br />
![image](https://github.com/Fangani141/-final_Pexam/assets/91513082/b20fce7c-d261-4dbf-b4fe-59a8658bc947)

# 第三章 面向對象分析



## 3.1用例實現
使用順序圖，按B-C-E架構實現每一個用例
<br />
![用例關係 drawio](https://github.com/Fangani141/-final_Pexam/assets/91513082/e1764855-3794-4c83-8c18-b0b992bf935b)

圖3-1登陸時序圖
<br />
![登陆时序图 drawio](https://github.com/Fangani141/-final_Pexam/assets/91513082/39553bc0-6377-464c-a5bc-d7e54e2c5cb6)

圖3-2刪除車輛信息時序圖
<br />
![刪除車輛訊息時序圖 drawio](https://github.com/Fangani141/-final_Pexam/assets/91513082/cd0fe65e-c41b-48d5-ab78-6b69ada16899)

圖3-3添加車輛信息時序圖
<br />

圖3-5查找車輛信息時序圖
<br />

圖3-6查看車輛信息時序圖
<br />
![查找車輛資訊時序圖 drawio](https://github.com/Fangani141/-final_Pexam/assets/91513082/561a3263-580d-4ed1-a2eb-61541ef4c180)

## 3.2分析類模型
建立系統的分析類圖，為每個類分配職責、屬性，及對類之間的關西建模
<br />
![分析類模型 drawio](https://github.com/Fangani141/-final_Pexam/assets/91513082/26256ab0-32fc-4e26-974d-57c8d0c60f6e)
<br />

# 第四章 面相對象設計

## 4.1數據庫設計
數據庫結構
1. 車輛信息表
<br />
![image](https://github.com/Fangani141/-final_Pexam/assets/91513082/b805f92e-2982-40bf-8961-67f962bc2f6d)

  表3.5車輛信息表

2. 管理員信息表
<br />
![image](https://github.com/Fangani141/-final_Pexam/assets/91513082/b09ad690-ca17-4e2c-9ba9-875d41701b20)

  表4.1管理員信息表

## 4.2設計類

實體類

在ODA階段得到的類圖中有兩個實體，分別是車輛和管理員。

邊界類

  1. 管理員登錄邊界類 - LogOn.java
  2. 車輛信息管理 - MainWindows.java
  3. 輸入車輛信息界面 - AddCar.java
  4. 查詢車輛信息界面 - FindCar.java
  5. 刪除車輛信息界面 - DelCar.java

控制類

  1. 登錄控制類 - 接收登錄請求，控制登錄過程的狀態，調用模型，將請求轉發到管理員登錄邊界類 LogOn.java。
  2. 車輛信息管理 - 接收請求，控制車輛信息管理的執行狀態，調用模型，獲得處理結果，將請求轉發到車輛信息管理 MainWindows.java。
  3. 輸入車輛信息 - 接收輸入請求，控制車輛信息輸入的執行狀態，調用模型，處理結果，將請求轉發到輸入車輛信息 AddCar.java。
  4. 查詢車輛信息 - 接收查詢請求，控制查詢車輛信息的執行狀態，調用模型，得到處理結果，將請求轉發到查詢車輛信息 FindCar.java。
  5. 刪除車輛信息 - 接收刪除請求，控制刪除車輛信息的執行狀態，調用模型，得到處理結果，將請求轉發到刪除車輛信息 DelCar.java。

## 4.3 軟體體系結構

本系統採用MVC設計模式搭建程序結構，模型用來完成對業務邏輯的封裝，控制器控制各個程序流程，也就是前述設計的控制類的實現；視圖用來顯示頁面，也就是前述設計的邊界類的實現。

模型部分除了封裝上述實體類的屬性外，還需要實現對應的各個方法，對全部的業務功能進行分類，設計各個業務的Bean如下。

carService實現車輛信息管理相關的業務，包含以下方法：

add_in() - 在車輛信息表中添加一條車輛入庫信息。
Add_out() - 在車輛信息表中添加一條車輛出庫信息。
FindCar() - 查詢車輛信息。
delCar() - 刪除車輛信息。
lookCar() - 查看車輛信息。

## 4.4 交互介面設計
  1.登陸logOn.java
  <br />
![image](https://github.com/Fangani141/-final_Pexam/assets/91513082/5ba703bd-afad-4051-8f8e-944215806164)

  圖4-1登陸介面設計

  2.車輛信息管理mainWindows.java
  <br />
![image](https://github.com/Fangani141/-final_Pexam/assets/91513082/97448ed9-d324-43c3-a164-c600c78983e0)

  圖4-2車輛信息管理介面設計
  <br />
![image](https://github.com/Fangani141/-final_Pexam/assets/91513082/51fca567-cdd1-4fc9-a273-4a8f75a6a8f5)

  圖4-3瀏覽車輛信息
  <br />
![image](https://github.com/Fangani141/-final_Pexam/assets/91513082/c0e98d58-5189-4fce-8e7e-8690b2654bef)

  圖4-4添加車輛信息
  <br />
![image](https://github.com/Fangani141/-final_Pexam/assets/91513082/df1a0082-17a1-4832-a900-6dc6d1e34837)

  圖4-5添加出庫車輛信息
  
  6. 刪除車輛信息DelCar.java
     <br />
![image](https://github.com/Fangani141/-final_Pexam/assets/91513082/fbc52907-a134-454e-a98b-4fb93a36624f)

  圖4-6刪除車輛信息
  7.查詢車輛信息findCar.java
  <br />
![image](https://github.com/Fangani141/-final_Pexam/assets/91513082/64a8813b-821d-43be-a05d-5375ea937ef9)

  圖4-7查詢車輛信息

# 第五章 面相對象實現

## 5.1停車場信息管理系統編碼實現
本系統基於Java+MySQL+ swing
<br />
![image](https://github.com/Fangani141/-final_Pexam/assets/91513082/84f40a14-5db8-4355-a35d-8bc06ee2e8db)

# 第六章 軟建測試與部屬
## 6.1軟建測試

本停車管理系統在設計開發過程中遵循軟體測試的V模型以規範軟體測試。V模型推行開發與測試並行的方式，在開發完一個功能模塊後就進行相應的單元測試，注重細節方面的問題，接著再進行集成測試，主要測試模塊間的接口能否互通的問題。最後，在進行功能測試來檢測整個系統運行是否正常。

在測試過程中主要採取的是功能測試，通過功能測試可以逐一檢測各個功能是否可以滿足停車場管理人員的需求。

## 6.2 功能測試

功能測試是一種黑盒測試，這是根據軟體需求的要求設計測試用例並驗證系統功能的過程，並且通過與測試系統的外部輸入與輸出的關係來驗證，功能測試在於測試功能是否正常，因此不考慮內部的實現方式，測試的前提就是系統已經處於運行狀態。

本停車管理系統在設計開發過程中多次對系統功能進行測試，確保功能的正常運作。

## 6.3 功能測試總結

主要對停車場管理系統的登錄、車輛駛入、車輛駛出、對車輛信息的增刪改查操作進行功能測試，測試過程中界面UI的顯示都符合預期，功能方面符合需求。

## 6.4 用例測試

### 6.4.1 登錄用例測試
<br />
![image](https://github.com/Fangani141/-final_Pexam/assets/91513082/8a8badb2-fa8b-405e-98b6-8ad473e782fb)


### 6.4.2添加信息用例測試
<br />
![image](https://github.com/Fangani141/-final_Pexam/assets/91513082/aeb5487d-3c2f-4b27-ac65-4d816d018bb1)


### 6.4.3查詢信息用例測試
<br />
![image](https://github.com/Fangani141/-final_Pexam/assets/91513082/01a1ed75-6c0d-43be-89c1-f02eec970eb9)


### 6.4.4瀏覽信息用例測試
<br />
![image](https://github.com/Fangani141/-final_Pexam/assets/91513082/adca12aa-83e0-46b1-8f01-de12d6a0aa26)


### 6.4.5刪除信息用例測試
<br />
![image](https://github.com/Fangani141/-final_Pexam/assets/91513082/1f947f98-fa16-4fa2-abe5-40627700efde)


# 6.5本章小節
本章捷主要介紹了對停車場管理系統進行功能測試的必要性和測試結果，針對當前停車管理系統設系了一系列的功能測試用例。通過系統測試使系統更能府和預期要求，並能檢測和修復一些開發過程中的bug。



