# 🐐 GoatBooking – Homestay Booking Platform

GoatBooking is a full-stack application that enables users to search, book, and manage homestay accommodations across various locations. The platform offers a web-based interface for users and an administrative dashboard for administrators.

## 📌 Features

### User Interface
- 🔍 Search for homestays by location and preferences
- 🗕️ Book and cancel reservations
- ❤️ View and manage favorite listings
- 🔐 Secure user authentication and profile management

### Admin Dashboard
- 🏠 Manage homestay listings and details
- 👥 Oversee user accounts and bookings
- 📊 Monitor booking statuses and analytics
- 🔐 Admin authentication and authorization

## 🛠️ Technologies Used

- **Frontend:**
  - HTML, CSS, JavaScript

- **Backend:**
  - C# with ASP.NET MVC
  - Entity Framework for ORM

- **Database:**
  - SQL Server

- **Tools & Utilities:**
  - Swagger for API documentation
  - Visual Studio for development

## 🚀 Getting Started

### Prerequisites
- .NET Framework or .NET Core SDK
- SQL Server
- Visual Studio

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/NguyenDuyHungIT17/goatBooking.git
   cd goatBooking
   ```

2. **Set up the database:**
   - Create a SQL Server database named `goatbooking`.
   - Import the provided `db_sql.sql` file to set up the schema.

3. **Configure the application:**
   - Open the solution in Visual Studio.
   - Update the database connection string in the `web.config` or `appsettings.json` file.

4. **Build and run the application:**
   - Build the solution to restore dependencies.
   - Run the application using IIS Express or your preferred web server.

5. **Access the application:**
   - Navigate to `http://localhost:[port]/` to access the user interface.
   - Navigate to `http://localhost:[port]/admin` to access the admin dashboard.

## 📁 Project Structure

```
goatBooking/
├── GOATBOOKING_test/            # Test projects and files
├── ad_booking/                  # Main application source code
├── db_sql.sql                   # Database schema
├── .vs/                         # Visual Studio settings
├── .vscode/                     # VS Code settings
├── ~$u1ecdc_web.docx                # Documentation (possibly temporary file)
```


## 📬 Contact

For any inquiries or feedback, please reach out to [nguyenduyhungit17@gmail.com](mailto:nguyenduyhungit17@gmail.com).
