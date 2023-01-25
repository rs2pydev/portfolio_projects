# Analysis and Modeling of Survival of Passengers Traveling on Titanic Ship

## 1. Source

- [Kaggle - Titanic - Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic/overview)

## 2. Dataset Description

According to the [Kaggle competition webpage](https://www.kaggle.com/competitions/titanic/overview), 
*"The sinking of the Titanic is one of the most infamous shipwrecks in history.** 
During her maiden voyage on the 15th of April, 1912, the widely considered "unsinkable" ship Titanic 
sank after colliding with an iceberg. Unfortunately, there weren’t enough lifeboats for everyone onboard, 
resulting in the death of 1502 out of 2224 passengers and crew.

While there was some element of luck involved in surviving, it seems some groups of people were more likely to 
survive than others. The pbjective of this challenge is to build a predictive model that can answer the question, 
"what sorts of people were more likely to survive?", using passenger data (i.e., **name**, **age**, **gender**, 
**socio-economic class**, etc).  

## 3. Problem Statement

Create a machine learning model that predicts which passengers survived the Titanic shipwreck.

## 4. Attribute Description

| S.N | Attribute | Description | Notes |
| :--- | :--- | :--- | :--- |
| 1. | **pclass** |	Passenger (ticket) class | Proxy for socio-economic status (SES) - `1`: 1st Class, `2`: 2nd Class, `3`: 3rd Class |
| 2. | **survived** | Passenger Survival | `0`: No, `1`: Yes |
| 3. | **name** | Passenger Name | |
| 4. | **sex** | Sex (gender) of passenger | Two genders: `female` and `male` | 	
| 5. | **age** | 	Age (in years) | If the age is estimated it is in the form of `xx.5` |  	
| 6. | **sibsp** | # of siblings / spouses aboard | *Sibling*: Brother, sister, stepbrother, stepsister; *Spouse*: Husband, wife (mistresses and fiancés were ignored) |
| 7. | **parch** |	# of parents / children aboard | *Parent:* Mother, father; *Child*: Daughter, son, stepdaughter, stepson; Some children travelled only with a nanny, therefore `parch=0` for them. |  	
| 8. | **ticket** |	Ticket number | |	
| 9. | **fare** |	Passenger fare | 	|
| 10. | **cabin** | Cabin number | | 	
| 11. | **embarked** | Port of Embarkation | `C`: Cherbourg, `Q`: Queenstown, `S`: Southampton |
