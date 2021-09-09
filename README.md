School Supplier

School supplier, as the name suggests is designed to highlight and advertise products aimed at the education sector.
Its design is to use the Django framework as a way of storing product information via a SQL database as to easily update and upload products and images to accompany them. 
It will also make use of session handling allowing specific users the ability to access particular parts of the site depending on user permissions. 

![schoolsupplierdevices](https://user-images.githubusercontent.com/73948537/132665178-7f5a8bdd-1474-4276-8f9e-71113f7f9e7d.png)

Features

Existing features

Navigation bar

![image](https://user-images.githubusercontent.com/73948537/132666895-fd8a5dc7-5de1-45b6-96ec-2ace97d60409.png)

- LOGO AND FAVICON
The navigation bar features a Logo, this links back to the landing page.
I have also created a favicon using the same logo, it is stored in the static folder.

![image](https://user-images.githubusercontent.com/73948537/132666956-82bd29b9-1fbb-4bbe-9a5e-3fcbff0d570b.png)

- CSS animation
Custom Css animation is used to give the user a more dynamic feeling when using the site.
When hovering other text and SVG's in the nav bar.

- CATAGORY DROP DOWN
The nav bar also features a dropdown box that shows all product categories (that are also active, see admin section)

![image](https://user-images.githubusercontent.com/73948537/132667035-31fcd283-b760-40fc-afdb-24d093f331bf.png)

- ACCOUNT DROPDOWN
Links to Account details and settings when logged into a user, you can also login and out using this tab. Greets user with their name (if logged inw)

![image](https://user-images.githubusercontent.com/73948537/132667096-4840bb0c-eb08-4625-a6c6-1a73afd6dc4a.png)


- SEARCH BAR
Feature to be reworked. no post form as of yet. (not implemented)

![image](https://user-images.githubusercontent.com/73948537/132667514-cb1bb8e7-d81a-4c15-8c0c-03664111ec89.png)

- FAQ LINK
FAQ link for the site for self-serve with customers. (not implemented)

- EMAIL LINK
Opens native email app on device with company email for queries. 

- CALL LINK
Opens native VOP service or mobile app on device with company phone for queries. 

- BASKET
Allows user to see how many items have been added to basket and links to basket.

![image](https://user-images.githubusercontent.com/73948537/132667619-4baf756e-37df-4d99-93bd-5c82109a374e.png)

- AGE GROUP LINKS
Links to product range based on school age groups (not implemented)

![image](https://user-images.githubusercontent.com/73948537/132667737-cf0584b0-4820-4213-ba98-8be82b438355.png)

Landing page
-AD SPACE
AD space for images to promote products and deals.

-NEWS/ UPDATES 
News and Updates tab, with useful information about the shop/store.

-POPULAR ITEMS TAB
Shows popular Items from the catalogue. 

![image](https://user-images.githubusercontent.com/73948537/132667786-4ec18d79-70a3-49d5-a710-19a74e247f6a.png)
 
-SHOP BY CATEGORY
Shows all products in a particular category (managed through Django backend)

![image](https://user-images.githubusercontent.com/73948537/132667842-356394be-7658-4240-952c-b4f778cbd35a.png)

-TESTAMONIALS
Basic JS script to allow for an image carousel showing customer testimonials.

![image](https://user-images.githubusercontent.com/73948537/132668193-d1615512-8a1b-4f50-bd8b-f12c926f1ca4.png)

Footer
-logo
Features Logo.

-Social media links
SVG's of popular social media sites used by businesses.

-Account links
Links to users dashboard items: Dashboard, Login, Sign up, Orders, Wishlist, Logout

-Products and More Products
Lists Product categories links to catalogue with all items in particular category

-About 
Links to: Our team, Privacy, Terms (not implemented)

![image](https://user-images.githubusercontent.com/73948537/132668233-c30194d5-e442-42ad-be6a-78719977847b.png)

Admin page
![image](https://user-images.githubusercontent.com/73948537/132669960-93fa9757-f5d4-465a-8efb-1ea594dd6429.png)


-Accounts
Allows a user with the correct permissions to add, remove and change permissions of accounts logged on the SQL database.

-Groups (Authentication and Authorization)
Allows the creation of groups, this is a quick way to give particular user's specific sets of permissions IE. Admin, Moderator or basic user.

-Catalogue (product information)
Allows for the creation of categories, product type and specification and products that are automatically added to the catalogue.

-Checkout (delivery information)
Allows for the creation of delivery timeframes and prices pickable through the checkout process.

-Orders (order items)
Allows for the creation and ability to edit orders.

Catalogue
-Items sharing same product type
Shows all items with same product type

-Single product
Shows products information such as description (viewable through orders), images and price. 


Session handling
-User Account
The ability to login and out of the site allows for session handling of particular user information.

-Orders
The ability to track orders made by the user.

-Login & security
ability to change username and delete account.

-Addresses
Ability to add, edit and delete delivery address.

-Wish list
Ability to manage Wishlist, read description and remove items from your Wishlist. 

Basket and checkout
-basket
Ability to change quantity, purchase and delete items from basket. 

-delivery choices
Ability to choose delivery options.

-address conformation
This shows the end user what delivery addresses are tied to their account. also allows user to edit delivery address.  

-Payment selection
Allows for user to pay Via paypal, SoFort and debit and Credit card *powered by paypal (not implemented)

Future features
finish implementations of broken or unfinished features.

Social media page, allowing users to connect and promote in an attempt to improve brand identity and interest in the brand and the stores products.

Testing

If you would like to test any of the features please login as the admin user. once logged in you can access the admin dashboard via /admin/
Admin user: info@schoolsupplier.co.uk 
Password: Admin365420

Unfixed bugs 

Email verification, Automated emails.
Payment via paypal, credit card and debit card.

DEPLOYMENT
-Heroku server

Credit
-bootstrap

Media
-Willowbrook, KI other brands

