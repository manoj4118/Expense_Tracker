


<h2 align="center">Project Title</h2>
<h1 align="center">Expense_Tracker</h1>
<h2 align="left">Technologies Used:</h2>
<h4 align="left">HTML CSS JAVASCRIPT CORE JAVA JDBC SERVLET JSP SQL MYSQL</h4>
<div>
<img align="left" alt="coding" width="500px" height="500px" src="https://cdni.iconscout.com/illustration/premium/thumb/expense-management-4268366-3561009.png">
  
<h3 align="right"><br>
  <br>
  <br>
  <br>
   <br>
  <br>
  <br>
Expense Tracker simplify your personal reimbursement management
Expense Tracker is used by user's to record their daily routine expenses in a digital and hassle-free way as opposed to the conventional manual documentation of expenses</h3>
</div>
  <br>
  <br>
  <br>
    <br>
  <br>
  <br>
<br>

<h2 align="center">How to Install and Run the Project</h2>
<h3 align="center">1)Extract the Zip File:</h3>
<p align="center">Extract the contents of the zip file to a directory on your system.</p>
<br>

<h3 align="center"> 2)Set Up Mysql: </h3>
<p align="center"> Ensure that you have MySQL installed on your system.</p>
<p align="center"> Start the MySQL server if it's not already running.</p>

<h3 align="center"> 3)Connect to MySQL: </h3>
<p align="center"> Use a MySQL client like MySQL Workbench.</p>

<h3 align="center"> 4)Create a Database: </h3>
<p align="center">Create a new database that will be used by project.The name of DB is expensetracker51</p>

<h3 align="center"> 4)Create a Tables: </h3>
<br>
<h3 align="center">Table Name:user </h3>
<table align="center">
  <tr>
  <th>userId (pk),(AI)</th>
    <th>username</th>
    <th>fullname</th>
    <th>email</th>
    <th>mobile</th>
    <th>password</th>
    </tr>
</table>
<br>
<h3 align="center">Table Name:contactus </h3>
<table align="center">
  <tr>
  <th>sno (pk),(AI)</th>
    <th>username</th>
     <th>email</th>
    <th>comment</th>
    </tr>
</table>
<br>
<h3 align="center">Table Name:expenses </h3>
<table align="center">
  <tr>
  <th>expensesId (pk),(AI)</th>
    <th>amount</th>
     <th>category</th>
    <th>description</th>
    <th>date</th>
    <th>userId (FK)</th>
    </tr>
</table>

<br>
<h3 align="center">Table Name:sendexpenses </h3>
<table align="center">
  <tr>
  <th>id (pk),(AI)</th>
    <th>username</th>
     <th>email</th>
      <th>userId (FK)</th>
    </tr>
</table>








