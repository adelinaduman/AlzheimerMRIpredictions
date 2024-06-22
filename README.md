# AlzheimerMRIpredictions
Implemented a deep learning model in Python to replicate the findings of a research paper on Alzheimer's disease prediction using brain MRI images.

# Image Classification for MRI of Patients with Alzheimer’s Disease Using 2D CNN

## Choice of the Paper

I chose this project for several reasons. Firstly, the impact of diseases on global health is immense, with approximately 29.8 million people affected worldwide in 2015. Addressing the challenges posed by diseases is crucial for improving healthcare outcomes and quality of life. Since I wanted to work on a project that is actively applied in real-world contexts, working on Alzheimer’s disease classification seemed relevant.

Additionally, I was intrigued by the application of deep learning in this project. Deep learning has shown remarkable success in various domains, and I was keen to explore its potential in the context of medical image analysis. I also found that this project would be the perfect opportunity to delve into deep learning techniques in practice.

What makes this project particularly interesting is its approach to image classification using 2D CNNs. While many existing papers exploit the use of 3D CNNs in analyzing MRI data, this project stands out by proposing a method that studies 2D CNNs. The writers transformed 3D MRIs into 2D images and used 2D CNNs for classification. Their models achieve comparable performance to 3D CNNs while offering several advantages. These include simplicity, lower operational costs, and similar efficiency, making it a practical and effective solution for medical image classification tasks.

## Task

The objective was to develop a 2D CNN model capable of classifying MRI images into four distinct categories: Non-Demented, Very Mild Demented, Mild Demented, and Moderate Demented. In a real-world context, this classification system aims to assist medical professionals in their diagnostic procedures.

## Method

My initial step involved preprocessing the dataset. This included standardizing the images to ensure uniformity in format and converting them from RGB to grayscale, given that MRI images are inherently in black and white.

Subsequently, I conducted exploratory data analysis, revealing class imbalances within the dataset. Notably, as the disease progresses, the representation of each class decreases, with the moderate demented category constituting a mere 5% of the dataset.

Using a codebase sourced from GitHub as a foundation, I constructed a 2D CNN model and proceeded to analyze the resulting confusion matrix.
