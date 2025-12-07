# Travel-Memory-Application-Deployment
Travel Memory Application Deployment

Step1: Create EC2 Instance and deploy the Travel-memory-Application
<img width="940" height="507" alt="image" src="https://github.com/user-attachments/assets/584ff645-4f17-43da-a472-a5e96ea70fdb" />

Step3: Connect the instance and Load repo from provided GIT URL and configure the Mongodb setting via Backend code and Front end react (node Js ) 

<img width="940" height="644" alt="image" src="https://github.com/user-attachments/assets/3073fc91-8631-43f1-8a4d-b964f37e1e8b" />
This Shows the Application Front end server is running after installing the node package

<img width="940" height="628" alt="image" src="https://github.com/user-attachments/assets/90684065-1181-4f08-bc73-4a5cb99e568a" />


This shows the Mongodb values from back end

<img width="940" height="628" alt="image" src="https://github.com/user-attachments/assets/b87f06eb-49cf-4dac-af9f-1d9003463de0" />

This Shows the Back end running screen
<img width="940" height="562" alt="image" src="https://github.com/user-attachments/assets/c95f3b5f-0e78-49e0-97e9-37a3066868ab" />

This shows the Front end running screen
<img width="940" height="592" alt="image" src="https://github.com/user-attachments/assets/644053c4-efd0-4287-8cc4-e79f9c4f50ae" />

Step 4: Configure the ASG group based on Target Tracking policy after creating the AMI from the existing EC2 instance
<img width="951" height="496" alt="image" src="https://github.com/user-attachments/assets/27726f2d-c9a4-45fa-83b7-78610799ec64" />

Step 5: Configure the Domain in Cloudflare and set the A records and access the site via Domain name
A Record setting
<img width="404" height="264" alt="image" src="https://github.com/user-attachments/assets/ea7c0852-ad18-4332-a173-536612cb63c7" />

Accessing the site via Domain name

<img width="940" height="518" alt="image" src="https://github.com/user-attachments/assets/9729eaa8-1a0b-4228-bcdd-4eb519670cb5" />

Step 6: Create Target group and add the EC2 instances to the Target Group

<img width="836" height="409" alt="image" src="https://github.com/user-attachments/assets/5b6e30c6-b02a-43fc-94b1-82a325699992" />


Step 7: Configure the Load Balance based on TG and update the DNS Name in Cloudflare

<img width="822" height="383" alt="image" src="https://github.com/user-attachments/assets/d4c00b09-42a6-4056-89e5-61348f85f5e9" />


