# R 언어 Hack Sheets

_You **can** mastering R language_

## Inatallation

## 참고서적

*[histogram] (http://www.ats.ucla.edu/stat/r/gbe/histogram.htm)
*[boxplot] (http://www.ats.ucla.edu/stat/r/gbe/boxplot.htm)
*[scatter] (http://www.ats.ucla.edu/stat/r/gbe/scatter.htm)
*[ggplot_boxplot] (http://www.ats.ucla.edu/stat/r/gbe/ggplot_boxplot.htm)
*[line-and-scatter] https://plot.ly/r/line-and-scatter/
*[iris_plots] (http://www2.warwick.ac.uk/fac/sci/moac/people/students/peter_cock/r/iris_plots/)
*[Scatter plot, ggplot2] (http://www.sthda.com/english/wiki/ggplot2-scatter-plots-quick-start-guide-r-software-and-data-visualization)
*[histogram, ggplot2] (http://www.r-bloggers.com/how-to-make-a-histogram-with-ggplot2/)
*[ggplot2](http://www.cookbook-r.com/Graphs/Plotting_distributions_(ggplot2)/)

Quick start guide는 [여기](http://www.sthda.com/english/wiki/ggplot2-histogram-plot-quick-start-guide-r-software-and-data-visualization)
[](http://www.sthda.com/english/wiki/ggplot2-histogram-easy-histogram-graph-with-ggplot2-r-package)
data mining 소개[pdf](http://datamining.dongguk.ac.kr/R/R%EC%9D%98%EC%84%A4%EC%B9%98%EB%B0%8F%EA%B8%B0%EB%B3%B8%EC%82%AC%EC%9A%A9%EB%B2%95.pdf)
영상자료[영상]https://www.youtube.com/watch?v=rqrrTfy-z-c

## public dataset
###인터넷으로 구할 수 있는 빅데이터용 자료들
 what to do : https://www.data.go.kr/#/L21haW4=
 what to do : http://data.seoul.go.kr/

### 스타벅스 매장 전략
 http://m.dongabiz.com/Business/Marketing/content.php?atno=1202054701&chap_no=1&sdkey=14424653996&user=dep#TOP

## R언어 문법

### 산점도
```R
plot(read, write)
names(hsb2)
cor(read, write)
```
###
```R
plot(math, write)
abline(lsfit(write, math))
```

###alternatively
```R
plot(math, write)
fit<-lm(write ~ math)
abline(fit)
```
