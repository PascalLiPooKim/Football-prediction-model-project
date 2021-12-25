# Football-prediction-model-project

## About the Project

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)

![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)

This project aimed at using some of the different Machine Learning models from the [```scikit-learn```](https://scikit-learn.org/stable/) library to make Football predictions based on real-world data from $14$ different leagues from the seasons $1990$ to $2021$. The football leagues are:

```
1. 2. Bundesliga
2. Bundesliga
3. EFL Championship
4. Eerste Divisie
5. Eredivisie
6. Ligue 1
7. Ligue 2
8. Premier League
9. Primeira Liga
10. Primeria Division
11. Segunda Division
12. Segunda Liga
13. Serie A
14. Serie B
```

All the codes were written in the ```Python``` programming language on ```Google Colab```. The $6$ classification ML algorithms that were chosen in this project are:

1. [Logistic Regression](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html)
2. [C-Support Vector Classification](https://scikit-learn.org/stable/modules/generated/sklearn.svm.SVC.html)
3. [K-nearest-Neighbors Classifier](https://scikit-learn.org/stable/modules/generated/sklearn.neighbors.KNeighborsClassifier.html)
4. [Random Forest Classifier](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html)
5. [AdaBoost Classifier](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.AdaBoostClassifier.html)
6. [Gradient Boosting Classifier](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.GradientBoostingClassifier.html)

The results of each of the model on the dataset are found in the ```footballPredictionModel.ipynb``` notebook.

## Acknowledgement

This project was given to me by one of the [```AiCore```](https://www.theaicore.com/) instructor _Blair Martin_ (Email: blair@theaicore.com) as part of a personal project for the **Data Science** pathway.

## Directory and File Structure

The way that the folders and the available files were structured in this project can be found below. The repository however does not include the pre-trained models. The latter can be obtained and downloaded via the links provided in the ```footballPredictionModel.ipynb``` notebook.

```


Football-prediction-model-project                 
├─ Football_Data                                  
│  ├─ Football_Data                               
│  │  ├─ Results                                  
│  │  │  ├─ 2_liga                                
│  │  │  │  ├─ Results_1990_2_liga.csv            
│  │  │  │  ├─ Results_1991_2_liga.csv            
│  │  │  │  ├─ Results_1992_2_liga.csv            
│  │  │  │  ├─ Results_1993_2_liga.csv            
│  │  │  │  ├─ Results_1994_2_liga.csv            
│  │  │  │  ├─ Results_1995_2_liga.csv            
│  │  │  │  ├─ Results_1996_2_liga.csv
│  │  │  │  ├─ Results_1997_2_liga.csv            
│  │  │  │  ├─ Results_1998_2_liga.csv            
│  │  │  │  ├─ Results_1999_2_liga.csv            
│  │  │  │  ├─ Results_2000_2_liga.csv            
│  │  │  │  ├─ Results_2001_2_liga.csv            
│  │  │  │  ├─ Results_2002_2_liga.csv            
│  │  │  │  ├─ Results_2003_2_liga.csv            
│  │  │  │  ├─ Results_2004_2_liga.csv            
│  │  │  │  ├─ Results_2005_2_liga.csv            
│  │  │  │  ├─ Results_2006_2_liga.csv            
│  │  │  │  ├─ Results_2007_2_liga.csv            
│  │  │  │  ├─ Results_2008_2_liga.csv            
│  │  │  │  ├─ Results_2009_2_liga.csv            
│  │  │  │  ├─ Results_2010_2_liga.csv            
│  │  │  │  ├─ Results_2011_2_liga.csv            
│  │  │  │  ├─ Results_2012_2_liga.csv            
│  │  │  │  ├─ Results_2013_2_liga.csv            
│  │  │  │  ├─ Results_2014_2_liga.csv            
│  │  │  │  ├─ Results_2015_2_liga.csv            
│  │  │  │  ├─ Results_2016_2_liga.csv            
│  │  │  │  ├─ Results_2017_2_liga.csv            
│  │  │  │  ├─ Results_2018_2_liga.csv            
│  │  │  │  ├─ Results_2019_2_liga.csv            
│  │  │  │  ├─ Results_2020_2_liga.csv            
│  │  │  │  └─ Results_2021_2_liga.csv            
│  │  │  ├─ bundesliga                            
│  │  │  │  ├─ Results_1990_bundesliga.csv        
│  │  │  │  ├─ Results_1991_bundesliga.csv        
│  │  │  │  ├─ Results_1992_bundesliga.csv        
│  │  │  │  ├─ Results_1993_bundesliga.csv        
│  │  │  │  ├─ Results_1994_bundesliga.csv        
│  │  │  │  ├─ Results_1995_bundesliga.csv        
│  │  │  │  ├─ Results_1996_bundesliga.csv        
│  │  │  │  ├─ Results_1997_bundesliga.csv        
│  │  │  │  ├─ Results_1998_bundesliga.csv        
│  │  │  │  ├─ Results_1999_bundesliga.csv        
│  │  │  │  ├─ Results_2000_bundesliga.csv        
│  │  │  │  ├─ Results_2001_bundesliga.csv        
│  │  │  │  ├─ Results_2002_bundesliga.csv        
│  │  │  │  ├─ Results_2003_bundesliga.csv        
│  │  │  │  ├─ Results_2004_bundesliga.csv        
│  │  │  │  ├─ Results_2005_bundesliga.csv        
│  │  │  │  ├─ Results_2006_bundesliga.csv        
│  │  │  │  ├─ Results_2007_bundesliga.csv        
│  │  │  │  ├─ Results_2008_bundesliga.csv        
│  │  │  │  ├─ Results_2009_bundesliga.csv        
│  │  │  │  ├─ Results_2010_bundesliga.csv        
│  │  │  │  ├─ Results_2011_bundesliga.csv        
│  │  │  │  ├─ Results_2012_bundesliga.csv        
│  │  │  │  ├─ Results_2013_bundesliga.csv        
│  │  │  │  ├─ Results_2014_bundesliga.csv        
│  │  │  │  ├─ Results_2015_bundesliga.csv        
│  │  │  │  ├─ Results_2016_bundesliga.csv        
│  │  │  │  ├─ Results_2017_bundesliga.csv        
│  │  │  │  ├─ Results_2018_bundesliga.csv        
│  │  │  │  ├─ Results_2019_bundesliga.csv        
│  │  │  │  ├─ Results_2020_bundesliga.csv        
│  │  │  │  └─ Results_2021_bundesliga.csv        
│  │  │  ├─ championship                          
│  │  │  │  ├─ Results_1990_championship.csv      
│  │  │  │  ├─ Results_1991_championship.csv      
│  │  │  │  ├─ Results_1992_championship.csv      
│  │  │  │  ├─ Results_1993_championship.csv      
│  │  │  │  ├─ Results_1994_championship.csv      
│  │  │  │  ├─ Results_1995_championship.csv      
│  │  │  │  ├─ Results_1996_championship.csv      
│  │  │  │  ├─ Results_1997_championship.csv      
│  │  │  │  ├─ Results_1998_championship.csv      
│  │  │  │  ├─ Results_1999_championship.csv      
│  │  │  │  ├─ Results_2000_championship.csv      
│  │  │  │  ├─ Results_2001_championship.csv      
│  │  │  │  ├─ Results_2002_championship.csv      
│  │  │  │  ├─ Results_2003_championship.csv      
│  │  │  │  ├─ Results_2004_championship.csv      
│  │  │  │  ├─ Results_2005_championship.csv      
│  │  │  │  ├─ Results_2006_championship.csv      
│  │  │  │  ├─ Results_2007_championship.csv      
│  │  │  │  ├─ Results_2008_championship.csv      
│  │  │  │  ├─ Results_2009_championship.csv      
│  │  │  │  ├─ Results_2010_championship.csv      
│  │  │  │  ├─ Results_2011_championship.csv      
│  │  │  │  ├─ Results_2012_championship.csv      
│  │  │  │  ├─ Results_2013_championship.csv      
│  │  │  │  ├─ Results_2014_championship.csv      
│  │  │  │  ├─ Results_2015_championship.csv      
│  │  │  │  ├─ Results_2016_championship.csv      
│  │  │  │  ├─ Results_2017_championship.csv      
│  │  │  │  ├─ Results_2018_championship.csv      
│  │  │  │  ├─ Results_2019_championship.csv      
│  │  │  │  ├─ Results_2020_championship.csv      
│  │  │  │  └─ Results_2021_championship.csv      
│  │  │  ├─ eerste_divisie                        
│  │  │  │  ├─ Results_1990_eerste_divisie.csv    
│  │  │  │  ├─ Results_1991_eerste_divisie.csv    
│  │  │  │  ├─ Results_1992_eerste_divisie.csv    
│  │  │  │  ├─ Results_1993_eerste_divisie.csv    
│  │  │  │  ├─ Results_1994_eerste_divisie.csv    
│  │  │  │  ├─ Results_1995_eerste_divisie.csv    
│  │  │  │  ├─ Results_1996_eerste_divisie.csv    
│  │  │  │  ├─ Results_1997_eerste_divisie.csv    
│  │  │  │  ├─ Results_1998_eerste_divisie.csv    
│  │  │  │  ├─ Results_1999_eerste_divisie.csv    
│  │  │  │  ├─ Results_2000_eerste_divisie.csv    
│  │  │  │  ├─ Results_2001_eerste_divisie.csv    
│  │  │  │  ├─ Results_2002_eerste_divisie.csv    
│  │  │  │  ├─ Results_2003_eerste_divisie.csv    
│  │  │  │  ├─ Results_2004_eerste_divisie.csv    
│  │  │  │  ├─ Results_2005_eerste_divisie.csv    
│  │  │  │  ├─ Results_2006_eerste_divisie.csv    
│  │  │  │  ├─ Results_2007_eerste_divisie.csv    
│  │  │  │  ├─ Results_2008_eerste_divisie.csv    
│  │  │  │  ├─ Results_2009_eerste_divisie.csv    
│  │  │  │  ├─ Results_2010_eerste_divisie.csv    
│  │  │  │  ├─ Results_2011_eerste_divisie.csv    
│  │  │  │  ├─ Results_2012_eerste_divisie.csv    
│  │  │  │  ├─ Results_2013_eerste_divisie.csv    
│  │  │  │  ├─ Results_2014_eerste_divisie.csv    
│  │  │  │  ├─ Results_2015_eerste_divisie.csv    
│  │  │  │  ├─ Results_2016_eerste_divisie.csv    
│  │  │  │  ├─ Results_2017_eerste_divisie.csv    
│  │  │  │  ├─ Results_2018_eerste_divisie.csv    
│  │  │  │  ├─ Results_2019_eerste_divisie.csv    
│  │  │  │  ├─ Results_2020_eerste_divisie.csv    
│  │  │  │  └─ Results_2021_eerste_divisie.csv    
│  │  │  ├─ eredivisie                            
│  │  │  │  ├─ Results_1990_eredivisie.csv        
│  │  │  │  ├─ Results_1991_eredivisie.csv        
│  │  │  │  ├─ Results_1992_eredivisie.csv        
│  │  │  │  ├─ Results_1993_eredivisie.csv        
│  │  │  │  ├─ Results_1994_eredivisie.csv        
│  │  │  │  ├─ Results_1995_eredivisie.csv        
│  │  │  │  ├─ Results_1996_eredivisie.csv        
│  │  │  │  ├─ Results_1997_eredivisie.csv        
│  │  │  │  ├─ Results_1998_eredivisie.csv        
│  │  │  │  ├─ Results_1999_eredivisie.csv        
│  │  │  │  ├─ Results_2000_eredivisie.csv        
│  │  │  │  ├─ Results_2001_eredivisie.csv        
│  │  │  │  ├─ Results_2002_eredivisie.csv        
│  │  │  │  ├─ Results_2003_eredivisie.csv        
│  │  │  │  ├─ Results_2004_eredivisie.csv        
│  │  │  │  ├─ Results_2005_eredivisie.csv        
│  │  │  │  ├─ Results_2006_eredivisie.csv        
│  │  │  │  ├─ Results_2007_eredivisie.csv        
│  │  │  │  ├─ Results_2008_eredivisie.csv        
│  │  │  │  ├─ Results_2009_eredivisie.csv        
│  │  │  │  ├─ Results_2010_eredivisie.csv        
│  │  │  │  ├─ Results_2011_eredivisie.csv        
│  │  │  │  ├─ Results_2012_eredivisie.csv        
│  │  │  │  ├─ Results_2013_eredivisie.csv        
│  │  │  │  ├─ Results_2014_eredivisie.csv        
│  │  │  │  ├─ Results_2015_eredivisie.csv        
│  │  │  │  ├─ Results_2016_eredivisie.csv        
│  │  │  │  ├─ Results_2017_eredivisie.csv        
│  │  │  │  ├─ Results_2018_eredivisie.csv        
│  │  │  │  ├─ Results_2019_eredivisie.csv        
│  │  │  │  ├─ Results_2020_eredivisie.csv        
│  │  │  │  └─ Results_2021_eredivisie.csv        
│  │  │  ├─ ligue_1                               
│  │  │  │  ├─ Results_1990_ligue_1.csv           
│  │  │  │  ├─ Results_1991_ligue_1.csv           
│  │  │  │  ├─ Results_1992_ligue_1.csv           
│  │  │  │  ├─ Results_1993_ligue_1.csv           
│  │  │  │  ├─ Results_1994_ligue_1.csv           
│  │  │  │  ├─ Results_1995_ligue_1.csv           
│  │  │  │  ├─ Results_1996_ligue_1.csv           
│  │  │  │  ├─ Results_1997_ligue_1.csv           
│  │  │  │  ├─ Results_1998_ligue_1.csv           
│  │  │  │  ├─ Results_1999_ligue_1.csv           
│  │  │  │  ├─ Results_2000_ligue_1.csv           
│  │  │  │  ├─ Results_2001_ligue_1.csv           
│  │  │  │  ├─ Results_2002_ligue_1.csv           
│  │  │  │  ├─ Results_2003_ligue_1.csv           
│  │  │  │  ├─ Results_2004_ligue_1.csv           
│  │  │  │  ├─ Results_2005_ligue_1.csv           
│  │  │  │  ├─ Results_2006_ligue_1.csv           
│  │  │  │  ├─ Results_2007_ligue_1.csv           
│  │  │  │  ├─ Results_2008_ligue_1.csv           
│  │  │  │  ├─ Results_2009_ligue_1.csv           
│  │  │  │  ├─ Results_2010_ligue_1.csv           
│  │  │  │  ├─ Results_2011_ligue_1.csv           
│  │  │  │  ├─ Results_2012_ligue_1.csv           
│  │  │  │  ├─ Results_2013_ligue_1.csv           
│  │  │  │  ├─ Results_2014_ligue_1.csv           
│  │  │  │  ├─ Results_2015_ligue_1.csv           
│  │  │  │  ├─ Results_2016_ligue_1.csv           
│  │  │  │  ├─ Results_2017_ligue_1.csv           
│  │  │  │  ├─ Results_2018_ligue_1.csv           
│  │  │  │  ├─ Results_2019_ligue_1.csv           
│  │  │  │  ├─ Results_2020_ligue_1.csv           
│  │  │  │  └─ Results_2021_ligue_1.csv           
│  │  │  ├─ ligue_2                               
│  │  │  │  ├─ Results_1990_ligue_2.csv           
│  │  │  │  ├─ Results_1991_ligue_2.csv           
│  │  │  │  ├─ Results_1992_ligue_2.csv           
│  │  │  │  ├─ Results_1993_ligue_2.csv           
│  │  │  │  ├─ Results_1994_ligue_2.csv           
│  │  │  │  ├─ Results_1995_ligue_2.csv           
│  │  │  │  ├─ Results_1996_ligue_2.csv           
│  │  │  │  ├─ Results_1997_ligue_2.csv           
│  │  │  │  ├─ Results_1998_ligue_2.csv           
│  │  │  │  ├─ Results_1999_ligue_2.csv           
│  │  │  │  ├─ Results_2000_ligue_2.csv           
│  │  │  │  ├─ Results_2001_ligue_2.csv           
│  │  │  │  ├─ Results_2002_ligue_2.csv           
│  │  │  │  ├─ Results_2003_ligue_2.csv           
│  │  │  │  ├─ Results_2004_ligue_2.csv           
│  │  │  │  ├─ Results_2005_ligue_2.csv           
│  │  │  │  ├─ Results_2006_ligue_2.csv           
│  │  │  │  ├─ Results_2007_ligue_2.csv           
│  │  │  │  ├─ Results_2008_ligue_2.csv           
│  │  │  │  ├─ Results_2009_ligue_2.csv           
│  │  │  │  ├─ Results_2010_ligue_2.csv           
│  │  │  │  ├─ Results_2011_ligue_2.csv           
│  │  │  │  ├─ Results_2012_ligue_2.csv           
│  │  │  │  ├─ Results_2013_ligue_2.csv           
│  │  │  │  ├─ Results_2014_ligue_2.csv           
│  │  │  │  ├─ Results_2015_ligue_2.csv           
│  │  │  │  ├─ Results_2016_ligue_2.csv           
│  │  │  │  ├─ Results_2017_ligue_2.csv           
│  │  │  │  ├─ Results_2018_ligue_2.csv           
│  │  │  │  ├─ Results_2019_ligue_2.csv           
│  │  │  │  ├─ Results_2020_ligue_2.csv           
│  │  │  │  └─ Results_2021_ligue_2.csv           
│  │  │  ├─ premier_league                        
│  │  │  │  ├─ Results_1990_premier_league.csv    
│  │  │  │  ├─ Results_1991_premier_league.csv    
│  │  │  │  ├─ Results_1992_premier_league.csv    
│  │  │  │  ├─ Results_1993_premier_league.csv    
│  │  │  │  ├─ Results_1994_premier_league.csv    
│  │  │  │  ├─ Results_1995_premier_league.csv    
│  │  │  │  ├─ Results_1996_premier_league.csv    
│  │  │  │  ├─ Results_1997_premier_league.csv    
│  │  │  │  ├─ Results_1998_premier_league.csv    
│  │  │  │  ├─ Results_1999_premier_league.csv    
│  │  │  │  ├─ Results_2000_premier_league.csv    
│  │  │  │  ├─ Results_2001_premier_league.csv    
│  │  │  │  ├─ Results_2002_premier_league.csv    
│  │  │  │  ├─ Results_2003_premier_league.csv    
│  │  │  │  ├─ Results_2004_premier_league.csv    
│  │  │  │  ├─ Results_2005_premier_league.csv    
│  │  │  │  ├─ Results_2006_premier_league.csv    
│  │  │  │  ├─ Results_2007_premier_league.csv    
│  │  │  │  ├─ Results_2008_premier_league.csv    
│  │  │  │  ├─ Results_2009_premier_league.csv    
│  │  │  │  ├─ Results_2010_premier_league.csv    
│  │  │  │  ├─ Results_2011_premier_league.csv    
│  │  │  │  ├─ Results_2012_premier_league.csv    
│  │  │  │  ├─ Results_2013_premier_league.csv    
│  │  │  │  ├─ Results_2014_premier_league.csv    
│  │  │  │  ├─ Results_2015_premier_league.csv    
│  │  │  │  ├─ Results_2016_premier_league.csv    
│  │  │  │  ├─ Results_2017_premier_league.csv    
│  │  │  │  ├─ Results_2018_premier_league.csv    
│  │  │  │  ├─ Results_2019_premier_league.csv    
│  │  │  │  ├─ Results_2020_premier_league.csv    
│  │  │  │  └─ Results_2021_premier_league.csv    
│  │  │  ├─ primeira_liga                         
│  │  │  │  ├─ Results_1990_primeira_liga.csv     
│  │  │  │  ├─ Results_1991_primeira_liga.csv     
│  │  │  │  ├─ Results_1992_primeira_liga.csv     
│  │  │  │  ├─ Results_1993_primeira_liga.csv     
│  │  │  │  ├─ Results_1994_primeira_liga.csv     
│  │  │  │  ├─ Results_1995_primeira_liga.csv     
│  │  │  │  ├─ Results_1996_primeira_liga.csv     
│  │  │  │  ├─ Results_1997_primeira_liga.csv     
│  │  │  │  ├─ Results_1998_primeira_liga.csv     
│  │  │  │  ├─ Results_1999_primeira_liga.csv     
│  │  │  │  ├─ Results_2000_primeira_liga.csv     
│  │  │  │  ├─ Results_2001_primeira_liga.csv     
│  │  │  │  ├─ Results_2002_primeira_liga.csv     
│  │  │  │  ├─ Results_2003_primeira_liga.csv     
│  │  │  │  ├─ Results_2004_primeira_liga.csv     
│  │  │  │  ├─ Results_2005_primeira_liga.csv     
│  │  │  │  ├─ Results_2006_primeira_liga.csv     
│  │  │  │  ├─ Results_2007_primeira_liga.csv     
│  │  │  │  ├─ Results_2008_primeira_liga.csv     
│  │  │  │  ├─ Results_2009_primeira_liga.csv     
│  │  │  │  ├─ Results_2010_primeira_liga.csv     
│  │  │  │  ├─ Results_2011_primeira_liga.csv     
│  │  │  │  ├─ Results_2012_primeira_liga.csv     
│  │  │  │  ├─ Results_2013_primeira_liga.csv     
│  │  │  │  ├─ Results_2014_primeira_liga.csv     
│  │  │  │  ├─ Results_2015_primeira_liga.csv     
│  │  │  │  ├─ Results_2016_primeira_liga.csv     
│  │  │  │  ├─ Results_2017_primeira_liga.csv     
│  │  │  │  ├─ Results_2018_primeira_liga.csv     
│  │  │  │  ├─ Results_2019_primeira_liga.csv     
│  │  │  │  ├─ Results_2020_primeira_liga.csv     
│  │  │  │  └─ Results_2021_primeira_liga.csv     
│  │  │  ├─ primera_division                      
│  │  │  │  ├─ Results_1990_primera_division.csv  
│  │  │  │  ├─ Results_1991_primera_division.csv  
│  │  │  │  ├─ Results_1992_primera_division.csv  
│  │  │  │  ├─ Results_1993_primera_division.csv  
│  │  │  │  ├─ Results_1994_primera_division.csv  
│  │  │  │  ├─ Results_1995_primera_division.csv  
│  │  │  │  ├─ Results_1996_primera_division.csv  
│  │  │  │  ├─ Results_1997_primera_division.csv  
│  │  │  │  ├─ Results_1998_primera_division.csv  
│  │  │  │  ├─ Results_1999_primera_division.csv  
│  │  │  │  ├─ Results_2000_primera_division.csv  
│  │  │  │  ├─ Results_2001_primera_division.csv  
│  │  │  │  ├─ Results_2002_primera_division.csv  
│  │  │  │  ├─ Results_2003_primera_division.csv  
│  │  │  │  ├─ Results_2004_primera_division.csv  
│  │  │  │  ├─ Results_2005_primera_division.csv  
│  │  │  │  ├─ Results_2006_primera_division.csv  
│  │  │  │  ├─ Results_2007_primera_division.csv  
│  │  │  │  ├─ Results_2008_primera_division.csv  
│  │  │  │  ├─ Results_2009_primera_division.csv  
│  │  │  │  ├─ Results_2010_primera_division.csv  
│  │  │  │  ├─ Results_2011_primera_division.csv  
│  │  │  │  ├─ Results_2012_primera_division.csv  
│  │  │  │  ├─ Results_2013_primera_division.csv  
│  │  │  │  ├─ Results_2014_primera_division.csv  
│  │  │  │  ├─ Results_2015_primera_division.csv  
│  │  │  │  ├─ Results_2016_primera_division.csv  
│  │  │  │  ├─ Results_2017_primera_division.csv  
│  │  │  │  ├─ Results_2018_primera_division.csv  
│  │  │  │  ├─ Results_2019_primera_division.csv  
│  │  │  │  ├─ Results_2020_primera_division.csv  
│  │  │  │  └─ Results_2021_primera_division.csv  
│  │  │  ├─ segunda_division                      
│  │  │  │  ├─ Results_1990_segunda_division.csv  
│  │  │  │  ├─ Results_1991_segunda_division.csv  
│  │  │  │  ├─ Results_1992_segunda_division.csv  
│  │  │  │  ├─ Results_1993_segunda_division.csv  
│  │  │  │  ├─ Results_1994_segunda_division.csv  
│  │  │  │  ├─ Results_1995_segunda_division.csv  
│  │  │  │  ├─ Results_1996_segunda_division.csv  
│  │  │  │  ├─ Results_1997_segunda_division.csv  
│  │  │  │  ├─ Results_1998_segunda_division.csv  
│  │  │  │  ├─ Results_1999_segunda_division.csv  
│  │  │  │  ├─ Results_2000_segunda_division.csv  
│  │  │  │  ├─ Results_2001_segunda_division.csv  
│  │  │  │  ├─ Results_2002_segunda_division.csv  
│  │  │  │  ├─ Results_2003_segunda_division.csv  
│  │  │  │  ├─ Results_2004_segunda_division.csv  
│  │  │  │  ├─ Results_2005_segunda_division.csv  
│  │  │  │  ├─ Results_2006_segunda_division.csv  
│  │  │  │  ├─ Results_2007_segunda_division.csv  
│  │  │  │  ├─ Results_2008_segunda_division.csv  
│  │  │  │  ├─ Results_2009_segunda_division.csv  
│  │  │  │  ├─ Results_2010_segunda_division.csv  
│  │  │  │  ├─ Results_2011_segunda_division.csv  
│  │  │  │  ├─ Results_2012_segunda_division.csv  
│  │  │  │  ├─ Results_2013_segunda_division.csv  
│  │  │  │  ├─ Results_2014_segunda_division.csv  
│  │  │  │  ├─ Results_2015_segunda_division.csv  
│  │  │  │  ├─ Results_2016_segunda_division.csv  
│  │  │  │  ├─ Results_2017_segunda_division.csv  
│  │  │  │  ├─ Results_2018_segunda_division.csv  
│  │  │  │  ├─ Results_2019_segunda_division.csv  
│  │  │  │  ├─ Results_2020_segunda_division.csv  
│  │  │  │  └─ Results_2021_segunda_division.csv  
│  │  │  ├─ segunda_liga                          
│  │  │  │  ├─ Results_1990_segunda_liga.csv      
│  │  │  │  ├─ Results_1991_segunda_liga.csv      
│  │  │  │  ├─ Results_1992_segunda_liga.csv      
│  │  │  │  ├─ Results_1993_segunda_liga.csv      
│  │  │  │  ├─ Results_1994_segunda_liga.csv      
│  │  │  │  ├─ Results_1995_segunda_liga.csv      
│  │  │  │  ├─ Results_1996_segunda_liga.csv      
│  │  │  │  ├─ Results_1997_segunda_liga.csv      
│  │  │  │  ├─ Results_1998_segunda_liga.csv      
│  │  │  │  ├─ Results_1999_segunda_liga.csv      
│  │  │  │  ├─ Results_2000_segunda_liga.csv      
│  │  │  │  ├─ Results_2001_segunda_liga.csv      
│  │  │  │  ├─ Results_2002_segunda_liga.csv      
│  │  │  │  ├─ Results_2003_segunda_liga.csv      
│  │  │  │  ├─ Results_2004_segunda_liga.csv      
│  │  │  │  ├─ Results_2005_segunda_liga.csv      
│  │  │  │  ├─ Results_2006_segunda_liga.csv      
│  │  │  │  ├─ Results_2007_segunda_liga.csv      
│  │  │  │  ├─ Results_2008_segunda_liga.csv      
│  │  │  │  ├─ Results_2009_segunda_liga.csv      
│  │  │  │  ├─ Results_2010_segunda_liga.csv      
│  │  │  │  ├─ Results_2011_segunda_liga.csv      
│  │  │  │  ├─ Results_2012_segunda_liga.csv      
│  │  │  │  ├─ Results_2013_segunda_liga.csv      
│  │  │  │  ├─ Results_2014_segunda_liga.csv      
│  │  │  │  ├─ Results_2015_segunda_liga.csv      
│  │  │  │  ├─ Results_2016_segunda_liga.csv      
│  │  │  │  ├─ Results_2017_segunda_liga.csv      
│  │  │  │  ├─ Results_2018_segunda_liga.csv      
│  │  │  │  ├─ Results_2019_segunda_liga.csv      
│  │  │  │  ├─ Results_2020_segunda_liga.csv      
│  │  │  │  └─ Results_2021_segunda_liga.csv      
│  │  │  ├─ serie_a                               
│  │  │  │  ├─ Results_1990_serie_a.csv           
│  │  │  │  ├─ Results_1991_serie_a.csv           
│  │  │  │  ├─ Results_1992_serie_a.csv           
│  │  │  │  ├─ Results_1993_serie_a.csv           
│  │  │  │  ├─ Results_1994_serie_a.csv           
│  │  │  │  ├─ Results_1995_serie_a.csv           
│  │  │  │  ├─ Results_1996_serie_a.csv           
│  │  │  │  ├─ Results_1997_serie_a.csv           
│  │  │  │  ├─ Results_1998_serie_a.csv           
│  │  │  │  ├─ Results_1999_serie_a.csv           
│  │  │  │  ├─ Results_2000_serie_a.csv           
│  │  │  │  ├─ Results_2001_serie_a.csv           
│  │  │  │  ├─ Results_2002_serie_a.csv           
│  │  │  │  ├─ Results_2003_serie_a.csv           
│  │  │  │  ├─ Results_2004_serie_a.csv           
│  │  │  │  ├─ Results_2005_serie_a.csv           
│  │  │  │  ├─ Results_2006_serie_a.csv           
│  │  │  │  ├─ Results_2007_serie_a.csv           
│  │  │  │  ├─ Results_2008_serie_a.csv           
│  │  │  │  ├─ Results_2009_serie_a.csv           
│  │  │  │  ├─ Results_2010_serie_a.csv           
│  │  │  │  ├─ Results_2011_serie_a.csv           
│  │  │  │  ├─ Results_2012_serie_a.csv           
│  │  │  │  ├─ Results_2013_serie_a.csv           
│  │  │  │  ├─ Results_2014_serie_a.csv           
│  │  │  │  ├─ Results_2015_serie_a.csv           
│  │  │  │  ├─ Results_2016_serie_a.csv           
│  │  │  │  ├─ Results_2017_serie_a.csv           
│  │  │  │  ├─ Results_2018_serie_a.csv           
│  │  │  │  ├─ Results_2019_serie_a.csv           
│  │  │  │  ├─ Results_2020_serie_a.csv           
│  │  │  │  └─ Results_2021_serie_a.csv           
│  │  │  └─ serie_b                               
│  │  │     ├─ Results_1990_serie_b.csv           
│  │  │     ├─ Results_1991_serie_b.csv           
│  │  │     ├─ Results_1992_serie_b.csv           
│  │  │     ├─ Results_1993_serie_b.csv           
│  │  │     ├─ Results_1994_serie_b.csv           
│  │  │     ├─ Results_1995_serie_b.csv           
│  │  │     ├─ Results_1996_serie_b.csv           
│  │  │     ├─ Results_1997_serie_b.csv           
│  │  │     ├─ Results_1998_serie_b.csv           
│  │  │     ├─ Results_1999_serie_b.csv           
│  │  │     ├─ Results_2000_serie_b.csv           
│  │  │     ├─ Results_2001_serie_b.csv           
│  │  │     ├─ Results_2002_serie_b.csv           
│  │  │     ├─ Results_2003_serie_b.csv           
│  │  │     ├─ Results_2004_serie_b.csv           
│  │  │     ├─ Results_2005_serie_b.csv           
│  │  │     ├─ Results_2006_serie_b.csv           
│  │  │     ├─ Results_2007_serie_b.csv           
│  │  │     ├─ Results_2008_serie_b.csv           
│  │  │     ├─ Results_2009_serie_b.csv           
│  │  │     ├─ Results_2010_serie_b.csv           
│  │  │     ├─ Results_2011_serie_b.csv           
│  │  │     ├─ Results_2012_serie_b.csv           
│  │  │     ├─ Results_2013_serie_b.csv           
│  │  │     ├─ Results_2014_serie_b.csv           
│  │  │     ├─ Results_2015_serie_b.csv           
│  │  │     ├─ Results_2016_serie_b.csv           
│  │  │     ├─ Results_2017_serie_b.csv           
│  │  │     ├─ Results_2018_serie_b.csv           
│  │  │     ├─ Results_2019_serie_b.csv           
│  │  │     ├─ Results_2020_serie_b.csv           
│  │  │     └─ Results_2021_serie_b.csv           
│  │  ├─ Match_Info.csv                           
│  │  └─ Team_Info.csv                            
│  └─ __MACOSX                                    
│     └─ Football_Data                            
│        └─ Results                               
│           └─ 2_liga                             
├─ Modified_Football_Data                         
│  └─ all_14_leagues_processed.csv                
├─ footballPredictionModel.ipynb                  
├─ LICENSE                                        
└─ README.md  
```

## LICENSE

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

The MIT License
