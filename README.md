# 🚀 Ruby on Rails 8 — 10 Projects to Master Rails

This repository is a **self-guided roadmap** to becoming an **expert in Ruby on Rails 8** by building **10 progressively advanced projects**.  
Each project introduces new Rails concepts, real-world design patterns, and modern Rails 8 features (like Turbo, Stimulus, and Hotwire 2).

---

## 🧱 Beginner → Intermediate Projects

### **1. Blog Platform (Beginner)**
**Core Concepts:** MVC structure, CRUD, routes, views, forms  
**Features:**
- Posts CRUD  
- Comments (nested resources)  
- User authentication (Devise)  
- Simple admin panel  

> 🧩 Learn: Rails fundamentals, routing, migrations, ActiveRecord basics, forms.

---

### **2. Task Manager / To-Do App (Beginner–Intermediate)**
**Core Concepts:** Associations, validations, AJAX with Turbo, Hotwire basics  
**Features:**
- Tasks belong to users  
- Real-time updates with Turbo Streams  
- Mark tasks complete/incomplete  
- Sorting and filtering  

> 🧩 Learn: Turbo Drive, partials, broadcasting updates, model validations.

---

### **3. Recipe Sharing App (Intermediate)**
**Core Concepts:** File uploads, associations, and nested forms  
**Features:**
- Users can post recipes with images  
- Tagging and categories  
- Comments + likes  
- User profile pages  

> 🧩 Learn: Active Storage, nested attributes, polymorphic associations, form objects.

---

### **4. Simple E-Commerce Store (Intermediate)**
**Core Concepts:** Cart management, sessions, Stripe integration  
**Features:**
- Product listings  
- Add to cart / checkout flow  
- Stripe payments  
- Order history  

> 🧩 Learn: Sessions, payments, background jobs for order emails, environment variables.

---

### **5. Event Management App (Intermediate)**
**Core Concepts:** Many-to-many relationships, calendar integration, invitations  
**Features:**
- Create/join events  
- Attendee management  
- Email reminders (Action Mailer)  
- Dashboard with upcoming events  

> 🧩 Learn: Action Mailer, Active Job, date/time handling, associations.

---

## 🚀 Advanced Projects

### **6. Social Network (Advanced)**
**Core Concepts:** Complex associations, Turbo Streams for live updates  
**Features:**
- Follow/unfollow system  
- Posts, comments, likes  
- Notifications in real time  
- Profile customization  

> 🧩 Learn: Polymorphic models, broadcasting, ActionCable/Turbo, caching, N+1 query optimization.

---

### **7. SaaS Subscription App (Advanced)**
**Core Concepts:** Billing, user plans, role-based access, Stripe or Paddle subscriptions  
**Features:**
- Multi-tiered pricing (Free, Pro, Business)  
- User dashboard  
- Webhooks for billing events  
- Team management  

> 🧩 Learn: Stripe webhooks, service objects, policy authorization (Pundit or CanCanCan), background jobs.

---

### **8. API-Only Backend with React/Vue Frontend (Advanced)**
**Core Concepts:** API mode, JWT authentication, CORS, frontend integration  
**Features:**
- Rails API providing JSON  
- SPA frontend (React or Vue)  
- Token-based auth  
- Pagination and filtering  

> 🧩 Learn: Rails API mode, serializers, JWT, integrating frontends.

---

### **9. Real-Time Chat App (Expert)**
**Core Concepts:** WebSockets, Turbo Streams, performance tuning  
**Features:**
- One-on-one and group chats  
- Live message updates  
- Online/offline presence  
- Message search and attachments  

> 🧩 Learn: ActionCable, Redis, Turbo Streams, caching, database indexing, scaling real-time apps.

---

### **10. Multi-Tenant SaaS Platform (Expert)**
**Core Concepts:** Multi-tenancy, scalability, custom domains, background jobs, analytics  
**Features:**
- Tenants (organizations) with isolated data  
- Custom domain/subdomain per tenant  
- Billing + roles per tenant  
- Admin analytics dashboard  

> 🧩 Learn: PostgreSQL schemas, Apartment gem (or custom tenant logic), scalability, background workers, ActiveJob + Sidekiq, service-oriented architecture.

---

## 🧠 Bonus Tips for Mastery

- Use **RSpec** for testing by project #3 onward.  
- Add **Docker** or **Kamal** deployment around project #5.  
- Integrate **Hotwire 2** fully by project #6.  
- Build your own **Rails gem or plugin** after project #8.  
- Deploy everything — use **Fly.io**, **Render**, or a **VPS**.  
- Document each project thoroughly — pretend each is client-facing.

---

## 💡 Suggested Learning Path

| Phase | Projects | Focus |
|:------|:----------|:------|
| **Phase 1** | 1–2 | Fundamentals: MVC, CRUD, Turbo basics |
| **Phase 2** | 3–5 | Intermediate: File uploads, payments, background jobs |
| **Phase 3** | 6–8 | Advanced: Real-time features, API development, authentication |
| **Phase 4** | 9–10 | Expert: Multi-tenancy, scaling, advanced architecture |

---

## 📚 Tools & Technologies to Use

- **Ruby on Rails 8**
- **PostgreSQL** (preferred)
- **Hotwire (Turbo + Stimulus)**
- **Devise / Pundit / RSpec**
- **Redis** for caching and ActionCable
- **Sidekiq** for background jobs
- **Stripe** for billing integrations

---

## 🎯 Goal
By completing all 10 projects, you will:
- Understand **every major Rails subsystem**
- Build and deploy **production-ready applications**
- Gain **real-world experience** in scalability, testing, and maintainable architecture  
- Be capable of working as a **professional Rails developer or architect**

---

## 🧩 License
This roadmap is open for learning and sharing — feel free to fork and customize it for your own growth journey.

---

### Made with ❤️ for learning Ruby on Rails 8
