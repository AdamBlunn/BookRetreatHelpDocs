# BookRetreatHelpDocs
The Help documentation for my Honours Project

# Administrator Functions
Below are the instructions on how to operate the six functions on the administrator dashboard. For a more technical breakdown on how these functions work, please refer to Chapter 3 of the Honours Project Report. 

## Add Books
This function Adds new books to the online database. Please note that this will only add them to the back end. Front-end webpages must still be added manually for each item. 

To add a book, carry out the following steps:
1. Press the add book button at the bottom of the add book card.
2. Enter ISBN
3. Enter book title
4. Enter author's name
5. Select a genre from the dropdown menu
6. Enter the length of the book
7. Enter the price of the book
8. Select the book's format from the dropdown menu
9. Select the book's type from the dropdown menu
10. Select the book's publication date by clicking on the field, selecting a date on the calendar and clicking off the calendar.
11. Enter the book's publisher.
12. Enter the amount of books the store has in stock.
13. Enter the Vue Router Link to the book's product component.
14. Enter the book's description
15. Upload an image of the book's cover.

### Vue Router Link
The vue router link is the route to the product's page and should also be stored in the index.js file of vue router (src/router/index.js). The format for these is /product/BookTitle. 
Note: if the title is too long then it should be abbreviated (e.g. The Wicked + The Divine: Year 1 becomes /product/WicDivY1 )
## Add Stock to Existing Book
1. Enter the book's ISBN.
2. Press the search button.
3. On the form that appears enter the new stock number that you would like to be added to the old stock number.
4. Press the "Update Record" button

## Edit Existing Book
Edit the details of a book that already exists within the database.

To use this function, do the following:
1. Enter the Book's ISBN
2. press the "Search" button
3. On the form that appears, enter book title
4. Enter author's name
5. Select a genre from the dropdown menu
6. Enter the length of the book
7. Enter the price of the book
8. Select the book's format from the dropdown menu
9. Select the book's type from the dropdown menu
10. Select the book's publication date by clicking on the field, selecting a date on the calendar and clicking off the calendar.
11. Enter the book's publisher.
12. Enter the amount of books the store has in stock.
13. Enter the Vue Router Link to the book's product component.
14. Enter the book's description
15. Upload an image of the book's cover.

Note: as the ISBN is the book's identifier it is not possible to change this once added. If the ISBN needs updated, the book must be deleted and recreated.

## Apply Discount to Book
Apply a discount of either 25% or 50% to a book, changing it's sale price. 

To use this function, do the following:
1. Enter the Book's ISBN
2. press the "Search" button
3. Select a discount from the dropdown menu
4. Press the continue button.
## Delete Book
Permenantly Delete a book from the database. Only to be done if absolutely neccesary. Please note that the book's page will still need to be manually wiped.

To use this function, do the following:
1. Enter the Book's ISBN
2. press the "Search" button
3. Confirm the deletion on the prompt that appears.

**This action is permenent, please ensure that the book must be deleted before carrying out this action**

## Make User an Administrator
Create a new Administrator user, giving them access to the Adminisrator Dashboard. The user must already have an account with the website.

To use this function, do the following:
1. Enter an email address that is tied to an account with the website.
2. Click Yes on the confirmation prompt that appears.
