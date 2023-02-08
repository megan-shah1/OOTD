# Sprint 1

## User Stories
- As a **fashion-conscious** individual, I want to be able to sign up for the app and upload images of my clothes so that I can keep track of my wardrobe.
- As a **traveler**, I want to be able to add attributes like location and type to my articles of clothing so that I can easily plan outfits for different destinations.
- As a **student** or **busy professional**, I want to be able to quickly view the options in my closet in an organized manner so that I can easily find what I need to wear for school/work each day.
- As a **creative person**, I want to be able to create outfits digitally and save them for later so that I can experiment with different styles and combinations.
- As a **minimalist**, I want to be able to delete saved outfits that I no longer need or like, so that I can keep my digital closet clean and organized.
- As a **budget-conscious** and environmentally-aware individual, I want to create unique outfit combinations in order to fully utilize my existing closet and reduce unnecessary spending.
- As someone who **often misplaces clothing**, I would like to specify the location of each item on the app to easily identify where my clothes are.

## Issues planned
**Front-end**
- Create a basic navigation bar that displays the following:
  - App name
  - At least two buttons with icons that link to other pages
  - Icon head for the user
- Create a basic closet view
  - Display a static grid of image cards for each clothing type (jeans, shirts, etc.)
  - Add functionality to one image card: The card is clickable and leads to a small gallery of clothes under that type
  - Add routing 
  - Pull data from a mock database (e.g., an array of closet items)

**Back-end**
- Set up Go, Gorm, Gorilla Mux, and all other needed packages
- Create a basic database that can insert user login information (using Postgres))
- Look at steps for how to authenticate user information and set up router 
- User enters information (hardcoded for now) and information will populate in database
- Experiement with different databases, Postgres and MongoDB, and see which one is more conducive to storing our data

## Successfully completed
- A navigation bar was created that featured the app name and buttons
- The basic closet view was added
  -  A static grid of image cards was created for the closet page
  -  Card was clickable and led to a new page on the website
  -  Routing was added to support navigation from one page to the next
- Database was set up using Gorm and Postgres Dialect package, this is hooked up to DBeaver so we will be able to see what information will be added
- Hashed Passwords
- Installed DBeaver
- Developed/Experimented with MongoDB as well, and made workflow with this as well (we will see which one will be easier to use)
  
## Not completed
-  We were unable to add icons to the nav bar due to time constraints + it is a low priority
-  We were unable to create a mock database to display the closet items. This was due to time constraints. 
-  We were unable to connect to the IP address we specified in our code (we are going to office hours for this 2/08)
   - Once we figure this out, we will be able to hook DBeaver and VSCode
