
# 🛠️ Full-Stack CRUD Application

This is a full-stack web application built using Angular for the frontend, Spring Boot for the backend, and Java with a relational database (e.g., MySQL) for data persistence. It supports full Create, Read, Update, and Delete (CRUD) operations on a sample data model.

## 🚀 Tech Stack

**Frontend**

* Angular
* TypeScript
* HTML / CSS

**Backend**

* Java
* Spring Boot
* RESTful APIs

**Database**

* MySQL (or H2 for testing/dev)
* JPA / Hibernate

## 🧩 Features

* Full CRUD functionality (Add, View, Edit, Delete items)
* RESTful API with Spring Boot
* Angular UI with reactive forms and HTTP integration
* CORS enabled for frontend-backend communication
* Data persisted in a MySQL database
* Simple, clean UI with form validation

## 🖥️ How It Works

* The **Angular** frontend communicates with the **Spring Boot** backend over HTTP.
* The backend exposes a set of **REST endpoints** to handle requests.
* The backend interacts with the **database** using JPA to perform CRUD operations.
* All state is synced between the database and UI.

## 📁 Project Structure

```
project-root/
├── backend/
│   └── src/main/java/... (Spring Boot backend code)
├── frontend/
│   └── src/app/... (Angular frontend code)
```

## 🧪 Running the App Locally

### Backend (Spring Boot)

1. Open the backend folder
2. Configure `application.properties` (set DB connection, CORS if needed)
3. Build and run:

   ```bash
   ./mvnw spring-boot:run
   ```

   or in IDE: run the main application class

### Frontend (Angular)

1. Navigate to the frontend directory
2. Install dependencies:

   ```bash
   npm install
   ```
3. Run the Angular app:

   ```bash
   ng serve
   ```
4. Open in browser: [http://localhost:4200](http://localhost:4200)

Make sure the backend is running on a port like `8080` and that CORS is enabled.

## ⚙️ Configuration Notes

* CORS: Enabled in Spring Boot via `@CrossOrigin` or global config
* Database schema auto-generated with JPA (if enabled)
* Update `proxy.conf.json` in Angular to route API calls during development

## 🧱 Example Use Case

This app can be adapted for managing:

* Users
* Products
* Tasks / To-Do items
* Inventory
* Contacts

## 📌 Next Steps / Possible Improvements

* Add authentication (e.g., JWT + Spring Security)
* Use a UI framework like Angular Material or Bootstrap
* Deploy frontend and backend to cloud (e.g., Netlify + Heroku or Docker + AWS)
* Add pagination, filtering, or search

## 📄 License

This project is open source and available under the [MIT License](LICENSE).


