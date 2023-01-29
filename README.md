# ModusDesign

ModusDesign provides graphic design services. The user can select a graphic design package and make a purchase. Once the design is finished, the user receives the product through their online account.

## Features

# Homepage
    - The homepage features the products using a picture gallery carousel which pauses when the cursor is hovering on top.
    - The user can login, sign up and logout of their account
    - the designer can login and logout of their account
    - the shopping bag in the top right corner indicates the accumulated amount of the products selected
    - the logo in the top left corner returns the user to the homepage whenever it is clicked
    - When scrolling down, the user is presented with the ethos and ease of access links
    - The footer holds social media links and contact information

# Main nav
    - The user can select the product packages in the navigation bar's dropdown menus
    - Each product package has a page with examples and descriptions

# Products
    - once selected, the products are added to the shopping bag

## Deployment

When you create the app, you will need to add two buildpacks from the _Settings_ tab. The ordering is as follows:

1. `heroku/python`
2. `heroku/nodejs`

You must then create a _Config Var_ called `PORT`. Set this to `8000`

If you have credentials, such as in the Love Sandwiches project, you must create another _Config Var_ called `CREDS` and paste the JSON into the value field.

The deployment terminal is set to 80 columns by 24 rows. That means that each line of text needs to be 80 characters or less otherwise it will be wrapped onto a second line.

## Resources

https://learndjango.com/tutorials/django-login-and-logout-tutorial