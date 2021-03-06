# Data Cleaning 資料清理

***
#### Definition :
```markdown

在得到一個資料集，由於是從各個來源的DB的，常常不完整或是髒亂，EX:空值、NULL或重複資料等，
這時候就需要進行的清理與處理，讓資料集更符合所需，進而能夠精確的分析。
```
#### 場景 :
```markdown
不論是使用python或是SQL，大多是以下狀況為資料清洗上常遇到的情況!
   ●刪除指定行及重新命名
   ●重複值及缺失值的處理
   ●字串處理
   ●合併處理
   ●窗口涵式的分組排序
```

***

#### 套件  :
```markdown
Pandas
   
   ●Pandas套件提供了許多資料清理的方法(Method)，故透過使用這個套件去做資料的前處理。

   ●其主要結構為Series,DataFrame。

      Series:為索引標籤及實際值的陣列組合。DataFrame:類似於關聯資料庫(table)結構化資料的格式。

      開始安裝Pandas->和所有的Python套件安裝時一樣，需要在Terminal終端機安裝

```
``pip3 install pandas``

   [01.Pandas基礎語法統整](https://github.com/Wiwi-Creator/Data_Cleaning/blob/main/Pandas_Basic.ipynb)
   
   [02.Pnadas基礎檔案操作](https://github.com/Wiwi-Creator/Data_Cleaning/blob/main/Read_Csv.ipynb)
   
   [03.Lambda/Apply語法練習](https://github.com/Wiwi-Creator/Data_Cleaning/blob/main/Lambda%E5%92%8CApply.ipynb)
   
