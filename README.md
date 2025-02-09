# 🎭 Celebrity Look-Alike

📌 **Project Overview**

The Celebrity Look-Alike project is a deep learning-based facial recognition system that identifies which celebrity you resemble. The project utilizes the **VGG-Face** model to extract facial features and compare them using cosine similarity.

🚀 **Features**

- **Face Recognition:** Identifies a celebrity match based on uploaded images.
- **Deep Learning Model:** Uses **VGG-Face** for facial feature extraction.
- **Cosine Similarity:** Determines the closest match from a dataset of celebrity images.
- **Triplet Loss Function:** Ensures better feature learning for facial recognition.

📂 **Project Structure**

```plaintext
Celebrity-Look-Alike/
│── Celebrity_Look_Alike.ipynb  # Jupyter Notebook with the main code
│── requirements.txt            # Project dependencies
│── README.md                   # Project documentation
│── dataset.pkl                 # Pickled celebrity embeddings
```

## 🔧 Installation Instructions

To get started with the project, follow these steps:

### 1. Clone the Repository

Clone the repository to your local machine:
```
git clone https://github.com/NivethaRajamani/Celebrity-Look-alike.git
cd Celebrity-Look-alike
```

### 2. Install Required Dependencies

This project requires several Python libraries. Install them using the following command:
```
pip install -r requirements.txt
```

Alternatively, you can install the libraries manually:
```
pip install tensorflow keras numpy scipy opencv-python pillow matplotlib notebook
```

### 3. Check Python Version

Make sure you're using Python 3.6 or above:
```
python --version
```

### 📝 Running the Look-Alike Notebook

#### 1. Open the Jupyter Notebook
Once the repository is set up and dependencies are installed, launch Jupyter Notebook:
```
jupyter notebook
```
Navigate to `Celebrity_Look_Alike.ipynb` in the Jupyter Notebook interface and open it.

#### 2. Run the Notebook Cells
Execute all the cells in the notebook. The model will process an input image and identify the closest celebrity match.

#### 3. Understanding the Process
- The model extracts facial embeddings from the user’s image using **VGG-Face**.
- It compares these embeddings with precomputed embeddings from the celebrity database.
- The closest match is determined using **cosine similarity**.
![image](https://github.com/user-attachments/assets/8d27f6a0-b83e-4ce8-b6ce-185c70a8cdb6)
![image](https://github.com/user-attachments/assets/94512378-ef03-428c-94a4-f8b79299f78d)


### 📌 Technologies Used

- **Python:** The primary programming language for the project.
- **Keras & TensorFlow:** For deep learning and face embedding extraction.
- **OpenCV:** For image processing and resizing.
- **VGG-Face:** A pre-trained deep learning model for facial recognition.
- **Matplotlib & PIL:** For image visualization and handling.
- **Jupyter Notebook:** For running and testing the model interactively.

### 📂 Dataset
The celebrity images used for comparison are stored in the `celebrity_database/` folder. The facial embeddings are precomputed and stored in `dataset.pkl` to speed up similarity computation.

### 🤝 Contributing
Contributions are welcome! If you'd like to improve the project, feel free to fork the repository, create a new branch, and submit a pull request.

📜 **License**
This project is licensed under the MIT License.

📞 **Contact**
For any questions or suggestions, feel free to reach out:

- **Author:** Nivetha Rajamani
- **Email:** nivetharajamani.jobs@gmail.com
- **GitHub:** [NivethaRajamani](https://github.com/NivethaRajamani)

