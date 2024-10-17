<!DOCTYPE html>
<html lang="en">
 <head>
  <title>
   A Web Page
  </title>
  <style>
   body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            margin: 0;
            padding: 0;
        }
        .container {
            width: 800px;
            margin: 0 auto;
            background-color: #fff;
            padding: 20px;
            border: 1px solid #ccc;
        }
        .header {
            display: flex;
            align-items: center;
            justify-content: space-between;
            padding: 10px 0;
        }
        .header input[type="text"] {
            width: 300px;
            padding: 5px;
        }
        .header img {
            width: 20px;
            height: 20px;
        }
        .nav {
            display: flex;
            justify-content: space-around;
            padding: 10px 0;
            border-bottom: 1px solid #ccc;
        }
        .nav a {
            text-decoration: none;
            color: #000;
            padding: 5px 10px;
        }
        .content {
            display: flex;
            padding: 20px 0;
        }
        .content img {
            width: 200px;
            height: 200px;
            border: 1px solid #ccc;
            margin-right: 20px;
        }
        .details {
            flex: 1;
        }
        .details p {
            margin: 10px 0;
        }
        .details input[type="text"], .details select {
            width: 100%;
            padding: 5px;
            margin: 5px 0;
            border: 1px solid #ccc;
        }
        .details input[type="checkbox"] {
            margin-right: 10px;
        }
        .details label {
            display: flex;
            align-items: center;
        }
        .details .checkbox-group {
            margin: 10px 0;
        }
        .details .checkbox-group label {
            margin-right: 20px;
        }
        .details .button {
            text-align: center;
            margin-top: 20px;
        }
        .details .button button {
            background-color: #4CAF50;
            color: white;
            padding: 10px 20px;
            border: none;
            cursor: pointer;
        }
  </style>
 </head>
 <body>
   <div class="nav">
    <a href="#">
     Home
    </a>
    <a href="#">
     Register
    </a>
    <a href="#">
     Policy
    </a>
    <a href="#">
     About
    </a>
   </div>
   <div class="content">
    <img src="img/mekbuk.jpeg" width="200"/>
    <div class="details">
     <p>
      Title Here: MacBook Air Pro 3 £566
     </p>
     <p>
      Description: Lorem ipsum dolor sit amet consectetur, adipisicing elit. Vitae quas quisquam minus beatae tempora et saepe quod magni. Distinctio asperiores error eum enim voluptates libero alias facilis. Amet, necessitatibus accusamus!
     </p>
     <p>
      Year: 2023
     </p>
     <p>
      Model: Macbook Air Pro 3
     </p>
     <p>
      Condition: Mint
     </p>
     <p>
      Total Amount: £566
     </p>
     <p>
      Pay to: 123-456-789-0
     </p>
     <p>
      Payment Type:
      <select>
       <option>
        Visa Debit
       </option>
      </select>
     </p>
     <p>
      Account Holder:
      <input type="text" value="Name Here"/>
     </p>
     <p>
      Account No:
      <input type="number" value=""/>
     </p>
     <div class="checkbox-group">
      <label>
       <input checked="" type="checkbox"/>
       Send to Mobile Phone
      </label>
      <label>
       <input checked="" type="checkbox"/>
       Email me copy of transaction
      </label>
     </div>
     <p>
      Send to Mobile Phone:
      <input type="number" value=""/>
     </p>
     <p>
      Send to Email:
      <input type="email" value=""/>
     </p>
     <div class="button">
      <button>
       Pay using QuidLink
      </button>
     </div>
    </div>
   </div>
  </div>
 </body>
</html>
