#Data Cleaning Assessment

The data cleaning needs for my three datasets are very similar. Mostly I have to cut out extra data such as team data, kid's data, and teen since that. Since the data is just in an excel file, I could cut out that data just using a delete function. One thing that I did was reformat my data into a machine-readable format since it was in vertical division lists by the categories of name, belt level, weight division, performance place, age, and gender. I formatted the data into columns of name, weight division, age division, belt level, gender, placement, Gi or No Gi, School, and Tournament. I then entered the relevant data into the columns. I set the name and weight division together as the primary key and reformated the data in my datasets based on that. In regards the time of reformatting the IBJJF data set took 8 hours because all of the reformatting was done by hand for both sets and I needed to reference a website (https://www.ibjjfdb.com/ChampionshipResults/1209/PublicRegistrations?lang=en-US) to find a missing weight division value for Bianca Barbosa Basilio.

#Authorship, Attribution, and Provenance About the File

The files were written by their respective organizations. The 2018 IBJJF Worlds dataset was written by the International Brazilian Jiu-Jitsu Federation and is available for public use. It was retrieved from (https://www.flograppling.com/results/6207361-2018-world-ibjjf-jiu-jitsu-championship/24562). The Masters data set was retrieved from (https://www.ibjjfdb.com/ChampionshipResults/895/PublicResults).

#Semantic Contents of File
The files contain data about the fighters that fought in these respective tournaments and the data is divided into the categories described above.

The main fields being used for this data set are name, weight division, performance place, and belt division.

The main datasets were all found on February 3rd 2019 and finalized for use on February 21st 2019. The IBJJF Masters dataset was added on the 14th to add more data from that tournament.

# Collection Process

I copy and pasted the records from the links above into Excel and created CSV files.

#Data Structure

The datasets are in CSV files saved in my computers drive, my cloud storage, and a flash drive.

The entities in the datasets are the fighters names.

The combined IBJJF dataset has 211 records of relevant fighters. Each record has the six categories of data that are: name, belt level, weight division, performance place, age division, and gender.


The types of data are as follows: names (string), belt level (categorical and hierarchal), weight division (categorical and hierarchal because of division names), performance place (integer and hierarchal), age division (categorical and hierarchal because of age division names), gender (categorical, non-hierarchal)

Other Description of Data:

Every data set has the same columns which are: name, belt level, weight division, performance place, age division, and gender. I believe that the names are enough of a description of them. The data values and types are described by the names and directly above this section. There are no missing values that I am aware of. I believe all of the unique column values are self-evident.

