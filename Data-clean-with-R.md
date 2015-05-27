---
title: "Data-clean-with-R"
author: "T.C. Hsieh"
date: "2015年1月25日"
output: html_document
---

### 1. Variable types and indexing techniques
- vectors have variables of _one_ type

```r
c(1, 2, "three")
```

```
[1] "1"     "2"     "three"
```

- shorter arguments are recycled

```r
(1:3) * 2
```

```
[1] 2 4 6
```

```r
(1:4) * c(1, 2)
```

```
[1] 1 4 3 8
```

```r
# warning! (why?)
(1:4) * (1:3)
```

```
Warning: 較長的物件長度並非較短物件長度的倍數
```

```
[1] 1 4 9 4
```





You can also embed plots, for example:

![plot of chunk unnamed-chunk-3](figure/unnamed-chunk-3.png) 

Note that the `echo = FALSE` parameter was added to the code chunk to prevent printing of the R code that generated the plot.
