# Bellatrix Sampe Rompon

Bachelor Degree of Telecommunications Engineering with 2 years of experience in developing and implementing Robotic Process Automation (RPA). Experienced in creating RPA systems that used in banking, finance, insurance, and human resource fields. Can work together in a team, have good communication skills, and quickly learn new things.

## Education
**Telkom University**

Bachelor of Telecommunication Engineering | GPA 3.41 / 4.00 | August 2018 - September 2022

## Work Experience


## RPA Projects


### Candidate Document Bots

![Candidate Document Bots](/assets/img/Candidate_Document_Bots_Flow.jpg)

**Developed using UiPath** 

RPA bots to automate the process of creating several candidate documents such as CV, candidate overview, and offering letter. The bot will get candidate data from Excel using **Excel Activities** or from a spreadsheet using **Google Workspace**. Candidate data will be input into a word document template and then saved into local folder using various activities from **word activities**. Documents are then sent to HR via email using **email activities**.

<br>

### Employee Agreement Bot

![Employee Agreement Bot](/assets/img/Employee_Agreement_Bot_Flow.jpg)

**Developed using UiPath** 

RPA bot to automate the process of creating employee agreement documents. The bot will read and get the candidate's KTP from email using several activities from **email activities**. The data on the KTP will be extracted using **OCR** ​​available on UiPath. The results of the data extraction will be saved into Excel using **Excel Activities** and then used to create an employee agreement document in Word using **Word Activities**. The employee agreement document will be sent to the candidate using **email activities**.

<br>

### ESPT Bot

![ESPT Bot](/assets/img/ESPT_Bot_Flow.jpg)

**Developed using UiPath** 

RPA bot to automate the process of inputting data into the ESPT application (tax application). The bot will get data from Excel using **excel activities**. For all processes in the ESPT application, various activities from **UI Automation Activities** are used, such as **click, check, type, get**, etc.

<br>

### SEO Ranking Bot

![SEO Ranking Bot](/assets/img/SEO_Ranking_Bot_Flow.jpg)

**Developed using UiPath** 

RPA bots to automate the process of calculating the ranking of each article from the company. To open the search engine, the bot uses the activity **open browser** from **UI Automation Activities**. For the search process on Google, bot use various activities from **UI Automation Activities** such as **type** and **click**. The bot will calculate the ranking of the article using **loop**.

<br>

### Policy Cancellation Bot

[image]

**Developed using UiPath** 
RPA bots to automate the process for canceling customer policies at an insurance company. The bot will retrieve data from Excel using **excel activities**. The bot will access the website for policy cancellation using **open browser** from **UI Automation Activities**. Data in Excel will be input on the website using various activities from **UI Automation Activities** such as **click, check, type, get**, etc. The results of the policy cancellation process will be recorded into the policy cancellation data excel.

<br>

### Job filtering on Jobstreet and Kalibrr Bot

[Publication](https://drive.google.com/drive/folders/1cYbpd9oaZZ6taVlCAc45Rp5rCD6evMKR?usp=drive_link)

[image]

**Developed using UiPath and Python** 

RPA bot to automate the job filtering process on the job site using **RPA** and **Natural Language Processing (NLP)** technology. The user will input personal data, education, work experience and job that the user wants on the Google form, then the data will be saved in a spreadsheet. The data in the spreadsheet will be used to generate a CV using RPA. RPA will scrape every job vacancy in the job site to take the job description and save the data in Excel. The data in Excel will be processed and compared with the user's CV using NLP. The final result of this bot are CV documents of the user which have been combined with tables and explanations of 10 job vacancies that best match the CV of the user.

<br>

### e-Statement Bot

[image]

**Developed using Automation Anywhere (AA360)**

RPA Bot to automate the data comparison process on e-Statements and core banking websites. To access the e-Statement website and core banking website, the bot use actions from the **browser package**. The PDF e-Statement from the website will be downloaded and converted into txt using the **extract text** action from the **pdf package**. The data in the e-Statement then compared with the data on the core banking website using **if logic** and **fuzzy match package**. The comparison results will be recorded in Excel using **Excel Advanced Package**.

<br>

### SKN RTGS Bot

[image]

**Developed using Automation Anywhere (AA360)**

RPA Bot to automate processes about SKN RTGS. The robot will retrieve the list of email sender requestor on FTP using actions from the **FTP/SFTP Package**. The bot will access the email and then download attachments using various actions from the **email package**. Excel and txt files from emails will be put into a folder using the action from **folder package**. The contents of Excel will be moved to the Excel logbook using various actions from the **Excel Advanced Package**. The robot will access the SKN RTGS related website and input overbooking using actions from **browser package**. Next, the robot accesses the website related to SKN RTGS again to input SKN RTGS data and then the output from this process will be saved in the specified folder. The output will be sent back to the requestor via email.
