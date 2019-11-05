## Predicting Ambitious Instruction in CPS Schools
[Project Blog](https://ivyabid.blogspot.com/2019/10/predicting-ambitious-instruction-at-cps.html)

This project involved two parts that are represented by two separate notebooks in the 'code' folder.

### Scraping and Data Gathering
One notebook is specific just to scraping my 5 Essentials data and combining it with other data that was downloadable as CSVs from other sources.

### Modeling
The other notebook will take you through my workflow in selecting features, developing my model, experimenting with feature engineering and alpha values, and finally testing and estimating error of my models.


### The 'Don't Grade This' Folder
I briefly experimented with changing my target, to SQRP rating, because I noticed it was heavily correlated with low-income students, and seemed to have polynomial features I thought would be interesting. I immediately discovered I would not be able to make as robust a model using SQRP as a target. It also didn't seem productive to try reverse-engineering a model for SQRP rating, a metric which is itself just the output of a complex polynomial function.
