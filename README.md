# Group5
***
| 小組定位      | 學號             |姓名      | 工作內容    |
| :----------- | :--------------- | :------ | :---------- |
| 組長         | C109118220 |[胡世堯](https://github.com/SHIH-yao) |資料蒐集、資料處理、 內容編整|
| 組員         | C109118212 |[薛至斌](https://github.com/angus426)   |統整討論資料、影片拍攝、影片剪輯|
| 組員         | C109118231 |[廖宇蓁](https://github.com/yuzhena) |內容編整、問卷製作、發放問卷|
| 組員         | C109118233 |[李文馨](https://github.com/C109118233) |統整討論資料、簡報製作|
| 組員         | C109118237 |[潘姿妤](https://github.com/Zhiyupan237) |程式編寫、程式除錯|
***
# 專案規劃表
| 編號 | 說明 | 需時(天) | 前置任務 |
| :--: | :---| :------: | :-----: |
|1|討論專案題目|1||
|2|討論工作分配|1|1|
|3|
|4|
|5|
|6|
|7|
|8|
|9|
### Mermaid
```mermaid
gantt
    title The Schedule of Communism

    section The Beginning of Communism
    Task A      :active,  des1,2022-10-01  , 2022-10-04
    section Communism 2
    Task B      :         des2, after des1 , 10d
    section Communism 3
    Task C      :         des3, after des2  , 10d
    section Communism 4
    Task D      :         des4, after des3  , 10d
```


```graphviz
digraph hierarchy {

                nodesep=1.0 // increases the separation between nodes
                
                node [color=Red,fontname=Courier,shape=box] //All nodes will this shape and colour
                edge [color=Blue, style=dashed] //All the lines look like this

                Headteacher->{Deputy1 Deputy2 BusinessManager}
                Deputy1->{Teacher1 Teacher2}
                BusinessManager->ITManager
                {rank=same;ITManager Teacher1 Teacher2}  // Put them on the same level
}
```
