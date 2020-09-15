Acute mountain sickness (AMS) is a common concern for mountain climbers who ascend higher than 2000m. 
Characterized by headache, lightheadedness, fatigue, nausea and insomnia, 
AMS is caused by a failure to adapt to the acute hypobaric hypoxia experienced at high altitudes. 

The drug acetazolamide has been used effectively to treat AMS; however, 
it has a variety of unpleasant side effects that can reduce compliance to taking it. 
Previous studies suggested that the herbal supplement ginkgo biloba might also be used to 
prevent AMS without side effects. 

To test this hypothesis, healthy Western volunteers who 
were hiking Mt. Everest were randomized to one of four treatments: placebo, ginkgo biloba only, 
acetazolamide only or ginkgo biloba and acetazolamide1. Treatment group as well as incidence of 
AMS and incidence of headache for the 487 individuals who completed the study are presented in Treckers.csv.

Source: J.H. Gertsch, B. Basnyat, E.W. Johnson, J. Onopa, and P.S. Holck (2005). 
"Randomized, Double-Blind Placebo Controlled Comparison of Ginkgo Biloba and Acetazolamide 
for Prevention of Acute Mountain Sickness Among Himalayan Trekkers: the Prevention of High Altitude Illness Trial", 
BMJ, 328: pp 797-

Data Dictionary:

Variable Name			Description				Details

ID				Participant ID				Numeric
Trt				Drug treatment				Numeric [1,2,3,4] 1 = placebo, 2 = acetazolamide only, 3 = ginkgo biloba only, 4 = acetazolamide and ginkgo biloba 
ACET				Indicator for taking acetazolamide	Numeric [0,1] 0 = no, 1 = yes
Ginkgo				Indicator for taking acetazolamide	Numeric [0,1] 0 = no, 1 = yes
AMS_out				Indicator for acute mountain sickness	Numeric [0,1] 0 = no, 1 = yes
Headache_out			Indicator for headache			Numeric [0,1] 0 = no, 1 = yes


 
