-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Gift of the Givers Web Application
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Overview
The Gift of the Givers Foundation stands as a beacon of hope in times of crisis, dedicated to providing swift and effective aid to communities struck by natural disasters and emergencies in South Africa and beyond. This project aims to develop a comprehensive C# web application for the foundation, serving as a centralized hub for managing relief efforts, coordinating volunteers, and facilitating resource allocation during times of crisis.
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Creating Account
![image](https://github.com/user-attachments/assets/589221f3-4c43-4e06-97c6-5179d858827b)
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Confirmation
![image](https://github.com/user-attachments/assets/0275d885-ed6f-48e5-b18a-622677d6a38c)
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Login Success!
![image](https://github.com/user-attachments/assets/e6256770-4cda-41a1-b77e-5fc7dcbd20f1)
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Admin UI - (LOGIN)
![image](https://github.com/user-attachments/assets/3f5886f9-a68f-4996-8854-c9943aa4464e)
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Admin Dashboard
![image](https://github.com/user-attachments/assets/727f4ed5-807e-4aa2-acc8-7bafed4cd509)
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
View Donations
![image](https://github.com/user-attachments/assets/7c268016-3ddc-4573-b2a3-7ff9cc05df19)
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
View Incidents
![image](https://github.com/user-attachments/assets/3facc968-efec-482e-9e61-0558f808808f)
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
View Volunteers
![image](https://github.com/user-attachments/assets/705b805e-83b7-48be-9cfc-b82be5d003d4)

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Key Features
Incident Reporting: Users can report incidents related to natural disasters and emergencies, ensuring that the foundation can respond quickly and effectively
![image](https://github.com/user-attachments/assets/99bb9d47-a66c-4a45-9294-dee50f249e72)

Donation Management: Users can make donations to support the foundation's efforts, helping to fund critical relief initiatives.
![image](https://github.com/user-attachments/assets/22bd56f9-9b92-4261-b909-94c1a292365d)

Volunteer Coordination: Individuals can sign up to become volunteers, facilitating the mobilization of resources and personnel during crises.
![image](https://github.com/user-attachments/assets/2b8c0b2b-498a-4c76-b17f-ccaec301aaac)

Technologies Used
ASP.NET MVC: For building the web application and implementing the Model-View-Controller design pattern.
Entity Framework: For data access and management, enabling interactions with the database.
Azure SQL Database: For storing user and incident data securely in the cloud.
HTML/CSS/JavaScript: For front-end development, ensuring a responsive and user-friendly interface.
Bootstrap: For responsive design and UI components.
Getting Started
Prerequisites
Visual Studio: Ensure you have Visual Studio installed with the ASP.NET and web development workload.
Azure Account: An active Azure subscription to set up the Azure SQL Database and host the application.
Installation
Clone the Repository:

bash
Copy code
git clone <repository-url>
cd GiftOfTheGiversApp
Open the Project in Visual Studio:

Open the .sln file in Visual Studio.
Install NuGet Packages:

Right-click on the project in Solution Explorer and select Manage NuGet Packages.
Install the required packages:
Entity Framework
Microsoft.AspNet.Identity.Core
Microsoft.AspNet.Identity.EntityFramework
Set Up Database:

Open the Web.config file and update the connection string to your Azure SQL Database.
xml
Copy code
<connectionStrings>
  <add name="DefaultConnection" 
       connectionString="Server=tcp:<your-server>.database.windows.net,1433;Initial Catalog=<your-database>;Persist Security Info=False;User ID=<your-username>;Password=<your-password>;MultipleActiveResultSets=False;Encrypt=True;TrustServerCertificate=False;Connection Timeout=30;" 
       providerName="System.Data.SqlClient" />
</connectionStrings>
Run Migrations:

Open Package Manager Console and run the following commands:
powershell
Copy code
Enable-Migrations
Add-Migration InitialCreate
Update-Database
Build and Run the Application:

Press F5 to build and run the application.
Navigate to the home page to start using the application.
Usage
User Registration: Users can create an account to access the full features of the application.
Report an Incident: Logged-in users can report incidents, which will be stored in the database.
Make a Donation: Users can donate funds to support relief efforts.
Become a Volunteer: Users can apply to volunteer, enabling the foundation to coordinate relief operations effectively.
Contributing
Contributions are welcome! If you would like to contribute to this project, please follow these steps:

Fork the repository.
Create a new branch (git checkout -b feature/YourFeature).
Make your changes and commit them (git commit -m 'Add some feature').
Push to the branch (git push origin feature/YourFeature).
Open a pull request.
License
This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgements
Thanks to the Gift of the Givers Foundation for their inspiring work in disaster relief.
Special thanks to all contributors who help improve this project.
