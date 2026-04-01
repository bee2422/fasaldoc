 Fasaldoc – AI Crop Disease Detection

Fasaldoc is an AI-powered crop disease detection prototype that helps farmers identify plant diseases instantly using image analysis. By selecting the crop type and region, and uploading an image, users receive disease predictions along with causes and solutions.

Features

1. Select crop type (e.g., Wheat)

2.  Select state (e.g., Maharashtra)

3.  Upload crop image

4.  AI-based disease detection

Displays:

1. Disease name

2. Confidence score

3. Causes

4. Recommended solutions

Demo

(https://youtu.be/pKQxhrhw2JE?si=cruNU46b7CkcCYA_)
 
How It Works

1. User selects crop and location


2. Uploads image of affected crop


3. Image is processed using a trained ML model


4. Model predicts disease based on dataset


5. Results are displayed with actionable insights

Tech Stack

Frontend: Flutter / Figma (Prototype UI)

Backend: Python (Flask) (optional for prototype)

Machine Learning: TensorFlow / Keras / OpenCV

Dataset: Plant disease dataset (custom or public)

Project Structure

fasaldoc/
│── frontend/          # UI (Flutter or Figma export)
│── backend/           # Flask API (if implemented)
│── model/             # Trained ML model files
│── dataset/           # Sample images (optional)
│── README.md

Installation & Setup

1️. Clone the repository

git clone https://github.com/bee2422/fasaldoc.git
cd fasaldoc

2️. Backend Setup (if using Flask)

pip install -r requirements.txt
python app.py

3️. Run Frontend

Flutter:


flutter run


Sample Input

Crop: Wheat

State: Maharashtra

Image: Diseased wheat leaf


Sample Output

Disease: Wheat Leaf Rust

Confidence: 92%

Cause: Fungal infection

Solution: Apply fungicide, avoid excess moisture


Future Scope

1.  Weather-based disease prediction

2.  Regional language support

3.  Real-time farmer advisory

4.  Mobile app deployment

5.  More crop and disease coverage






