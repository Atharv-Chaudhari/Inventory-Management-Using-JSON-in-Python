# Welcome to The Inventory Management System 
<p align="center">
<img src="https://www.kindpng.com/picc/m/264-2640361_inventory-management-system-png-transparent-png.png" width="600" height="400"/>
</p>
                                                                                                                                   
        NOTE :- 

        1) all functions throw all required errors on invalid inputs or illegal operations...!!!

        2) If you wish to run then product data file will be generated automatically without any need of upload or you can comment down that product code to insert your product data file and run purchase reports json file will be generated automatically when first user will buy something...!!!
        
        3) Each Function will update JSON file after its execution automatically...!!!
## So There are Two Types of Functionalities :-
### 1) Admin
### 2) User

<p align="center">
<img src="https://raw.githubusercontent.com/Atharv-Chaudhari/ETG-Internship-Work-and-Projects/main/Inventory%20Management%20Using%20JSON/Images%20for%20Readme/Admin%26user.jpg"/>
</p>                                                                                                                          
                                                                                                                                   
## 🧿 Admin Functionality :-
#### Basically This is just for managing the Inventory for person having extra permissions like inserting,updating and deleting product details which should be at owner or manager level only.

<p align="center">
<img src="https://raw.githubusercontent.com/Atharv-Chaudhari/ETG-Internship-Work-and-Projects/main/Inventory%20Management%20Using%20JSON/Images%20for%20Readme/admin.jpg"/>
</p> 

#### Follwing Are The functions at Admin Level ⤵

### 1) Display All Products Details ➡
#### In This Function Admin Will have two options either he wants all list as it is in DataBase or else he want to have a look on all products by their categories.

Category Wise :-
<p align="center">
<img src="https://raw.githubusercontent.com/Atharv-Chaudhari/ETG-Internship-Work-and-Projects/main/Inventory%20Management%20Using%20JSON/Images%20for%20Readme/display_admin_catwise.jpg"/>
</p> 

According to insert sequence:-

<p align="center">
<img src="https://raw.githubusercontent.com/Atharv-Chaudhari/ETG-Internship-Work-and-Projects/main/Inventory%20Management%20Using%20JSON/Images%20for%20Readme/display_admin_insert.jpg"/>
</p>

### 2) Display Specific Product Details ➡ (this uses product ID to filter all products we can use product name also....)
#### In this Function Admin will have to enter Product ID of which details he wants to check he will get all details regarding that particular product.

<p align="center">
<img src="https://raw.githubusercontent.com/Atharv-Chaudhari/ETG-Internship-Work-and-Projects/main/Inventory%20Management%20Using%20JSON/Images%20for%20Readme/display_admin_specific.jpg"/>
</p> 

### 3) Insert New Product Data in Inventory ➡
#### This Function will allow Admin to Add New Product Details in Inventory. Also provides Functionality to add new attribute property for specific product if Admin want to add other than basic 5 properties/details.

<p align="center">
<img src="https://raw.githubusercontent.com/Atharv-Chaudhari/ETG-Internship-Work-and-Projects/main/Inventory%20Management%20Using%20JSON/Images%20for%20Readme/insert_admin.jpg"/>
</p> 

### 4) Update Product Data In Inventory ➡
#### This Function will provide Admin two options either he wants to update all details of product or he wants to edit any specific detail/attribute of product. Also it will Throw Error on invalid product ID.

<p align="center">
<img src="https://raw.githubusercontent.com/Atharv-Chaudhari/ETG-Internship-Work-and-Projects/main/Inventory%20Management%20Using%20JSON/Images%20for%20Readme/update_admin.jpg"/>
</p> 

### 5) Delete Product or Remove Product From Inventory ➡ (we can give one more functionality to delete any attribute of product details to delete)
#### Here Admin can remove products that are out of stock or want to delete. Also it will Throw Error on invalid product ID.

<p align="center">
<img src="https://raw.githubusercontent.com/Atharv-Chaudhari/ETG-Internship-Work-and-Projects/main/Inventory%20Management%20Using%20JSON/Images%20for%20Readme/update_admin.jpg"/>
</p> 

### 6) Display Purchase Reports ➡
#### Admin can have a look on user purchases with two options like either he want to check all purchase reports or  want to check purchase report of any specific customer/user. This Also Provid Functionality to show message that no reports present if no purchase happened by any user...!!! Also it will Throw Error on invalid User ID.

Purchase Reports Before any user purchase :- 
<p align="center">
<img src="https://raw.githubusercontent.com/Atharv-Chaudhari/ETG-Internship-Work-and-Projects/main/Inventory%20Management%20Using%20JSON/Images%20for%20Readme/reports_admin_before.jpg"/>
</p>

Purchase reports After User Purchase :-
<p align="center">
<img src="https://raw.githubusercontent.com/Atharv-Chaudhari/ETG-Internship-Work-and-Projects/main/Inventory%20Management%20Using%20JSON/Images%20for%20Readme/reports_admin_after.jpg"/>
</p> 

### 7) Admin Can Delete Whole Database also if he wants to clear all...!!! (As This Functionality is so sensitive it is not mentioned but Code is present in commented part)

## 🧿 User Functionality:-
#### This is Basically something like customer can operate to buy products and get his bill and previous bills record too have no functionally or access to product to either insert or modify or delete it.

<p align="center">
<img src="https://raw.githubusercontent.com/Atharv-Chaudhari/ETG-Internship-Work-and-Projects/main/Inventory%20Management%20Using%20JSON/Images%20for%20Readme/user.jpg"/>
</p> 

#### Follwing Are The Functions at User Level ⤵

### 1) Display All Products with their Details ➡
#### This Function will help user/customer to buy products and also will give information about product.

All Products :-
<p align="center">
<img src="https://raw.githubusercontent.com/Atharv-Chaudhari/ETG-Internship-Work-and-Projects/main/Inventory%20Management%20Using%20JSON/Images%20for%20Readme/display_user_all_products.jpg"/>
</p> 

Category wise details :-
<p align="center">
<img src="https://raw.githubusercontent.com/Atharv-Chaudhari/ETG-Internship-Work-and-Projects/main/Inventory%20Management%20Using%20JSON/Images%20for%20Readme/display_user_cat.jpg"/>
</p> 

### 2) Display Specific Product with its details ➡
#### This Function will help user/customers who want to see specific product details. Also Customer can see products by there category.

<p align="center">
<img src="https://raw.githubusercontent.com/Atharv-Chaudhari/ETG-Internship-Work-and-Projects/main/Inventory%20Management%20Using%20JSON/Images%20for%20Readme/user_specific_product.jpg"/>
</p>

### 3) USers All Purchase reports ➡ (Something Like Purchase History)
#### This Function will help user to track his purchase and all bills reports till today. Also This Function Provides Information Only to User if He enters User ID. (we can add password features also here to increase more functionality)

If User have no purchase records :-
<p align="center">
<img src="https://raw.githubusercontent.com/Atharv-Chaudhari/ETG-Internship-Work-and-Projects/main/Inventory%20Management%20Using%20JSON/Images%20for%20Readme/user_purchase_before.jpg"/>
</p>

After User purchases products :-
<p align="center">
<img src="https://raw.githubusercontent.com/Atharv-Chaudhari/ETG-Internship-Work-and-Projects/main/Inventory%20Management%20Using%20JSON/Images%20for%20Readme/user_purchase_after.jpg"/>
</p>

### 4) Buy The Product ➡
#### This is the main Function of this part this will allow user/customer to buy products it will give error if customer buy product with high quantity than in stock also user will get one more chance to correct quantity if he want to save efforts or restarting process or he can skip that product too. Also Customer will get message of out of stock if product is not present in inventory (quantity=0). Customer can buy multiple products simulteneously by using product ID's (we can add buying product by its name also) user/customer will error messages if he enters wrong choices...!!!

<p align="center">
<img src="https://raw.githubusercontent.com/Atharv-Chaudhari/ETG-Internship-Work-and-Projects/main/Inventory%20Management%20Using%20JSON/Images%20for%20Readme/user_purchase.jpg"/>
</p> 

## 5) Bill Generation ➡ (This is Supportive Function for buy product funtion) 
#### User/Customer will get his bill regarding purchases done by him just after purchase with unique 10 digit Transaction ID. (if user buys multiple products in one go it will give aggraegate bill...!!!)

<p align="center">
<img src="https://raw.githubusercontent.com/Atharv-Chaudhari/ETG-Internship-Work-and-Projects/main/Inventory%20Management%20Using%20JSON/Images%20for%20Readme/user_bill.jpg"/>
</p> 
