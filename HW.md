# I.基本觀念
```
資料階層(data hierarchy)==>Bit（位元）→Byte（字元）→Field（資料欄）→Record（資料錄）→Table（資料表）→Data Base（資料庫）
資料表(Table): 	欄位（field）與	記錄（record）
資料庫(Database)
資料(data)與資訊(information)
```

### 檔案處理系統(DBMS) vs. 資料庫(Database)[各有何優缺點]
```
檔案處理系統(DBMS) 
優點「檔案處理系統來處存和管理資料」
缺點「當更改時會出現資料不一致的情況」
           
資料庫(Database)
優點「降低資料重複性、改善資料不一致的情況、資料共享、容易存取、縮短開發時間」
缺點「需要更多的記憶體、容易被入侵」
```

# II.資料庫理論:
```
資料模型（data model）: 
   Network data model[1969,Charles Bachman]
   Hierarchical data model[60年代,IBM]
   relational Data Model[1969, Edgar F. Codd]
   
   Object-oriented data model
   Multi-dimensioncal data model[data warehouse  vs Data Mall]

資料庫系統 ANSI/SPARC 架構[略]
```
# III.資料庫管理系統
```
```
### SQL分成DDL│DML│DCL
```
●SQL(Structured Query Language)
    SQL的範圍包括資料插入、查詢、更新和刪除，資料庫模式建立和修改，以及資料存取控制。
   
●DDL(Data Definition Language)
    用來定義資料庫、資料表、檢視表、索引、預存程序、觸發程序、函數等資料庫物件。
    可以用來建立、更新、刪除 table,schema,domain,index,view
●DML(Data Manipulation Language)
    用來處理資料表裡的資料。
●DCL(Data Control Language)
    用來控制資料表、檢視表之存取權限，提供資料庫的安全性。
```
# IV.大數據與新興資料庫
```
```
### 4.1.Big data的特色: 3V vs 5V
```
  Big Data  3V’s ==Volume(數量)個人和機構產生的資料量、Velocity(速度)處理資料的速率、Variey(多樣性)資量能呈現或儲存的多種格式

  Big Data  5V’s ==>Volume、Variety、Velocity、Value(價值)大數據的定義從最早的3Vs、Veracity(真實)有很多時候資料的產出是人為有意地操作
```
### 4.2.大數據興起激發出新興資料庫發明===> NoSQL 
```
