# RPA-EXPERIMENT-5
## AIM:
   To create a UiPath workflow that scrapes structured data from a website and saves it into a CSV file.

## ALGORITHM:
Step 1: Create a New Process Open UiPath Studio and create a new process named WebScrapingExample.

Step 2: Open the Target Website Open your web browser and go to: [https://www.amazon.com] 

Step 3: Use Data Scraping Wizard In UiPath Studio, click on "Data Scraping" from the Design tab.
* When the wizard opens:
* Click on the first product title.
* Then click on the second product title to teach the pattern.
* When prompted, extract URL as well (optional).
* Click Next, then Finish.
* The extracted data will be stored in a DataTable variable (e.g., ExtractDataTable).
  
Step 4: Write Data to CSV After the Data Scraping activity, drag a Write CSV activity.

* Properties: Input: ExtractDataTable FilePath: "BooksData.csv" (you can choose your own name) Include Headers: ✔️ (checked)
Step 5: Run the Workflow
* Save the workflow. Click Run.

## PROGRMA:
![image](https://github.com/user-attachments/assets/73e639ae-966e-42a2-9758-add0889d7a26)


## OUTPUT:
![image](https://github.com/user-attachments/assets/55c6825d-9ad7-4988-90bf-1c974c2956dd)

## RESULT:
  The workflow successfully scrapes data from the website and saves it into a CSV file using UiPath's Data Scraping and File I/O activities.
