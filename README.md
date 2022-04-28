# Green Grocery
## WBD Project

Group Number -30

## Problem Motivation
- In these present situations, it is difficult for farmers to sell their products at a fair price in markets. Customers are buying hybrid fruits and vegetables which are not good for health which contain harmful substances.
- Customers are buying products at a higher price than the market price.

## Problem Statement
Farmers can sell fruits, vegetables, and dairy products at fair market prices on our website and customers can buy directly organic products from farmers through the website which are fresh and healthy for the body.
 
## Problem Solution
- Farmers can sell fruits, vegetables, and dairy products at fair market prices on our website
- Customers can buy directly organic products from farmers through the website which are fresh and healthy for the body

## Project Overall Idea
- Farmers can contact the GreenGrocery website and can sell their vegetables, fruits, and dairy products at fair prices.
- The process includes, firstly, the delivery guy picks their products and the management staff is responsible for
updating these products on the website.
- Users can log in to the website and can buy organic fruits, vegetables, and dairy products which are very fresh and healthy that come directly from farmers.
- Users can then select their required products and the respective quantity of each product and add them to the cart. After adding to the cart, the user can checkout and fill in the shipping details, and enter payment details.
- After a successful transaction, the user will get an order confirmation and a tracking link. Users can resolve their queries in the Contact Us section.

For more details about the project, please refer to the [**"Green Grocery PPT.pdf"**][1]

[1]: https://github.com/fsd30/Green-Grocery/blob/main/Green%20Grocery.pdf "Title"

## Get Started

The below steps show how to get started with the code running!.

★ Download git from the link:
https://git-scm.com/downloads.

★ Download node and npm from link
https://nodejs.org/en/.

★ After that in the terminal type ```pip install npm```.

★ Open the command prompt and run the command: 
```cd WBD_Group_30```

★ We must now create two .env files in /client/ and /api/ folders.
  
★ In the client .env file:

- Create an environment variable "REACT_APP_STRIPE" and assign it your stripe account url for successful completion of payments.

★ In the api .env file:

- Create different variables with names as shown below 

  - MONGO_URL: For connecting to the MongoDB collection.
  - PASS_SEC = This is used for encrypting the password and can be named anything. 
  - JWT_SEC = This will be used for initialization of JWT Token and can be named anything as per convenience.
  - STRIPE_KEY = Here, the url of the stripe key must be provided.
  - CLOUD_NAME = This is the cloud name used for cloudinary.
  - CLOUDINARY_API_KEY = This is the api key used for cloudinary.
  - CLOUDINARY_API_SECRET = This is the api secret key of cloudinary account 

★ Now, we have to install several dependencies.

- Change the directory to client Folder and enter the command ```yarn``` in the command line.
- Then, open another terminal and cd to the Admin Folder and enter the command ```yarn``` in the command line.
- Repeat this process for Volunteer and then API folder as well in different terminals and enter the command ```yarn``` in the command lines.

★ Finally to run the servers, use the following command
in all the terminals: ```yarn start```

★ Then, the terminal will prompt to open different URL's or else
enter the following URL's in your broweser for differenet pages.
- Enter http://localhost:3000/ for the frontend page (Client).
- Enter http://localhost:3001/ for the Admin Page.
- Enter http://localhost:3002/ for the Volunteer Page.

The API will run in the http://localhost:5000/ for the backend part and connceting to the MongoDB database.

★ After performing all the steps in correct order, the web application will start running smoothly. 

## Group Members

<pre>
Anirudh Jakhotia          - S20190010007
Neeraj Dusa               - S20190010047
Harish Mullagura          - S20190010124
Rakesh Ganeshula          - S20190010052
Kanduri Jayanth Sri Ram   - S20190010084
</pre>
