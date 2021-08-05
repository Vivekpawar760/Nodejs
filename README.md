# VisionPractical

Application
  Create an Application in Angular 8+& Nodejs. You can use any database for store data (Mongo dB, MySQL, MS SQL)

1. Create the registration form with the following fields and proper validations.
  a. Student Name – TextBox -- Required
  b. Address – Text Area – Required – Max 100 characters
  c. Class – Dropdown – Required
  d. Age – text box –Required – should be number only
  e. Hobbies -- Checkbox – At least one should be selected.
  f. Gender – Radio Button – Required
  g. State – Dropdown –Required – Bind from the DB.
  h. City – Dropdown – Required – Bind from the DB based on the selected state.
  i. Pincode – Textbox—required – max length 6
  j. Photo – FileUpload – Required.
2. Create a database based on the above field and give proper relationship.
3. Save the student data from the above form into the student table in DB.
4. Display the inserted students records in a table including the uploaded photo.
5. Add Edit and Delete button in the above gird.
6. Perform edit and delete based on the clicked button
7. Add a confirmation before delete.
8. Add searching, sorting and pagination functionality in the gird.
9. Add an “Export” button which will export all the data in table into an excel sheet.


step to follow before run application

1) import database on phpmyadmin and name of database should be nodejs
2) node API start on port: 8000
3) first run command "npm install" on Angular Side
