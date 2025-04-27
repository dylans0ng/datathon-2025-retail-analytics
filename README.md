# Modecraft Ecommerce Data Analysis Project
### 📝 Project Overview
For the 6th DubsTech Datathon, we analyzed data from Modecraft, an ecommerce store offering various household items. The company sought insights from both operational and marketing perspectives to guide strategic decisions.

### 📙 Data Description
The dataset contained over 500,000 order records with the following columns:

- InvoiceNo (Unique Invoice ID)
- StockCode (Unique Product ID)
- Description (Product Name)
- Quantity (Total units purchased)
- InvoiceDate (Date and time of the invoice)
- UnitPrice (Price per unit in pounds)
- CustomerID (Unique Customer ID)
- Country (Country of origin for the order)
  
### 🗑️ Data Cleaning Process
Our data preparation involved several key steps:

1. __Initial Assessment:__

- Examined data dimensions and structure
- Identified null values across columns
- Analyzed basic statistics to understand data distribution
- Handling Negative Values
- Identified and removed negative quantities (likely returns or inventory adjustments)
- Documented the percentage of data removed
  
2. __Handling Missing Values:__

- Replaced null CustomerIDs with "Unknown Customer"
- Replaced missing product descriptions with "Unknown Product"

3. __Feature Engineering:__

- Renamed "Description" column to "Product Name" for clarity
- Added a "Season" column based on the month from InvoiceDate
- Created a "Month" column to enable time-based analysis

4. __Final Verification:__

- Confirmed all null values were properly addressed
- Saved the cleaned dataset for further analysis

### 📁 Files in this Repo
#### retail-data-cleaning.ipynb
This file contains all the Python code used to clean the data. At the very end of this Python notebook, we exported a cleaned version of the data in the format of a CSV file.

#### seasonal-performance-dashboard.pbix
This file cannot be viewed directly from GitHub, but it can be downloaded it viewed on the Power BI Desktop app. It contains our "Seasonal Business Performance" dashboard.

### 📊 Canva
All other links can be found in our Canva [presentation](https://www.canva.com/design/DAGlwVlCVwo/qXdaVok-uXooKnCkfuT6hQ/edit?utm_content=DAGlwVlCVwo&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)!
