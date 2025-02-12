In this project, we:

•	Utilized Python and Pandas to load, manipulate, and analyze datasets representing network traffic data from 9 IoT devices.

•	Leveraged NumPy for numerical computations and array operations to prepare data for machine learning.

•	Applied Scikit-learn's StandardScaler to standardize data and improve model performance.

•	Employed Matplotlib to generate insightful visualizations of data distributions and patterns for each device and the combined dataset.

•	Performed Exploratory Data Analysis (EDA) to identify key characteristics and potential anomalies in the network traffic data.

•	Implemented data cleaning and preprocessing techniques to handle missing values and enhance data quality.

•	Prepared the dataset for machine learning model training and evaluation by splitting it into train, test, and threshold calculation sets.

•	Demonstrated familiarity with cybersecurity concepts and applications of machine learning in intrusion detection systems by working with the N-BaIoT dataset.

Installing Dependencies from requirements.txt
Follow these steps to install the required Python dependencies on your system.
✅ Prerequisites:
•	Ensure Python (>=3.x) and pip (>=21.x) are installed.
•	Check Python and pip versions:
sh
CopyEdit
python --version
pip --version
📌 Installation Instructions
🖥️ Windows:
1.	Open Command Prompt or PowerShell.
2.	Navigate to the project directory:
sh
CopyEdit
cd path\to\your\project
3.	Run:
sh
CopyEdit
pip install -r requirements.txt
🍏 macOS & 🐧 Linux:
1.	Open Terminal.
2.	Navigate to the project directory:
sh
CopyEdit
cd /path/to/your/project
3.	Run:
sh
CopyEdit
pip install -r requirements.txt
🔍 Additional Tips:
•	If using a virtual environment, activate it before running the installation:
sh
CopyEdit
# Windows (CMD)
venv\Scripts\activate

# Windows (PowerShell)
venv\Scripts\Activate.ps1

# macOS/Linux
source venv/bin/activate
•	If you face permission issues, try:
sh
CopyEdit
pip install --user -r requirements.txt
•	For system-wide installation, use:
sh
CopyEdit
sudo pip install -r requirements.txt
🛠️ Verifying Installation:
Run:
sh
CopyEdit
pip list
to check if all packages are installed.
