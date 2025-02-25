This is a basic template for deploying machine learning models as a web application using **Flask**.

## Getting Started
(Run the bash code in your VSCode's terminal)

### 1. Clone the Repository
Clone the repository to your local machine (make sure u have git installed):

### 2. Install Dependencies
Install all necessary libraries using the provided requirements.txt:

```bash
pip install -r requirements.txt
```

### 3. Prepare Your Machine Learning Model
Replace the Jupyter notebook and CSV file with your own.
Train your model, dump and save it using pickle:
```python

import pickle
pickle.dump(rf, open('model.pkl', 'wb'))  # Replace 'rf' with your trained model
```

### 4. Update app.py
In app.py, update the code to load your pickled model:


### 5. Customize index.html
Edit index.html to modify the webpage interface, or change the frontend as you like.


### 6. Run the Application
Run the Flask application:

```bash
python app.py
```
or click on run button (▶) in ```app.py``` file.

The app will be available at http://127.0.0.1:5000/.

Do ```ctrl```+click on the url in the terminal to load the webpage.
