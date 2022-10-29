 Sporty Shoes - SimpliLearn Phase 3 Assessment

 Technologies Used

 Java : 1.8 
 Spring Boot : 2.7.0 
 Lombok  
 H2  
 JPA 
 Spring Security Starter 
 


 File Structure


src
├── main
│   ├── java
│   │   └── com
       └── api
           └── Phase3_Spring
               ├── SportyShoesApplication.java
            
               ├── controller
               │   ├── Authenticate.java                                                                                                                                    		 └── Product.java
                     └── SearchPurchase.java
                      └── SearchUsers.java

               ├── SpringDao
               │   └── Dao.java                                                                                     ├── model
               │   ├── Product.java
               │   └── Purchase.java
                     └── User.java

│   └── resources
│       └── application.properties
           └── Templates
└── index.html
└── ListPurchase.html
└── ListUser.html
└── Product.html
└── Purchase.html
└── SearchUser.html
└── Welcome.html


└── test
    ├── java
    └── sportyShoeApplicationTest.java`

 Project Structure

This project uses Spring Boot for Model and Controller Implementation
Availaible apis are -
  - /Login
  - /changePW
  - /manageProducts
  - /purchase/PurchaseBycategory

Current Implementation relies simply on String for storing order list.

Also for admin authentication spring-security-starter has been used with credentials saved in `application.properties` file.
