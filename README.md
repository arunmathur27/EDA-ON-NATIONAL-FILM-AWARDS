# <center><b>**National Film Awards : The History**<b></center>
Exploratory Data Analysis Done on NATIONAL FILM AWARDS given between 2015 - 2019
    
  
The Awards were first presented in 1954. The **Government of India** conceived the ceremony to honor films made across India, on a national scale, to encourage the furthering of Indian art and culture. Since 1973, the Indian Directorate of Film Festivals administers the ceremony along with other major film events in India annually.    

The 1st <font color="red">**National Film Awards**</font>, presented by <font color="red">**Ministry of Information and Broadcasting**</font>, India to felicitate the best of Indian Cinema censored in the year 1953.Ceremony took place at Vigyan Bhavan, New Delhi on 10 October 1954 and awards were given by then President of India, <font color="red">**Dr Rajendra Prasad**</font>.

Instituted as State Awards for Films, which over the years known as National Film Awards, in its first year, were given in three different categories to honour the films at national level. Films made in all Indian languages were considered for the award. Awards were instituted, in order to encourage the production of the films of a high aesthetic and technical standard and educational and culture value.
    
---
# **Table of Contents**
---

**1.** [**Introduction**](#Section1)<br>
**2.** [**Problem Statement**](#Section2)<br>
**3.** [**Installing & Importing Libraries**](#Section3)<br>
  - **3.1** [**Installing Libraries**](#Section31)
  - **3.2** [**Upgrading Libraries**](#Section32)
  - **3.3** [**Importing Libraries**](#Section33)

**4.** [**Data Acquisition & Description**](#Section4)<br>
  - **4.1** [**Data Description**](#Section41)
  - **4.2** [**Data Information**](#Section42) 
  
  ---
<a name = Section1></a>

# 1. Introduction

### The National Film Awards Analysis

---

National Film Awards were first awarded 10th October, 1954. <font color="red">**The Government of India**</font> wished to honour the excellence in Indian Cinema on a national scale. It was in 1973 when the Directorate of Film Festivals started administering the ceremony along with other major events in the country. 


The National Film Awards are presented and categorised in three sections- Feature Films, Non-Feature Films and Best Writing on Cinema. The jury is appointed by the Directorate of Film Festivals in India without any influence from the Government too on awards.


#### The National Film Awards Are Presented By <font color="red">**The President Of India**</font> And Happen To Be The Highest Honours In Indian Cinema.

    
    ---
<a name = Section2></a>
# 2. Problem Statement
---

**A list of rules is presented yearly in a document of regulations which is called the National Film Award Regulations.
The awards aim at encouraging the making of films of aesthetic and technical excellence. The films are also encouraged to have social relevance, which may aid in the understanding and appreciation of cultures of different regions of the country in cinematic form. The films made in the country must abide by the unity and integrity of the nation.** 


##### Through EDA on **The National Film Awards** we try to explore the following facts: 
- Q1. Top 10 award winning films that had won the highest number of award between 2015 - 2019
- Q2. How many awards given in each season between 2015 - 2019
- Q3. Top 10 awards winning directors that had won the highest number of awards between 2015 - 2019
- Q4. Top 10 awards winning producers that had won the highest number of awards between 2015 - 2019
- Q5. Top 5 awards winning directors & their season wise performance between 2015 - 2019
- Q6. What was Season wise, category wise awards distribution between 2015 - 2019
- Q7. Top 10 awards wining film's language and their % share between 2015 - 2019
- Q8. Top 10 Hindi films under feature film category that had won the highest number of award between 2015 - 2019
- Q9. Top 10 Hindi films under non-feature film category that had won the highest number of award between 2015 - 2019 
- Q10. Top 10 pair of producer & director that had won the highest number of award between 2015 - 2019


- Apart that, We will also try to explore that how much **The National Film Awards** are able to achive its **objectives** which are:
 - Encourage to <font color="red">**social awareness**</font> by promoting the social relevance subjected films.
 - To make the people of india <font color="red">**understand & appreciate the cultures**</font> of different regions of our country through films.
 - To Promote The <font color="red">**unity and integrity of the nation**</font> through films made by country's film industry.

<a name = Section3></a>
---
# 3. Installing & Importing Liberaries
---

---
<a name = Section31></a>
### **3.1 Installing Libraries**
---
    
!pip install -q datascience

!pip install -q pandas-profiling                                    
!pip install matplotlib
!pip install numpy
!pip install pandas
!pip install pandas-profiling[notebook]
!jupyter nbextension enable --py widgetsnbextension
!pip install plotly
!pip install seaborn    
    

    
    
    
- The dataset consists of information about the National Film Awards(MIB).

| Records | Features | Dataset Size |
| :--: | :--: | :--: |
| 309 | 8 | 41.0 KB | 

<br>

| # | Feature Name | Feature Description |
|:--:|:--|:--| 
|1| Sr. No.  | A numeric serial number |
|2| Year     | Year in which award was given |
|3| CATEGORY |	Name of Category in which the awards was given |
|4| TITLE    |	Name of Files to which the award was given |
|5| DIRECTOR |	Name of Director of the film |
|6| PRODUCER |	Name of Producer of the film |
|7| LANGUAGE |	Language in which the file was made |
|8| AWARDS   |	Name of award given to the film |    

    
## **Dataset Statistics exctracted from profiling reports**

### **Data Stastics**
- Number of variables **8**  and Number of observations **309**
- Missing cells	**77**
- Missing cells (%)   **3.1%**
- Duplicate rows	**0**
- Duplicate rows (%)	**0.0%**
- Total size in memory	**19.4 KiB**

### **Variable types**
- Numeric type **1**
- Categorical **7**



### **Alerts**

- Dataset has **76627 (14.1%)** duplicate rows Duplicates
- **TITLE** has a high cardinality: **309** distinct values	**High cardinality**
- **DIRECTOR** has a high cardinality: **278** distinct values	**High cardinality**
- **PRODUCER** has a high cardinality: **265** distinct values	**High cardinality**
- **LANGUAGE** has a high cardinality: **68** distinct values

- **LANGUAGE** is highly correlated with **CATEGORY**	High correlation

- **DIRECTOR** has **15 (4.9%)** missing values
- **PRODUCER** has **28 (9.1%)** missing values
- **LANGUAGE** has **28 (9.1%)** missing values
- **AWARDS** has **6 (1.9%)** missing values

    
    ---
# Summarization & Conclusion
---
​
- Through this EDA on National Film Awards, We had find the following facts :-
​
- **86 awards** was given in 66th NFA-2018, which is highest number of awards given during 2015 - 2019.
- **85 awards** was given in 63th NFA-2015, which is Second highest number of award given during 2015 - 2019.'
​
​
- **Bajirao Mastani** has won **7 awards**, which is highest number of awards won by any film in all category during 2015 - 2019.
- **Nathicharami** has won **5 awards**, which is Second highest number of awards won by any film in all category during 2015 - 2019.
​
​
- **Sanjay Leela Bhansali** has won **10 awards**, which is highest number of awards won by any **director** during 2015 - 2019.
- **Kaushik Ganguly** has win **7 awards**, which is Second highest number of award won by any **director** during 2015 - 2019.
​
​
- **Kaushik Ganguly** has won the **7 award** in **3 season out of 5** during 2015 - 2019. He has won 1 awards in 2016, 4 awards in 2017 and 3 awards in 2019. That means films directed by **Kaushik Ganguly** are more consistant in terms of winning the award than the films directed by **Sanjay Leela Bhansali**.
​
- **Sanjay Leela Bhansali** has won the **10 award** in **2 season out of 5** during 2015 - 2019. He has won 7 awards in 2015 and 3 awards in 2018. That means films directed by **Sanjay Leela Bhansali** are less consistant in terms of winning the award.
​
- **Vatri Maaran & Rama Das** both has won **5 awards** in **2 season out of 5** during 2015 - 2019.
​
​
- Films Produced by **Films Division** has won **9 awards**, which is highest number of awards won  by any **production/production** during 2015 - 2019.
- Films Produced by **Eros International And Bhansali Productions** has won **7 awards**, which is Second highest number of awards won by any **production/production** during 2015 - 2019.
- Fimls Produced by **Tejaswini Enterprises** has win **5 awards**, which is Third highest number of awards won by any **production/production** during 2015 - 2019.
​
​
- **58 awards** given under **Feature Film** category in **season 66th NFA -2018** which was highest number of awards won under this category.
- **40 awards** given under **Feature Film** category in **season 64th NFA -2016** which was lowest number of awards won under this cagegory.
​
​
- **30 awards** given under **Non-Feature Film** category in **season 65th NFA -2017** which was highest number of awards won under this category.
- **23 awards** given under **Non-Feature Film** category in **season 67th NFA -2019** which was lowest number of awards won under this category.
​
- If we compute the **range** for awards won under **Feature Film** category that comes to **18** (Range = Max-Min)  
- If we compute the **range** for awards won under **Non-Feature Film** category that comes to **7** (Range = Max-Min)  
​
​
- **28.5 % of awards** won by **Hindi language** films which is the **highest percentage of awards** won during 2015 - 2019.
- **14.9 % of awards** won by **Marathi language** Films which is the **second highest percentage of awards** won during 2015 - 2019.
- **14.5 % of awards** won by **Malayalam language** films which is the **third highest percentage of awards** won during 2015 - 2019.
​
​
- **Bajiroa Mastani** has won **7 awards**, which is the **highest number of awards** won by any **Hindi language** film during 2015 - 2019.
- **Uri:The surgical Strike** & **Marakkar- Arabikkadali Nte-Simham** both had won **4 awards**, which is the **second highest number of awards** won by any **Hindi language** film during 2015 - 2019.
- **Dum Laga Ke Haisha**, **Andhadhun**, **Nanak Shah Fakir**, **Piku**, **Padmaavat** & **Tanu Weds Manu Return** each of these films had won **3 awards**, which is the **third highest number of awards** won by any **Hindi language** film during 2015 - 2019.
​
​
- **7 awards** won under **Feature films** category by the films produced and directed by pair of **Arka Mediaworks & S.S.Rajamouli** during 2015 - 2019.
- **7 awards** won under **Feature films** category by the films produced and directed by pair of **Eros International And Bhansali Productions & Sanjay Leela Bhansal** during 2015 - 2019.
​
​
- **5 awards** won under **Non - Feature films** category by the films  produced and directed by pair of **Tejaswini Enterprises & Manjunatha S. (Mansore)** during 2015 - 2019.
- **4 awards** won under **Non - Feature films** category by the films  produced and directed by pair of **Aashirvad Cinemas & Priyadarshan** during 2015 - 2019.
​
