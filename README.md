# Project Proposal 


### 1.What goal will your website be designed to achieve?

For users to learn more about the detail and ingredients in makeup products. The website can maybe also have access for the users to see where the products a located in store or a current price. 

### 2.What kind of users will visit your site? In other words, what is the demographic of your users?**

Ages from teen to older. Also, users with allergy or sensitive skin types that are looking for specific products. 

### 3.What data do you plan on using? You may have not picked your actual API yet, which is fine just outline what kind of data you would  like it to contain.

There are a couple of APIs, which contain makeup products that lists the description and part of the ingredients list. I'm planning on separating keywords in the descriptions for the user to filter and navigate. There are also shopping APIs, which might contain more information of where to locate the products if possible. There are also some open data APIs, which have some information on cosmetic chemicals listings, which can provide more detail to some of the makeup products. http://makeup-api.herokuapp.com/, https://data.gov/

### 4.In brief, outline your approach to creating your project (knowing that you may not know everything in advance and that these details might change later). Answer questions like the ones below, but feel free to add more information:

#### a.  What does your database schema look like? 

* Makeup: ID, Product, Ingredients, Image, Description

* Ingredients: ID, name, description
* Brand: ID, name
* User: ID, username, password, first_name, last_name
* Favorites: ID, makeupID (FK), ingredientID (FK)

#### b.  What kinds of issues might you run into with your API?

Ingredients or descriptions for some of the makeup products might not populate since there might not be enough information. There may be many unique ingredients as well, which may be more extensive in data searching. Some of the APIs are limited when including makeup, but have more in food items. Also, the API might be down, depending on how well the API can be accessed. 

#### c. Is there any sensitive information you need to secure?

If there is a user profile added, along with a username and password, then this will need to be secured. This would need to be hidden in the website and from other users. 

#### d. What functionality will your app include?

* The user will be able to navigate through different makeup products and search through ingredients if possible. 
* The app will also include a filtering section where the user can filter by makeup or ingredients for example. 
* If a profile is added to this app, then the user can save the product in their profile. Besides looking at the product, and ingredient,
    
#### e. What will the user flow look like? Login and log out feature to save information or get information?

The user will be able to navigate through the homepage and to category filters for the makeup products. If there is a profile, the user will be able to save the products to their profile. The login and logout feature will also be implemented. 

#### f. What features make your site more than CRUD? Do you have any stretch goals?

In the profile, there can be a suggestion product that populates. Also, a small quiz feature for recommendation. There can be a autofill feature or product horizontal scrolling feature, which might also populate the image if it's available. There might be reviews,feedback or ratings from others users or recommended features. 
