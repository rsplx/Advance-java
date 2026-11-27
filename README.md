# Advance-java
in rayspractice there inseert update and basic use shown

mysql> select * from mark where physics = 34 and chemistry = 34 and maths = 34;
Empty set (0.00 sec)                                                                 = "who have passed in boundary passing mark is 34"

mysql> select * from mark where physics  <= 33 and chemistry <=33 and maths <=33 ;
+--------+-------+---------+-----------+-------+
| rollno | name  | physics | chemistry | maths |
+--------+-------+---------+-----------+-------+
|     10 | vedik |      20 |        25 |    33 |
+--------+-------+---------+-----------+-------+
1 row in set (0.00 sec)                                                              = "who have less then 34 they have failed"

mysql> select * from mark where physics  >= 80 and chemistry >=80 and maths >=80 ;
+--------+---------+---------+-----------+-------+
| rollno | name    | physics | chemistry | maths |
+--------+---------+---------+-----------+-------+
|      2 | durgesh |      88 |        90 |    82 |
+--------+---------+---------+-----------+-------+
1 row in set (0.00 sec)                                                                + " who has more then 80 marks in all subject he is topper"

mysql>
