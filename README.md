# Sitecore-Powershell-Script-Backup-Utility

Once you install package(Powershell Script Backup Related Items Package.zip), it will add a button in Developer tab to take scripts backup and on its click it will open interactive dialogue for this.
![image](https://user-images.githubusercontent.com/63503137/163937336-ccc72084-f51a-48a8-b212-df7ffa817545.png)

## 1. Script folder selection dialogue
![image](https://user-images.githubusercontent.com/63503137/163938561-fde6a455-820d-496a-a630-2ddcec07a339.png)
 - ### Folder List in Script Library
 - It uses script-library as root folder and show all files/folder in it, user can select all folders which contains needed script files. 
 - ### Subfolder lookup verification		
 - If it is checked then only subfolder will be looked up for any script else it will loopup script files in chosen folders only.

## 2. Script selection dialogue
 - ### Scripts Tab
 - Select all files whose backup needs to be taken
  ![image](https://user-images.githubusercontent.com/63503137/163939189-cf9b16ec-f4bd-4294-b88c-1d6468a4ff7e.png)

 - ### Output Tab
  ![image](https://user-images.githubusercontent.com/63503137/163939552-d200e21b-c362-479f-9e20-1869231944d6.png)
  - #### a. How to output script details
  - It defines how the backup will be stored i.e. in single file only, respective .ps1 file to be created for each selected script or only needs file details on console.   
  - #### b. Specify Path where script folder will reside
  - It will define basic path where backup needs to be taken by default it will have **App Data** folder of your application .
  - #### c. Folder Name where script file/s to be saved
  - Actual folder name under which files will get store, so finally files stored in details given in b+c

## Final outcome
Files will be saved in given folder, as shown below
![image](https://user-images.githubusercontent.com/63503137/163940377-4fe6345c-11b9-4d14-9104-ee49eb3e2729.png)


Hope it will help you to save your work or any other importent .ps1 file.
Happy coding !!!

Please comment your feedback or any improvement needed.



