<center>
    
# Project: CRIME INCIDENT REPORTS 
### Jiangyun Wang <br> Northeastern University, Boston, MA, USA
</center>

--- 
<center>
    
### Abstract
**Summary:**

The project is to investigate crime incidents in Boston. Since Boston Police Department (BPD) with limited resources, the report aims to provide some recommendations to help BPD manage the distribution of available police resources effectively. In order to achive the goal, the project will analyze in three different directions: relation of time and crime incident numbers, relation of offense group and crime incident numbers, and relation of location and crime incident numbers.

**Data Sources:**

This project includes two data sources: *tmp59ldga_d.csv* and *rmsoffensecodes.xlsx*, both of which are from the Boston government website -- *Analyze Boston*[4]. The primary source of data is *tmp59ldga d.csv* issued by BPD, which reports the preliminary details of an incident to BPD officers are reacting to. This dataset contains multiple columns: incidents id, Offense type, offense group, date, duration, place and so on. Records start in June 2015 to now. Another data source, *rmsoffensecodes.xlsx*, documents the realtionship between offense code and offense description.


**Key Conclusions:**

The project finds some specific patterns, which might help BPD reasonably deploy available police resources based on the Bostonian specities of time, locations, and offense groups and improve their effectiveness of resolving cases of crime. 

</center> 

### Introduction
**Explanation:**

The project is about to analyze when and where is the high frequency of crime incidents occurred in Boston, which are the most common incidents that happens in Boston. It can help BPD deploy reasonable police resources and enhance the effectiveness of BPD in resolving cases of crime.

**Goals:**

1. Relation of time and crime incident numbers
    - Months
    - Seasons
    - Day of week
1. Relation of offense group and crime incident numbers
    - Motor Vehicle Accident Response
    - Larceny
1. Relation of location and crime incident numbers.
    - WASHINGTON ST


### Methodology
- Step-by-Step:
    1. A module *pandas* helps to import data sources. Moreover, pandas is a powerful module in Python, whose functionalities include extracting, grouping, sorting, converting, and plotting. It will be more convenient to plot by columns and list or dict.
    1. loc is frequently used in the project, because it helps to get the specific columns and filter out redundent data.
    1. Both data sources come from the Boston government website -- *Analyze Boston*
    1. There are some researches in the project and their citations are at the end of the project
- Modules are imported and show below:
