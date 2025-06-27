<h1 align="center">🧵 Pattern Sense: Classifying Fabric Using Deep Learning</h1>

---

**Pattern Sense** is a deep learning-based web application that classifies fabric patterns from uploaded images. It uses a Convolutional Neural Network (CNN) trained on a dataset of fabric images to predict one of 10 predefined pattern categories. This project demonstrates how artificial intelligence can assist industries like textiles, fashion, and e-commerce in automating visual recognition tasks.

---

# 📌 Project Objective

To build a system that can identify fabric patterns using image classification. The goal is to automate manual textile sorting and support businesses in organizing and tagging fabric types efficiently.

---

# 🛠️ Tech Stack

- **Frontend**: HTML, CSS  
- **Backend**: Python using Flask  
- **Deep Learning**: TensorFlow and Keras (CNN)  
- **Image Handling**: Keras Preprocessing, NumPy  
- **Interface**: Runs locally on a Flask server

---

# 🧠 Key Features

- Simple web interface to upload fabric images  
- Automated prediction using a trained CNN model  
- Supports 10 distinct fabric pattern categories  
- Displays predicted result along with the uploaded image  
- Lightweight and works offline on localhost

---

# 🧵 Fabric Pattern Categories

The model can recognize the following fabric patterns:

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

# 🔄 Workflow

1. User uploads a fabric image through the web interface  
2. Image is resized and normalized to match model input  
3. The trained CNN model processes the image  
4. The model returns the most probable pattern class  
5. The result is shown on the screen with the uploaded image preview

---

# 👥 Roles and Contributions

- **Deepika Rama Lakshmi** – Team Lead  
  - Designed the CNN model  
  - Integrated the model with Flask backend  
  - Coordinated project tasks and handled deployment

- **Nissy**  
  - Collected and labeled dataset  
  - Performed preprocessing of images

- **Ramdevu Vijay**  
  - Developed the frontend interface using HTML & CSS  
  - Conducted testing and resolved integration issues

- **Jagadeswari**  
  - Handled documentation, reports, and presentations

---

# 📁 Project Structure

- **app.py**: Flask backend logic  
- **model_cnn.h5**: Trained CNN model file  
- **templates/**: Contains `home.html` and `result.html` for UI  
- **static/**: Includes styles and uploaded images  
- **README.md**: Documentation file

---

# 🚀 How to Run the Project

1. Install Python and required packages: Flask, TensorFlow, NumPy  
2. Clone or download the project folder  
3. Ensure the trained model file (`model_cnn.h5`) is present  
4. Run the Flask server  
5. Open `http://localhost:5000` in your browser  
6. Upload a fabric image to see the predicted pattern

---

# 📈 Results

- Successfully classifies fabric images into correct categories  
- Provides near-instant feedback via a web interface  
- Useful for offline, educational, and experimental use cases

---

# 🔮 Future Scope

- Expand dataset to include more complex and blended patterns  
- Deploy the app online for public use  
- Enhance the model using transfer learning (e.g., ResNet, MobileNet)  
- Add drag-and-drop upload and live camera input support

---

# 📘 Conclusion

Pattern Sense shows how deep learning models can be applied in practical scenarios such as textile pattern recognition. This project merges AI and web technologies to offer a simple, intelligent solution for real-world pattern classification problems.

---

# 👩‍💻 Developed By

**Team Members:**  
- Deepika Rama Lakshmi (Team Lead)  
- Nissy  
- Ramdevu Vijay  
- Jagadeswari
