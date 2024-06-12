# 分析

選擇 breast cancer dataset 作為預測用資料集。從 scatter plot 可以看出這個資料集的分佈大多都不會重疊，可以完美的分成兩群。Wine dataset 雖然也可以不錯的分群，但是還是有不少重疊資料。20 Newsgroups Dataset 的種類極多，且多數資料都有重疊，因此不適合。

# KNN

分析時，特徵分為 2 類，
1. 'mean radius', 'mean perimeter', 'mean area'
2. 'mean texture', 'mean smoothness'
最終分析的結果列於最 `breast.ipynb` 的最後