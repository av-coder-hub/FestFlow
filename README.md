# FestFlow 🎉

**FestFlow** is a simple event management application that allows users to manage events such as conferences, festivals, or other gatherings. With features like event creation, attendee management, and real-time updates, it provides a straightforward and user-friendly platform for organizing events.

---

## Table of Contents 📚
1. [Introduction](#introduction)
2. [Features](#features)
3. [Technologies Used](#technologies-used)
4. [Installation](#installation)
5. [Usage](#usage)
6. [Contributing](#contributing)
7. [License](#license)

---

## Introduction 🌟

**FestFlow** is an easy-to-use web application for managing events. Built using **Spring Boot (Java)** for the backend, **MySQL** for the database, and **HTML/CSS** for the frontend, FestFlow allows users to create and manage events efficiently.

---

## Features 🎯

- **Create Events**: Event organizers can easily create events with details such as name, date, location, and description.
- **Event List**: A list of events is displayed where users can view all upcoming events.
- **Attendee Registration**: Users can register to attend events, making it easy to track attendees.
- **Simple UI**: The UI is simple and responsive, making it easy to navigate and use on different devices.
- **Event Management**: Organizers can manage event details, including the status and update event information.

---

## Technologies Used ⚙️

- **Frontend**:
  - HTML
  - CSS
  - Bootstrap (for responsive design)

- **Backend**:
  - Spring Boot (Java)
  - RESTful APIs for data handling

- **Database**:
  - MySQL

---

## Installation 🛠️

Follow these steps to get the project up and running locally:

### Prerequisites 🔑
Make sure you have the following installed:
- Java (JDK 8 or higher)
- Spring Boot
- MySQL
- Maven (for building the project)

### 1. Clone the repository

```bash
git clone https://github.com/av-coder-hub/FestFlow.git
```

### 2. Navigate to the project folder

```bash
cd FestFlow
```

### 3. Set up the database
Create a MySQL database called `festflow`:

```sql
CREATE DATABASE festflow;
```

Update the database connection details in the `application.properties` file (in the `src/main/resources` folder) as follows:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/festflow
spring.datasource.username=root
spring.datasource.password=yourpassword
spring.jpa.hibernate.ddl-auto=update
```

### 4. Build the project
Use Maven to build the Spring Boot project:

```bash
mvn clean install
```

### 5. Run the application
Start the Spring Boot application:

```bash
mvn spring-boot:run
```

Your application should now be running at `http://localhost:8080`.

---

## Usage 🚀

1. **Create an Event**: Log in as an admin and create an event by filling out the event details.
2. **View Events**: Anyone can view the list of all upcoming events.
3. **Register for an Event**: Users can register to attend an event by submitting their details.
4. **Event Updates**: Admins can update event information such as date, venue, and description.

---

## Contributing 🤝

We welcome contributions to **FestFlow**! If you would like to contribute, follow these steps:

1. Fork this repository.
2. Create a new branch (`git checkout -b feature-name`).
3. Make your changes and commit them (`git commit -am 'Add new feature'`).
4. Push to your branch (`git push origin feature-name`).
5. Open a pull request to merge your changes into the main repository.

---
