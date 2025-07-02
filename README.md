**# 🦠 Malaria Cell Classification using ResNet50**



This project uses deep learning to classify malaria-infected and uninfected cell images using the \*\*ResNet50\*\* architecture with \*\*TensorFlow\*\*. The dataset is sourced from TensorFlow Datasets and the model is trained with data augmentation and transfer learning techniques.



---



**## 📁 Project Structure**



\- `malaria\_classifier.ipynb` – Jupyter notebook with complete code  

\- `README.md` – This file  

\- `my\_model.h5` – Trained model (hosted externally on Google Drive)



---



\## 📚 Dataset



This project uses the \*\*Malaria Cell Images Dataset\*\* provided by \*\*TensorFlow Datasets (TFDS)\*\*.



\- 📂 Source:([**TFDS - Malaria Dataset**](https://www.tensorflow.org/datasets/catalog/malaria))

&nbsp;

&nbsp; 

\- The dataset contains 2 classes:



&nbsp; - `Parasitized` – infected with malaria

&nbsp; - `Uninfected` – healthy cells



\- Automatically loaded using:



&nbsp; ```python

&nbsp; tfds.load('malaria', split='train', with\_info=True)





🧠 Key Features



✅ Uses ResNet50 (transfer learning)



✅ Data augmentation for better generalization



✅ Splits dataset into training and validation



✅ Shows class distribution and sample images



✅ Displays confusion matrix and predictions





🚀 How to Run This Project



**Step 1: Install Required Packages**



pip install tensorflow tensorflow-datasets matplotlib scikit-learn



**Step 2: Run the Notebook**



* Open malaria\_classifier.ipynb in Jupyter Notebook or Google Colab



* Run all cells to load data, train the model, and evaluate



**💡 Motivation**



Malaria is a major health issue in many tropical regions. Automating infected cell detection through deep learning can assist healthcare professionals in faster and more accurate diagnoses.



🙋‍♂️ Author



https://github.com/Haritha191003





