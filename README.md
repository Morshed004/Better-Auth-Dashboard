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

## Set up environment variables

Create a **`.env`** file in the root of the project and add the following:

```bash
DATABASE_URL="postgresql://user:password@localhost:5432/mydb"
BETTER_AUTH_SECRET="your-secret-key"
BETTER_AUTH_URL="http://localhost:3000/api/auth"
