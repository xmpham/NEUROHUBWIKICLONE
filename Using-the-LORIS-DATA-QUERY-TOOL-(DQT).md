This documentation provides a brief overview on how to perform the data selection (image data and behavioural data) of the COVID-19 datasets in the UK Biobank and it’s visibility into NeuroHub. 

###  Context
[ukb-covid.loris.ca](https://ukb-covid.loris.ca/) holds a reduced set of data for the UKBiobank participants having COVID19 records. From the Data Query Tool **(DQT)** module, you will be able to query that dataset for any variable (fields) along with T1w provided in our ukbb application. 
Clicking the Export to NeuroHub button, all selected fields will be saved in a _csv_ file in your _NeuroHub_ project. If the selected fields contain images files, a special file (_CBRAIN File List_) will be created. This special file will allow users to use the copy of the file that resides on Compute Canada without avoiding the creation of a copy of all those image files.

### Prerequisite
You need an approved UKBiobank account before requesting a LORIs account (details on the application process can be found [here](https://github.com/neurohub/neurohub_documentation/wiki/UKBiobank-Access-Request). After having filled the request account form for UKBiobank data access, you should have received an email from _no-reply@ukb-covid.loris.ca_ containing a password to access a LORIS instance.

### Step by step
- go to [https://ukb-covid.loris.ca/](https://ukb-covid.loris.ca) 
- login using your email address and the password from the email. 
  - If it is the first time you login, you will be prompted to enter a new password

IMAGE

- you are directed to your dashboard

IMAGE

- use the menu _Report > Data Query Tool_ at the top to access the **DQT** module [here](https://ukb-covid.loris.ca/dataquery/)
- now, you can see the overview of the **DQT** 

IMAGE

### Query the data 
#### Define Fields
- Select Define fields
  -Instrument: To select a field, first choose an instrument then select the desired fields. The UKbiobank organized the data in a [tree](https://biobank.ndph.ox.ac.uk/showcase/browse.cgi) where nodes are categories and the leaves are the fields (variables). The instruments in the DQT are the first parent nodes of each field.
    - ex: [Vocabulary level](https://biobank.ndph.ox.ac.uk/showcase/field.cgi?id=6364) is under its parent category [here](https://biobank.ndph.ox.ac.uk/showcase/label.cgi?id=504).
    - *Special cases for demographics, images and covid19.
      - Demographics contain LORIS specific fields about the participants (e.g.: Date of birth, Sex).
      - * Note about date of birth. The dataset only contains the year of birth and month of birth. We set the day of birth to the 15 of each month for every participant.
  - use _mri_data_ and select _Selected_t1 w_ to get access to the structural images
      - you will see a download icon, indicating that these fields are files by themselves (instead of scalar values), thus they will be handled differently during the Download and Export step
- _Search with instrument:_ Here, you can enter a free text (e.g. T1w)
- _Visits:_ with this option you can further narrow your search




