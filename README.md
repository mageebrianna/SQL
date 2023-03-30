# SQL
SQL

/** Clothing:
Long Sleeve Tee (11)
Short Sleeve Tee (2)
Shorts (6)
Yoga Pants (16)
Biker Shorts (12)
Tank Top (18)
Sweatshirt (21)
Crewneck (17)
Basketball Shorts (24)
Graphic Tee (15)
Shaw (19)
Zipper Jacket (20)
Pajama Set (5)
Winter Coat (7)
Overalls (22)
**/

CREATE TABLE clothing (id INTEGER PRIMARY KEY, name TEXT , quantity INTEGER , onesize INTEGER , plussize INTEGER, price INTEGER);

INSERT INTO clothing VALUES (1, "Long Sleeve Tee" , 11 , 4 , 7 , 15.95);
INSERT INTO clothing VALUES (2, "Short Sleeve Tee" , 2 , 0 , 2 , 12.25);
INSERT INTO clothing VALUES (3, "Shorts" , 6 , 2 , 4 , 19.85);
INSERT INTO clothing VALUES (4, "Yoga Pants" , 16 , 6 , 10 , 12.75);
INSERT INTO clothing VALUES (5, "Biker Shorts" , 12, 8 , 4 , 11.75 );
INSERT INTO clothing VALUES (6, "Tank Top" , 18 , 10 , 8 , 8.00);
INSERT INTO clothing VALUES (7, "Sweatshirt" , 21, 6 , 15 , 20.00);
INSERT INTO clothing VALUES (8, "Crewneck" , 17 , 12 , 5 , 21.37);
INSERT INTO clothing VALUES (9, "Basketball Shorts" , 24 , 15 , 9 , 13.50);
INSERT INTO clothing VALUES (10, "Graphic Tees" , 15 , 5 , 10 , 15.25);
INSERT INTO clothing VALUES (11, "Shaw" , 19 , 8 , 11 , 17.56);
INSERT INTO clothing VALUES (12,"Zipper Jacket" , 20 , 10 , 10 , 18.98);
INSERT INTO clothing VALUES (13, "Pajama set" , 5 , 5 , 0 , 16.83);
INSERT INTO clothing VALUES (14, "Winter Coat" , 7 , 5 , 2 , 49.99);
INSERT INTO clothing VALUES (15, "Overalls" , 22 , 10 , 12 , 36.98);

SELECT * FROM clothing;
SELECT MAX(price) from clothing;
