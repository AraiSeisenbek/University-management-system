Project name: "University managment system".

Entities are main classes with variables that we will store and retrieve from database. In our project we have 4 entities: Student, Department, Gpa, and University.

Interface Repository are interface that we used in order to override our construct. There are Interfaces: StudentRepository.java

Repository is class that has method with commands for our database, like insert , select etc. There are Interfaces: IStudentRepository.

IDB is interface that helps with connection to Database.

PostgresDB is a class that implements and retrieves from database login , password.

Controller is a class that notifies us if we created new object in our database. There are three controllers: StudentController, DepartmentController, GpaController, UniversityController.

Application retrives variables that we inserted with usage of our console.

Main uses all classes as one mechanism.
