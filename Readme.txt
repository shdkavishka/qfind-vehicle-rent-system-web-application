--UOM LIBRARY SYSTEM--

This application contains 4 models
 *Book 
 *Admin
 *Member
 *Borrowing
 
 Used JPA hibernate to create tables.
 
 Each repository is extended from the JpaRepository.
 
 Created a dto classes and mapper classes since the user inputs need to verify befor storing data in the DB.
 
 Added a simple login page and it verify the Librabrain credentials.
 
 For the ui used the datatables library and wrote the js files to add create, update, delete functions.
 
To start the application
mvn spring-boot:run

To create a user
curl -H "Content-Type: application/json" -X POST http://localhost:8080/add-admin -d "{\"username\":\"tom\",\"password\":\"123\"}"

