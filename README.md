<!DOCTYPE html>
<html>
<body>
<h2 align="center">🛠 Technologies and Tools 🛠</h2>
  
<h1>PLANT PATHOLOGY</h1>

<p>PLANT PATHOLOGY</p>

<h2>Main Features</h2>

<h3>Authentication and Authorization</h3>

<ul>
    <li>Integrated authentication and authorization using Identity Framework and JSON Web Tokens (JWT) for security.</li>
    <li>User account management with registration and login capabilities.</li>
</ul>

<h3>User Role Management</h3>

<ul>
    <li>Implements role-based authorization with two main roles: "User" and "Admin."</li>
</ul>

<h3>Book Management (Books)</h3>

<ul>
    <li>Provides API for basic operations on book information, including create, update, list, view details, and delete. These operations require "Admin" role permissions.</li>
</ul>

<h3>Auto-Mapping with AutoMapper</h3>

<ul>
    <li>Utilizes the AutoMapper library to map between Data Transfer Object (DTO) objects and database objects.</li>
</ul>

<h3>Repository</h3>

<ul>
    <li>Creates a repository (IBookRepository) to abstract database operations.</li>
</ul>

<h3>Customized Swagger</h3>

<ul>
    <li>Integrates Swagger to automatically generate API documentation and provide a user-friendly interface for API testing.</li>
</ul>

<h3>Display Roles on Swagger UI</h3>

<ul>
    <li>Customizes the Swagger interface to display the roles of logged-in users.</li>
</ul>

<h3>Error Handling</h3>

<ul>
    <li>Customizes the API to provide informative error messages when users attempt unauthorized actions due to permissions.</li>
</ul>
    
</body>
</html>
