 
Files	    Description
label.csv   Contains the patient identifier, patient_hash, along with the labels
            hf (heart failure), ca (arrhythmia) & death
	    holdout: strata=0, testing: strata=1, training: strata=2
	    last_t is the end of follow-up

1234567890123456.csv 
            files with this naming convention contain the ECG leads
	    for patient with identifier patient_hash='1234567890123456'		     

pseudo.csv  Contains the patient identifier, patient_hash, along with the labels
            hf1-hf10 (heart failure), ca1-ca10 (arrhythmia) & death1-death10
	    For example, XX1 is the label for year 1, XX10 for year 10, etc.
	    holdout: strata=0, testing: strata=1, training: strata=2
