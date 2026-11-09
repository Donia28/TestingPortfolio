### Title: Test report for GroceryMate Website Tests ###
**Reporter: Dounya Chichah**

**Date: 08.11.2026**

**Test Object: https://grocerymate.masterschool.com/store**

**Environment: Windows 11, Chrome Browser, Safari, Microsoft Edge**

### Scenario 1: User Age exactly 18

As a user of GroceryMate, I am able to access the alcohol section when I am exactly 18 years old.
| Step # | Action                           | Expected Outcome                                                                    | Actual Result                                                                         | OK/NOK |
|--------|----------------------------------|-------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------|--------|
| 1      | Go to GroceryMate                | Home page appears                                                                   | Home page appears                                                                     | OK     |
| 2      | Select 'Shop' Page               | Age Verification appears                                                            | Age Verification appears                                                              | OK     |
| 3      | Fill 08-11-2008 as Date of Birth | The message "You are of age. You can now view all products, even alcohol products."appears and the user can access the alcohol section  | The message "You are of age. You can now view all products, even alcohol products." appears and the user can access the alcohol section  | OK     |
                                           
<img width="653" height="342" alt="image" src="https://github.com/user-attachments/assets/4f76c9ee-2fcf-4853-a597-16abd01f8e08" />
<img width="362" height="81" alt="image" src="https://github.com/user-attachments/assets/2a8aa335-6556-41b6-bdf0-7f85f8fd53d5" />


### Scenario 2: User Age 

As a user of GroceryMate, I am not able to sign up when I register with an invalid Date of Birth.

| Step# | Action                               | Expected outcome                                           | OK/NOK | URL                                                | Link to issue               |
|-------|--------------------------------------|------------------------------------------------------------|--------|----------------------------------------------------|-----------------------------|
| 1     | Go to login page FindMate            | Login page appears                                         | OK     | [https://findmate.masterschool.com/](https://findmate.masterschool.com/)     |                             |
| 2     | Click on Sign up                     | You are directed to the sign up page                       | OK     | /auth                                              |                             |
| 3a    | Fill in 'InputValidationTest' as username |                                                            |        |                                                    |                             |
| 3b    | Fill 19-08-1820 as Date of Birth     |                                                            |        |                                                    |                             |
| 3c    | Write 'This is my Bio'               |                                                            |        |                                                    |                             |
| 3d    | Write karin@faculty.masterschool.com as e-mail address |                                                            |        |                                                    |                             |
| 3e    | Password is 'RandomPassword1'        |                                                            |        |                                                    |                             |
| 4     | Click sign up                        | You cannot be 200 years old, so I expect an error message  | NOK    |                                                    | [https://github.com/software-engineering-ms/example-portfolio/issues/2](https://github.com/software-engineering-ms/example-portfolio/issues/2) |

