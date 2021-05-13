1. ADS_Pre_Processing (Google Spreadsheet)

Tasks associated with : Group wise list of diseases and symptoms (explicit, implicit, total)

	This file contains that information about the diseases associated with each group; for
	each of those diseases, their explicit symptoms and count, their implicit symptoms and
	count, their total set of symptoms and count, and number of samples respectively

2. ADS_Pre_Processing (.ipynb)

	This file contains code written to carry out all the pre processing tasks

3. disease_wise_symptom_count (.p - pickle)

Tasks associated with : Disease wise set of total symptoms, wrt entire dataset

	This file contains a dict object where the key is disease name and value is a dict 
	containing the associated symptoms and count. This is calculated with respect to 
	the entire dataset

4. master_disease_wise_explicit_symptom_count (.p - pickle)

Tasks associated with : Disease wise set of explicit symptoms, wrt master dataset

	This file contains a dict object where the key is disease name and value is a dict 
	containing the associated explicit symptoms and count. This is calculated with respect 
	to the master dataset

5. master_disease_wise_implicit_symptom_count (.p - pickle)

Tasks associated with : Disease wise set of implicit symptoms, wrt master dataset

	This file contains a dict object where the key is disease name and value is a dict 
	containing the associated implicit symptoms and count. This is calculated with respect 
	to the master dataset

6. symptom_disease_matrix (.xlsx)

Tasks associated with : Symptom - Disease Associations, wrt entire dataset

	This file is an excel document containing the symptom - disease association matrix. 
	It is very big and sparse. So handle with care.

7. symptom_wise_disease_count (.p - pickle)

Tasks associated with : Symptom wise disease count, wrt entire dataset

	This file contains a dict where the key is symptom name and the value is a dict 
	containing the set of associated diseases and their counts respectively

 
	
