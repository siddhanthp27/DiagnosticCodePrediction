# A Neural Machine Translation based Approach for Predicting Medical Procedures using Diagnostic Sequences

Automating diagnosis coding is a predictive healthcare application that involves building predictive models for large-scale patient data. Here, I have coded an approach for automatically predicting suitable diagnostic procedures given patients’ medical records. I viewed the problem as one of Neural Machine Translation, where we translate the sequence from the diagnoses space to the procedure space.

Description of the Files:

- **Bleu.ipynb**: Contains the evaluation script that evaluates the BLEU Score for the translations
- **Dict_Pkl_Generator.ipynb**: Data Preprocessing file. Stores the dict of sequences with patient_id and hospital_visit_id
- **Disease_Feature_Generator.ipynb**: Contains a simple model to generate the sequences
- **Vanilla LSTM - End to End.ipynb**: Contains the main model for generation of procedure sequences
