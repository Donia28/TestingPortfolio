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


### Scenario 2: User Age just below 18
As a user of GroceryMate, I am not able to access the alcohol section when I am just below 18 years old.
| Step # | Action                           | Expected Outcome                                                                    | Actual Result                                                                         | OK/NOK |
|--------|----------------------------------|-------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------|--------|
| 1      | Go to GroceryMate                | Home page appears                                                                   | Home page appears                                                                     | OK     |
| 2      | Select 'Shop' Page               | Age Verification appears                                                            | Age Verification appears                                                              | OK     |
| 3      | Fill 10-11-2008 as Date of Birth | The message "You are underage. You can still browse the site, but you will not be able to view the alcohol products."appears and tthe alcohol section is empty  | The message "You are underage. You can still browse the site, but you will not be able to view the alcohol products."appears and tthe alcohol section is empty | OK     |

<img width="470" height="125" alt="image" src="https://github.com/user-attachments/assets/2196a18f-8f9b-4c8e-8c57-252e52acb601" />
<img width="548" height="532" alt="image" src="https://github.com/user-attachments/assets/1bf46ef8-1951-4b32-8cb3-fe066d61a4ac" />
