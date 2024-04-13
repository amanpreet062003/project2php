update.php is similarly working as members.php as it only get open after login.

To set up and run the provided SQL code in phpMyAdmin, follow these steps:

Start XAMPP and Services:

Open XAMPP Control Panel. Start the Apache server and MySQL service by clicking the "Start" button next to their respective names. Access phpMyAdmin:

Open your web browser and go to http://localhost/phpmyadmin/. Create a New Database:

Click on the "Databases" tab in phpMyAdmin. Enter a database name (e.g., university_registration) in the "Create database" field. Click the "Create" button. Run the SQL Code:

Select the newly created database from the left sidebar. Click on the "SQL" tab in the top menu. Paste the provided SQL code into the SQL query box. Click the "Go" button to execute the SQL code. This will create the courses table and insert sample data. Verify the Database:

Go back to the "Databases" tab and select your database from the list. Click on the "Tables" tab to see if the courses table was created successfully.

sql code :- ( CREATE TABLE students ( id int(100) NOT NULL AUTO_INCREMENT, name varchar(100) NOT NULL, email varchar(100) NOT NULL, password varchar(100) NOT NULL, image varchar(100) NOT NULL, PRIMARY KEY (id) ) ENGINE=InnoDB AUTO_INCREMENT=1 DEFAULT CHARSET=utf8mb4

CREATE TABLE IF NOT EXISTS contact_messages ( id INT AUTO_INCREMENT PRIMARY KEY, name VARCHAR(255) NOT NULL, email VARCHAR(255) NOT NULL, message TEXT NOT NULL, created_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP ); CREATE TABLE IF NOT EXISTS courses ( course_id INT AUTO_INCREMENT PRIMARY KEY, course_name VARCHAR(255) NOT NULL, description TEXT NOT NULL, max_capacity INT NOT NULL );

INSERT INTO courses (course_name, description, max_capacity) VALUES ('Introduction to Programming', 'Learn the basics of programming.', 50), ('Web Development', 'Learn to build websites.', 40), ('Database Management', 'Learn about databases.', 30), ('Data Structures and Algorithms', 'Learn advanced programming concepts.', 20);

)


Index.php

![Screenshot from 2024-04-13 13-57-16](https://github.com/amanpreet062003/project2php/assets/146962888/51a2374f-5f99-4504-b2bf-37816fcdaf47)







View couses.php
![Screenshot from 2024-04-13 13-57-27](https://github.com/amanpreet062003/project2php/assets/146962888/88d422a0-29bf-4574-8b8a-89ed91c7bea9)


login.php
![Screenshot from 2024-04-13 13-57-32](https://github.com/amanpreet062003/project2php/assets/146962888/3299044a-8cff-4dc7-aeb6-eb8a668611a8)


registration.php

![Screenshot from 2024-04-13 13-57-30](https://github.com/amanpreet062003/project2php/assets/146962888/6fc24832-b992-4918-a85a-397d1bc59406)


contact.php

![Screenshot from 2024-04-13 13-57-35](https://github.com/amanpreet062003/project2php/assets/146962888/98596c82-198e-45cf-8688-4244ec916219)


aboutus.php

![Screenshot from 2024-04-13 13-57-23](https://github.com/amanpreet062003/project2php/assets/146962888/da860e2e-3932-4184-90f4-989f5cbeaf89)


phpmyadmin

![Screenshot from 2024-04-12 15-50-54](https://github.com/amanpreet062003/project2php/assets/146962888/b319a5b3-fccd-4e33-af86-00dc6dfa9761)
![Screenshot from 2024-04-13 14-24-16](https://github.com/a![Screenshot from 2024-04-13 14-25-15](https://github.com/amanpreet062003/project2php/assets/146962888/e29baac0-fa96-499a-a397-6bc0afbb94bb)
manpreet062003/project2php/assets/146962888/57a90513-1c4c-42bd-b277-744de6bdaf53)


