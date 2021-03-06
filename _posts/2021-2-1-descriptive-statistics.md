---
layout: post
title: Descriptive Lab
---
**Dataset Chosen:** Country Vaccinations  

**Analysis:**  
For this lab I chose to analize how many vaccines countries have adminstered by 1/24/21 and the trends in how many vaccines have been delivered per day.  

Frequency of Number of Vaccines Administered Between 12/13/20 and 1/24/21 by 60 Countries:

This variable proved to be highly variable with a range of 161492900. The mean number of total vacciens delivered was 1211611 but this data was heavily skewed left as can be seen in the violin plot below.
The IQR of this data is 676753.75 making any values above 1402936.3 potential outliers. Overall, when looked at in the form of a table this data clearly shows that some countries are using significantly
more vaccines than others.  

|Index|Countries        |Total_Vaccines |
|-----|-----------------|---------------|
|0|              Argentina     |   292023.0|
|1|                Austria     |   170144.0|
|2|                Bahrain     |   144130.0|
|3|                Belgium     |   174307.0|
|4|                 Brazil     |   604722.0|
|5|               Bulgaria     |    26119.0|
|6|                 Canada     |   801238.0|
|7|                  Chile     |    63047.0|
|8|                  China     | 15000000.0|
|9|             Costa Rica     |    29389.0|
|10|               Croatia     |   64951.0|
|11|                Cyprus     |    17379.0|
|12|               Czechia     |  192267.0|
|13|               Denmark     |   203166.0|
|14|               Ecuador     |      108.0|
|15|               England     |  5970175.0|
|16|               Estonia     |    25964.0|
|17|               Finland     |    91260.0|
|18|                France     |  1026871.0|
|19|               Germany     |  1632777.0|
|20|             Gibraltar     |     9807.0|
|21|                Greece     |   157388.0|
|22|               Hungary       | 153392.0|
|23|               Iceland       |   8249.0|
|24|                 India       |1582201.0|
|25|             Indonesia        |149242.0|
|26|               Ireland        |121900.0|
|27|           Isle of Man        |  3648.0|
|28|                Israel       |3615145.0|
|29|                 Italy       |1370449.0|
|30|                Kuwait       |   2500.0|
|31|                Latvia       |  19022.0|
|32|            Lithuania        | 67036.0|
|33|           Luxembourg        |  6897.0|
|34|                 Malta       |  18930.0|
|35|                Mexico       | 618768.0|
|36|          Netherlands        |135000.0|
|37|      Northern Ireland       | 178331.0|
|38|               Norway        | 73844.0|
|39|                  Oman        | 30675.0|
|40|                Panama        |  5594.0|
|41|                Poland        |701164.0|
|42|              Portugal        |249891.0|
|43|               Romania        |446285.0|
|44|                Russia       |1000000.0|
|45|          Saudi Arabia        |295530.0|
|46|              Scotland        |409421.0|
|47|                Serbia        |163355.0|
|48|            Seychelles        | 18353.0|
|49|             Singapore        | 60000.0|
|50|              Slovakia        | 92167.0|
|51|              Slovenia        | 55680.0|
|52|                 Spain       |1165825.0|
|53|                Sweden      |  146775.0|
|54|           Switzerland      |  169783.0|
|55|                Turkey      | 1244653.0|
|56|  United Arab Emirates      | 2487789.0|
|57|        United Kingdom      | 6822981.0|
|58|         United States      |20537990.0|
|59|                 Wales      |  265054.0|  

![Violin Plot](https://drive.google.com/uc?id=1YRGB50BbJmDxYPBlQXMgOZ7FX6WwdpVh)  
  
  
  
Number of Vaccines Delivered Per Day (Worldwide) Between 12/13/20 and 1/24/21:

The range of the number of vaccines given in a day was 58285873. This data can also be seen to bias left on the violin plot and has a mean of 13248640. The IQR for this data is 19967772 meaning any value above 51007928 could be considered outliers. The line graph relating date to number of vaccines delivered on a date also has a trend line with the equation 906133.0279402252x + -5780154.703023799, which has a positive slope indicating general growth in the number of vaccines given per day.  

|Index |Dates          |Vaccines Delivered Worldwide|
|------|----------------|----------------------------|
|0|2020-12-13     |30662.0|
|1|2020-12-14     |297.0|
|2|2020-12-15     |1529663.0|
|3|2020-12-16     |3683.0|
|4|2020-12-17     |7201.0|
|5|2020-12-18     |10615.0|
|6|2020-12-19     |11951.0|
|7|2020-12-20     |1912217.0|
|8|2020-12-21     |664316.0|
|9|2020-12-22     |148455.0|
|10|2020-12-23     |1211112.0|
|11|2020-12-24     |298146.0|
|12|2020-12-25     |338381.0|
|13|2020-12-26     |2322106.0|
|14|2020-12-27     |2525913.0|
|15|2020-12-28     |2837836.0|
|16|2020-12-29     |965883.0|
|17|2020-12-30     |4068680.0|
|18|2020-12-31     |6029205.0|
|19|2021-01-01     |1555249.0|
|20|2021-01-02     |6804925.0|
|21|2021-01-03     |4828703.0|
|22|2021-01-04     |7119315.0|
|23|2021-01-05     |8670638.0|
|24|2021-01-06     |8652788.0|
|25|2021-01-07     |10920151.0|
|26|2021-01-08     |12171059.0|
|27|2021-01-09     |14430888.0|
|28|2021-01-10     |11223371.0|
|29|2021-01-11     |21496307.0|
|30|2021-01-12     |22776428.0|
|31|2021-01-13     |36488082.0|
|32|2021-01-14     |28064683.0|
|33|2021-01-15     |30887136.0|
|34|2021-01-16     |18829140.0|
|35|2021-01-17     |20616232.0|
|36|2021-01-18     |22374196.0|
|37|2021-01-19     |40234975.0|
|38|2021-01-20     |58286173.0|
|39|2021-01-21     |46341670.0|
|40|2021-01-22     |50359379.0|
|41|2021-01-23     |50210375.0|
|42|2021-01-24     |11433287.0|  

![Violin Plot](https://drive.google.com/uc?id=1iCazskIitz8FamLL9SgQm32x9O991YDp)  
  
![Line Plot](https://drive.google.com/uc?id=1Dwo-dAaaPyLpycAPVDPMQbtDP1748-fE)

**Code:**  

Code for Frequency of Number of Vaccines Administered Between 12/13/20 and 1/24/21 by 60 Countries Violin Plot:  
```
import seaborn as sns, matplotlib.pyplot as plt, pandas as pd, numpy as np

data = pd.read_csv("country_vaccinations.csv")
final_country_data = []
countries = []
out = 0

for i in range(len(data)):
    if(i < len(data) - 1):
        if data['country'][i] != data['country'][i+1]:
            final_country_data.append(out + 0 if np.isnan(float(data['total_vaccinations'][i])) else float(data['total_vaccinations'][i]))
            countries.append(data['country'][i])
            out = 0
        else:
            out += 0 if np.isnan(float(data['total_vaccinations'][i])) else float(data['total_vaccinations'][i])
    else:
        countries.append(data['country'][i])
        final_country_data.append(out + 0 if np.isnan(float(data['total_vaccinations'][i])) else float(data['total_vaccinations'][i]))
        
final_country_data = pd.Series(final_country_data)
countries = pd.Series(countries)
graph = sns.violinplot(x=final_country_data)
plt.xlabel("total vaccinations per country")
plt.title("Total Vaccinations (2020-12-13 to 2021-01-24)")
plt.show()
```  

Code for Number of Vaccines Delivered Per Day (Worldwide) Between 12/13/20 and 1/24/21 Violin Plot:  
```
import seaborn as sns, matplotlib.pyplot as plt, pandas as pd, numpy as np, Analize as a
#from datetime import datetime as d

data = pd.read_csv("country_vaccinations.csv")
dates = []
total_per_date = []
for e in data['date']:
    if e not in dates:
        dates.append(e)


dates = a.applyToList(dates, lambda  x: str(x).replace("-10-","-.3-"))
dates = a.applyToList(dates, lambda  x: str(x).replace("-11-","-.2-"))
dates = a.applyToList(dates, lambda  x: str(x).replace("-12-","-.1-"))
dates.sort()
dates = a.applyToList(dates, lambda  x: str(x).replace("-.3-","-10-"))
dates = a.applyToList(dates, lambda  x: str(x).replace("-.2-","-11-"))
dates = a.applyToList(dates, lambda  x: str(x).replace("-.1-","-12-"))

for e in dates:
    tempSeries = data[data['date'] == e]['total_vaccinations']
    temp = 0
    for e in tempSeries:
        temp += 0 if np.isnan(float(e)) else float(e)
    total_per_date.append(temp)

total_per_date = pd.Series(total_per_date)
graph = sns.violinplot(x=total_per_date)
plt.xlabel("Vaccines Delivered in a Day")
plt.title("Distribution of Vaccines Delivered in a Day")
plt.show()
```  

Code for Number of Vaccines Delivered Per Day (Worldwide) Between 12/13/20 and 1/24/21 Line Graph:  
```
import seaborn as sns, matplotlib.pyplot as plt, pandas as pd, numpy as np, Analize as a
from datetime import datetime as d

data = pd.read_csv("country_vaccinations.csv")
dates = []
dateDif = []
total_per_date = []
for e in data['date']:
    if e not in dates:
        dates.append(e)


dates = a.applyToList(dates, lambda  x: str(x).replace("-10-","-.3-"))
dates = a.applyToList(dates, lambda  x: str(x).replace("-11-","-.2-"))
dates = a.applyToList(dates, lambda  x: str(x).replace("-12-","-.1-"))
dates.sort()
dates = a.applyToList(dates, lambda  x: str(x).replace("-.3-","-10-"))
dates = a.applyToList(dates, lambda  x: str(x).replace("-.2-","-11-"))
dates = a.applyToList(dates, lambda  x: str(x).replace("-.1-","-12-"))


for e in dates:
    tempSeries = data[data['date'] == e]['total_vaccinations']
    temp = 0
    for e in tempSeries:
        temp += 0 if np.isnan(float(e)) else float(e)
    total_per_date.append(temp)


for e in dates:
    dateDif.append(abs(float((d.strptime(dates[0], "%Y-%m-%d") - d.strptime(e, "%Y-%m-%d")).days)))

total_per_date = pd.Series(total_per_date)
dates = pd.Series(dates)
dateDif = pd.Series(dateDif)
regression = a.listRegression(list(dateDif), list(total_per_date))

graph = sns.lineplot(x = dates, y = total_per_date)
plt.plot([0, 42], [regression[1], 42*regression[0] + regression[1]])
plt.xlabel("Date")
plt.ylabel("Vaccines Delivered (10^x)")
plt.title("Date vs. Vaccines Delivered")
plt.xticks(fontsize = 5)
plt.yticks(np.arange(0,80000000,2000000))
plt.show()
```  

Code for Imported Analize:  
```
import math

#Applies func to list, can pass through values
def applyToList(applyTo: list, func, through1 = None, through2 = None, through3 = None, **varThrough) -> list:
    if type(applyTo) != list:
        raise Exception("Invalid Input: List Expected")
    out = []
    if through3 != None:
        for e in applyTo:
            out.append(func(e), through1, through2, through3) if varThrough == {} else out.append(func(e), through1, through2, through3, varThrough)
        return out
    elif through1 != None:
        for e in applyTo:
            out.append(func(e), through1, through2) if varThrough == {} else out.append(func(e), through1, through2, varThrough)
        return out
    elif through1 != None:
        for e in applyTo:
            out.append(func(e), through1) if varThrough == {} else out.append(func(e), through1, varThrough)
        return out
    else:
        for e in applyTo:
            out.append(func(e)) if varThrough == {} else out.append(func(e), varThrough)
        return out

#Applies func to dict, can pass through through
def applyToDict(applyTo: dict, func, through1 = None, through2 = None, through3 = None, **varThrough) -> dict:
    if type(applyTo) != dict:
        raise Exception("Invalid Input: Dict Expected")
    out = {}
    if through3 != None:
        for e in applyTo.keys():
            out[e] = func(applyTo[e], through1, through2, through3) if varThrough == {} else func(applyTo[e], through1, through2, through3, varThrough)
        return out
    elif through2 != None:
        for e in applyTo.keys():
            out[e] = func(applyTo[e], through1, through2) if varThrough == {} else func(applyTo[e], through1, through2, varThrough)
        return out
    elif through1 != None:
        for e in applyTo.keys():
            out[e] = func(applyTo[e], through1) if varThrough == {} else func(applyTo[e], through1, varThrough)
        return out
    else:
        for e in applyTo.keys():
            out[e] = func(applyTo[e]) if varThrough == {} else func(applyTo[e], varThrough)
        return out


#averages list
def avgList(apply: list) -> float:
    add = 0
    sub = 0
    for i in apply:
        add+= 0 if i == None else float(i)
        sub += 1 if i == None else 0
    return add/(len(apply)-sub)

#finds average deviation of list
def avgListDev(apply: list) -> float:
    avg = avgList(apply)
    add = 0
    sub = 0
    for i in apply:
        add += 0 if i == None else abs(float(i)-avg)
        sub += 1 if i == None else 0
    return add / (len(apply)-sub)

#finds maximum value in list
def maxList(apply: list) -> object:
    return max(apply)

#finds maximum value in dict keys
def maxKeyDict(apply: dict) -> object:
    return max(apply)

#finds maximum value in dict elements
def maxElementDict(apply: dict) -> object:
    return max(apply.values())

#finds key of maximum value in dict elements
def maxElementKeyDict(apply: dict) -> object:
    return max(apply, key=lambda key: apply[key])

#sorts list
def listSort(apply: list, reverse=False) -> list:
    apply.sort(reverse=reverse)
    return apply

#sorts dict by value of keys
def sortKeyDict(apply: dict, reverse=False) -> dict:
    out = {}
    temp = sorted(apply, reverse=reverse)
    for e in temp:
        out[e[0]] = e[1]
    return out

#sorts dict by value of elements
def sortElementDict(apply: dict, reverse=False) -> dict:
    out = {}
    temp = sorted(apply.items(), key=lambda x: x[1], reverse=reverse)
    for e in temp:
        out[e[0]]=e[1]
    return out

#finds length of number
def lenNumber(apply:float) -> int:
    return int(len(str(apply))) - 1 if '.' in str(apply) else int(len(str(apply)))

#calculates mode of list
def listMode(apply: list) -> object:
    d = listFrequencyDict(apply)
    m = maxElementDict(d)
    out = []
    for e in d.keys():
        if d[e] == m:
            out.append(e)
    return out


#def listModeFrequency (apply: list) -> int:

#calculated range of list
def listRange(apply: list):
    apply = listSort(apply)
    return abs(apply[len(apply)-1] - apply[0])

def listFrequencyDict(apply: list) -> dict:
    out = {}
    for e in apply:
        try:
            out[e] +=1
        except KeyError:
            out[e]=1
    return out

#segments lists in a dict
def dictionarySegment(dictionary: dict, lookFor: object, lookForKey = None, *keys) -> dict:
    out = {}
    for e in dictionary.keys() if lookForKey == None else [lookForKey]:
        for i in range(len(dictionary[e])):
            if dictionary[e][i] == lookFor:
                for g in dictionary.keys() if keys == () else keys:
                    try:
                        out[g].append(dictionary[g][i])
                    except KeyError:
                        out[g] = [dictionary[g][i]]
    return out
#listSegment(base: list, lookFor: object, *apply:list) -> list:

#finds median of list
def listMedain(apply: list) -> float:
    apply = listSort(apply)
    if len(apply) % 2 != 0:
        return float(apply[int(.5*(len(apply)-1))])
    else:
        return float((apply[int((len(apply)-1)*.5)]+apply[int(len(apply)*.5)])/2)

#Calculates standered deviation of list, excludes None types
def listStndDeviation(apply: list) -> float:
    avg = avgList(apply)
    add = 0
    sub = 0
    for i in apply:
        add += 0 if i == None else (float(i) - avg)**2
        sub += 1 if i == None else 0
    return math.sqrt(add / (len(apply) - sub - 1))

#returns a list of z scores
def listZScore(apply: list) -> list:
    out = []
    avg = avgList(apply)
    dev = listStndDeviation(apply)
    for e in apply:
        out.append(abs(e-avg)/dev)
    return out

#takes in formatted contingency table and outputs formatted conditional probability table
def dictConditionalMatrix(apply: dict) -> dict:
    out = {}
    index = 0
    for i in range(len(apply["labels"])):
        if apply["labels"][i] == "totals":
            index = i
    out["labels"] = apply["labels"][0:-2]
    out["n"] = apply["totals"]
    for e in apply.keys():
        if e != "labels" and e != "totals":
            out[e] = []
    for e in apply.keys():
        if e != "labels" and e != "totals":
            for i in range(len(apply[e])):
                if i != index:
                    out[e].append(float(apply[e][i])/float(apply["totals"][i]))
    return out

def listCorrelation(xaxis: list, yaxis: list) -> float:
    if len(xaxis) != len(yaxis):
        raise Exception("Mismatched Data")
    n = len(xaxis)
    xs = listStndDeviation(xaxis)
    ys = listStndDeviation(yaxis)
    hold = 0.
    for i in range(n):
        hold += (xaxis[i] - xs) * (yaxis[i] - ys)
    hold *= (1/(n-1)) * (1/(xs*ys))
    return hold

def listRegression(xaxis: list, yaxis: list) -> list:
    m = listCorrelation(xaxis, yaxis) * (listStndDeviation(yaxis)/listStndDeviation(xaxis))
    b = avgList(yaxis) - (m * avgList(xaxis))
    return [m,b]
```
