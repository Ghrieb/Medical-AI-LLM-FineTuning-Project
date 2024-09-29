# Medical-AI-LLM-FineTuning-Project
This project showcases the fine-tuning of a large language model (Meta Llama 2) to become an expert in the medical domain, specifically focusing on genomic characterization and viral genomics. It was developed as part of the "Introducing Generative AI with AWS" course offered by Udacity and AWS.

The aim of this project is to demonstrate the power of Generative AI and Machine Learning to solve real-world challenges in biomedical research and healthcare, highlighting how AI models can be fine-tuned to generate contextually accurate and domain-specific text, making it a valuable asset in fields such as medical diagnostics, personalized medicine, and healthcare innovation.

# Project Summary
As a dual major student in Developmental Biology and Computer Science, this project uniquely bridges my knowledge in both fields. The goal was to transform a pre-trained LLM into a domain-specific medical model through fine-tuning, aligning the project with the medical field's need for AI-powered solutions in areas such as genomics, viral research, and personalized medicine.

The project was developed using AWS SageMaker, and with a strict $25 budget allocation, the model was successfully deployed and fine-tuned, emphasizing resource efficiency and scalability.

# Course Information: "Introducing Generative AI with AWS"
This course, offered by Udacity in partnership with AWS, is designed to provide hands-on experience in Generative AI using AWS SageMaker and state-of-the-art models like Meta Llama 2. The course covers the following areas:

- AI and ML foundations: Introduction to Generative AI and how large language models (LLMs) work.
- Model Deployment: How to deploy and use pre-trained models using AWS SageMaker.
- Fine-Tuning Large Models: Training models on domain-specific datasets.
- Text Generation: Using AI to generate high-quality, domain-specific text content.

# Project Objectives
## 1. Deploy Meta Llama 2 on AWS SageMaker:
- Use Meta Llama 2 7B as the base model, which was pre-trained for text generation tasks.
- Evaluate the pre-trained model to assess its general ability to understand medical content.

## 2. Fine-Tune the Model for Medical Domain:
- Fine-tune the pre-trained model using a medical dataset focused on genomic characterization and viral genomics.
- Adapt the model to produce more contextually accurate and domain-specific responses related to genomic research and biomedical sciences.

## 3. Evaluate the Fine-Tuned Model:
- Test the fine-tuned model to compare its performance with the pre-trained version, specifically on medical text generation tasks.
- Analyze improvements in the model’s ability to understand and generate accurate medical terminology and research insights.

# Dataset
The dataset used for fine-tuning the model focuses on medical genomic data, including information on viral genomics, genomic characterization, and related medical research. The dataset is stored in the repository under the data/medicaldataset.txt file.

## The key dataset areas include:
- Genomic Research: Text related to genetic and molecular research in healthcare.
- Viral Genomics: Data specifically focusing on viruses such as HIV, HBV, and HCV.
- Personalized Medicine: Research data on how genomics contributes to personalized healthcare solutions.

# Key Files:
## Model_Evaluation.ipynb:
Deploy and evaluate the pre-trained Meta Llama 2 model using AWS SageMaker.
Analyze the model's initial performance in generating medical domain text before fine-tuning.

## Model_FineTuning.ipynb:
Fine-tune the pre-trained model using a medical dataset.
Improve the model's domain-specific text generation capabilities, especially for viral genomics and personalized medicine.

## Project_Documentation_Report.pdf:
A detailed report documenting the entire process, from deploying the model to evaluating its performance after fine-tuning.

## results/:
Pre-tuned Output: The output generated by the model before fine-tuning.
Fine-tuned Output: The improved output after fine-tuning the model on the medical dataset.

# Technical Details
1. Pre-trained Model: The base model used was Meta Llama 2 7B, which was fine-tuned using the medical dataset to specialize in genomic research.
2. Fine-Tuning: This was performed using AWS SageMaker with a GPU-based instance (ml.g5.2xlarge) to accelerate the training process.
3. Text Generation: The model takes medical text as input and generates domain-specific outputs related to viral genomics and genomic characterization.
4. Comparison: After fine-tuning, the model displayed significantly more relevant and accurate outputs in the medical domain, outperforming the pre-trained version in understanding and generating medical research content.

# Next Steps
Future work could involve expanding the model's capabilities to other medical fields and further optimizing the fine-tuning process for personalized medicine and disease prediction tasks.

# Results and Key Findings
- Pre-trained Model: The model was capable of generating generic biomedical text, but it lacked specificity in the medical domain.
- Fine-tuned Model: After fine-tuning, the model became proficient in genomic research and viral genomics, demonstrating improved contextual relevance and accuracy in medical text generation.

# Impact on Healthcare:
The fine-tuned model can potentially be used in various healthcare applications, such as:
- Medical diagnostics: Generating insights for healthcare professionals.
- Research Support: Assisting researchers in generating and reviewing domain-specific literature.
- Genomic Analysis: Supporting the development of personalized treatments by analyzing genomic data.

# About Me
I am a dual major in Developmental Biology and Computer Science, passionate about bridging the gap between AI/ML and biomedical sciences. My career goals involve using cutting-edge technologies like Generative AI to solve real-world challenges in healthcare innovation and contribute to the United Nations Sustainable Development Goals (UN SDGs).

# Acknowledgments
A huge thank you to Udacity and AWS for offering this course and providing the resources to build and deploy this project.
Special thanks to my instructor, Mathew Purcell, for his invaluable guidance and support throughout this learning journey.

# License
This project is licensed under the MIT License – see the LICENSE.md file for more details.
