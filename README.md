# Devocart
Welcome to Devocart - an eCommerce store, a user influencive online shopee where you can find yourself picking up things more than what you had in mind.
### About
Devocart is developed using HTML, CSS and JS, also PHP and MySQL database for backend and validation. Devocart offers a seamless shopping experience for users to browse, purchase, and manage their orders and wishlisted items. This README file provides an overview of the website's features, installation guide, and usage instructions.

![Screenshot 2024-03-19 101504](https://github.com/yesaswinidevipendem/eCommerce-website/assets/99169709/5b085727-ac35-41d7-907e-d613a7ee0b97)

### User authorization Features
 Users can create an account, login, and securely access their profile information.
 
 ![Screenshot 2024-03-19 101823](https://github.com/yesaswinidevipendem/eCommerce-website/assets/99169709/572b4cb5-e178-40ee-8942-60fbf81edf92)

![Screenshot 2024-03-19 101440](https://github.com/yesaswinidevipendem/eCommerce-website/assets/99169709/67fec5a5-3600-4d7c-9f00-934acadc74f5)

### Product Catalog Display
Devocart offers a wide range of products categorized into various brands and items for easy navigation. Users can view detailed descriptions, and add items to their cart and wishlist.
You can either view products from homepage or fron the products page.

![Screenshot 2024-03-18 124610](https://github.com/yesaswinidevipendem/eCommerce-website/assets/99169709/243024e2-fca7-4657-a43c-aecd816e15b1)

![Screenshot 2024-03-18 124842](https://github.com/yesaswinidevipendem/eCommerce-website/assets/99169709/117eee29-9b1f-42d0-adf3-e634c0e98121)

### Cart Features
The website features a cart system that allows users to add products, adjust quantities, save in wishlist and remove items before proceeding to checkout.

![Screenshot 2024-03-18 130709](https://github.com/yesaswinidevipendem/eCommerce-website/assets/99169709/608a6860-eb55-420a-b10f-7a6c74b13e6e)

The wishlist allows user to add the product back to the cart or delete the product.

![Screenshot 2024-03-18 130828](https://github.com/yesaswinidevipendem/eCommerce-website/assets/99169709/f45888c1-2a96-4e9f-b9ea-6039ce38803c)

you can udjust the quantities in the cart and check the updated price.

![Screenshot 2024-03-18 131856](https://github.com/yesaswinidevipendem/eCommerce-website/assets/99169709/52d49fb9-2990-401a-a399-b5da4ad4a3e1)

### Brand Categorization
The user can also browse the products by the brand name on the top.

![Screenshot 2024-03-18 132353](https://github.com/yesaswinidevipendem/eCommerce-website/assets/99169709/5a4e3e73-59b1-4811-b6bb-f39307b9bf6f)

### Logging out
User can logout of their account , but user need to login to access the cart while shopping.

![Screenshot 2024-03-18 132648](https://github.com/yesaswinidevipendem/eCommerce-website/assets/99169709/ed099bef-3507-470f-90e5-90b0a6f4a868)

# XAMPP (Cross-Platform Apache, MySQL, PHP):
XAMPP is a free and open-source cross-platform web server solution stack package developed by Apache Friends, consisting mainly of the Apache HTTP Server, MariaDB database, and interpreters for scripts written in the PHP and Perl programming languages.

![Screenshot 2024-03-18 132824](https://github.com/yesaswinidevipendem/eCommerce-website/assets/99169709/468a21fc-13de-4f10-8815-150dba511404)

### Web Browser:
Any modern web browser such as Google Chrome, Mozilla Firefox, or Microsoft Edge.
Import the shopee.sql file into your MySQL database to create the tables. I have created 4 tables based on my requirement.

![Screenshot 2024-03-18 132933](https://github.com/yesaswinidevipendem/eCommerce-website/assets/99169709/17e71871-bfc5-4bd8-9c83-b6c5c0ba49b9)

### Run the Application
Start your web server.
Access the Devocart website through your web browser.

# EC2 instance
Create an EC2 instance in your AWS Cloud account and deploy your ecommerce website.
Follow these steps..
#### Step-1 
Open Aws and log in to your free tier account and go to the console.
#### step-2
Search for EC2 and click on it.
#### Step-3
Click on Launch Instance and select required OS and create the instance.
#### Step-4
Create a key pair which will be used further.
#### Step-5
After setting security to ssh, http, and https you will launch the instance.
Now your instance will start running.
#### Step-6
Open the instance and click on connect option, from there select RDP client.
#### Step-7
In the RDP client, download the remote desktop and click on get password.
#### Step-8
Upload the private key file you downloaded before and click on Decrypt Password.
#### Step-9
Copy the password given and open the remote desktop. Now paste the password and you can access the remote desktop.
#### Step-10
Install Chrome if needed and install Xampp. Copy paste your files/folder in the drive/xampp/htdocs folder.
Run the Xampp panel and Use the public Ipv4 address to open the file in th browser.
