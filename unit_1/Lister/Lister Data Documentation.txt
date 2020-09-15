Mortality data for individuals who had upper or lower limb amputations before and after 
the discovery of antiseptics are presented in the Lister.csv dataset. 

Source: Lister (1870). Effects of the Antiseptic System of Treatment 
Upon the Salubrity of a Surgical Hospital. The Lancet, 1:4-6,40-42. 

Data Dictionary:

Variable Name		Description				Details

ID			Participant ID				Numeric [ID]
Antiseptic		Antiseptic use				Numeric [0,1], 1 = pre-discovery, 1 = post-discovery
Limb			Limb amputated				Numeric [1,2], 1 = lower limb, 2 = upper limb
Outcome			Participant outcome			Numeric [0,1] 0 = did not survive, 1 = survived
