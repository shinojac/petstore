###API Testing for Swagger endpoints:

The project has Postman collection of API tests to be used for 2 swagger endpoints mentioned in Petstore
-  PET  
-  USER 

##### Features :
Project contains test cases for follwing endpoints

*Pet*
1. Add Pet to store
2. Get Pet info by ID
3. Get List Pets status - Available
4. Pets available-Pending Status
5. Pets Available - Sold Status
6. Get List of Pets Invalid Status
7. Get Pet Info by ID Not found
8. Update Pet details
9. Update Pet name and status
10. Upload Image
11. Delete Pet

*User*
1. Create User 
2. Get User Name
3. Update User details
4. Delete User

###### Prerequisites to run the test
- A server environment (e.g., Linux, Ubuntu)
- Git (to checkout/cone code in branch  `feature/Shino-CBATest` )
- Postman (or a similar API development tool for testing)

##### How to run:
1. Open Postman.
2. Impost the collection `Shino-CBATest`
3. Select the collection `Shino-CBATest`
		Note: For the test Pets>>Upload image, Select an Image in the request body for the test before running.
4. Click the "Run" button.
5. Configure the run settings if needed. (Default settings recommended)
6. Start the run.
7. Review the results.

Please feel free to reach out if you have any questions or encounter any issues during the setup process.

##### Validations
Validations are added to check the responses for each endpoints and to check the schema.
Certain tests need an input file (jpeg, png..). Test may show failed otherwise.

##### References : 
###### Pet endpoint: https://petstore.swagger.io/#/pet
###### User endpoint: https://petstore.swagger.io/#/user
