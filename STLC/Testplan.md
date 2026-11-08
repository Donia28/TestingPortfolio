# **Test Plan for A Grocery shopping website**

## **1. Analyze the Product**

### **Objective**
The primary objective of the product is to allow costumers to browse, select and purshase groceries online easily, conveniently and surely without neewding to visit a physical supermarkt.

### **User Base**
The website is designed to be accessible to individuals of all age groups. All users can browse and purchase regular grocery products. However, access to and purchase of alcoholic beverages are strictly restricted to individuals aged 18 and above.

### **Hardware and Software Specifications**

- **Hardware Requirements:**
    - Devices: PCs, laptops, smartphones, tablets
    - Specifications: Standard configurations for Android and iOS devices, desktops with minimum 4GB RAM, 2GHz processor
- **Software Requirements:**
    - Operating Systems: Windows, macOS, Android, iOS
    - Browsers: Chrome, Firefox, Safari, Edge
    - Dependencies: Backend services, third-party ad services, payment gateways

### **Product Functionality**

The product allows users to:

-  Register and log in
-  Browse in all the grocery sections (Except alcohol section for users under 18)
-  Filter by pricing
-  Place their favourite items into "Favourites"
-  Register and login functionality
-  Searching for products, sorting on price, categories of products
-  Add products to favorites
-  Add products to basket
-  Check-out process: billing and sending information in a form, choose payment method. Calculation of costs (calculate total price)
  
## **2. Design the Test Strategy**

### **Scope of Testing**

- **In Scope:**
    - Age restriction for alcohol products
    - Filter items by pricing
    - Add and remove items to/from the cart
    - Pay with Card
    - Product Rating System
    - Shipping cost change
       
- **Out of Scope:**
    - Backend database operations not affecting the user interface
    - Delivery services

### **Type of Testing**

- Functional Testing
- Regression Testing
- Performance Testing
- Usability Testing

### **Risks and Issues**

- **Delays in Testing**
    - Mitigation: Implement a buffer period in the schedule.
- **Lack of test data**
    - Mitigation: Create mock data sets for testing purposes.

### **Test Logistics**

- **Dounya Chichah** - Test Manager
- **Harry Down** - QA Engineer (Functional and Regression Testing)
- **Alex Johnson** - QA Engineer (Performance and Security Testing)
- **Sasha Brown** - QA Engineer (Usability Testing)
- **Maria Garcia** - End User for UAT

## **3. Define Test Objectives**

### **Objectives**

- **Functionality:** Ensure existing and new functionalities work as intended.
- **GUI:** Verify the graphical user interface for usability and consistency.
- **Performance:** Confirm the system's performance under expected load conditions.
- **Usability:** Assess the user-friendliness of the platform.

### **Expected Outcomes**

- **Functionality:** All features perform correctly according to specifications.
- **GUI:** The interface is intuitive, responsive, and free of defects.
- **Performance:** The platform meets performance benchmarks under load.
- **Usability:** Users can navigate and use the platform easily.

## **4. Define Test Criteria**

### **Suspension Criteria**

- Testing will be suspended if critical defects are found that block further testing.
- Lack of necessary resources or test environment failures.

### **Exit Criteria**

- All planned tests have been executed.
- Run Rate: At least 100% of all test cases have been executed.
- Pass Rate: At least 90% of executed test cases have passed.
- All critical and high-priority defects have been resolved and closed.
- No severity 1 or severity 2 defects are open.
- Performance metrics meet the defined standards.
- User acceptance testing has been completed, and sign-off has been obtained.

## **5. Resource Planning**

- **Human Resources:** QA team, development team, end users for UAT
- **Hardware:** PCs, laptops, smartphones, tablets
- **Software:** Browsers (Chrome, Firefox, Safari, Edge), operating systems (Windows, macOS, Android, iOS)
- **Infrastructure:** Test environments, automation tools, performance testing tools

## **6. Plan Test Environment**

- **Test Environments:** Real devices installed with real browsers and operating systems to simulate user conditions.
- **Environments:** Development (DEV), Testing (TEST), Acceptance (ACC)

## **7. Schedule and Estimation**

| Activity | Start Date | End Date | Environment | Responsible Person | Estimated Effort |
| --- | --- | --- | --- | --- | --- |
| Test Planning | 01/08/2024 | 05/08/2024 | All | Test Manager | 20 hours |
| Test Case Design | 06/08/2024 | 15/08/2024 | All | QA Team | 40 hours |
| Unit Testing | 16/08/2024 | 25/08/2024 | DEV | Development Team | 60 hours |
| Integration Testing | 26/08/2024 | 30/08/2024 | TEST | QA Team | 30 hours |
| System Testing | 01/09/2024 | 10/09/2024 | TEST | QA Team | 80 hours |
| Regression Testing | 11/09/2024 | 15/09/2024 | TEST | QA Team | 40 hours |
| Performance Testing | 16/09/2024 | 18/09/2024 | TEST | QA Team | 20 hours |
| Security Testing | 19/09/2024 | 21/09/2024 | TEST | QA Team | 20 hours |
| UAT | 22/09/2024 | 30/09/2024 | ACC | End Users | 50 hours |
| Production Release | 01/10/2024 | 01/10/2024 | PROD | DevOps Team | 10 hours |

## **8. Determine Test Deliverables**

Documents/tools that must be created to support testing activities in the project:

- **Test Plan Document**
- **Test Cases and Test Scripts**
- **Test Data**
- **Test Reports**
- **Defect Reports**
- **UAT Sign-off Document**
