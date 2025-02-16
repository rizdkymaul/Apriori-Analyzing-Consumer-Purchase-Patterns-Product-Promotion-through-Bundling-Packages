# Apriori-Analyzing-Consumer-Purchase-Patterns-Product-Promotion-through-Bundling-Packages
 Implementation of Apriori Algorithm in Analyzing Consumer Purchase Patterns to Determine Product Promotion through Bundling Packages

Seven Stereo (PT. Tuju Nata Persada) is a company specializing in the retail of musical and audio products. The company operates sales through integrated online platforms (marketplaces) and maintains strong engagement on social media to reach its customers. Additionally, Seven Stereo has a physical store that provides customers with a direct shopping experience. With a focus on quality and innovation, Seven Stereo aims to meet the needs of music and audio enthusiasts across Indonesia.

Based on the research conducted using data mining techniques to discover association rules with the Apriori algorithm, the following conclusions can be drawn:

• Implementation of the Apriori Algorithm: The Apriori algorithm can be effectively implemented to identify consumer purchase patterns based on transaction data from PT. Tuju Nata Persada between January 1, 2023, and June 30, 2023, totaling 2733 transactions. By applying a minimum support of 0.01 (1%), a minimum confidence of 0.2 (20%), and a minimum lift value of 5, 26 association rules were generated. For example, if a consumer purchases PAC112J and CORT CM15R, there is an 83.33% chance that they will also buy NUX MG300. The remaining 25 association rules can be used as references for promotional strategies such as bundling products, as all rules are supported by strong data with lift values greater than 1. These rules can also aid in managing surplus inventory by aligning them with desired promotional strategies.

• Web Application Implementation: The deployment of the Apriori algorithm via a web application developed using python and flask framework facilitates user access to and utilization of the model for identifying consumer purchase patterns.

I apologize, but due to company confidentiality regarding the website implementation, I am unable to share that information here. If you have any questions, please feel free to contact me directly. 😊

![alt text](https://github.com/rizdkymaul/Apriori-Analyzing-Consumer-Purchase-Patterns-Product-Promotion-through-Bundling-Packages/blob/main/static/images/tampilan_utama_website.png?raw=true)

# Required Libraries for Installation
• Flask
• mlxtend
• Pandas
• NumPy
• xlrd
• xhtml2pdf
• openpyxl

# Important Notes:
 1. Data processing can only be performed on datasets that contain date and product columns.
 2. If the resulting DataFrame from the data processing is empty, a warning will appear in the top left corner in red.
 3. If the uploaded dataset has the same name as an existing file in storage, it will be overwritten. All uploaded files are stored in the "dataset" folder.
 4. The input period on the web interface must correspond to the date and time present in the dataset.
 
# Instructions to Run the Server:
  1. Ensure that Python is installed.
  2. Then, open the terminal and enter the following commands in order:

```
pip install -r requirements.txt -v
python -m venv myenv
myenv\Scripts\activate
flask --app server run
```
