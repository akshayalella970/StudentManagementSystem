# StudentManagementSystem
# Student Management System Using Spring Boot

The **Student Management System** is a web-based application developed using **Spring Boot** that streamlines the management of student records through a simple and user-friendly interface. The application follows the **Model-View-Controller (MVC)** architecture, ensuring a clean separation of concerns and making the system scalable and maintainable.

The system enables administrators to perform essential **CRUD (Create, Read, Update, Delete)** operations on student data. Users can add new student records, view the complete list of students, edit existing information, and delete records when necessary. Each student record contains details such as **First Name, Last Name, Email, Course, and Mobile Number**.

The backend is built using **Spring Boot**, **Spring MVC**, and **Spring Data JPA (Hibernate)**, which simplify application development and database interaction. Student information is stored in a relational database such as **MySQL** or **Oracle**, while **Hibernate** handles object-relational mapping (ORM) between Java objects and database tables.

The frontend is developed using **Thymeleaf** as the template engine along with **Bootstrap** to provide a responsive and modern user interface. Form validation and data binding ensure accurate and reliable data entry.

This project demonstrates key concepts of enterprise application development, including dependency injection, MVC architecture, RESTful request handling, JPA repositories, and database connectivity. It serves as an excellent learning project for understanding full-stack Java web development and can be extended with features such as authentication, role-based access control, student search, pagination, report generation, and attendance management.


PROJECT STRUCTURE

StudentManagementSystem
│
├── src/main/java
│   └── com/example/studentmanagement
│       ├── controller
│       │      StudentController.java
│       │
│       ├── entity
│       │      Student.java
│       │
│       ├── repository
│       │      StudentRepository.java
│       │
│       ├── service
│       │      StudentService.java
│       │      StudentServiceImpl.java
│       │
│       └── StudentManagementApplication.java
│
├── src/main/resources
│   ├── templates
│   │      index.html
│   │      add-student.html
│   │      edit-student.html
│   │
│   ├── static
│   │
│   └── application.properties
│
└── pom.xml
