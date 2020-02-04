## Tracking Information

### Background
This application is designed to summarise differences between 2 files of similar data structures. The current implementation checks for recency by the label of the file. Files must be labeled in date order (yyyy-mm-dd) in order to ensure accurate results.

### Steps for Generating Report:
* Create a folder and save the 2 files--current and previous--in this folder. Name of folder is irrelevant.
* Files stored in the folder must labeled according to the date they refer to, using the format yyyy-mm-dd (for example, 2020-12-29).
* Ideally, this tracking worksheet and the folder containing the 2 files may be placed in the same folder. This is for convenience, and not a requirement.
* To generate the report, simply click on the "Generate Differences" button. The sheets "New" and "Cancelled" will be populated accordingly.

### Note:
It's not important to clear the sheets before running a new report, as this is done at application runtime.


### Caution!
This application has been designed to accept only 2 files (at the moment) in the specified working directory. Supplying more than 2 files may result in unexpected behaviour.
