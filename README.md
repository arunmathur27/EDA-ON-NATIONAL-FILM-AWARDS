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
    
# A package that is required by pandas-profiling library
!pip install -q datascience

# A library to generate basic statistics about data
!pip install -q pandas-profiling                                    
!pip install matplotlib
!pip install numpy
!pip install pandas
!pip install pandas-profiling[notebook]
!jupyter nbextension enable --py widgetsnbextension
!pip install plotly
!pip install seaborn    
    
