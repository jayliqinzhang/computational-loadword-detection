This code repository implement the method of computational loanword detection using the sound distance. The result of the paper shows that the sound distances generated by the sound-class-alignment (SCA) based method (List, 2012) is the most superior among the evaluated sound distance measurement method. The data used in this experiment is from Mennecier et al.(2016).  


# Sound distance

Running the sca_distance.py output the sound distance generated from the SCA-based method. The data is in the format as shown in the excel file "mydata.xls". The output of sca_distance.py is the pickle file containing the a list of tuples representing: 

(concept, distance, ipa_in_turkic, ipa_in_indoiranian)

for instance, 

('one', 0.84, 'bɪr', 'jak')

It will be used for further loanword detection in the next step. 

On the other hand, you can use your own data in the format as in the excel file to generate a tuple list. 


