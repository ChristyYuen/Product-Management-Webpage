# Product Management Webpage

## Description
This project is a web-based product management system that allows users to view a list of products, delete individual items, and sort the products by cost. The delete functionality is secured using signed URLs, ensuring that only authorized deletions occur. The project also implements sortable columns for the Product Cost field, providing an interactive user experience with proper icon toggling to reflect the sorting state.

## Features

1. **Delete Button with Icon**
   - Each product row has a **Delete** button with an appropriate delete icon.
   - When the **Delete** button is clicked, only the corresponding product item is deleted.

2. **Signed Delete URL**
   - The delete action is secured using a **signed URL**, preventing unauthorized deletions.
   - Attempts to tamper with the signature by manually modifying the URL, or copying the URL to a different browser, result in rejection.

3. **Product Cost Column**
   - Initially, the **Product Cost** column is unsorted.
   - Clicking on the **Product Cost** column header toggles the sorting state between ascending and descending.
   - The sorting icon reflects the current sorting status, updating accordingly.

## Instructions to Run

1. Clone the repository:
      ```bash 
      git clone https://github.com/your-username/Product-Management-Webpage.git

2. Ensure you have the necessary dependencies and server environment set up.

3. Run the application on your local server, and access it in your browser.

4. Interact with the product list by deleting items and sorting the Product Cost column.


## What is py4web?
**py4web** is a modern web framework designed to simplify web application development with Python. It focuses on productivity, providing an easy setup and out-of-the-box features like database integration, authentication, form handling, and role-based access control. A successor to web2py, py4web maintains the same simplicity and robustness but has been optimized for modern web standards. Its lightweight design allows for the rapid creation of secure, scalable, and maintainable web applications. Though this project doesn't directly use py4web, it could be a good option for expanding its features.