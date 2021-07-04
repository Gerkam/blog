<h1><div align="center"> This is review of methods for Change Point Detection</div></h1>

<h1><div align="center">Task Description</div></h1>

https://en.wikipedia.org/wiki/Change_detection

![]({{ site.baseurl }}/images/posts/change_point_detection/change_point_types.png "change_point_types")

2 type of task:
    online and offline prediction
    

Most Popular Methods:

- Контрольные карты [Shewhart, 1931]
- Алгоритм кумулятивных сумм (CUSUM) [Page, 1954]
- Экспоненциально взвешенное скользящее среднее [Roberts, 1959]
- Фильтр Калмана [Kalman, 1960]
- Байесовские методы [Girshick & Rubin, 1952; Ширяев, 1961]
- Процедура Ширяева-Робертса [Ширяев, 1961; Roberts, 1966]
- Метод обобщенного отношения правдоподобия [Willsky, 1976]
- the binary segmentation algorithm (Scott and Knott 1974; Sen and Srivastava 1975)
- the segment neighborhood algorithm (Auger and Lawrence 1989; Bai and Perron 1998) 
- PELT algorithm (Killick, Fearnhead, and Eckley 2012a)
- Anomaly detection methods

Most Popular libs:

- https://github.com/deepcharles/ruptures
- https://github.com/linkedin/greykite
- https://eng.uber.com/orbit/ ?
- EconMl ?
- https://lindeloev.github.io/mcp/articles/packages.html
- https://www.marinedatascience.co/blog/2019/09/28/comparison-of-change-point-detection-methods/
- http://CRAN.R-project.org/package=changepoint
- https://cran.r-project.org/web/packages/changepoint/changepoint.pdf
- https://www.r-bloggers.com/2015/01/change-point-detection-in-time-series-with-r-and-tableau/
 
Tasks:
- Single change point detection

We now introduce the general likelihood ratio based approach to test this hypothesis. The potential for using a likelihood based approach to detect changepoints was first proposed by Hinkley (1970) who derives the asymptotic distribution of the likelihood ratio test statistic for a change in the mean within normally distributed observations. The likelihood based approach was extended to changes in variance within normally distributed observations by Gupta and Tang (1987). The interested reader is referred to Silva and Teixeira (2008) and Eckley, Fearnhead, and Killick (2011) for a more comprehensive review.
- Multiple

pass