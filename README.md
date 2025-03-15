# 🐴🤖 Human vs Horse Image Classifier  

A Deep Learning model that classifies images as either **Human** or **Horse** using Convolutional Neural Networks (CNNs).  

## 🚀 Features  
✅ Trained on a dataset of human and horse images  
✅ Uses a CNN model for accurate classification  
✅ Supports image testing for predictions  
✅ Can be fine-tuned for better performance  

## 📂 Project Structure  
```
human-horse-classifier/
│── dataset/            # Folder for images (if applicable)
│── models/             # Trained model files (saved as .h5, .pt, etc.)
│── src/                # Python scripts for training, testing, and inference
│── notebook/           # Jupyter Notebook (if used)
│── requirements.txt    # List of dependencies
│── README.md           # Project details
│── .gitignore          # Ignore unnecessary files
```

## 📊 Dataset  
The model is trained using a dataset containing images of **humans and horses**. If using a public dataset, specify the source.  
Example: [Stanford Horses Dataset](http://vision.stanford.edu/Datasets/)

## ⚙️ Installation  
1️⃣ Clone this repository:  
```bash
git clone https://github.com/your-username/human-horse-classifier.git
cd human-horse-classifier
```
2️⃣ Install dependencies:  
```bash
pip install -r requirements.txt
```
3️⃣ Run the model for testing:  
```bash
python src/test_model.py --image sample.jpg
```

## 🎯 Training the Model  
To train the model from scratch, run:  
```bash
python src/train.py
```

## 🖼️ Example Output  
| Input Image | Prediction |
|-------------|-----------|
| ![Human Image](example-human.jpg) | **Human** |
| ![Horse Image](example-horse.jpg) | **Horse** |

## 🔥 Future Improvements  
- Add **data augmentation** for better generalization  
- Optimize model performance with **hyperparameter tuning**  
- Deploy as a **web app or API**  

## 📌 Contributing  
Feel free to fork and improve the project!  

## 🏷 License  
This project is open-source and available under the **MIT License**. 
