                                                    Pattern Sense: Classifying Fabric Using Deep Learning

**Pattern Sense** is a deep learning-based web application that classifies fabric patterns from images. The system uses a Convolutional Neural Network (CNN) and provides an easy-to-use interface where users can upload fabric images and get instant pattern classification results.

---

## 📌 Project Objective

The goal of this project is to automate the identification of various fabric patterns such as Floral, Polka, Striped, etc., using deep learning techniques. This helps reduce manual effort in fabric sorting and enhances efficiency in textile and fashion-related industries.

---

## 🛠️ Tech Stack

- **Frontend**: HTML, CSS  
- **Backend**: Python (Flask)  
- **Deep Learning**: TensorFlow, Keras  
- **Image Processing**: NumPy, Keras Preprocessing  
- **Deployment**: Runs locally on Flask server

---

## 🧠 Key Features

- User-friendly web interface for uploading fabric images  
- Automatic classification into 10 fabric pattern categories  
- Real-time prediction display with uploaded image preview  
- Offline/local setup without any internet dependency

---

## 🧵 Fabric Pattern Categories

The model classifies images into the following 10 categories:

- Chevron  
- Dots  
- Floral  
- Geometric  
- Houndstooth  
- Paisley  
- Striped  
- Plaid  
- Polka  
- Solid

---

## 🔄 Workflow

1. User uploads a fabric image through the web interface.  
2. The image is resized and preprocessed to match model input format.  
3. The image is passed through a pre-trained CNN model.  
4. The model predicts the most likely fabric pattern.  
5. The predicted result and uploaded image are displayed on the result page.

---

## 🧑‍💻 Roles and Contributions

- **Deepika Ramalakshmi** (Team Lead):  
  Model design, Flask integration, and final demo  
- **Nissy**:  
  Dataset collection and preprocessing  
- **Ramdevu Vijay**:  
  Frontend design (HTML/CSS), testing, and debugging  
- **Jagadeswari**:  
  Documentation and presentation

---

## 🗂️ Project Structure

- `app.py`: Flask application file  
- `model_cnn.h5`: Trained CNN model weights  
- `templates/`: HTML files (`home.html`, `result.html`)  
- `static/`: CSS styles and uploaded images  
- `README.md`: Project documentation

---

## 🚀 How to Run the Project

1. Install Python dependencies (Flask, TensorFlow, NumPy)  
2. Place the `model_cnn.h5` file in the root directory  
3. Run the Flask app using `python app.py`  
4. Open your browser and navigate to `http://localhost:5000`  
5. Upload a fabric image and view the predicted pattern

---

## 📈 Results

- The model successfully classifies fabric patterns with high accuracy on the custom dataset  
- The web app is responsive and provides results within seconds of image upload  
- Useful in contexts like e-commerce platforms, textile classification, and fabric management tools

---

## 🔮 Future Scope

- Add more pattern categories and expand the dataset  
- Deploy the app online for global access  
- Improve model accuracy using advanced architectures (e.g., transfer learning)  
- Add camera-based live fabric detection

---

##  Conclusion

Pattern Sense demonstrates how deep learning, especially CNNs, can be used in the real world to automate visual classification tasks. This project showcases the integration of AI with web technologies to create a functional and interactive solution for fabric pattern recognition.

---

## 👩‍🎓 Developed By

Final Year B.Tech Students  
Ideal Institute of Technology

- Deepika Rama lakshmi (Team Lead)  
- Nissy  
- Ramdevu Vijay  
- Jagadeswari
