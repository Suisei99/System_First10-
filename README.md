# System_First10-
# 專題題目: 科技碳淨零
### 內容:
###### 
  由於台灣有炎熱的天氣，許多人在家都會開啟冷氣來消暑，不過，不少使用者也擔心電費會因此而爆表，所以不敢長時間開啟，但也有人覺得變頻空調開開關關的反而會更加耗電，大部分的使用者使用變頻空調的習慣都不一樣，有的人認為吹整天比較省電；有的認為若要出門一段時間的話，關掉反而比較省電，但是這沒有正確答案，都會因外在環境因素產生不一樣的答案 。
  對此，本小組希望能夠透過紅外線熱像儀來偵測房間內的熱外洩，並從熱像儀中提出熱像資料，再使用AI人工智慧應用來分析影像資料來量化環境這個不確定因素，使「到底變頻空調開一整天跟開開關關哪個更省？」這個議題得到最適合的解答。 

---

### 組長: 余承彥
#### 組員: 林荿絴、郝冠淵、沈育朋、林孟坤


---
## 組員任務分配 : 
| 姓名 | 負責任務 |
| ---- | ---- |
| 余承彥 | 撰寫計劃書、 學習相關技術、任務分配、程式開發、撰寫使用手冊、使用者訓練、轉換檔案 |
| 林荿絴 | 撰寫計劃書、 學習相關技術、任務分配、程式開發、程式測試、系統測試、使用者測試 |
| 郝冠淵| 學習相關技術、程式開發、程式測試、系統測試、使用者訓練 |
| 沈育朋| 學習相關技術、程式開發、取得硬體、安裝軟硬體、使用者測試 |
| 林孟坤| 學習相關技術、採購硬體、取得硬體、程式開發、安裝軟硬體、使用者測試 |
---
## 科技碳淨零 1024
|序 | 任務 | 需時(天) |  前置任務  |
|:--:|:---:|:-----:|:-----:|
| 1  | 撰寫計劃書 | 28 | - |
| 2  | 任務分配 |3 | 1 |   
| 3  | 學習相關技術 | 45 | 2 |
| 4  | 採購硬體 | 3 | 3 |
| 5  | 程式開發 | 60 | 4 |
| 6  | 取得硬體 | 3 | 5|
| 7  | 程式測試 | 15 | 6 |
| 8  | 撰寫使用手冊 | 10 | 6 |
| 9  | 安裝軟硬體 | 3 | 7,8,9 |
| 10 | 系統測試 | 10 | 9 |
| 11 | 轉換檔案 | 8 | 10 |
| 12 | 使用者訓練 | 3 | 10 |
| 13 | 使用者測試 | 7 | 11 |

---

## 甘特圖:
```mermaid

gantt
    title 系統分析流程
    dateFormat  MM-DD
    section 任務
    撰寫計劃書 : a1, 07-01, 28d
    任務分配 : a2, 07-29, 3d
    學習相關技術 : a3, 08-02, 45d
    採購硬體 : a4, 09-16, 3d
    程式開發 : a5, 09-19, 60d
    取得硬體 : a6, 11-18, 3d
    程式測試 : a7, 11-21, 15d
    撰寫使用手冊 : a8, 11-21, 10d
    安裝軟硬體 : a9, 12-06, 3d
    系統測試 : a10, 12-06, 10d
    轉換檔案 : a11, 12-16, 8d
    使用者訓練 : a12,12-16, 7d
    使用者測試 : a13, 12-24, 7d

```
```mermaid

gantt
    title 系統分析流程
    dateFormat  MM-DD
    section 余承彥
          撰寫計劃書 : a1, 07-01, 28d
          任務分配 : a2, 07-29, 3d
          學習相關技術 : a3, 08-02, 45d
          採購硬體 : a4, 09-16, 3d
          程式開發 : a5, 09-19, 60d
          撰寫使用手冊 : a8, 11-21, 10d
          使用者訓練 : a12,12-16, 7d
          轉換檔案 : a11, 12-16, 8d
          
    section 林荿絴
         撰寫計劃書 : a1, 07-01, 28d
          任務分配 : a2, 07-29, 3d
          學習相關技術 : a3, 08-02, 45d          
          程式開發 : a5, 09-19, 60d
          程式測試 : a7, 11-21, 15d
          系統測試 : a10, 12-06, 10d
          使用者測試 : a13, 12-24, 7d
        
    section 郝冠淵
        學習相關技術 : a3, 08-02, 45d
        程式開發 : a5, 09-19, 60d
        程式測試 : a7, 11-21, 15d
        系統測試 : a10, 12-06, 10d
        使用者訓練 : a12,12-16, 7d
        
    section 沈育朋
        學習相關技術 : a3, 08-02, 45d
        程式開發 : a5, 09-19, 60d
        取得硬體 : a6, 11-18, 3d
        安裝軟硬體 : a9, 12-06, 3d
        使用者測試 : a13, 12-24, 7d
        
    section 林孟坤
        學習相關技術 : a3, 08-02, 45d
        採購硬體 : a4, 09-16, 3d
        程式開發 : a5, 09-19, 60d
        取得硬體 : a6, 11-18, 3d
        安裝軟硬體 : a9, 12-06, 3d
        使用者測試 : a13, 12-24, 7d
```
## Pert圖與關鍵路徑:
```mermaid

classDiagram
  direction LR

  
  class 撰寫計劃書 {
    編號 : 001
    開始 : 2022-07-01
    結束 : 2022-07-29
    需時 : 28d
  }
  class 任務分配{
    編號 : 002
    開始 : 2022-07-29
    結束 : 2022-08-02
    需時 : 3d
  }
  class 學習相關技術{
    編號 : 003
    開始 : 2022-08-02
    結束 : 2022-09-16
    需時 : 45d
  }
  class 採購硬體{
    編號 : 004
    開始 : 2022-09-16
    結束 : 2022-09-19
    需時 : 3d
  }
  class 程式開發{
    編號 : 005
    開始 : 2022-09-19
    結束 : 2022-11-18
    需時 : 60d
  }
  class 取得硬體{
    編號 : 006
    開始 : 2022-11-18
    結束 : 2022-11-21
    需時 : 3d
  }
  class 程式測試{
    編號 : 007
    開始 : 2022-11-21
    結束 : 2022-12-06
    需時 : 15d
  }
  class 撰寫使用手冊{
    編號 : 008
    開始 : 2022-11-21
    結束 : 2022-12-01
    需時 : 10d
  }
  class 安裝軟硬體{
    編號 : 009
    開始 : 2022-12-06
    結束 : 2023-12-09
    需時 : 3d
  }
  class 系統測試{
    編號 : 010
    開始 : 2022-12-06
    結束 : 2022-12-16
    需時 : 10d
  }
  class 轉換檔案{
    編號 : 011
    開始 : 2022-12-16
    結束 : 2022-12-24
    需時 : 8d
  }
   class 使用者訓練{
    編號 : 012
    開始 : 2022-12-16
    結束 : 2022-12-23
    需時 : 7d
  }
   class 使用者測試{
    編號 : 013
    開始 : 2022-12-24
    結束 : 2022-12-31
    需時 : 7d
  }
  
  
  撰寫計劃書 --|> 任務分配 
  任務分配 --|> 學習相關技術
  學習相關技術 --|> 採購硬體
  採購硬體 --|> 程式開發
  程式開發 --|> 取得硬體
  取得硬體 --|> 程式測試
  程式測試 --|> 安裝軟硬體
  撰寫使用手冊 --|> 安裝軟硬體  
  安裝軟硬體--|> 系統測試
  系統測試 --|> 轉換檔案
  轉換檔案 --|> 使用者測試
  使用者訓練 --|> 使用者測試
```
### 關鍵路徑: 1 -> 2 -> 3 -> 4 -> 5 -> 6 -> 7 -> 10 -> 11-> 13



---
