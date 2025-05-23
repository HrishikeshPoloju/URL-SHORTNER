# 🔗 URL Shortener

A sleek and secure **URL Shortener** built with modern web technologies — powered by **React + Vite**, styled with **Tailwind CSS** and **Shadcn UI**, and backed by **Supabase** for authentication, database, and analytics.

<br/>

![Screenshot 2025-05-23 165849](https://github.com/user-attachments/assets/35e6f100-791c-4b49-a138-df16d5bedc36)
![Screenshot 2025-05-23 170231](https://github.com/user-attachments/assets/6a70b61a-ba1b-4a89-a8df-b2251e944255)

## 🚀 Lighthouse Performance Report

![Screenshot 2025-05-23 170312](https://github.com/user-attachments/assets/07cda8fc-5d95-4635-91d8-f485c4770401)

### 📊 Key Metrics

| Metric           | Score |
|------------------|-------|
| **Performance**   | 🟠 53  |
| **Accessibility** | 🟢 93  |
| **Best Practices**| 🟢 96  |
| **SEO**           | 🟠 75  |

### ✅ What’s Already Optimized:
- ✅ Semantic HTML for accessibility
- ✅ Use of HTTPS and secure resources
- ✅ Proper ARIA labels and roles
- ✅ Lazy loading for images

### 🛠️ Upcoming Improvements:
- 🔧 Reduce JavaScript bundle size
- 🔧 Optimize images (WebP, compression)
- 🔧 Improve server response times (TTFB)
- 🔧 Defer non-critical JS & CSS

> ℹ️ Report generated using Chrome DevTools Lighthouse at `http://localhost:5173/`


---

## 🚀 Features

- 🔐 **User Authentication** – Login/Signup via Supabase (Email/OAuth)
- ✂️ **Shorten URLs** – Instantly generate clean, trackable links
- 📊 **Analytics Dashboard** – Track click counts and usage stats
- 🌐 **Custom Link Routing** – Auto-redirect to original URL
- ⚡ **Blazing-fast Frontend** – Built with Vite + React 18
- 💅 **Modern UI** – Built using Tailwind CSS + Shadcn UI components

---

## 🛠 Tech Stack

| Layer        | Technology                           |
|--------------|---------------------------------------|
| Frontend     | [React](https://reactjs.org/), [Vite](https://vitejs.dev/), [Tailwind CSS](https://tailwindcss.com/), [Shadcn UI](https://ui.shadcn.com/) |
| Backend/API  | [Supabase](https://supabase.com/) – Auth, Database, Realtime |
| Database     | Supabase PostgreSQL                  |
| Deployment   | [Vercel](https://vercel.com/) / Netlify |
| Version Control | Git + GitHub                      |

---

## 📦 Installation

```bash
# Clone the project
git clone https://github.com/<your-username>/url-shortener.git
cd url-shortener

# Install dependencies
npm install

# Start dev server
npm run dev
