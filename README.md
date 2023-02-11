![Header](https://media.npr.org/assets/img/2022/06/21/gettyimages-1241423375-cb7850626ce4a3e4982b6555fc110f18767c67db.jpg)
Hello there <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="25px"> 
This project is a datacamp practice project that I have done while studying the data scientist with R track :)

## 📖 Table of Contents:
* [Scenario](https://github.com/AishaAhmedToulba/visual-history-of-nobel-prize-winners-#-scenario-)
* [Objectives](https://github.com/AishaAhmedToulba/visual-history-of-nobel-prize-winners-#-objectives-)
* [Tools & Process](https://github.com/AishaAhmedToulba/visual-history-of-nobel-prize-winners-#-tools-)
* [Outcomes](https://github.com/AishaAhmedToulba/visual-history-of-nobel-prize-winners-#-outcomes-) 

## 👀 Scenario
<img src="https://planning-org-uploaded-media.s3.amazonaws.com/thumbnail/scenario-planning-2.png" width="120px">
The Nobel Prize is perhaps the worlds most well known scientific award. Except for the honor, prestige and substantial prize money the recipient also gets a gold medal showing Alfred Nobel (1833 - 1896) who established the prize. Every year it's given to scientists and scholars in the categories chemistry, literature, physics, physiology or medicine, economics, and peace. The first Nobel Prize was handed out in 1901, and at that time the Prize was very Eurocentric and male-focused, but nowadays it's not biased in any way whatsoever. Surely. Right?

Well, we're going to find out! The Nobel Foundation has made a dataset available of all prize winners from the start of the prize, in 1901, to 2016.

## 🎯 Objectives  

**1.Analyzing the winners in the dataset, from 1901 to 2016 we want to find out which sex and which country is the most commonly represented.**

**2.Analyzing when did the USA start to dominate the nobel prize charts.**

**3.Finding out if there is some imbalance between how many male and female prize winners , and analyze how significant is this imbalance And is it better or worse within specific prize categories like physics, medicine, literature, etc.?.**

**4.Finding out if there are repeated laureates , those lucky who have gotten it more than once.**

**5.Analyzing how old are the laureates when they got the prize.**

**6.Analyzing age trends within different prize categories.**


 ## ⚙️ Process:
  1. **Setting up our working environment**: Github repository & Jupyter Notebook 
  2. **Data  Understanding**:
   - Understanding the dataset we have :
   <div align="center">

| Variable              | Description                                                                                   |
|:----------------------|:----------------------------------------------------------------------------------------------|
| Year              |  The year in which the laureate got the prize  |
| Category                | The category in which the Nobel Prize is accorded                 |
| Prize                   | The name of the prize awarded.                                    |
| motivation	     |  Motivation of the nobel prize.  |
| prize_share    | The prize share the laureate got |
| Category                | The category in which the Nobel Prize is accorded                 |
| laureate_id                  | The id of the laureate.                                    |
| laureate_type	     |  is it individual or oranizational ?  |
| full_name   | The name of the laureate. |  
| birth_date   | The birth date of the laureate. |
| birth_city               | The city in which the laureate is born.                |
| birth_country	                  | The birth country of the laureate.                                    |
| laureate_type	     |  is it individual or oranizational ?  |
| sex   | The gender of the laureate.|  
| organization_name   |  |
| organization_city	               |                 |
| organization_country	                  |                                    |
| death_date	     |   |
| death_city	   | |  
| age		   | |  
</div>

  3. **Data Exploration**: 
  - Analyzing the different variables , and create new variables to answer the objectives of our analysis. 
  - Creating different interactive visualizations to support our analysis. 
  
    ## 📌 Outcomes:
    - **The are 911 nobel laureates as of between 1901 and 2016.**
 <div align="center">

| Sex             | Count                                                                                  |
|:----------------------|:----------------------------------------------------------------------------------------------|
| Female              |  49 |
| Male               | 836               |
| NA               | 26               |
</div>

**91.76% of the  laureates of the nobel prize are male while 5.37%  are female.**

- **USA Dominance.**
<img align="center" src="https://github.com/AishaAhmedToulba/visual-history-of-nobel-prize-winners/blob/main/blob/main/images/descarga%20(10).png" width="700px">

**As we can see from the plot above , the USA became the dominating winner of the Nobel Prize first in the 1930s and has kept the leading position ever since.**

**Maybe it shouldn't come as a shock that there is some imbalance between how many male and female prize winners there are, but how significant is this imbalance?.**

<img align="center" src="https://github.com/AishaAhmedToulba/visual-history-of-nobel-prize-winners/blob/main/blob/main/images/descarga%20(11).png" width="700px">

**From the plot above , we can see that the imbalance is pretty large with physics, economics, and chemistry having the largest imbalance. Medicine has a somewhat positive trend, and since the 1990s the literature prize is also now more balanced. The big outlier is the peace prize during the 2010s, but keep in mind that this just covers the years 2010 to 2016.**

Given this imbalance, who was the first woman to receive a Nobel Prize? And in what category?
**The first woman to receive a nobel prize is Marie Curie, née Sklodowska born on 1867-11-07	in Marsaw , the prize category is Physics.**
 
**In the table below , we can see the lucky ones who got the nobel prize more than once.**
The list of repeat winners contains some illustrious names! We again meet Marie Curie, who got the prize in physics for discovering radiation and in chemistry for isolating radium and polonium. John Bardeen got it twice in physics for transistors and superconductivity, Frederick Sanger got it twice in chemistry, and Linus Carl Pauling got it first in chemistry and later in peace for his work in promoting nuclear disarmament. We also learn that organizations also get the prize as both the Red Cross and the UNHCR have gotten it twice.

 <div align="center">

| full_name            | n                                                                                 |
|:----------------------|:----------------------------------------------------------------------------------------------|
| Comité international de la Croix Rouge (International Committee of the Red Cross)	              |  3 |
| Frederick Sanger               | 2               |
| John Bardeen	               | 2               |
| Linus Carl Pauling		              |  2|
| Marie Curie, née Sklodowska              | 2              |
| Office of the United Nations High Commissioner for Refugees (UNHCR)               |2               |
</div>

- How old are you when you get the prize?
<img align="center" src="https://github.com/AishaAhmedToulba/visual-history-of-nobel-prize-winners/blob/main/blob/main/images/descarga%20(13).png" width="700px">

The plot above shows us a lot! We see that people use to be around 55 when they received the price, but nowadays the average is closer to 65. But there is a large spread in the laureates' ages, and while most are 50+, some are very young.

We also see that the density of points is much high nowadays than in the early 1900s -- nowadays many more of the prizes are shared, and so there are many more winners. We also see that there was a disruption in awarded prizes around the Second World War (1939 - 1945).

**looking at age trends within different prize categories.**

<img align="center" src="https://github.com/AishaAhmedToulba/visual-history-of-nobel-prize-winners/blob/main/blob/main/images/descarga%20(12).png" width="700px">

We see that both winners of the chemistry, medicine, and physics prize have gotten older over time. The trend is strongest for physics: the average age used to be below 50, and now it's almost 70. Literature and economics are more stable, and we also see that economics is a newer category. But peace shows an opposite trend where winners are getting younger!
