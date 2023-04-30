#Analytics on Tech-Pub

## Project Steps:

### Project Description
### Data Extraction
### Dashboard

### Project Description: Data of different technical publications related to Medical field is collected by web scrapping from the open source website of PubMed! Then those files are extracted, and capture the required data from them which will be passed as input to the powerbi dashboard to see the visuals and get insights about the countries, authors, topics where most research is being carried out.

### Project Architecture: ADF is used to automatically extract the .tar.gz files and Get .xml for saving into ADLS Gen2 blob storage.
![image](https://user-images.githubusercontent.com/123322861/235358934-8c819be9-4730-4934-971b-a6a468d7b124.png)

### Steps Performed in powerBI:
Data is downloaded from the website in the .tar.gz format.
Downloaded data is extracted into .xml files and get stored in ADLS gen2.
Processed the .xml files and collected only the required data from it.
The extracted data is made into a data frame.
The data frame with all the required data is then downloaded as csv file. 
Now the file is passed as input to the powerbi for creating visuals and get insights of data.

### Sample Picture from PowerBI Report:

![image](https://user-images.githubusercontent.com/123322861/235359091-668c1537-2646-4f67-a948-bc3919fa83eb.png)










