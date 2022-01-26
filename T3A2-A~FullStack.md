# T3A2-A Full Stack Application 
# Axel Whitford / Sam O'Donnell / Tia Koenig

# Desciption of Website

## Client

'Little Parliament' and 'Our Store' is a quaint little cafe in Rainbow Beach that also doubles up as a souvenir gift shop.
## Purpose and Functionality

Brief - Create a website for a cafe and souvenir store called Little Parliament. This website should act as a landing page for customers who don't know that Little Parliament exists yet, it will showcase the menu, a little bit about the cafe as well as the products that are for sale in the store. As Little Parliament is located in Rainbow Beach, a secluded tourist town, guests to the town like to have an idea of what is available before arriving at the town. This means the content on the website should be clear concise, and not overwhelming.

The landing page should give a good quick synopsis about the cafe, as well as be alluring enough to make the user explore more of the page. The next page would be an about us page and would showcase more detail about why the cafe exists as well as a little information about the owners. The menu page would showcase the menu in a fun way, instead of just being a static image it will be an interactive page, that has a small description, image, and price of all the items on the menu. The products page would be a static image page that has a list of all current items in stock, with the ability to add these items to a cart, purchase them, and possibly reserve them for pick-up. 

As this will be a website with the possibility of becoming live, the owner of the cafe would like to be able to make changes without having to go through a developer. An admin panel where they can log in and add, update and delete products and menu items as the need arises. 

### Features 

#### Menu showcase 

This website will have an entire page dedicated to the menu of Little Parliament. The menu will showcase each individual item that is on the menu as well as a brief description of it, the price of the item, and an image that shows off the final product. The Menu will be a free-flowing list with a little bit of animation to draw the attention of the user of the website to the products. The menu will also allow you to click onto each product and open a more detailed version of it. There will be the ability to filter the category of food items (coffee, Breakfast, Lunch) giving the user an easy way to browse the menu. 

#### Products Page/Cart 

As Little Parliament also has a souvenir/gift shop attached to it called 'Our Shop' we are implementing a products page that showcases all the items that are available in-store, these products will be purchasable from this page, will display a price, an image, and a small description. The product can also be clicked on to open a more detailed page, that may showcase multiple images, a detailed description, and the ability to add it to a cart. 

The cart system will showcase everything you've added to the cart so far, a total of how much your order has accumulated. As well as give you the option to edit existing products, delete them or check out. 

The checkout system will be integrated with Stripe, and allow the user to purchase items that have been first added to the cart. As this is a small beach town the client doesn't wish to use post, so all users will be notified that their product is ready for pick-up via a mailing system. 


#### Mailing system

This project will implement a mailer system that automatically e-mails users after certain actions are complete. The most important action that is performed is sending users receipts as well as confirmation when products are purchased. This should be automatic and customizable so that each user gets a unique experience with the email. Users are also able to subscribe to an ongoing email newsletter that gives them updates on Little Parliament and Our Shop. 

#### Admin panel

As the Client wants to make this website live and isn't tech-savvy enough to understand how to implement code, she wants to be able to make changes and update the website. This is why an admin panel will be added, a secret area that lets her input sign-in details which then takes her to an area that lets her perform certain actions on the website with ease. Actions such as:

- Products
      - Add / Remove / Edit Products
      - Adjust option to make certain products "Featured"
      - Maybe the ability to put items on sale (prob just for products)?
      - Stock tracking
- Menu
      - Ability to add/remove/edit products from the menu (different table to the products she sells)
      - Same deal about featured
      - Set item to sold out
- Newsletter [ Enabled / Disabled ]
      - Mailing list table
      - Some sort of an option to unsubscribe from the mailing list

These actions will be shown on an easy-to-understand UI dashboard that lets her make the changes live to the site. 

#### Stay-up-to-date 

There will be a stay up-to-date section on this website that will portray recent news to the viewers of this website. First and foremost this will be seen with an Instagram integration which will display the 5-6 most recent posts made by Little Parliament. There will also be links on this section that will take the user to the respective social media accounts. This will also be where users can subscribe to the ongoing email newsletter. 

### Additional nice-to-have features

#### Table ordering

A feature that would be nice to have is the ability to get to the menu page from an external QR code. Once there it would be great if the user could order food from the menu, pay for it through the website and then have the food delivered to the kitchen through the pre-existing till system.

This would simplify the process of taking orders and handling payments but would be entirely dependent on the pre-existing systems within Little Parliament.

#### Reserving Items

Another nice to have feature for the Our Shop section of this website is the ability to put an item on hold. You've browsed the products and really want to pick something up but know you won't be able to get into the shop for another few days. This feature will allow users to have peace of mind that the product they have their eye on won't be sold out by the next time they swing by. 

## Target audience

## Tech stack

### Front end 
- React
  - Redux

### Back end 
- Rails
  - Sorbet (Type enforment)
  - ActiveRecord (ORM)
  - Devise + Bcrypt (for secure admin access)
  - Cancancan (Roles and permissions)
- PostgreSQL
- AWS S3  (Data storage)
- Testing?

### Third-party
- Stripe
- Heroku 
- AWS S3

##	Dataflow Diagram

![Admin DFD](https://user-images.githubusercontent.com/80095448/151127725-1cf0736b-4aa1-4123-b706-15b8cf3020dc.png)

![Customer DFD](https://user-images.githubusercontent.com/80095448/151127803-7ebe915c-1d0e-48c5-8182-6d272b5d7923.png)



##	Application Architecture Diagram



##	User Stories



##	Wireframes

### Sitemap

### Landing Page   

### About us page

### Menu Page

### Menu Item Detail page

### Products page

### Products Detail page

### Admin Panel Page

##	Screenshots of Project Management


