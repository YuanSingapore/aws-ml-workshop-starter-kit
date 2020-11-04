+++
title = "Electronic healthcare record processing and classification with Amazon Textract, Comprehend Medical and SageMaker"
description = "Build a medical document processing pipeline with Amazon Textract and Comprehend Medical and then use Amazon SageMaker to train a machine learning classification model."
date = 2019-11-18T08:23:04+11:00
weight = 35
chapter = false
difficulty = "Intermediate / Advanced"
CFTemplate = "apj_aiml_loft_workshop.yml"
CFTemplateName = "SagemakerNotebooks"
time = "2hr"
inlists = true
+++

The advent of Machine learning is undoubtfully speeding up the medical world development, such as new drug discovery and manufacturing, automating the diagnosis through computer vision, personalized treatments and improvements to organization of patients’ health records. Here is a list of ML applications in healthcare.
![](/images/module-medical-document-processing-and-classification/ML_in_healthcare.png )

The availability of large amount of clinical data is opening up lots of new opportunities for digital transformation in the healthcare industry, including patient management optimization, ML predictive diagnosis and forecasting heprogression/recovery trajectories. However, patients’ health records have long been captured and kept as hard copies. In fact, nearly 20% of the doctors still prefer to use paper medical records. Such a phenomenon have greatly affected the pace of digitalization and knowledge sharing, thus limiting the ability to realize the potential from the wealth of medical data. In addition, doctors’ notes are often captured in free texts and is usually difficult to comprehend and extract meaningful data for analysis.  To address the challenges in utilizing medical records, we have specifically developed a workshop that will guide you to: 

1) Build a medical document processing pipeline with Amazon Textract and Comprehend Medical;
2) Build, train and deploy a classification machine learning model with medical data extracted from the medical document processing pipeline

### Goals to achieve

By the end of this workshop, you are expected to pick up the following skills:
1)	To digitalize documents using Amazon Textract;
2)	To extract medical terms from doctor’s notes using Amazon Sagemaker Comprehend;
3)  To visualize, clean and organize dataset for model training;
4)	To build, train and deploy a model artifact using Amazon SageMaker notebook.



### Lab Overview

{{< video "Yuan introduction recording.mp4" >}}

>  **Speaker: Yuan Shi, Data Scientist for AWS Public Sector Asia Pacific** 


### Lab Steps
{{% children depth="2" %}}


Click [here](./scenario/) to get started by reviewing the architecture.
