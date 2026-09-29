# Transport Management System

A web-based application for managing transport operations, including bus availability, passenger requests, scheduling, bids, and notices. Built with PHP and MySQL, with role-based access for each level of the organization.

## Features

- **Role-based portals**: separate pages for Admin, Director General, Deputy Director General, General Service Executive Officer, Stock Clerk, Employee, and Passenger
- **Authentication**: login, logout, and password recovery
- **Bus search**: search for available buses
- **Requests**: submit, view individual requests, and view scheduled requests
- **Scheduling**: calendar for trips and requests
- **Bids**: view bids
- **Notices**: view organization notices
- **User management**: view and update individual user records
- **Content pages**: about us, about organization, general association information, feedback, slideshow
- **Image handling**: upload and retrieval of images
- **Multi-language support**: language resources in the `Language` folder
- **Documentation**: project documents in the `Documentation` folder

## Project Structure

```
Transport-Managment-System/
├── Admin/                                  # Administrator pages
├── DirectorGeneralManagerPage/             # Director General pages
├── DeputyDirectorGeneral/                  # Deputy Director General pages
├── GeneralServiceExcutiveOfficerManPage/   # General Service Executive Officer pages
├── StockclerkPage/                         # Stock clerk pages
├── Employee/                               # Employee pages
├── PassengerPage/                          # Passenger pages
├── connection/                             # Database connection settings
├── DB/                                     # Database resources
├── Documentation/                          # Project documentation
├── Language/                               # Language files
├── css/  js/  images/                      # Static assets
├── form1/  help/                           # Forms and help pages
├── ims.sql                                 # Database schema and data
├── index.php                               # Landing page
├── login.php                               # Login handler
└── *.php                                   # Shared pages and scripts
```

## Tech Stack

| Layer    | Technology            |
| -------- | --------------------- |
| Frontend | HTML, CSS, JavaScript |
| Backend  | PHP                   |
| Database | MySQL                 |
| Server   | Apache (XAMPP / WAMP) |

## Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/TimBroAhm/Transport-Managment-System.git
   ```

2. **Place the project in your web server directory**

   - XAMPP: `C:\xampp\htdocs\Transport-Managment-System`
   - WAMP: `C:\wamp64\www\Transport-Managment-System`

3. **Create the database**

   - Start Apache and MySQL.
   - Open `http://localhost/phpmyadmin`.
   - Create a new database, then import `ims.sql`.

4. **Configure the connection**

   Set your MySQL host, username, password, and database name in the `connection` folder.

5. **Run the application**

   Open `http://localhost/Transport-Managment-System/` in your browser.

## User Roles

| Role                             | Responsibility                                  |
| -------------------------------- | ----------------------------------------------- |
| Admin                            | System administration and user management       |
| Director General                 | Top-level oversight and approvals               |
| Deputy Director General          | Request review and approvals                    |
| General Service Executive Officer| Service coordination and bus scheduling         |
| Stock Clerk                      | Stock and inventory records                     |
| Employee                         | Submit and track transport requests             |
| Passenger                        | Search available buses and submit requests      |

## Author

**TimBro**
GitHub: [@TimBroAhm](https://github.com/TimBroAhm)
