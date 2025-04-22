# Answer3.sql
1. *Create Table:*
   ```sql
M   CREATE TABLE student ( id INT PRIMARY KEY,
       fullName VARCHAR(100),
       age INT
   );
   ```

2. *Insert Records:*
   ```sql
   INSERT INTO student (id, fullName, age)
   VALUES
   (1, 'John Doe', 22),
   (2, 'Jane Smith', 20),
   (3, 'Emily Davis', 21);
   ```

3. *Update Age:*
   ```sql
   UPDATE student
   SET age = 20
   WHERE id = 2;
   ```