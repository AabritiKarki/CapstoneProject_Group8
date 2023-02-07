# Capstone Project - Group8

## Business Problem
Depression and PTSD (post-traumatic stress disorder) are both mental health conditions that
can have a significant impact on a person's daily life. Depression is characterized by persistent
feelings of sadness, hopelessness, and a lack of interest or pleasure in activities while PTSD is a
condition that can develop after a person experiences or witnesses a traumatic event, such as a
natural disaster, combat, sexual or physical assault, or a serious accident. Both depression and
PTSD can be treated with therapy, medication, and other forms of support. It's important for
anyone experiencing symptoms of either condition to seek professional help.
Mental health intervention strategies can vary based on the specific needs and concerns of the
client as identified through their input data. Through the form we are trying to identify
Cognitive Behavioral Therapy (CBT) that can help clients identify their problem, seek the help
that they need in order to cope with their situation and get better.

## Analytical Methods
**Development of Psychometric Questionnaire**: As the questionnaire will be used as the method
of data collection, the questions will be carefully designed to capture data points required for
identifying depression or PTSD and the type of therapy required.

**Data Gathering and Labeling**: The data will be gathered through Google Forms. The data
received will be processed and clustered to identify groups with similar responses and thus
persona. Each group identified from the cluster analysis will be closely analyzed by
mental-health experts to create appropriate labels from personal and type of therapy required.
The labeled-data will be then fed into the ML Model for classification.

**Development of ML Model**: The textual data will be separated from quantitative and
categorical data gathered. A NLP model such as BERT will be used to extract features from
textual inputs and convert them into a feature vector. This will be combined with other data and
fed into ML models for classification.

**Integration of ML Model with Google Form**: The ML Model will be deployed and accessible
through Webhook [3]. Once any new submissions are made in google form, the webhook will
receive data submitted and classify survey response. An automated email will be sent to
mental-health practitioners and concerned authorities notifying about the survey response and
predicted mental health condition and appropriate therapy for the user.
