# Better Auth Dashboard

A modern, secure, and extensible authentication system using [better-auth](https://www.npmjs.com/package/better-auth), with a protected dashboard page, simple animations using Framer Motion, and a PostgreSQL database managed via Prisma ORM.

## 🚀 Features

- 🔐 **Authentication** with [better-auth](https://www.npmjs.com/package/better-auth)
- 🛡️ **Private route** management
- 📊 Protected **dashboard** page
- 🎞️ Smooth UI transitions with **Framer Motion**
- 🗄️ **PostgreSQL** database using **Prisma**
- 🧪 Easy-to-configure **environment variables**

---

## 🧱 Tech Stack

| Tool | Description |
|---|---|
| **Next.js / React** | Frontend Framework |
| **better-auth** | Authentication Library |
| **Prisma** | ORM for TypeScript & PostgreSQL |
| **PostgreSQL** | Relational Database |
| **Framer Motion** | Animation Library for React |

---

##  ⭐ Set up environment variables

Create a **`.env`** file in the root of the project and add the following:

```
DATABASE_URL="postgresql://user:password@localhost:5432/mydb"
BETTER_AUTH_SECRET="your-secret-key"
BETTER_AUTH_URL="http://localhost:3000/api/auth"
```

## 📦 Installation

**1. Clone the repository**

git clone [https://github.com/your-username/Better-Auth-Dashboard.git](https://github.com/Morshed004/Better-Auth-Dashboard.git) \
cd Better-Auth-Dashboard


**2. Install dependencies**

```
npm install
# or yarn install
```

**Setup the database (using Prisma Migrations)**

```
npx prisma migrate dev --name init
```
**Run the development server**

```
npm run dev
# or yarn dev
```
