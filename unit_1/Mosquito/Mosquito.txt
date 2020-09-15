The Mosquito.csv dataset contains data recorded in an experiment conducted on male soldiers 
in the Indian Army who were stationed in the Tezpur/Solmara garrison in Northeast India. 
Thirty soldiers were randomly selected to receive one of five types of mosquito repellant patch. 
Three of the treatments were a single repellant and two were combinations of two repellants. 
After giving informed consent, the study participants affixed the patches at predetermined points 
on their uniforms and research assistants (who were blinded to the type of repellant used) counted 
the number of times a mosquito landed on each individual in an hour. 

Source: A. Bhatnagar and V.K. Mehta (2007). "Efficacy of Deltamethrin and Cyfluthrin 
Impregnated Cloth Over Uniform Against Mosquito Bites," Medical Journal Armed Forces India, Vol. 63, pp. 120-122.

Data Dictionary:

Variable Name		Description				Details

ID			Participant ID				Numeric [ID]
Treatment		Mosquito repellant patch treatment	Numeric [0, 1] 0 = single repellant, 1 = combination of two repellants
Mosq_count		Mosquito count in one hour		Numeric [count]
