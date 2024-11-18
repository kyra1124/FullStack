The Application is developed using Spring Boot,Maven ,  MySQL DB,

The Application provides various endpoints to do the following

1. Add Employee to a Database: In this task, the candidate needs to implement an
API endpoint to add an employee to the database. The employee data should include the
fields EmployeeName, PhoneNumber, Email, and ProfileImage (an URL to the Employee's profile image [use
google images]). Additionally, the candidate needs to generate a unique UUID as the ID field
for the Employee and return this ID,if the Employee is successfully added to the
database.
2. Get All Employees: The candidate needs to implement an API endpoint to retrieve
all employees from the database.
3. Delete Employee by ID: The candidate needs to implement an API endpoint to
delete an employee from the database based on their ID.
4.Update Employee by ID: The candidate needs to implement an API endpoint to
update the details of an employee in the database based on their ID
5.Get nth Level Manager of an Employee: The candidate needs to implement an API
endpoint that takes an employee ID and a level (n) as input and returns the nth level
manager of that employee.
For example, if employee A reports to B, and B reports to C, and n=1, then the API should return the manager B for employee A, and if n=2, it should return
manager C for employee A
6.Get Employees with Pagination and Sorting: Modify the "Get All Employees" task
to implement pagination and sorting options. Allow the client to specify the page number,
page size, Return the appropriate subset of
employees based on the pagination parameters





[
    {
        "name": "Kyra",
        "jobTitle": "Software Devloper",
        "phone": "7386127109",
        "email": "kyra1124@outlook.in",
        "imageUrl": "https://imgv3.fotor.com/images/blog-richtext-image/10-profile-picture-ideas-to-make-you-stand-out.jpg"
    },
    {
        "name": "Zia",
        "jobTitle": "Fashion Designer",
        "phone": "7993866127",
        "email": "Zia@outlook.com",
        "imageUrl": https://cdn5.vectorstock.com/i/1000x1000/73/04/female-avatar-profile-icon-round-woman-face-vector-18307304.jpg

    },
    {   "name": "Megan",
        "jobTitle": "Model 3 Generative AI",
        "phone": "9878678890",
        "email": "megan@gmail.com",
        "imageUrl": https://www.shutterstock.com/image-vector/face-happy-girl-avatar-laughing-260nw-1459862774.jpg
    }
]
