# CAM
Centralized Assessment Manager for Burp Suite

### Quick Summary
* Allows users to set severity levels to vulnerabilities based on whatever you want(color coding) as not all threats have the same impact on all systems.
* Add screenshots for the vulnerability
* Persistence settings save your file locations
* Import/Export capabilities
* HTML report format is supported (DOCX and XLSX are in the code but are non-functioning at the moment) | You can edit the HTML to fit your report needs

# Installing
* Download the CAM.py file 
* Open Burp -> Extender -> Extensions -> Add -> Choose CAM.py file.
* Burp will add CAM tab

# How to use
After installing Burp Suite will have the CAM tab in its UI.
![alt tag](https://github.com/PolitoInc/CAM/blob/master/CAM_User_Guide_1.PNG)

^Project Settings tab^: 
* Open the Project Settings tab (CAM -> Project Settings) and create a new project. (I reccomend on an encrypted partition) 
* The "Details" area can be used to save any project details such as URLs, credentials, contact details, or any other comments.
* Generate report is where you can set the report type. NOTE: Only HTML works currently.
* The import and export buttons can be used to send other people reports and allows them to import it into the extension.
* "Open directory", this button just opens up where your project is stored at. (I might remove this later.)

![alt tag](https://github.com/PolitoInc/CAM/blob/master/CAM_User_Guide_4.PNG)

^Vulnerability Tab^:
* Here we can create vulnerabilities/add vulnerability descriptions/add remidiation guidelines.
* Vulnerabilities can be color coded and the threat levels changed to your preference.
* Screenshots can be added here as well. The "Add Image" button will add whatever image is copied to your clipboard.
* You can view the screenshots by clicking them CAM will use the default image viewer setup on your system. 

![alt tag](https://github.com/PolitoInc/CAM/blob/master/CAM_User_Guide_3.PNG)

^Right-click option^:
* We can right-click on a url in the "Target" tab send to CAM from there. 

![alt tag](https://github.com/PolitoInc/CAM/blob/master/CAM_User_Guide_5.PNG)

^ This is what happens after you "send to Cam", you must select a vunerability to put it under. 

* There are request/response tabs as well and pull the same information from the "Target" tab into CAM. 

NOTE: CAM will create a folder where ever you set the directory if you delete this folder CAM will not work at all. You have to use the "Remove Current" button in the "Project Settings" tab within CAM. 

### To Do
* Get DOCX and XLSX report formats working

