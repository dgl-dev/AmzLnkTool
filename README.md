# AmzLnkTool
Tool to take in Amazon links with text description and format into css-grid
## Background
Dunaway Group LLC markets books and associated products through Amazon. 
Websites include JeremiahPress.com. Pages of product links must
be created and maintained.  

The process is :
  - Find a book
  - Get the link
  - Get the description
  - Add to css-grid page template   - Title, Author, Desc, link

Associated with this process is adding new items to the Our Books 
and Books We've Found sections and to the weekly blog  
## Design
This project will be a Flask app
  - Pages
    - Select file holding a set of links - books by Victor Davis Hanson
    - Display those links in 4 x n grid where 4 is number of elements for 
    each link n is number of links
The process of getting the link, ... is manual
  - Do the search (saved)
  - CaP the Title, Author, Blurb, link into a flask page
  - The input will be saved as  Sqlite3 db

