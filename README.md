# Phonepe-Pulse-Data
Data Extraction
Utilize scripting to clone the GitHub repository and fetch the data from the Phonepe Pulse GitHub repository. The fetched data will be stored in a suitable format such as CSV or JSON for further processing.

Data Transformation
Utilize Python scripting along with libraries such as Pandas to manipulate and preprocess the fetched data. This step may include tasks such as data cleaning, handling missing values, and transforming the data into a format suitable for analysis and visualization.

Database Insertion
Connect to a MySQL database using the "mysql-connector-python" library in Python. Insert the transformed data into the MySQL database using SQL commands. This step ensures efficient storage and retrieval of the data.

Dashboard Creation
Utilize the Streamlit and Plotly libraries in Python to create an interactive and visually appealing dashboard. Utilize Plotly's built-in geo map functions to display the data on a map and Streamlit to create a user-friendly interface with multiple dropdown options for users to select different facts and figures to display.

Data Retrieval
Connect to the MySQL database using the "mysql-connector-python" library to fetch the data into a Pandas dataframe. Utilize the data in the dataframe to update the dashboard dynamically, ensuring that users have access to the latest data.

Deployment
Ensure the solution is secure, efficient, and user-friendly. Thoroughly test the solution and deploy the dashboard publicly, making it accessible to users. This step involves deploying the dashboard to a web server or platform where users can access it from their web browsers.
