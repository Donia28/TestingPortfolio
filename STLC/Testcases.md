### Test case design**
**1. Age Restriction for alcohol**
Test Design Techniques: BVA, EP, Error guessing
1. **Boundary Value Analysis**:
    - **Test Case**: Verify 
        - **Input**: Date of Birth = (Today - 16 years)
        - **Expected Outcome**: Account creation successful.
**2. Filtering by pricing**
Test Design: Decision table, Error guessing

**3. 10% Discount on total of 100 Euros or more**
Test Design: BVA, EP, Error guessing


### Test Cases:
1. **Boundary Value Analysis**:
    - **Test Case**: Verify account creation for a user exactly 16 years old.
        - **Input**: Date of Birth = (Today - 16 years)
        - **Expected Outcome**: Account creation successful.
2. **Boundary Value Analysis**:
    - **Test Case**: Verify account creation for a user just below 16 years old.
        - **Input**: Date of Birth = (Today - 16 years + 1 day)
        - **Expected Outcome**: Error message "You must be at least 16 years old to create an account."
3. **Equivalence Partitioning**:
    - **Test Case**: Verify account creation for users below the age of 16.
        - **Input**: Date of Birth = (Today - 15 years)
        - **Expected Outcome**: Error message displayed.
4. **Equivalence Partitioning**:
    - **Test Case**: Verify account creation for users above the age of 16.
        - **Input**: Date of Birth = (Today - 17 years)
        - **Expected Outcome**: Account creation successful.
5. **Error Guessing**:
    - **Test Case**: Verify system behavior when Date of Birth is not entered.
        - **Input**: Date of Birth field left empty.
        - **Expected Outcome**: Error message "Date of Birth is required."
6. **Error Guessing**:
    - **Test Case**: Verify system behavior when an invalid Date of Birth format is entered.
        - **Input**: Date of Birth = "13/25/2008"
        - **Expected Outcome**: Error message "Invalid Date of Birth format. Please use MM/DD/YYYY."

