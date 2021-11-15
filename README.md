# clinical_trials
In this demo, I matched 10 patients to 5 clinical trials. Patient and clinical trials first went through named entity recognition (NER) using STANZA. NER extracted problems, treatment, and tests. Secondly, I computed patient-trial similarity using clinicalBERT.

#ner.ipynb
purpose: NER
input: patients_synthetic.csv
output: trials_ner_211112.csv, patients_ner_211112.csv

#similarity.ipynb
purpose: calculate patient-trial similarity
input: trials_ner_211112.csv, patients_ner_211112.csv
output: demo_211115.csv
