---
title: "Hello R and Github"
author: "Tesfanesh"
date: "4/16/2021"
output: html_document
---
This is the assignment to be submitted
```{r}
a<-2
a
b<-5
b
r1<-a+b
r1
r2<-a-b
r2
r3<-a*b
r3
r4<-a/b
r4
v1<-c(r1,r2,r3,r4)
v1
v1<-c(r1,r2,r3,r4,a**b)
print(v1)
v2<-c("sum","difference","product","ratio","power")
v2
df<-data.frame(v1,v2)
names(df)[1]<-"Results"
names(df)[2]<-"Operation"
df
df[1, ]
df[2, ]
df[3, ]
df[ ,1]
```
