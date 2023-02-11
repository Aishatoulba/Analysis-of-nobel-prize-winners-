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

**7.Finding out the oldest and the youngest winner of a Nobel prize as of 2016.**

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

