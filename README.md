# Vehicle-Tracking-System-Using-Arduino-through-GPRS-Network
User Manua

Edit in code: 
1.	Give the APN of your used SIM. 
2.	Give your firebase host. 
3.	Give your firebase Secret key. 

Wiring: 

See our paper or the wiring diagram attached in this reprository. 



Accessing Firebase Hostname and Secrete Key: 
•	Accessing Host Name:
1.	From the firebase home page, Go to Console>Select the Project from project list>Real time database. The Hostname is on the top of your real-time data. 
•	Accessing Secret Key: 
1.	From the realtime database page, click on the Setting icon> users and permission> Service Account>Database secret. Click on the Show button and copy the secret key. 

Opening a firebase project and realtime Database: 
1.	From the firebase home page, Go to Console> Create a project>Give the project name and accept the condition and press continue> Disable Google Analytic and press continue>Continue. Your project is created. 
2.	Now you have to create a realtime database. To create realtime database, click Build>Realtime Database> Create Database>Keep the location as it is (US central 1) and press the Next button>Select start in test mode and press Enable. Your realtime Database is created. 
3.	Go to the Rules tab and make the code snippets on the page similar as:  

{

  "rules": {
  
    ".read": true,  
    
    ".write": true,  
    
  }
  
}


Then click on Publish button. 
4.	Now your Realtime Database is ready. The Hostname and the Secret key can be accessed as described above. 
