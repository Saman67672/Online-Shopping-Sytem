# Online-Shopping-Sytem using C++ (OOP Project)
A feature-rich, object-oriented shopping platform in C++ with login security, admin control, and file-based data persistence.
This project was developed not only as a functional system but also as a practical application of theoretical computer science principles.

# Objective:
The primary objective of this project is to design and implement a simplified yet functional online shopping system using Object-Oriented Programming (OOP) in C++, with a strong focus on modularity, data encapsulation, and role-based access. It aims to simulate key operations of real-world e-commerce platforms in a command-line environment using file handling instead of databases.
Purpose
To apply OOP principles (inheritance, polymorphism, encapsulation, abstraction) in a real-life use case.

To demonstrate the separation of concerns between different user roles such as admin and customer.

To manage inventory and simulate product transactions using simple text file-based persistence.

To serve as a mini-project or academic submission that showcases technical understanding and coding discipline.
Implementation
Built entirely in C++, using classes for each key component (user, admin, product, inventory, order).

Implements role-based login system with validation.

Admin role: Add, update, delete products.

User role: View products, place orders.

Data such as user credentials and product listings are stored in and retrieved from .txt files using file handling.

The application runs via a menu-driven console interface.
ey Concepts Used:
Classes & Objects

Inheritance (Admin inherits from User)

File I/O Streams (ifstream, ofstream, fstream)

Conditional logic and loops

Basic string handling and validation
Limitations
While the system is functional, it has certain constraints:

❌ No GUI: Only command-line interface.

❌ No database: All data is stored in .txt files (less secure, harder to scale).

❌ No password encryption: Credentials are stored in plain text.
uture Improvements
To enhance the system further, the following features can be added:

🔐 Encrypt passwords using hashing (e.g., SHA-256).
🖥️ GUI interface using frameworks like Qt, SFML, or JavaScript frontend + C++ backend.

🌐 Database integration (MySQL/SQLite) for secure and scalable storage.
✅ Conclusion
This project successfully demonstrates the application of Object-Oriented Programming in C++ to build a functional and role-based online shopping system. With features like secure login, inventory control, and file-based data persistence, it serves as both a practical learning tool and a solid foundation for more advanced e-commerce applications.
