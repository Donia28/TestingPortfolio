### Test case design**
**1. Age Restriction for alcohol**
Test Design Techniques: BVA, EP, Error guessing
### Test Cases:
1. **Boundary Value Analysis**:
    - **Test Case**: Verify access to alcohol section for users exactly 18 years old.
        - **Input**: Date of Birth = (Today - 18 years)
        - **Expected Outcome**: Access successful.
2. **Boundary Value Analysis**:
    - **Test Case**: Verify access to alcohol section for users just below 18 years old.
        - **Input**: Date of Birth = (Today - 18 years + 1 day)
        - **Expected Outcome**: Error message "You are underage. You can still browse the site, but you will not be able to view alcohol products."
3. **Equivalence Partitioning**:
    - **Test Case**: Verify access to alcohol section for users below the age of 18.
        - **Input**: Date of Birth = (Today - 17 years)
        - **Expected Outcome**: Error message "You are underage. You can still browse the site, but you will not be able to view alcohol products."
4. **Equivalence Partitioning**:
    - **Test Case**:  Verify access to alcohol section for users above the age of 18.
        - **Input**: Date of Birth = (Today - 17 years)
        - **Expected Outcome**: Access successful.
5. **Error Guessing**:
    - **Test Case**: Verify system behavior when Date of Birth is not entered.
        - **Input**: Date of Birth field left empty.
        - **Expected Outcome**: Error message "Date of Birth is required."
6. **Error Guessing**:
    - **Test Case**: Verify system behavior when entering special characters in the birth section.
        - **Input**: Date of Birth ##-##-####.
        - **Expected Outcome**: Error message "Invalid date of birth"
                  
**2. Product Rating System**
Test Desuígn Techniques: User Case Testing, EP
1. **User Case Testing**:
    - **Test Case**:  Verify that the user cannot rate a product as a guest.
        - **Input**: Rate a product as a guest
        - **Expected Outcome**: The Rating bouton is deactivated (Grey)
2. **Equivalence Partitioning**:
    - **Test Case**:  Verify that the user can change his rate to 3 times
        - **Input**: Rate a product twice
        - **Expected Outcome**: The Rating is changed
3. **Equivalence Partitioning**:
    - **Test Case**:  Verify that the user can change his rate to 3 times
        - **Input**: Rate a product 4 times
        - **Expected Outcome**: The Rating cannot be changed after the 3rd time.
                  
**3. Free shipping for orders above 100 Euro (inclusive)**
Test Design: BVA, EP
### Test Cases:
1. **Boundary Value Analysis**:
    - **Test Case**:  Verify that the free shipping is applied on total of 100.
        - **Input**: Total item of exactly 100 euro
        - **Expected Outcome**: Free shipping is applied and displayed
2. **Boundary Value Analysis**:
    - **Test Case**:  Verify that the free shipping is applied on total of 99.
        - **Input**: Total item of exactly 99 euro
        - **Expected Outcome**: Free shipping is not applied and the shipping costs are added to the total.
1. **Boundary Value Analysis**:
    - **Test Case**:  Verify that the free shipping is applied on total of 200.
        - **Input**: Total item of exactly 200 euro
        - **Expected Outcome**: Free shipping is applied and displayed
