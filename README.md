# Instructions
1. [Go to Snowflake Marketplace and get Cybersyn's Financial Data Package](https://app.snowflake.com/marketplace/listing/GZTSZAS2KF7/cybersyn-inc-financial-data-package)
    - Please leave the name of the database default as 'FINANCIAL_DATA_PACKAGE'
2. On the right side menu bar go to 'Streamlit' section
3. On the top right click on '+ Streamlit App'
4. Change 'App name' to something descriptive
5. Select Warehouse
6. Choose database where app will live (we suggest create a new one)
7. Choose schema inside the above database (we suggest create a new one)
8. Click 'Create'
9. You should see a page with default code
10. Copy code from streamlit_app.py in this repository and replace the default code on the page
11. Click 'Run' on the top right
12. Wait for app to load
    - If there is an error then make sure the correct database and schema is specified on line 22 and 23. Default is FINANCIAL_DATA_PACKAGE but if you mounted package from marketplace with different database name then please change and re-run
