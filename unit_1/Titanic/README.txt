In the early hours of April 15, 1912, the unsinkable ship RMS Titanic sank 
when it struck an iceberg, killing more than half of the passengers and crew aboard. 
The Titanic.csv dataset contains demographic information for 889 of those passengers 
as well as a record of whether or not that each passenger survived. 

Source: Stanford University. 2016. A Titanic Probability. Titanic Training Dataset. 
https://web.stanford.edu/class/archive/cs/cs109/cs109.1166/problem12.html


Data Dictionary:

Variable Name			Description							Details

Survived			Indicates if the passenger survived the sinking or not		Numeric [0,1] 0 = no, 1 = yes
Pclass				Passenger class							Numeric [1,2,3] 1 = 1st class, 2 = 2nd class, 3 = 3rd class
Name				Passenger name							Character [string]
Sex				Passenger sex							Character [female, male]
Age				Passenger age							Numeric [in years]
Siblings/Spouse Aboard		Indicates the number of siblings and/or a spouse also aboard	Numeric [count] 
Parents/Children Aboard		Indicates the number of parents and/or children also aboard	Numeric [count]
Fare				Ticket fare paid						Numeric [£] 
