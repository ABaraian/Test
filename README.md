# CSCI-381-Data-Modeling
Projects for CSCI 381 Data Modeling
Goal For Project:
Create a database for a subscription based movie watching company much like Netflix. The databse should track customers, when they pay their subscription, how they pay, and what movies they watch, employees and where they work, offices and the movie reposities they handle, and the movie repositories, which movies they contain, and what their coverage zone is.

Steps:
1. Keep CUSTOMER, EMPLOYEE, PAYMENT, and MOVIE and delete the rest of the entities
2. Create a descriminator for PAYMENT called PAYMENTTYPE which will allow customers to pay with either credit card, debit card, or check
3. Create OFFICE which will represent decentralized offices that employees can work in, will handle certain customer payments, and will work on a specific repository. The offices can be rented out in different buildings or in the same bulding but on different floors.
4. Create REPOSITORY which will contain certain movies and will be used to stream different movies to different customers depending on their region much in the same way Netdlix does
