<h1><div align="center"> This is review of methods for Change Point Detection</div></h1>

<h1><div align="center">Task Description</div></h1>

https://en.wikipedia.org/wiki/Change_detection

![]({{ site.baseurl }}/images/posts/change_point_detection/change_point_types.png "change_point_types")


2 type of task:
    online and offline prediction
"""
Change point detection methods are divided into two main branches: online methods, that aim to detect changes as soon as they occur in a real-time setting, and offline methods that retro- spectively detect changes when all samples are received. The for- mer task is often referred to as event or anomaly detection, while the latter is sometimes called signal segmentation.
""" - selective review 1 paragraph    

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
- https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5464762/#:~:text=Change%20point%20detection%20(CPD)%20is,well%20as%20change%20point%20detection.
- BCPD
- https://arxiv.org/pdf/1801.00718.pdf
- https://onlinelibrary.wiley.com/doi/abs/10.1002/bs.3830190605
- https://arxiv.org/pdf/1801.00718.pdf
- https://habr.com/ru/company/jugru/blog/527186/
- https://arxiv.org/pdf/1101.1438.pdf   
    
    
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

Literature:
- https://charles.doffy.net/files/sp-review-2020.pdf
