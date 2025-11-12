# 👋 Hi, I'm **Tsaagane Obakeng Shepherd**
**Final-Year IT Student | Junior Full-Stack .NET + React Developer**  
Pretoria, South Africa · Open to Junior Developer Roles  
📞 067 630 8354 · 📧 obakengtsaagane@gmail.com  

---

## 🚀 **InsureClaim – Full-Stack Insurance SaaS (Personal Project)**
> A **modern, modular insurance management system** built from scratch as a **Software-as-a-Service (SaaS)** platform.  
> Runs 100 % locally with full-stack functionality: authentication, claims processing, policy management, and analytics.  
> Designed using **Clean Architecture**, **Dependency Injection**, and **Entity Framework Core** — production-ready and Azure-compatible.

---

### 🧱 **Project Overview**

**Goal:** Deliver a professional, role-based insurance platform capable of handling customers, policies, claims, and reports, all powered by a secure backend and an interactive frontend.

| Module | Description |
|---------|--------------|
| **Authentication** | JWT-based login & registration with Admin / Agent / Customer roles |
| **Policy Management** | CRUD for Life, Auto, Health, and Property policies |
| **Claims Handling** | Create, approve, and track insurance claims |
| **Payments (Mock)** | Transaction flow simulation with amount validation |
| **Logging & Monitoring** | Serilog-based structured logs for diagnostics |
| **Reporting & Dashboard** | Interactive charts and metrics via React components |
| **Scalable Design** | Modular codebase, container-ready for future cloud deployment |

---

### ⚙️ **Local Development Setup**

#### 🧩 Backend (.NET 8 + SQL Server)
```bash
cd backend/InsureClaim.API
dotnet ef database update
dotnet run
```
Runs at → https://localhost:7016

#### 💻 **Frontend (React + Vite + Tailwind)**
```bash
Copy code
cd frontend
npm install
npm run dev
```
Runs at → http://localhost:5173

### ✅ **The frontend and backend communicate locally through configured CORS for seamless API integration.**

### 🧰 **Tech Stack**

- **Backend:**  C# (.NET 8) · ASP.NET Core Web API · Entity Framework Core · LINQ
- **Frontend:** React 18 · Vite · TailwindCSS · Axios · Context API · Recharts
- **Database:** SQL Server (EF Core Migrations + Seed Data)
- **Auth:** JWT Role-Based Authentication (Admin / Agent / Customer)
- **Logging:** Serilog · xUnit Testing
- **Tools:** Git · GitHub · VS Code · Postman · Lucidchart (ERD & Data Flow)
- **Architecture:** Clean Architecture · Dependency Injection · Repository Pattern
  
### 📊 **System Architecture**
**Data Layer:** EF Core models, repository abstraction, and CTE queries
**Business Layer:** Service-based logic with validation and DTOs
**API Layer:** RESTful endpoints with request-response pipelines
**Frontend Layer:** Modular React dashboard with reusable components
**Security:** JWT tokens, password hashing, role-based access control

### 🧠 **Project Status**
✅ **100 % Complete (Local SaaS Version)**
- Fully operational backend and frontend communicating locally with secure authentication, business logic, and reporting dashboards.
- The architecture is ready for deployment to Azure, Railway, or Render whenever desired — without additional restructuring.

### 🧭 **Learning Outcomes**
Full-stack development using .NET 8 + React
Clean Architecture and modular backend design
RESTful API engineering and JWT authentication
Real-world DB management and CTE query optimization
End-to-end SaaS lifecycle (design → implementation → testing)

### 🧾 **Version Summary**
Phase	Description	Status
1	Core Backend Setup (Auth, DB, Logging)	✅
2	Claims & Policy Management	✅
3	Reporting & Analytics	✅
4	UI Integration & Validation	✅
5	Final Testing & Documentation	✅
Total	Local SaaS Completion	🎯 100 %

💼 Connect with Me
🌐 GitHub – obakengshepherd

💼 LinkedIn – Obakeng Tsaagane (www.linkedin.com/in/obakeng-tsaagane-307544244)

📧 obakengtsaagane@gmail.com
