# SMS Spam Detection System Using NLP

This is a Machine Learning application designed to classify emails as **Spam** or **Ham** (Not Spam). The project uses natural language processing (NLP) techniques and machine learning algorithms to accurately identify spam emails.

## Features
- Classifies emails into **Spam** or **Ham**.
- Pre-trained machine learning model for efficient and quick predictions.
- Supports user inputs for real-time email classification.
- Simple and easy-to-understand interface.

## Project Structure
├── spamDetector.py # Main Python file for email classification ├── Spam Detector.ipynb # Jupyter Notebook for exploratory data analysis (EDA) and model training ├── requirements.txt # List of dependencies for the project ├── spam/ # Dataset folder containing training data │ └── spam.csv # Email data (spam/ham) for training and testing ├── spam123.pkl # Trained machine learning model ├── vec123.pkl # Saved TF-IDF vectorizer for text transformation ├── README.md # Project documentation └── .venv/ # Virtual environment


## How to Run the Project
Follow the steps below to set up and run the project:

### Prerequisites
- Python 3.8 or higher
- pip (Python package manager)
  
1. Clone the Repository
   
2. Install Dependencies
Install the required Python packages using the requirements.txt file:
bash
Copy
Edit
pip install -r requirements.txt
3. Run the Application
Run the main Python file to classify emails:

bash
Copy
Edit
python spamDetector.py
4. Input an Email for Classification
When prompted, enter an email string to classify it as Spam or Ham.

Data Preprocessing:

Text cleaning (removal of special characters, numbers, and stopwords).
Tokenization and stemming/lemmatization for efficient text analysis.
Feature Extraction:

Uses the TF-IDF (Term Frequency-Inverse Document Frequency) vectorizer to transform email text into numerical data.
Model Training:

The application uses a machine learning model (e.g., Logistic Regression, Naive Bayes, or similar) trained on a labeled dataset of spam and ham emails.
Prediction:

The input email is transformed using the pre-trained TF-IDF vectorizer and passed to the trained model for classification.
Technologies Used
Python: Programming language.
Pandas: For data manipulation.
NumPy: For numerical computations.
Scikit-learn: For machine learning and NLP techniques.
Jupyter Notebook: For exploratory data analysis and model training.
Dataset
The dataset used for training the model is located in the spam folder. It contains labeled emails categorized as spam or ham. You can replace or expand this dataset with additional data for better accuracy.

Future Improvements
Add a web-based interface using Flask or Django for user-friendly interaction.
Improve the model accuracy with advanced algorithms like Random Forest or XGBoost.
Incorporate additional datasets for robust training.
Add functionality to classify bulk emails.
Contributing
Contributions are welcome! Feel free to open an issue or submit a pull request if you have suggestions or improvements.

License
This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgments
The creators of the dataset used for training.
The open-source community for providing excellent tools and resources.
Happy coding! 🚀



![Screenshot 2025-02-07 004419](https://github.com/user-attachments/assets/01a864bc-23c5-4c97-b3dd-d310868ae982)
![Screenshot 2025-02-07 004349](https://github.com/user-attachments/assets/e8aae6a5-3a0e-4114-80a3-ad2d5ab020a1)
![Screenshot 2025-02-07 004309](https://github.com/user-attachments/assets/6d9bc7b3-570d-4d2f-b1c7-ba1030eceb85)

# DAKSH MALHOTRA
IG:@idakshmalhotra
