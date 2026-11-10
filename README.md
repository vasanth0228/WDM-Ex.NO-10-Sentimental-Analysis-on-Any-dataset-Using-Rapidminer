# WDM-Ex.NO-10-Sentimental-Analysis-on-Any-dataset-Using-Rapidminer
## NAME: Vasanth Kumar V
## DATE:
**AIM:**<br>
To create a project for Sentimental Analysis on Any Dataset a Using Rapidminer<br>
**Description:**<br>
**Procedure:**<br>
**1.Import Excel data**<br>
a. Drag the "Read Excel" operator from the IO folder onto the process canvas.

b. Double-click on the operator to open its configuration panel.

c. Specify the path to the Excel file you want to analyze.

d. Configure options such as sheet selection, header inclusion, etc.

e. Click on the "Run" button to execute the operator and import the Excel data.<br>

**2.Perform sentiment analysis with Generate Attributes operator**<br>
a. Drag the "Generate Attributes" operator from the Operators panel onto the canvas.

b. Connect the output of the "Extract Sentiment" operator to the input of the "Generate Attributes" operator.

c. Double-click on the "Generate Attributes" operator to configure it.

d. Specify a name for the new sentiment attribute you want to generate (e.g., "Sentiment").

e. Choose the sentiment analysis algorithm, "VADER."

f. Click on the "Run" button to perform sentiment analysis on the Excel data and generate the sentiment attribute.

**3.Interpret and export the results**<br>
a. Analyze the sentiment analysis results from the generated visualizations.

b. If desired, drag the "Write Excel" operator onto the canvas to export the sentiment analysis results to a new Excel file.

c. Connect the output of the visualization operator(s) to the input of the "Write Excel" operator.

d. Configure the file path and other settings for the Excel export.

e. Click on the "Run" button to export the sentiment analysis results to a new Excel file.

**Design:**<br>
<img width="1916" height="1010" alt="Screenshot 2026-11-01 180143" src="https://github.com/user-attachments/assets/10b567d9-2544-4126-8cec-ddb6c3726f7f" />

**Output:**<br>
<img width="1056" height="987" alt="Screenshot 2026-11-02 104412" src="https://github.com/user-attachments/assets/e324c7f6-2610-42b6-8aac-14a8e8ffa4bc" />


**Result:**
Sentimental Analysis on Twitter Dataset Using Rapidminer is implemented.
