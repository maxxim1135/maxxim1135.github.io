# maxxim1135.github.io

## Structure

The project consists of 5 folders (but probably we are interested only at 2 of them:

### Pages:
you may find here html core files for static pages


- #### index.html 
    the main one page with a booking "search" engine. You can choose a city, booking dates and desired capacity of an auditorium 

- #### search.html
    the page with results from early mentioned engine. They are structured as a list of result-cards. Each of them contains a photo, city, address, dates, capacity and price/hour values. There's also a booking button to proceed with an order. When scaling to smaller screens, the result-cards structure changes to fit them

- #### orders.html
    after successful booking it is planned to find an order in a list of orders, which is organized as a table. The list contains an order id (which also is a link to a more detailed page), date of booking, city, address and a confirmation status. For smaller screens the list appears as a list of cards, not a table

- #### order1.html
    this is a temporary page just to show how details of an order would look like

- #### account.html 
    users may find or change here their details  

All these files have navigation bar and footer section. Navigation bar contains links to home (index.html), account(account.html),orders (orders.html) and a logout option

- #### auth / login / register.html
    the authorization pages. First of all, you visit auth page where you can choose one of two ways: to login or to register. After that it redirects to login or register either. After successful authorization or registration you are redirect to index.html, where a journey starts 


### Styles:
you may find here scss and compiled css files. Color variables are extracted to variables.scss
Command to compile scss to css (should be executed inside styles folder): 

*sass styles.scss styles.css*

### Resourses:
here are (will be) stored icons, images and so on

### Errors:
the folder contains html error pages just not to clutter the main folder

### Templates:
the folder, where reusable componens will be stored in the future



