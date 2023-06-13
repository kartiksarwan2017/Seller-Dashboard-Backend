# Sellers Dashboard Backend API

## Problem Statement
The task is to enable a seller to sell online, there will be a common page for
all the sellers to come & register themselves

## Introduction

Creating a **Sellers Dashboard Backend API** where sellers can register and login themselves, create a new store and list their inventories based on the category and subcategory added. It is built using Nodejs, ExpressJs, MongoDB.

<br/>


## 🔗 Important Links

> ## Checkout the Website [Seller Dashboard Backend API](https://seller-dashboard-backend.onrender.com)
> ## Backend API [Sample Postman Documentation Link](https://documenter.getpostman.com/view/9062378/2s93sdZXuz)

<br />

## Features

- **Sign Up**
<p> Seller can able to create His/Her Account if it doesn't exists earlier. Details required to create a new account are email, businessName, password, confirm password.</p>

- **Sign In**
<p> Seller can able to login to the existing account by entering the details such as email, password.</p>

- **Create Store**
<p>Seller can able to create a new store by entering details such as GSTIN Number, Store Logo URL, Store Timing.</p>

- **Create Category**
<p>Seller can able to create a new category in the store by entering detail such as Category Name.</p>

- **Create Sub-Category**
<p>Seller can able to create a new sub-category in the store based on the category selected by entering detail such as Sub Category Name.</p>

- **Create New Inventory**
<p>Seller can able to create a new inventory based on the category and subcategory selected. New inventory can be created
by entering details such as productName, MRP, SellingPrice, quantity, Product Image URL.</p>

- **Displaying list of all inventory**
<p>Users can able to see the list of all inventories of the specific seller based on the category and subcategory selected.</p>

<br/>


## Routes & URL

- **/api/seller/register**
  <p> To Register a new seller hit the following URL with a post request:</p>
  https://seller-dashboard-backend.onrender.com/api/seller/register

- **/api/seller/login**
  <p>To Login the existing seller hit the following URL with a post request:</p>
  https://seller-dashboard-backend.onrender.com/api/seller/login

- **/api/seller/store/create/:id**
  <p>To Create a new store for a specific seller, hit the following URL with a post request:</p>
   https://seller-dashboard-backend.onrender.com/api/seller/store/create/:id

- **/api/seller/store/add-category/:sellerId/:storeId**
  <p>To create a new category in the store of the seller, hit the following URL with a post request:</p>
  https://seller-dashboard-backend.onrender.com/api/seller/store/add-category/:sellerId/:storeId

- **/store/add-inventory/:categoryId/:subCategoryId**
  <p>To create a new subcategory for a particular category in the store of seller, hit the following URL with a post request: </p>
   https://seller-dashboard-backend.onrender.com/api/seller/store/add-inventory/:categoryId/:subCategoryId

- **/seller/store/add-inventory/:categoryId/:subCategoryId**
  <p> To create a new inventory for a particular subcategory, hit the following URL with a post request: </p>
  https://seller-dashboard-backend.onrender.com/seller/store/add-inventory/:categoryId/:subCategoryId

- **/store/all-inventories/:subCategoryId**
  <p>To display the list of all inventory based on the category and subcategory selected, hit the following URL with a get request:</p>
  https://seller-dashboard-backend.onrender.com/seller/store/all-inventories/:subCategoryId

  <br/>

## Tools Used

 <p align="justify">
<img height="140" width="140" src="https://www.startechup.com/wp-content/uploads/January-11-2021-Nodejs-What-it-is-used-for-and-when-where-to-use-it-for-your-enterprise-app-development.jpg" alt="nodeJS logo">
<img height="140" width="140" src="https://www.edureka.co/blog/wp-content/uploads/2019/07/express-logo.png" alt="expressjs logo">
<img height="140" width="140" src="https://g.foolcdn.com/art/companylogos/square/mdb.png" alt="mongoDB logo">
<img height="140" width="140" src="https://mms.businesswire.com/media/20210806005076/en/761650/22/postman-logo-vert-2018.jpg" alt="postman logo">
<img height="140" width="140" src="https://www.pngitem.com/pimgs/m/13-131098_visual-studio-code-logo-hd-png-download.png" alt="vscode logo">
</p>

- Version Control System: Git
- VCS Hosting: GitHub
- Integrated Development Environment: VSCode
  <br/>
  <br/>

## Requirements

For development, you will only need Node.js and a node global package installed in your environement and mongodb for database.

### Node

- Node Installtion on Windows
  Go on to the [official Node.js website](https://nodejs.org/en/) and download the installer. Also, be sure to have `.git` available in your PATH,
  `npm` might need it (You can find [git](https://git-scm.com/)).
- Other operating System
  You can find more information about the installation on the official [Node.js website](https://nodejs.org/en/) and the official [NPM website](https://www.npmjs.com/).

If the installation was successful, you should be able to run the following command.

```
$ node --version
v16.13.0

$ npm --version
8.2.0
```

If you need to update `npm`, you can make it using `npm`! Cool right? After running the following command, just open again the command line and be happy.

```
$ npm install npm -g

```

<br/>

## To run the project on your local machine:

1. Open terminal.

2. Change the current working directory to the location where you want the cloned directory.

   ```
   $ git clone https://github.com/kartiksarwan2017/Seller-Dashboard-Backend

   ```

3. Install all the dependencies by running :

   ```
   npm install

   ```

4. Run npm start to run the project at local host, port 8000:

   ```
   $ npm start

   ```

<br/>

## Configuration

Open `a/nice/path/to/a.file` then edit it with your settings. You will need:

- A setting
- one more setting
- Another one more setting

## Screens

<p align="justify">
   
### Register Seller:    
<img src="/screenshots/Register.PNG" />
   
### Login Existing Seller:
<img src="/screenshots/Login.PNG" />
   
### Create a New Store:    
<img src="/screenshots/createStore.PNG" />

### Create a New Category:

<img src="/screenshots/createCategory.PNG" />

### Create a New SubCategory:

<img src="/screenshots/createSubCategory.PNG" />

### Create a new Inventory:

<img src="/screenshots/createInventory.PNG" />

### Display list of all Inventories

<img src="/screenshots/listofInventories.PNG" /> 

</p>
<br/>
