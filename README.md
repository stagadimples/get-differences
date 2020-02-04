## Tracking Information

### Background
This application is designed to summarise differences between 2 files of similar data structures. The current implementation checks for recency by the label of the file. Files must be labeled in date order (yyyy-mm-dd) in order to ensure accurate results.

### Steps for Generating Report:
* Clone repository, and download contents to a location on your PC.
* Replace contents of **data** folder with the 2 files--current and previous--which are to be compared.
* Files stored in the **data** folder must labeled according to the date they refer to, using the format **yyyy-mm-dd** (for example, 2020-12-29).
* This report is generated from the file named **tracking-worksheet.xlsm**.
* To generate the report, simply click on the **Get Differences** button, and select **data** folder. The sheets **New** and **Cancelled** are automatically populated accordingly.

### Additional Notes:
* You may need to **enable macros** when prompted to do so.
* It's not important to clear the sheets before running a new report, as this is done at application runtime.


### Caution!
This application has been designed to accept only 2 files (at the moment) in the specified working directory. Supplying more than 2 files may result in unexpected behaviour.
