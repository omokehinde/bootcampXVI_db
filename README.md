# bootcampXVI_db

This database shows the user in an online store app. 
The user table shows all user id, customer_id, staff_id, name, email.
the customer table contains customer id, address, phone number and SSN
The staff table contains the staff id, address, phoneNumber, accountNumber and SSN

INSERT INTO user VALUES(NULL, "Kenny", "black@me.com");
INSERT INTO user VALUES(NULL, "Cythnia", "cythian@me.com");

INSERT INTO customer VALUES(NULL, "42, abdere, lagos, NG", "080056686877", "KN345678912");
INSERT INTO user VALUES(NULL, "1, kenny street, LG, NG", "09067784455", "00223765401", "NK345600912");

SELECT *FROM user;
SELECT *FROM customer;
SELECT *FROM staff;

DELETE FROM user WHERE id = 2 AND staff id = 6;
