🧠 Brain Tumor Detection Using Deep Learning (ANN, DNN, CNN)
This project focuses on detecting brain tumors from MRI scan images using deep learning models. It compares the performance of ANN, DNN, and CNN, and deploys the most accurate model with a user-friendly interface.

🚀 Project Overview
Developed and evaluated ANN, DNN, and CNN models for binary image classification (Tumor / No Tumor).
Compared model performance using metrics like accuracy, precision, recall, and F1-score.
Selected CNN as the best-performing model.
Deployed the CNN model using Gradio to create an interactive web UI for real-time predictions.

🧪 Technologies Used
Python
TensorFlow / Keras
Scikit-learn
Gradio
Matplotlib, Seaborn
NumPy, Pandas

🧠 Model Comparison

Model	Accuracy	Precision	Recall	F1-Score
ANN   	87%	      85%	     88%	   86%
DNN	    91%	      90%	     91%	   90%
CNN	    96%	      95%	     97%	   96%

🌐 Deployment
The final CNN model is integrated into a Gradio interface that allows users to upload MRI images and receive instant predictions.

🔧 How to Run Locally:
bash
git clone https://github.com/Arati9703/Brain_Tumor_bot.git
cd Brain_Tumor_bot
pip install -r requirements.txt
python app/app.py

📷 UI Preview
(You can include a screenshot or short demo GIF of the Gradio interface here)

📌 Key Highlights
Hands-on image classification using deep learning
Real-time prediction with an interactive interface
Model performance comparison and tuning
Practical deployment using Gradio
