# clinical_trials
In this demo, I matched 10 patients to 5 clinical trials. Patient and clinical trials first went through named entity recognition (NER) using STANZA. NER extracted problems, treatment, and tests. Secondly, I computed patient-trial similarity using clinicalBERT.

ner.ipynb <br />
purpose: NER <br />
input: patients_synthetic.csv <br />
output: trials_ner_211112.csv, patients_ner_211112.csv <br />

similarity.ipynb <br />
purpose: calculate patient-trial similarity <br />
input: trials_ner_211112.csv, patients_ner_211112.csv <br />
output: demo_211115.csv <br />
