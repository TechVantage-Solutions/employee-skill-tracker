
# Employee Skills Tracker - Refactor & Optimize

## Overview
This project is an **Employee Skills Tracker** application consisting of:  
1. **Backend:** Java Spring Boot REST API using in-memory mock data.  
2. **Frontend:** Angular with Angular Material for the UI.  

The application was initially created by a Junior Engineer. Your task is to **analyze, refactor, and optimize** the codebase to make it production-ready, scalable, and maintainable.  

---

## Task Description
Your goal is to improve this project so that it can:  
- Scale to support **millions of users**.  
- Follow best practices for clean, maintainable, and testable code.  
- Be production-ready, ensuring performance, security, and modularity.

### Instructions
1. **Analyze the Codebase:** Identify key areas of improvement in both backend and frontend code.  
2. **Refactor & Optimize:** Implement changes to address the identified issues.  
3. **Document Your Changes:** Provide a summary explaining the improvements you made and why.  
4. **Test Your Code:** Add unit tests and integration tests where applicable.  

---

## Deliverables
1. **Refactored Project Code**: Submit the improved code as a GitHub repository or zip file.  
2. **Technical Documentation**:  
   - Outline the key changes and improvements.  
   - Explain how the changes make the app scalable and production-ready.  
3. **Test Coverage**: Add unit tests and integration tests where applicable.  
4. **Setup Instructions**: Update the README file with instructions for running the improved application.

---

## Evaluation Criteria
1. **Code Quality**: Clean, readable, maintainable code, and error treatment following best practices.  
2. **Scalability**: Database persistence, optimized endpoints, and modular frontend.  
3. **Testing**: Unit tests and integration tests to ensure code reliability.  
4. **Problem-Solving**: Clear identification and resolution of performance bottlenecks and architectural flaws.  
5. **Documentation**: Clarity in describing improvements and how they contribute to production readiness.

### Bonus Points  
- Implement **JWT-based authentication** for secure API access.  
- Add **pagination** and **sorting** to the employee and skills list endpoints.  
- Optimize frontend for performance by using **lazy loading** and **Angular services**.  
- Containerize the app using **Docker** for deployment.  

---

## Setup Instructions

### Prerequisites
- **Java 17+** and **Maven** (for backend)
- **Node.js 16** and **Angular CLI** (for frontend)

### Backend Setup (Spring Boot)
1. Navigate to the backend folder:
   ```bash
   cd backend
   ```
2. Build and run the backend:
   ```bash
   mvn spring-boot:run
   ```
3. Verify that the backend runs on `http://localhost:8080`.

### Frontend Setup (Angular)
1. Navigate to the frontend folder:
   ```bash
   cd frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm run start
   ```
4. Open the app in your browser at `http://localhost:4200`.
