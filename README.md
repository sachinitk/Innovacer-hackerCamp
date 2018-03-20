
#please see the Anylatics.pdf for the pdf and complete description and refrenences of the paper at the EOF --- describe the pdf of the paper used for meta anylasiss 

# Requirements(Python Module): {Python - Version(3.5.4 or higher)}

	os
	pandas
	dedupe

## Steps to run :

	1. Make sure you have the specified python version installed in your system.
	2. Make sure you have installed all the modules specified above.
	3. Open the text editor(sublime text) and edit the file name on which you want to run the script.
	4. Open Terminal/Shell run the command
		'''
			python InternAnylatics.py
		
		'''
	5. After when you are done with above steps you will see new file will be generated with all the name without duplication of any of the name.



#  Input:
	Sachin			24/11/34	M	Desh Raj
	Sachin D			24/11/34	M	Desh Yadav 

	ln			dob		gn	fn
	Frometa			24/11/34	F	Vladimir 
	Frometa Garo		24/11/34	F	Vladimir Antonio
	Frometa Garo		24/11/34	F	Vladimir A
	Frometa			24/11/34	F	Vladimir
	Frometa G		24/11/34	F	Vladimir
	Frometa			24/11/34	F	Vladimir A 
	Frometa G		24/11/34	F	Vladimir A 
	


# Sample Output:
	Sachin		24/11/34	M	Desh Rah

	ln		dob		gn	fn
	Frometa		24/11/34	F	Vladimir 





### IF YOU WISH TO RETRAIN THE MODEL THEN DELETE THE FILE NAMED: 
	csv_example_learned_settings
	csv_example_training.json
### THESE FILES CONTAINS THE WEIGHTS AND ALL THE TRAINING SETTING.
