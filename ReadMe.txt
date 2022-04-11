-- DATABASE

CREATE DATABASE members;

username: usn
password: 123

-- TABLE

CREATE TABLE Members (
  id INT NOT NULL PRIMARY KEY GENERATED ALWAYS AS IDENTITY (START WITH 202100000, INCREMENT BY 1),
  fname varchar(50),
  lname varchar(50),
  age varchar(5),
  contact varchar(15),
  subscription varchar(20),
  amount varchar(20),
  status varchar(15)

);

--SAMPLE RECORDS

INSERT INTO Members (fname, lname, age, contact, subscription, amount, status) VALUES('Juan','Dela Cruz','24','9295550994','3 months','8400.00','NOT PAID'),
('Michelle','Gracia','21','9194863617','3 months','8400.00','NOT PAID'),
('Lindon','Reyes','22','9220588765','6 months','16500.00','NOT PAID'),
('Kate','Ramos','29','9282966825','12 months','28000.00','NOT PAID'),
('Rian','Mendoza','32','9295955485','1 month','3800.00','NOT PAID'),
('George','Santos','19','9802103155','1 months','3800.00','NOT PAID'),
('Michael','Flores','18','9321434739','6 months','16500.00','NOT PAID'),
('Anne','Gonzales','28','9830852479','3 months','8400.00','NOT PAID'),
('Cristoff','Bautista','35','9293759569','6 months','16500.00','NOT PAID'),
('Marie','Villanueva','29','9074845918','12 months','28000.00','NOT PAID')

