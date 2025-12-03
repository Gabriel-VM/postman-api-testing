# postman-api-testing
📌 Overview
-
This repository contains Postman API testing collections that demonstrate practical skills in API usage, request handling, variables, basic scripting, and validation.

The purpose is to showcase hands-on practice with REST APIs and test automation foundations.

The requests represent manipulations on the catalogue of a library (searching books, adding a book to the catalogue, updating a book status, deleting a book from the catalogue).

-----------------------

🚀 Requirements
-
To run these collections, you will need:

- Postman Desktop App or Postman Web

- Basic understanding of HTTP and REST APIs

---------------------

📥 How to Import the Collection
-

- Option 1 — Drag & Drop

Download the .json collection file from this repository.

Open Postman.

Drag the files into the interface — Postman will auto-import it.

- Option 2 — Manual Import

Open Postman

Click Import

Select Files

Choose the exported .json files

Confirm

---------

▶️ How to Run the Collection
-

After importing...

Select the collection you imported

Set the following collection variable:

- baseUrl = https://library-api.postmanlabs.com

Press Send to execute a request

⚠️ Important: the requests must be sent following top to down order (so you can add a book and create the "id" variable, that will be required by the next requests in the list)

------

🔎 What You Can Test
-

This collection includes:

-  GET, POST, PATCH, DELETE requests
-  Query parameters, request bodies, headers
-  SON responses and status code validation
-  asic scripting in Post-Request and Tests tabs
-  ostman variables for reusability

You can explore each request, modify values, debug behavior, and extend the tests.

------

📌 Notes
-

- ⚠️Collection variables are provided only for demonstration purposes.
  
- ⚠️ The API key included in this collection is provided for public educational use and is not tied to personal or private services.
You can also generate your own through Postman’s training material: https://academy.postman.com/page/students


----

💡 Suggestions
-

Feel free to:

- Duplicate the collection and expand testing
- Add new endpoints
- Combine with Newman to run via CLI and generate reports

------

✨ Author
-

Gabriel Martins
- QA Analyst | API Testing Enthusiast
- 📌 LinkedIn: www.linkedin.com/in/gabrielvillamilmartins/
