# Assignment


In our team, we leverage specific software technologies, We want you to demonstrate your ability to comprehend and effectively work with the technologies integral to our team's workflow.

For this task, we aim to build a full-stack web application. The application will accept user input via a well-designed user interface, process the data according to the requirements, and perform CRUD operations on a chosen database.

NOTE : 
- Use naming conventions for files and variables.   
- Use git flow.    
- Create tests.

  

<details>
  <summary>Frontend</summary>   
  
- Make the UI similar to this [example]([https://shorturl.at/qCIY5](https://www.figma.com/file/d8dGyuJIbrbdJzEN0l3lSI/home-assignment-web-app-design?type=design&node-id=0-1&mode=design&t=MKpkjPgyLBMpddqf-0)) as much as you can.  
- Create an initial screen for uploding files using drag and drop box and also using the file explorer.   
- Create a feature that enables the user to view ongoing file uploads.
- Create a new window that shows the folowing statistics (choose at least 3) :  
    - Upload time compared to file size.  
    - Average file size categorized by file type.  
    - Segregation of file types based on upload success and failure rates.   
    - Sorting files by upload date and total daily size.  

</details>

<details>
  <summary>Backend</summary>

  - Deploy the infrastructure from the `docker-compose.yaml` file.
  - Create a server for the UI and Preform validations on files.
  - Extract metadata and store it .  
  - store the files , and check for duplications.
  - API endpoints :
    - `POST -> /file ` + some metadata.
    - `GET ->  /statistics?querytype=avgsizebytype` .   
     

</details>


BONUS : Create a `Dockerfile` for a production-ready environment.    

  
GOOD LUCK ! 
