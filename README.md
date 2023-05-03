# Dementia Classification based on Linguistic Analysis
Yunxi (Claire) Cheng, Tripti Sharma, Linting (Linsey) Wang, Sifan(Ellen) Zhu

## Project Overview
Our goal is to classify *if a patient has dementia /Alzheimers based on linguistic data from the DementiaBank dataset*. The label is a binary value indicating if the patient has dementia (1) or not (0). The predictor is the transcripts with audio data containing sentences from patients with or without dementia.

## Motivation & Novelty
Dementia is a debilitating neurological disorder that affects millions of people worldwide. Early diagnosis and intervention can significantly improve patients' quality of life, but it can be challenging to identify dementia in its early stages. Machine learning models can help to classify individuals with dementia based on language use patterns, which can serve as an early diagnostic tool.

Healthcare professionals, researchers, and caregivers who work with individuals with dementia would find such models useful. Implementing these models could improve the quality of care and treatment for individuals with dementia while also supporting research into the underlying mechanisms of the disease.

## Data Source
Dataset for this project is retrived from DementiaBank.

The dataset contains audio recordings and transcriptions of conversations between individuals with dementia and no dementia as the control. Transcriptions were transcribed using CLAN (Computerized Language Analysis) software tool which provides a user-friendly interface for transcribing audio data and allows researchers to create coded transcripts for detailed linguistic analysis. In this project, the audio data from the DementiaBank corpus was transcribed using CLAN and then preprocessed for use in the neural network. The .cha files were obtained from TalkBank and preprocessed to remove irrelevant information and convert them to a format suitable for training a machine learning model.

The basic motive behind the neural network and classification is to identify patterns in language use that are characteristic of individuals with dementia. The neural network uses the transcriptions of conversations between individuals with dementia and their caregivers to learn these patterns and classify individuals as either having dementia or not. By accurately classifying individuals with dementia, the model can serve as an early diagnostic tool, allowing for earlier intervention and improved outcomes for patients.


