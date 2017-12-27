# CyclingDataScience
Data Science is a hot topic that is impacting a huge range of diverse areas from business to sport. With so many cyclists collecting and uploading their data, there is plenty of raw material upon which to draw interesting insights. This project takes a look at how we might explore a set of historic rides. As a possible objective it would be very helpful to be able to categorise rides automatically.

I took as a data set Garmin files covering 2014-2017 that I had uploaded to Golden Cheetah (GC). This excellent software calculates a large range of statistics and provides an excellent interface for exploring rides. In Preferences you can enable a restful web service api that will be available whilst GC is running. This provides URLs that you can call from external programmes to retrieve data. For some reason I could not make this work reliably using Python 3.5, so this notebook runs Python 2.7. A separate Python 3.5 notebook in this folder is used to download the Strava history.

This project explores applications of data science in cycling. The objective is the produce a series of blogs demonstrating a range of techniques.

The root folder includes an Orange canvas that uses the 'History_Gavin_Names.csv" calculated in the Clusters folder. 

The first blog based on files in the Clusters folder may be found here here
https://science4performance.com/2017/12/12/cycling-data-science-clusters/

Second blog explores using Decision Trees, Random Forests and Support Vector Machines, here
https://science4performance.com/2017/12/24/cycling-data-science-building-models/
