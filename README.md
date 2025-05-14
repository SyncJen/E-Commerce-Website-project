# E-Commerce-Website-project
📝 Project Description
Kart Style is a responsive and user-friendly e-commerce web application designed specifically for showcasing and selling men’s and women’s fashion products. It aims to replicate the core functionality of real-world e-commerce platforms such as Amazon and Myntra while focusing on elegant UI and smooth user experience.

The application allows users to sign up, log in, view fashion products, and proceed through a simulated order dispatch process verified using a dispatch code. The system handles user authentication, product display, and basic order verification without a backend server (using local storage for simulation).

🌐 Technologies Used
🔧 Frontend:
HTML5

CSS3

JavaScript (Vanilla JS)

🖥 Backend Simulation:
LocalStorage (for storing user credentials and dispatch ID)

💡 Tools & IDE:
IntelliJ IDEA (Spring Boot environment for future enhancements)

VS Code (for frontend editing)

Spring Initializr (for setting up backend dependencies)

🧩 Modules Overview
1. Open Page (Login & Signup)
User registration form with inputs: name, email, phone number, and password.

On successful signup, a 4-digit Dispatch ID is generated and displayed.

Login form to verify credentials stored in local storage.

Upon successful login, the user is redirected to index.html (Product Page).

2. Product Page (index.html)
Displays available fashion items for both men and women.

UI-ready for filtering and sorting (future upgrade).

3. Dispatch Confirmation Page
Allows user to verify a dispatch using the 4-digit code shown during signup.

If the entered dispatch code matches any registered user’s dispatch ID in local storage, it confirms the order and redirects the user to the product page.

🔄 Application Flow
text
Copy
Edit
User ➝ Open Page ➝ Signup/Login ➝ Store User + Dispatch ID in localStorage ➝ 
Successful Login ➝ Redirect to index.html ➝ Dispatch Page ➝ Enter Dispatch Code ➝
✔️ Valid → Redirect to Products
❌ Invalid → Show Error
✅ Key Features
Clean and aesthetic UI with modern styles

Login & signup functionality with validation

LocalStorage-based user management (no server required)

Randomized Dispatch Code generation on signup

Dispatch verification logic based on user input

Page routing via window.location.href

Scalable codebase with potential backend integration (Spring Boot-ready)

🚀 Future Enhancements
Integration with real database (MySQL) via Spring Boot

Secure user authentication with JWT

Add-to-cart and checkout functionality

Payment gateway integration

Admin panel for managing products and users

User profile dashboard

👨‍💻 Team Members
Name	Role
Jenifer Maria	Frontend Development & UI Design
Lokesh	Backend Simulation & Logic Handling
Rizwan	LocalStorage Integration & Testing
Soniya	Dispatch Flow & Validation Logic
Sowmiya	Project Coordination & Documentation
