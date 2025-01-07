Go Library Management Project
This project is a web-based library management system implemented in Go. It allows dynamic creation of categories and books, supports searching by any alphabet character, and enables booking of books for specific time periods. Upon booking expiration, the book's status automatically updates to available. The front end utilizes Bootstrap v5 for responsive design.

Features
Dynamic Management: Create and manage book categories and individual books dynamically.
Search Functionality: Search for books and categories using any alphabet character.
Booking System: Book a book for a specific time period; status updates automatically upon booking expiration.
User Authentication: Custom login and registration system with admin middleware to protect authenticated routes.
Responsive Design: Front end built with Bootstrap v5 for seamless user experience across devices.
Technologies Used
Backend: Go (Golang)
Frontend: HTML5, Bootstrap v5, JavaScript
Routing: Gorilla Mux
Session Management: Gorilla Sessions
Validation: Ozzo Validation
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/iamsabbiralam/Go-Library-Management-Project.git
Navigate to the project directory:

bash
Copy code
cd Go-Library-Management-Project
Install dependencies:

Ensure you have Go installed. Then, run:

bash
Copy code
go mod tidy
Set up the database:

Configure your database settings in the project.
Apply necessary migrations to set up the database schema.
Run the application:

bash
Copy code
go run main.go
Access the application:

Open your browser and navigate to http://localhost:8080.

Usage
Admin Panel: Access administrative features such as adding/removing books and categories, and managing user bookings.
User Registration: Users can register and log in to book books.
Search and Booking: Search for books or categories and book available books for a desired time period.
Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes.

License
This project is licensed under the MIT License.

Acknowledgements
Gorilla Mux
Gorilla Sessions
Ozzo Validation
Bootstrap v5
For more information, visit the project repository.
