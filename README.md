# PhonePe Pulse Data Visualization 2018-2022

This project is a data visualization tool for PhonePe's pulse data from 2018 to 2022. It allows users to explore and analyze various metrics related to PhonePe's business performance.

**HOME** 
![image](https://github.com/Tirumal024/Phonepe/assets/131777752/3773ecbc-b2e3-4e47-b985-8f8f86e52d0c)

**TOP CHARTS**

TRANSACTION
![image](https://github.com/Tirumal024/Phonepe/assets/131777752/9a7f4cd7-a212-45f5-a0ff-f17b165a8cd3)

USERS
![image](https://github.com/Tirumal024/Phonepe/assets/131777752/4eebeb0f-7a2e-488e-b98c-686dcf2c64ba)

**VISUVALIZATION**
TRANSACTION
![image](https://github.com/Tirumal024/Phonepe/assets/131777752/4adb90aa-d7b7-4f2a-8a16-7343d084df5b)

Top Payment Type
![image](https://github.com/Tirumal024/Phonepe/assets/131777752/e31d996b-9314-49a1-b1c0-23f23beb9c61)

State To Explore
![image](https://github.com/Tirumal024/Phonepe/assets/131777752/ddc251fd-5c55-40f2-a167-3669bd9ba2f5)

USERS
![image](https://github.com/Tirumal024/Phonepe/assets/131777752/a34e76a5-2505-4f87-bf8e-b73e7a4d50e2)

Users State
![image](https://github.com/Tirumal024/Phonepe/assets/131777752/c52eda69-1a3d-44e0-a14b-4be3e6940e0b)

# Installation and Cloning

Clone the repository to your local machine using git clone https://github.com/PhonePe/pulse.git Install the required Python packages.

**Data extraction:**

Clone the Github using scripting to fetch the data from the Phonepe pulse Github repository and store it in a suitable format such as JSON. Use the below syntax to clone the phonepe github repository into your local drive. from git.repo.base import Repo Repo.clone_from("GitHub Clone URL","Path to get the cloded files")
Refer my PhonePe_cloning and extraction.ipynb file

# Dashboard creation:

To create colourful and insightful dashboard I've used Plotly libraries in Python to create an interactive and visually appealing dashboard. Plotly's built-in Pie, Bar, Geo map functions are used to display the data on a charts and map and Streamlit is used to create a user-friendly interface with multiple dropdown options for users to select different facts and figures to display.

# Data retrieval:

Finally if needed Using the "mysql-connector-python" library to connect to the MySQL database and fetch the data into a Pandas dataframe.

# EXPLORE

Run python Phonepe_Pulse.py to start the application(streamlit run Phonepe_Pulse.py). Access the application in your web browser by navigating to http://localhost:8501 Select the desired date range and metrics to visualize. Explore the data using the interactive charts provided by Plotly Express.
