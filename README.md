# 💼 DevPort — Portfolio Builder

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=flat&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-black?style=flat&logo=jsonwebtokens)
![Cloudinary](https://img.shields.io/badge/Cloudinary-3448C5?style=flat&logo=cloudinary&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat&logo=tailwind-css&logoColor=white)

A scalable portfolio-building platform with a real-time live editor, secure authentication, and optimized media delivery — lets users build and publish a developer portfolio without writing code.

## 🚀 Live Demo
[https://devportt.vercel.app](#) — replace with your actual deployed URL

![Demo Screenshot](#) <!-- drop a screenshot of the live editor here -->

## ✨ Key Features
- **Real-time live editor** built on Next.js App Router with **10+ reusable UI components** for responsive customization
- **Secure authentication** — JWT + Bcrypt password hashing + OTP-based email verification for safe onboarding
- **Cloudinary integration** for optimized storage and CDN delivery of images, PDFs, and resumes — cut media load times by up to **40%**

## 🧱 Tech Stack
| Layer | Technology |
|---|---|
| Frontend | Next.js (App Router) |
| Backend | Express, Node.js |
| Database | MongoDB |
| Auth | JWT, Bcrypt, Nodemailer (OTP) |
| Media | Cloudinary |
| Styling | Tailwind CSS |

## 🛠️ Getting Started

```bash
git clone https://github.com/subhash865/<repo-name>.git
cd <repo-name>
npm install
```

Create a `.env.local`:

```
MONGODB_URI=your_mongo_uri
JWT_SECRET=your_jwt_secret
CLOUDINARY_URL=your_cloudinary_url
SMTP_EMAIL=your_email
SMTP_PASSWORD=your_email_app_password
```

Run locally:

```bash
npm run dev
```

## 📌 Roadmap
- [ ] Custom domain support for published portfolios
- [ ] More live-editable templates

## 📄 License
MIT
