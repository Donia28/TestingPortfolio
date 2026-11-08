## Home work: Requirements
**The assignment**
- Write down which critical questions you can ask as a tester. Think of at least 3 questions per new feature. 
In the next session we will discuss these questions; after this you will receive the details of the requirements.
The software
- You will test a webshop, which can be found here: https://grocerymate.masterschool.com/
**The webshop has the following basic functionalities:**
- Register and login functionality
- Searching for products, sorting on price, categories of products
-	Add products to favorites
-	Add products to basket
-	Check-out process: billing and sending information in a form, choose payment method. Calculation of costs (calculate total price)

**New features**
**1. Product Rating System**
- Requirement: Users should be able to rate products with a 5-star system and have the option to add written feedback.
- Questions:
  - How should be verified that the rate is made by a human and not by a robot? 
  - Can the user rate multiple times?
  -	Can the user modify his rate?
  - Can the user rate as a guest without having an account?
- Detailed Requirement: 
The user must have a valid account to rate a product. They may change their rating for a product no more than three times. Before submitting a rating, they must complete CAPTCHA verification.

**2. Age Verification for Alcoholic Products**
- Requirement: Alcoholic products require age verification. A modal should appear when navigating to the alcoholic products category asking if the user is 18+. Users must input their age before accessing the alcoholic products.
- Questions:
  - How should the age verification be implemented?
  - In what format should the birth date be in?
  - How should be truly verified that the Costumer is really +18? (online ID Verification)
  - What should happen if the customer is underage? Should an error message appear, or should they be automatically redirected to the home page?
- Detailed requirement:
When navigating in the alcoholic section a question about the birthday should appear in this form DD/MM/YY. Then the ID-Verification should be completed. If the costumer is underage (-18) an Error message should appear “You must be 18 or older to purchase alcohol. We’re unable to complete your purchase ”.

**3. Shipping Cost Changes**
- Requirement: Free shipping for orders above a certain amount. Orders below this amount will incur a shipping fee.
- Questions:
  - What is meant by “amount”? The Total price or the number of orders?
  - What should the minimum order amount be to qualify for free shipping?
  - Is this amount included?
- Detailed requirement:
Free shipping on orders totaling €100 or more. Orders of exactly €100 also qualify for free shipping.
