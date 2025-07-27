# 🌍 Tourly – Travel Booking System

A secure, session-based **Full Stack Travel Booking Web Application** where users can book **cabs, flights, hotels**, and **tourist packages**, manage their profiles, and view or cancel bookings. Admins have access to all user and booking data via a dashboard.

---

## 🛠️ Tech Stack

**Frontend:**
- HTML5, CSS3, JavaScript
- Responsive Design (Flexbox & Grid)
- LocalStorage & SessionStorage for client-side data

**Backend:**
- Java 17 + Spring Boot
- Spring Security (Authentication & Authorization)
- MySQL Database
- JPA & Hibernate
- PasswordEncoder for encrypted passwords

---

## ✨ Features

### 👤 User Features
- User Registration & Secure Login
- Profile Dashboard
- Bookings for:
  - 🚖 Cabs
  - 🏨 Hotels
  - ✈️ Flights
  - 🧭 Tourist Packages
- View and Cancel Bookings
- Contact Form to reach support

### 🔐 Admin Features
- Admin Login
- Sidebar Dashboard
- View All:
  - Users
  - Cab, Flight, Hotel, and Tourist Bookings
  - Contact Queries
- Delete Bookings (via checkboxes)

---

## 📦 REST API Overview

### 🔑 User APIs
| Method | Endpoint | Description |
|--------|----------|-------------|
| `POST` | `/api/users/register` | Register new user |
| `POST` | `/api/users/login` | Login user |
| `GET` | `/api/users/{id}` | Get user profile |
| `PUT` | `/api/users/{id}` | Update user profile |

### ✈️ Booking APIs
| Booking | Endpoints | Methods |
|---------|-----------|---------|
| Hotel | `/api/hotels/book`, `/hotels/user/{id}` | `POST`, `GET`, `DELETE` |
| Cab | `/api/cabs/book`, `/cabs/user/{id}` | `POST`, `GET`, `DELETE` |
| Flight | `/api/flights/book`, `/flights/user/{id}` | `POST`, `GET`, `DELETE` |
| Package | `/api/packages/book`, `/packages/user/{id}` | `POST`, `GET`, `DELETE` |

### 🛡️ Admin APIs
| Method | Endpoint | Description |
|--------|----------|-------------|
| `POST` | `/api/admin/login` | Admin authentication |
| `GET` | `/api/admin/users` | View all users |
| `GET` | `/api/admin/{type}` | View all bookings (by type) |
| `DELETE` | `/api/admin/{type}/{id}` | Delete specific booking |

---

## ✅ Project Outcomes

- Created a responsive travel booking platform with real-time session-based features.
- Integrated REST APIs with secured user and admin roles.
- Used Spring Security and JPA for authentication and data access.
- Implemented frontend dashboards with booking summaries and action controls.
- Applied Git version control and deployed source code to GitHub.

---

## 🧠 What I Learned

- REST API design and integration
- Session and local storage in frontend apps
- Full Stack development with Java Spring Boot
- Role-based access control (RBAC)
- GitHub collaboration and repository management

---

## 🎓 Extra

- ✅ Attended **Git & GitHub Workshop** – Learned effective version control practices.

---

## 💬 Contact

Feel free to connect for feedback or collaboration:

🌐 GitHub: [kiran-kumar23](https://github.com/kiran-kumar23)
