REVOLUTIONARY DIABETIC RETINOPATHY DETECTION USING ADVANCED COMPUTATIONAL MODELS

Diabetic retinopathy (DR) is a leading cause of blindness among adults of working age, necessitating early detection and treatment to prevent severe vision loss. Manual grading for DR diagnosis is costly and time-intensive, underscoring the need for automated retinal image analysis to improve efficiency and reduce healthcare expenses.
This project aims to develop a deep learning method using a pre-trained Convolutional Neural Network (CNN), ResNet-152, to classify DR into five severity levels: No DR, Mild, Moderate, Severe, and Proliferative DR. Automation aims to streamline grading procedures and enhance diagnostic accuracy.
Additionally, a Graphical User Interface (GUI) system is being created for efficient patient data management, addressing model bias in imbalanced datasets. This initiative seeks to innovate DR detection and assessment, aiming to improve healthcare delivery and patient outcomes in ophthalmology.

Dataset : APOTS Kaggle Blindness dataset

Tech Stack Required and Implementation

Numpy, Pandas, Matplotlib: Essential libraries for data manipulation and visualization.
Torch package: Required for building and using neural networks in PyTorch.
Tkinter: Used for creating the GUI.
MySQL: Database management tool.

Setup Instructions:

Install Dependencies:  
Install the required packages using  pip install numpy pandas matplotlib torch tkinter 

MySQL Setup:  
Install and set up MySQL  And Configure server settings by setting the username and password.

Download Project Files: 
Essential files required are blindness.py, model.py ,classifier.pt

Database Configuration: 
Create a new database and table in MySQL. and Update the database configuration in the blindness.py file.

Model File Configuration: 
Ensure the classifier.pt file is in the same directory as the project files And Update the path in the model.py file.

Running the Application: 
Execute the blindness.py file from the terminal.
This will start the GUI. Upload an image to get predictions.
