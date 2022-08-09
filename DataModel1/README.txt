About Dataset
Context
The motivation behind creation this dataset is to analyse the performance of professors and students. The dataset is aimed towards recording the journey of students in a particular course, right from his/her admission till last of his/her course. of-course, This is the initial version. We will keep adding other tables and data fields to this. Enjoy Data Science.

Content
The dataset contains the information of an imaginary institute. Information about its departments, Professors, Student Counselling, Coursers offered, course student selected to get admission and student performance in different examinations.


****TABLE: Department_Information
This table has information about the departments in the university. The department ID and DOE (date of establishment).
Field 1: Department ID
Field 2: Department Name
Field 3: Department Establishment Date


****TABLE: Employee_Information
Each row in this dataset represent the details about a professor.
Field 1: Employee ID (Unique ID of Professor)
Field 2: Date of Birth of Professor
Field 3: Date of Joining
Field 4: Department ID where the Professor Belongs to.

****TABLE: Student_Counceling_Information
This table has admission (counselling) information about students. Each row represents a student.
Field 1: Student ID
Field 2: Date of Admission
Field 3: Date of Birth
Field 4: Choice of department a student submitted
Field 5. Department name (Student get admitted)


****TABLE: Student_Performance_Data
This dataset has performance details of students.
Field 1: StudentID
Field 2: SemesterName
Field 3: PaperID
Field 4: PaperName
Field 5: Marks


