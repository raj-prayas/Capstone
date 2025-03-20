# Capstone

# ECommerce Online Bookstore

## Project Overview
The ECommerce Online Bookstore is a web application that allows users to browse, purchase, and manage books online. The platform features user authentication, a shopping cart, order management, and an admin panel for managing books and users.

## Key Features
- **User  Registration and Login**: 
  - Users can create accounts and log in securely.
  - Role-based access (Admin and Customer).
  
- **Book Catalog**: 
  - Users can view a list of available books with details (title, author, price, description, image).
  - Search and filter functionality to find books easily.

- **Shopping Cart**: 
  - Users can add books to their cart.
  - View cart summary, including total price and itemized list.

- **Order Management**: 
  - Users can place orders for books in their cart.
  - Order history view for users to track past purchases.

- **Admin Panel**: 
  - Admins can manage books (add, update, delete).
  - View and manage user accounts and orders.

- **Interactive Quizzes** (Optional): 
  - Quizzes related to books for user engagement.
  - Users can take quizzes and receive feedback.

## Technology Stack
- **Frontend**: React.js for building user interfaces.
- **Backend**: Node.js with Express for server-side logic.
- **Database**: SQL (e.g., MySQL, PostgreSQL) for data storage.
- **State Management**: Context API for managing user authentication state.
- **Styling**: CSS/Bootstrap for responsive design.

## Database Design
- **Users Table**: Stores user information (User ID, FirstName, LastName, Password, Email, Role).
- **Books Table**: Stores book details (BookID, Title, Author, Price, Description, ImageURL).
- **Cart Table**: Stores items in the user's cart (CartID, UserID, BookID, Quantity).
- **Orders Table**: Stores order details (OrderID, UserID, OrderTotal, OrderStatus).
- **OrderItems Table**: Stores items in each order (OrderItemID, OrderID, BookID, Quantity).

## Optimization Strategies
- Indexing key columns for fast lookups.
- Using foreign keys to maintain data integrity.
- Normalized structure to reduce redundancy.

## Setup Instructions

### Prerequisites
- Node.js and npm installed on your machine.
- A SQL database (e.g., MySQL, PostgreSQL) set up and running.

### Installation
1. **Clone the Repository**:
   ```bash
   git clone <repository-url>
   cd ebook-front-end
