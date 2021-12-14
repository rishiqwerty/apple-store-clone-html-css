# Ecommerce Website

Apple store clone website(HTML/ CSS)

# Common elements

Header is common in every page.
- Grid is use for creating the layout of header, with 3 blocks in a row.
- Now since nav is disappearing and sidebar button is appearing in mobile layout I am using display: none property for removing the nav.

## Home Page

- Home is divided into 3 sections. Each sections contain image, text and button icons.
- Last section contains two divs.
- At the end we have the footer.
- Nav tag contains all the links to different product category, this section disappears in mobile layout.
## Product List page
- This page first section has image representing the product category.
- Second section is a grid which contains all the products.

## Single Item Page

- This page contains the detail of a product. In desktop mode the image is moved to the left and all the description and buttons moved to the right.
- In mobile, description section will be moved to the bottom.
- Also the Add to cart button will be fixed at the bottom.

## Cart Page

- This page list all the items with its price, size and quantity.
- In mobile layout the first row of one product contains Product image, product name and remove button. To do that I used grid-column allow product-name and product-image take up extra grids and hence move all the other items to the bottom. Also I used order to to rearrange the items.
- Again the check-out button is made fixed at the bottom.

## Checkout page

- This page is divided into Account Information and Payment Method. I had used flex to arrange them vertically/horizantally based on device
- Account section contains input and select tags for data input. State and Zip field is kept in a single div and is arranged using flex. 
- Similarly In payment section Expiry section is also using flex.