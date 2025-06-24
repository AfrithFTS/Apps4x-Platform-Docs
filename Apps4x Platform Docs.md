# Apps4x Platform Documentation

## Introduction

Apps4x is a platform to develop any applications without coding, simply says `"No Code Platform"`. Apps4x Platform has ability to build `n` number of applications. This platform is structured to start in the single Organization. Inside the Organization, there was multiple environment can create. In the single Environment can create multiple company. In the single Company can create multiple applications.

This Document try to explain the apps4x functions and features for beginers who are all try to understand the apps4x platform.

## Sign Up

  - Starting from Sign-up process is better to understand the platform for beginers.

  - To use and experience the apps4x platform, first need to sign-up with basic details to create an account on apps4x platform.

## Sign In

  - Once Sign up process has been completed, you can use your created credentials to login to the apps4x platform.

## Organization/Environment/Company:

  - When you are login the platform for the first time, you can view the platform organization page as default screen.

  - In that page, you can create a new organization here by selecting plans you need.

  - Once created and open the organization, you can view the 3 tabs of Overview, Environment and People.

**Overview:**

In the Organization Overview page, you can see the Config settings option. There are two Config settings option, they are,

  - Multicompany
  - Company Filter

    - **Multicompany -** You can enable the Multicompany checkbox to group the environment and companies under environment.

    - **Company Filter -** By enabling the Company Filter, the same datas are shown in all the companies which comes under single organization.

**Environment:**

  - In the Environment page, you can create an Environments under the Organization.

  - You can add members for the every environment from the Available users list who you need.

  - If you need to add new user, go to People tab to create.
  
  - Only members can access the environment.

  - Click Environment that you've created, it will navigate you to Envrionment Overview tab.

  - Click Company tab, In that Company tab you can create companies.

  - Every Company has 2 settings options,
    
    - Config Settings
    - User

    **Config -** Config Settings used to add title, icon, theme and Enable Active Directory Login for the Company.

    **User -** To Add users for company which shows available users list from evnironment users.

**People:**

  - In People page, you can create users for the environments and assign those users in which environment you need.

  - There are 2 Organization user type, `Admin and User.` You should choose which type of user is creating. Because of some application access were given only for the Admin user type.

## Home

  - Once user added in the Company, you should login again from the scratch to the Apps4x.

  - When you are login to the Apps4x, it will redirect you to the Apps4x Home page were you can see the Studio app.

## Apps:  

  - You can create Apps using the button on top right `Apps+` as where you can find on Apps4x Home page.

  - Otherwise you can create apps inside the Studio.

  - There are some types in apps,
   
    - Apps
    - Portal
    - Workspace
    - Website
    - Mobile App
    - Api App
    - External

## Connector:

  - In the Studio, Click Connector tab and click `+` icon to create connector.

  - There are some types in Connector,

    - SQL
    - Mondo DB
    - Rest Api
    - Api Method
    - Swagger

For DB Connector we need to give the connection string of the DB,

 Example:

	-SQL
	-Mango DB
	
   - REST API Connector
	
		- Using REST API connector we can integrate the third party apis into our application,
		
		- For using the REST API connector we need to create the parameter for BASE URL,

		- In studio page in left side menu bar you can find the parameter menu create a paramter as follows
		
		Keyname: baseurlarcotest

        Value:   https://test.arco.sa/ManpowerApp(end point of your api),

        Description:  arco test url

   - Swagger Connector

		- For using the the swagger connector you already should have your swagger json

		- For using the swagger connector we need to create the parameter for BASE URL
			
		- In studio page in left side menu bar you can find the parameter menu create a paramter as follows
		
		Keyname: baseurlfakerestapi

        Value:   https://fakerestapi.azurewebsites.net (end point of your api)

        Description:  fakerestapi

		- Your absoulte path should be /swagger/v1/swagger.json
			
		- Makesure your swagger is working fine
		
		- API method Connector
		
		- Will be developed in future

## Studio:

  In Studio, you can create any type of applications you need