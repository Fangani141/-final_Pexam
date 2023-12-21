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
<br />

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

表2-1 "進入停車場"用例規約
<br />

![image](https://github.com/Fangani141/-final_Pexam/assets/91513082/b3bec189-6759-4835-ad99-2d9672dcad89)
<br />

表2-2 "進入停車場"用例規約

![image](https://github.com/Fangani141/-final_Pexam/assets/91513082/aba58e87-4a1b-48b2-b5a8-c72efd2da4e7)

<br />

表2-3 "支付費用"用例規約


![image](https://github.com/Fangani141/-final_Pexam/assets/91513082/38c6dce9-8046-4c70-9e49-4e734fe4cee7)
<br />

表2-4 "離開停車場"用例規約


![image](https://github.com/Fangani141/-final_Pexam/assets/91513082/144a6fff-ee7c-4331-bfec-3b933247d3d6)
<br />

表2-5 "登陸"用例規約


![image](https://github.com/Fangani141/-final_Pexam/assets/91513082/88bd0bd2-b3dd-4cd5-904f-85c6a85e15a4)
<br />

表2-6 "查看車輛信息"用例規約


![image](https://github.com/Fangani141/-final_Pexam/assets/91513082/ac305945-b7bb-45c5-ad76-14412f4090e1)
<br />

表2-7 "查詢車輛信息"用例規約


![image](https://github.com/Fangani141/-final_Pexam/assets/91513082/42c364a7-7db9-4c7a-8699-5db09793a9b9)
<br />

表2-8 "導入車輛信息"用例規約


![image](https://github.com/Fangani141/-final_Pexam/assets/91513082/1cc4e714-6e35-4f6a-b994-71ef5835ca0e)
<br />

表2-9 "刪除車輛信息"用例規約


![image](https://github.com/Fangani141/-final_Pexam/assets/91513082/b20fce7c-d261-4dbf-b4fe-59a8658bc947)
<br />

# 第三章 面向對象分析



## 3.1用例實現
使用順序圖，按B-C-E架構實現每一個用例


![登陆时序图 drawio](https://github.com/Fangani141/-final_Pexam/assets/91513082/3eecd287-f584-46b1-a127-c00c1af1b60b)
<br />


圖3-1登陸時序圖

![刪除車輛訊息時序圖 drawio](https://github.com/Fangani141/-final_Pexam/assets/91513082/cd0fe65e-c41b-48d5-ab78-6b69ada16899)
<br />







圖3-2刪除車輛信息時序圖


![添加車輛訊息時序圖 drawio (1)](https://github.com/Fangani141/-final_Pexam/assets/91513082/1b2034c6-74bc-40e2-ac7f-bee3badddcd5)
<br />


圖3-3添加車輛信息時序圖




![查找車輛資訊時序圖 drawio](https://github.com/Fangani141/-final_Pexam/assets/91513082/62000962-59c4-42e9-a6a9-d80bbd4f9e7a)
<br />


圖3-5查找車輛信息時序圖



![查看車輛資訊時序圖 drawio](https://github.com/Fangani141/-final_Pexam/assets/91513082/eeb2dcae-6893-477f-8e2b-f277d3013a2b)
<br />

圖3-6查看車輛信息時序圖



## 3.2分析類模型
建立系統的分析類圖，為每個類分配職責、屬性，及對類之間的關西建模
<br />
![分析類模型 drawio](https://github.com/Fangani141/-final_Pexam/assets/91513082/26256ab0-32fc-4e26-974d-57c8d0c60f6e)
<br />

# 第四章 面相對象設計

## 4.1數據庫設計
數據庫結構
1. 車輛信息表
   

![image](https://github.com/Fangani141/-final_Pexam/assets/91513082/b805f92e-2982-40bf-8961-67f962bc2f6d)
<br />

  表3.5車輛信息表

2. 管理員信息表

![image](https://github.com/Fangani141/-final_Pexam/assets/91513082/b09ad690-ca17-4e2c-9ba9-875d41701b20)
<br />

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

![image](https://github.com/Fangani141/-final_Pexam/assets/91513082/8a8badb2-fa8b-405e-98b6-8ad473e782fb)
<br />

### 6.4.2添加信息用例測試

![image](https://github.com/Fangani141/-final_Pexam/assets/91513082/aeb5487d-3c2f-4b27-ac65-4d816d018bb1)
<br />

### 6.4.3查詢信息用例測試

![image](https://github.com/Fangani141/-final_Pexam/assets/91513082/01a1ed75-6c0d-43be-89c1-f02eec970eb9)
<br />

### 6.4.4瀏覽信息用例測試

![image](https://github.com/Fangani141/-final_Pexam/assets/91513082/adca12aa-83e0-46b1-8f01-de12d6a0aa26)
<br />

### 6.4.5刪除信息用例測試

![image](https://github.com/Fangani141/-final_Pexam/assets/91513082/1f947f98-fa16-4fa2-abe5-40627700efde)
<br />

# 6.5本章小節
本章捷主要介紹了對停車場管理系統進行功能測試的必要性和測試結果，針對當前停車管理系統設系了一系列的功能測試用例。通過系統測試使系統更能府和預期要求，並能檢測和修復一些開發過程中的bug。


# 第七章 停車場管理系統

（一）汽車、停車場、便道結構體的實現：

1. 汽車資訊被封裝成一個結構體，包括車牌號碼、入場時間，而入場時間的型別是time_t，用來記錄時間戳。
2. 停車場與便道被分別封裝為順序棧和鏈式隊列。

```
typedef struct Car
{
	char plateNumber[50];   //汽车车牌
	time_t approachTime;  //进如停车场时间
}Car;

//停车场（顺序栈）
typedef struct parkStack
{
	Car park[MAX];  //停车场的车位
	int top;        //栈指针
}parkStack;

//便道车位结点
typedef struct sidewalkNode
{
	Car position;   //数据域：便道中的一个车位
	struct sidewalkNode* next;  //指针域：指向下一个结点
}sidewalkNode;

//便道（链式队列）
typedef struct sidewalkQueue
{
	sidewalkNode* front;  //头指针
	sidewalkNode* rear;   //尾指针
}sidewalkQueue;
```

（二）汽車進入停車場：

汽車進入停車場的函數設計思路如下：

1. 進入停車場需要輸入車牌並保存。
2. 檢查停車場是否已滿，若尚未滿則繼續停車。保存汽車進入停車場的時間戳，並輸出汽車進入停車場的當前時間以及停在哪個車位。若停車場已滿，則將車輛停放到便道上，並輸入車輛停放在哪個便道。

```
//停车函数
void approach(parkStack* p, sidewalkQueue* sq)
{
	char number[50] = { 0 };
	printf("请输入车牌：");
	scanf("%s", number);
	if (!isFull(p)) //停车场是否满
	{
		//车辆停车
		printf("[开始停车]\n");
		strcpy(p->park[++p->top].plateNumber, number); //存储车牌
		time(&p->park[p->top].approachTime); //获取当前停车时间戳
		//ctime( )函数可以将时间戳转成人类可以直接看的懂的时间格式，如：The time is Fri Apr 29 12:25:12 1994
		printf("当前时间：%s", ctime(&p->park[p->top].approachTime));
		printf("车牌为%s的车停放在停车场%d号车位\n", p->park[p->top].plateNumber, p->top + 1);
		printf("[停车结束]\n");
	}
	else
	{
		//只能停在便道等待
		sidewalkNode* tmp = (sidewalkNode*)malloc(sizeof(sidewalkNode)); //为新来的车辆开辟一个空间
		if (tmp != NULL)
		{
			strcpy(tmp->position.plateNumber, number); //存放车牌
			tmp->next = NULL;
			sq->rear->next = tmp; //紧跟在便道中的车辆之后，即链接在已有结点之后
			sq->rear = tmp;  //修改队尾指针
		}
		printf("停车场已满，车辆只能停放在便道等候！\n");
		int count = 0;
		sidewalkNode* p = sq->front->next;
		while (p != NULL)
		{
			count++;
			p = p->next;
		}
		printf("车牌为%s的车停放在便道%d号车位\n", sq->rear->position.plateNumber, count);
	}
}

```
（三）汽車離開停車場：

汽車離開停車場的函數設計思路如下：

1. 輸入欲離開的汽車車牌。
2. 檢查停車場是否有該車輛，若有，則將在該車輛後進入的汽車暫時存入輔助棧中，讓該車輛離開。離開時，輸出離開的車輛、離開時間以及應繳納的停車費。若沒有，則輸出提示訊息。
3. 汽車離開後，將輔助棧中的汽車按照原先的次序回到停車場。
3. 檢查便道中是否有汽車，若有，則讓最先進入便道的車輛（隊頭元素）進入停車場，記錄進入停車場時的時間戳，並輸出汽車進入停車場的當前時間以及停在哪個車位。若沒有，則不進行任何操作。

```

//离开函数
void leave(parkStack* p, parkStack* ap, sidewalkQueue* sq)
{
	if (!isEmpty(p)) //检查停车场是否空
	{
		char number[50] = { 0 };
		printf("请输入离开的车牌：");
		scanf("%s", number);
		int n = p->top;
		int post = 0; //记录车辆停放的位置
		while (n > -1)  //检查停车场是否有该车辆
		{
			if (!strcmp(p->park[n].plateNumber, number))
			{
				post = n;
				break;
			}
			n--;
		}
		if (n == -1)
		{
			printf("停车场没有该车辆！\n");
		}
		else
		{
			Car tmpCar;
			time_t timer;
			while (p->top > post) //在该车辆之后进来的车辆全部入辅助栈
			{
				pop(p, &tmpCar); //车辆离开停车场，相当于出栈，并将元素存入到tmpCar中
				push(ap, &tmpCar); //车辆进入辅助栈，相当于入栈，将元素存入到辅助栈中
			}
			time(&timer); //获取时间戳
			long long total = timer - p->park[p->top].approachTime; //车辆总共停了多少秒
			long long h = total / 120; //计算停车多少小时
			long long m = (total - h * 120) / 60; //计算停车多少分钟
			long long s = total - h * 120 - m * 60; //计算停车多少秒
			printf("当前时间：%s", ctime(&timer));
			printf("车牌为%s的车辆离开停车场\n", p->park[p->top].plateNumber);
			printf("车辆停车时间总计：%lld时%lld分钟%lld秒，应缴费%lld元\n", h, m, s, total);
			p->top--; //该车辆出栈
			while (!isEmpty(ap)) //让路的车辆按照原来的次序回到停车场
			{
				pop(ap, &tmpCar);
				push(p, &tmpCar);
			}
			if (!isSidewalkEmpty(sq)) //如果便道不空，将便道中最前面的车入停车场，即队头元素出队
			{		
				sidewalkNode* s = NULL;
				s = sq->front->next; //s指向要删除的结点
				time(&s->position.approachTime); //记录汽车进入停车场时间
				printf("当前时间为：%s", ctime(&s->position.approachTime));
				printf("便道中车牌为%s的车辆进入停车场\n", s->position.plateNumber);
				p->park[++p->top] = s->position; //结点入栈（相当于便道中的汽车进入停车场）
				sq->front->next = s->next; //防止链队断裂
				free(s); //释放结点空间
			}
		}
	}
	else
	{
		printf("停车场为空！\n");
	}
}

```


（四）顯示停車場資訊：

1. 輸出目前停車場中每輛汽車的車牌號碼和所在車位。
   
```

//显示停车场信息
void showParking(parkStack* p)
{
	int i = 0;
	printf("[开始显示信息]\n");
	for (i = 0; i <= p->top; i++)
	{
		printf("车牌为%s的车辆停放在%d车位\n", p->park[i].plateNumber, i + 1);
	}
	printf("[显示结束，停车场目前停放了%d辆汽车]\n", p->top + 1);
}

```
（五）顯示便道資訊：

輸出目前便道中每輛汽車的車牌號碼和所在車位。

```
//显示便道信息
void showSidewalk(sidewalkQueue* sq)
{
	printf("[开始显示信息]\n");
	sidewalkNode* p = sq->front->next; //让p指向便道中第一辆汽车（队头元素）
	int count = 0;
	while (p != NULL)
	{
		printf("车牌为%s的车辆停放在%d车位\n", p->position.plateNumber, ++count);
		p = p->next;
	}
	printf("[显示结束，便道目前停放了%d辆汽车]\n", count);
}

```
# 參考資料
[停車場管理系統](https://blog.csdn.net/weixin_46970264/article/details/106645869?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522170307128616800186595925%2522%252C%2522scm%2522%253A%252220140713.130102334..%2522%257D&request_id=170307128616800186595925&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2%7Eall%7Etop_positive%7Edefault-1-106645869-null-null.142&fbclid=IwAR0Cme_ilQoYYEvXV7_OQ0DAC0rzODPajblqPRtjzWnnwOOOoDgC9w6ggWg)

