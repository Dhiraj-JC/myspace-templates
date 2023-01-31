MySpace

1. login
2. SignUp
3. Dashboard
4. DashboardContent
5. Products
6. Product
7. CreateProduct
8. UpdateProduct
9. NotFound


DB: 
Batch : 
API : 









Login Screen
	=> UserName
	=> Password

SignUp screen
	=> Username
	=> password
	=> Confirm password

Product screen
	=> Product Name
	=> Product Description
	=> Product Quantity
	=> Product Price
	
	
	
--------------------------------------------------

Backend :
Project creation
DB creation
install dependencies
Model creation
connect to DB
implement apis
integration JWT token
Middleware to validate

Frontend :
Project creation
Install Dependencies
Boostrap integration
Component Creation
Register for routing
State implementation
API integration
Route Protection

--------------------------------------------

  
Frontend: 

npm i axios bootstrap jwt-decode react-router-dom --save
axios
bootstrap
jwt-decode
react-router-dom

Backend: 
npm i bcrypt cors dotenv express jsonwebtoken mongoose nodemon --save

bcrypt
cors
dotenv
express
jsonwebtoken
mongoose
nodemon

-----------------------------------------------------

const emailPattern = /^(([^<>()[\]\.,;:\s@\"]+(\.[^<>()[\]\.,;:\s@\"]+)*)|(\".+\"))@(([^<>()[\]\.,;:\s@\"]+\.)+[^<>()[\]\.,;:\s@\"]{2,})$/i;
  const passwordPattern = /^(?=.*[a-z])(?=.*[A-Z])(?=.*\d)(?=.*[@$!%*?&])[A-Za-z\d@$!%*?&]{8,10}$/;