# University-Database-Management
# University Management System

This project is a University Management System built with PostgreSQL. It is designed to handle all the essential tasks of managing a university's data, from storing information to organizing relationships between different entities like students, courses, professors, mentors and departments and even  extra-curricular activitie clubs.

## How the System Works:

1. **Data Entry**:  
   - The system allows you to enter data into multiple tables. For example, you can add new students, courses, faculty members, or departments into the database.  
   - Each type of data has its own table, but they are all connected so that everything is well-organized. Most o fthe table are connected with Department Name .For instance, students can be linked to the courses they are enrolled in, and professors can be assigned to the courses they teach.And there are mentors which are from few proffesors only but there is a lil bit different, they have to monitor activities of a group of student who comes under their mentorship.

2. **Managing Relationships**:  
   - The system manages the relationships between tables. This means you can link data across different categories. For example, the system knows which students are in which courses, which professor is teaching which course, and which department offers those courses and much more.Department Name is the common connection mostly.  

3. **Advanced Features**:  
   - **Cursors**: The system uses cursors to go through data row by row, which is useful when you want to process data in smaller chunks.  
   - **Functions**: Functions are used to handle repetitive tasks, like calculating grades  without writing the same code multiple times.  
   - **Procedures**: Procedures help to execute a series of tasks in a specific order. For example, you can automate the process of changing renrollment number of student.  
   - **Triggers**: These are automatic actions that occur when certain events happen. For instance, if a student drops the admission then his details will be automatically stored in backup-table.

4. **Querying the Data**:  
   - The system allows you to perform queries to fetch useful information from the database. You can easily ask questions like "Which students are enrolled in a particular course?", "What grades has a student received?", or "What is the teaching schedule for a professor?" and even more complex queries using join.  
   - These queries help retrieve and display the data you need in a meaningful way, making it easy to manage university operations.

## Why This Project is Useful:

This University Management System is built to help universities store and manage their data in an organized and efficient manner. By automating many of the tasks involved in managing students, courses, and faculty, it makes administrative work faster and reduces errors. The use of PostgreSQL also ensures that the database is  scalable, and capable of handling large amounts of data.
