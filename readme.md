# Titanic and Lusitania Data Mining 
----


This week we will be looking at who survives famous ship sinking (Titanic and Lusitania). 

## Titanic Data Description

#### Dataset contains information on 1309 Passengers
##### details below:

| Columns   | Description                                         |
|:---------:|:----------------------------------------------------|
| PClass    | Ticket Class: 1 = 1st, 2 = 2nd, 3 = 3rd  |
| Survived  | 1 = Survived 0 = Deceased                           |
| Sex       | Female or Male                                      |                                           
| Age       | Age in years              |
| Sibsp     | # of siblings / spouses aboard the Titanic        |
| Parch     | # of parents / children aboard the Titanic        |
| Ticket    | Ticket Number   |                                           
| Fare      | Passenger Fare    |                                           
| Cabin     | Cabin Number        |                      
| Embarked  | Port of Embarkation	C = Cherbourg, Q = Queenstown, S = Southampton |
| Boat      | Lifeboat ID     |                                           
| Body      | Body ID number  |                                          
| Home.dest | Destination     |   

###### Variable Notes

pclass: A proxy for socio-economic status (SES)
* 1st = Upper
* 2nd = Middle
* 3rd = Lower

age: Age is fractional if less than 1. If the age is estimated, is it in the form of xx.5

* sibsp: The dataset defines family relations in this way...
* Sibling = brother, sister, stepbrother, stepsister
* Spouse = husband, wife (mistresses and fiancés were ignored)
* 
* parch: The dataset defines family relations in this way...
* Parent = mother, father
* Child = daughter, son, stepdaughter, stepson
* Some children travelled only with a nanny, therefore parch=0 for them.

## Lusitania Data Description

#### Dataset contains information on 1961 Passengers and Crews
##### details below:

| Columns   | Description                                         |
|:---------:|:----------------------------------------------------|
| Family Name    | Last Name |
| Title     | Title                          
| Personal Name | First Name 
| Fate | Lost, Saved, Saved (died from trauma), Not on Board 
| Age | age in years children under 2 in months and infants 
| Department Class | Passanger: Saloon(1st class), Second, Third Crew: Deck, Victualling, Engineering, Band, Stowaway
| Passenger Crew | Passenger, Crew, Stowaway 
| Citizenship | Country 
| Position | position of Crew Member
| Status | Marital Status 
| City | City of Origin 
| County | County of Origin 
| State | State of Origin 
| Country | Country of Origin 
| Lifeboat | Lifeboat 
| Rescue Vessel | Rescue Vessel 
| Body No. | Body Identification Number 
| Ticket No. | Ticket Identification Number 
| Cabin No. | Cabin Number A, B, C, D, E
| Traveling | Traveling Companions 
| Value | Corrosponds to Fate 1 = Survived 0 = Deceased
| Adult Minor | Age < 18 Minor => 18 Adult 
| Sex | Female or Male     

###### Variable Notes

Number of decks	10 – Navigation, Boat (A), Promenade (B), Shelter (C), Saloon (D), Main (E), Lower (F), Orlop, Lower Orlop, Tank Top

Passenger accommodation	Designed:
* 552 saloon (first class, 260 rooms)
* 460 second cabin (second class, 145 rooms)
* 1,186 third class (302 rooms)
* 2,298 total 
* In 1915:
* 563 saloon (first class)
* 464 second cabin (second class)
* 1,138 third class
* 2,165 total

Crew accommodation	Designed:
* 69 deck
* 389 victualling
* 369 engineering
* 827 total (850 in 1915)











