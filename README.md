🌿 Ganesh Leaf Prediction Portal

A web-based Machine Learning Portal that predicts the type of plant species based on leaf measurements such as sepal length, sepal width, petal length, and petal width.
The system allows users to choose between K-Nearest Neighbors (KNN) and Naive Bayes models for prediction — all through a beautiful, responsive, and glass-themed web interface.

🧠 Project Overview

This project demonstrates the integration of Flask (Python) with a machine learning model for real-time predictions in an interactive UI.
It is designed as a clean, modern, and educational example of deploying ML models on the web.# LEAF-PREDICTION

✨ Features

🌱 Predicts plant species using leaf measurements.

🤖 Choice of KNN or Naive Bayes models.

📊 Displays confusion matrix, classification report, and accuracy.

💎 Elegant glassmorphism UI with smooth gradients and animations.

🧩 Fully responsive design for desktop and mobile.

⚙️ Flask backend for handling ML logic and form data.

🏗️ Project Structure

Ganesh-Leaf-Prediction-Portal/
│
├── static/
│   ├── final_interface.css          
│   └── ganesh1.jpg                  
│
├── templates/
│   └── final_interface.html         
│
├── app.py                           
├── model_knn.pkl                    
├── model_nb.pkl                     
├── requirements.txt                 
└── README.md    

⚙️ Installation & Setup

Follow the steps below to set up and run the project locally:

1️⃣ Clone the Repository
git clone https://github.com/your-username/Ganesh-Leaf-Prediction-Portal.git
cd Ganesh-Leaf-Prediction-Portal
2️⃣ Create a Virtual Environment (Recommended)
python -m venv venv
Activate it:

Windows:
venv\Scripts\activate
Mac/Linux:
source venv/bin/activate
3️⃣ Install Dependencies
pip install -r requirements.txt

4️⃣ Run the Application
python app.py

5️⃣ Access the Web App

Open your browser and visit:

http://127.0.0.1:5000/

📈 Model Details
Model	Description	Library
KNN	K-Nearest Neighbors Classifier	scikit-learn
Naive Bayes	GaussianNB Classifier	scikit-learn

Both models are trained on the Iris dataset for demonstration and prediction purposes.

🖥️ Interface Preview
Section	Description
👤 Profile Card	Displays an intro and photo of Ganesh with description.
🔮 Prediction Form	Takes user input for sepal/petal measurements and model choice.
📊 Metrics Display	Shows confusion matrix, classification report, and accuracy.
🧩 Technologies Used
Category	Tools
Frontend	HTML5, CSS3 (Glassmorphism, Responsive Design)
Backend	Python Flask
Machine Learning	Scikit-learn
Deployment Ready	Compatible with Render, Vercel, or any Flask-compatible host
🧪 Example Input
Feature	Example Value
Sepal Length	5.1
Sepal Width	3.5
Petal Length	1.4
Petal Width	0.2
Model	KNN or Naive Bayes
📜 Output Example
🌿 Predicted Species: Iris-setosa
✅ Model Accuracy: 96.7%


Includes:

Confusion Matrix

Classification Report

🤝 Contributing

Contributions are welcome!
If you'd like to enhance this project:

Fork the repository

Create a new feature branch (git checkout -b feature-name)

Commit your changes (git commit -m "Added new feature")

Push to the branch (git push origin feature-name)

Create a Pull Request

📄 License

This project is licensed under the MIT License — feel free to modify and use it with attribution.

👨‍💻 Author

Developed by: Ganesh Bachalakuri
📧 [ganeshbachalakuri10@gmail.com]

🌐 GitHub Profile [https://github.com/GaneshBachalakuri]

“Turning data into intelligence and intelligence into action.” 🌿
