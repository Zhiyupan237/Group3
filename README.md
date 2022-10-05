# Group5
***
| 小組定位      | 學號             |姓名      | 工作內容    |
| :----------- | :--------------- | :------  | :---------- |
| 組長         | C109118220 |[胡世堯](https://github.com/SHIH-yao)   |程式編寫、程式除錯、上台報告|
| 組員         | C109118212 |[薛至斌](https://github.com/angus426)   |程式編寫、程式除錯、製作Github|
| 組員         | C109118231 |[廖宇蓁](https://github.com/yuzhena)    |程式編寫、程式除錯、製作Github|
| 組員         | C109118233 |[李文馨](https://github.com/C109118233) |程式編寫、程式除錯、製作簡報|
| 組員         | C109118237 |[潘姿妤](https://github.com/Zhiyupan237)|程式編寫、程式除錯、上台報告|
***
# 專案規劃表
| 編號 | 說明 | 需時(天) | 前置任務 | 完成日期 |
| :--: | :---| :------: | :-----: | :-----: |
|1|討論專案題目|1||10/04|
|2|討論工作分配|1|1|10/05|
|3|github製作|84|2|
|4|資料搜集與整理|14|2|
|5|程式編寫|49|4|
|6|程式除錯|21|5|
|7|簡報製作|14|3、5|
|8|上台報告|1|7|

### Mermaid
```mermaid
gantt
    title The Schedule of Communism

    section 討論專案題目
    Task A      :active,  des1,2022-10-01  , 2022-10-02
    section 討論工作分配
    Task B      :         des2, after des1 , 1d
    section GitHub製作
    Task C      :         des3, after des2  , 84d
    section 資料蒐集與整理
    Task D      :         des4, after des3  , 14d
    section 程式編寫
    Task E      :         des5, after des4  , 49d
    section 程式除錯
    Task F      :         des6, after des5  , 21d
    section 簡報製作
    Task G      :         des7, after des6  , 14d
    section 上台報告
    Task H      :         des8, after des7  , 1d
```


```graphviz
digraph {
	node[shape=record];
	rankdir="LR";
    no1 [label = "取得授權 | 編號:1 | 開始:第1天 | 結束:第10天 | 需時:10天"]
    no2 [label = "聘僱分析師 | 編號:2 | 開始:第11天 | 結束:40 | 需時:30天"]
    no1->no2
    no3 [label = "規劃訓練 | 編號:3 | 開始:第41天 | 結束:第45天 | 需時:5天"]
    no4 [label = "安排後勤 | 編號:4 | 開始:第41天 | 結束:第65天 | 需時:25天"]
    {rank=same;no3 no4}
    no2->no3
    no2->no4
    no5 [label = "宣告訓練 | 編號:5 | 開始:第66天 | 結束:第95天 | 需時:30天"]
    no3->no5
    no4->no5
}
```

