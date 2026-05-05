[README.md](https://github.com/user-attachments/files/27389493/README.md)
# Leave Management System (LeaveMS)

A modern, responsive **frontend-only Leave Management System** built using **HTML5, CSS3, Bootstrap 5, and JavaScript**, designed for deployment on **Vercel** via **GitHub** as part of a Cloud Computing assignment.

---

## 🚀 Features

- 🏠 **Home Page** — Modern landing with hero section.
- 📊 **Dashboard** — Summary cards + charts (Leaves per month, Leave type distribution).
- 📝 **Apply Leave** — Full validated form (Employee ID, Name, Department, Leave Type, Dates, Reason).
- 📜 **Leave History** — Professional table with realistic dummy data + status badges.
- ✅ **Approval Process** — HR / Admin panel with Approve / Reject buttons.
- 📱 Fully responsive (mobile + desktop).
- ☁️ Ready for one-click Vercel deployment.

---

## 🗂 Folder Structure

```
leave-management-system/
│
├── index.html
├── dashboard.html
├── apply-leave.html
├── leave-history.html
├── approval.html
├── style.css
├── script.js
├── vercel.json
└── README.md
```

---

## 🛠 Tech Stack

| Layer       | Technology      |
|------------|-----------------|
| Markup     | HTML5           |
| Styling    | CSS3 + Bootstrap 5 |
| Scripting  | JavaScript (Vanilla) |
| Charts     | Chart.js (CDN)  |
| Hosting    | Vercel          |
| Versioning | GitHub          |

---

## ☁️ Deployment Guide (Beginner-Friendly)

### Step 1 — Create the project folder
1. Create a folder named `leave-management-system` on your computer.
2. Save **all the provided files** inside that folder (exact same names).

### Step 2 — Create a GitHub repository
1. Go to <https://github.com> and log in.
2. Click **+ → New repository**.
3. Name it `leave-management-system`.
4. Choose **Public**, do NOT add README (you already have one).
5. Click **Create repository**.

### Step 3 — Upload files to GitHub (no Git knowledge needed)
1. On the new repo page, click **"uploading an existing file"**.
2. Drag and drop **all the files** from your folder.
3. Click **Commit changes**.

### Step 4 — Connect GitHub to Vercel
1. Go to <https://vercel.com> and sign in **with GitHub**.
2. Click **Add New → Project**.
3. Select your `leave-management-system` repo → **Import**.
4. Leave all settings as default (Framework Preset: **Other**).
5. Click **Deploy**.

### Step 5 — Get your live public URL
- After 30–60 seconds Vercel gives a URL like:
  `https://leave-management-system-yourname.vercel.app`
- Open it — your project is LIVE 🎉.

### Common Mistakes & Fixes
| Problem | Fix |
|--------|-----|
| 404 on a page | Filenames must match exactly (case-sensitive on Vercel). |
| CSS not loading | Ensure `style.css` is in the **same folder** as the HTML files. |
| Charts not showing | Internet required (Chart.js loads via CDN). |
| Vercel build fails | Make sure no `package.json` exists — it’s a static site. |

---

## 📸 Submission Checklist

**Screenshots to take:**
1. GitHub repository page (showing all files).
2. Vercel dashboard showing successful deployment.
3. Live deployed URL — all 5 pages:
   - Home, Dashboard, Apply Leave, Leave History, Approvals.
4. Browser address bar showing the `.vercel.app` URL.

**Links to submit:**
- ✅ GitHub Repo URL
- ✅ Live Vercel URL

**Proof of deployment success:**
- Vercel "Ready" green status badge
- Live site opens without errors

---

## 🎓 Viva Q&A — Quick Answers

**Q1. Why frontend-only architecture?**
> It is lightweight, fast, and ideal for demonstrating UI and cloud deployment. No server cost, easy to host on static platforms like Vercel.

**Q2. Why Vercel?**
> Vercel offers free, instant deployment with global CDN, automatic HTTPS, and seamless GitHub integration — perfect for static frontend projects.

**Q3. What is CI/CD?**
> CI/CD = Continuous Integration / Continuous Deployment. Every time we push code to GitHub, Vercel automatically rebuilds and redeploys the site — no manual steps.

**Q4. Why GitHub integration?**
> GitHub provides version control and collaboration. Combined with Vercel, every commit triggers an auto-deployment, enabling true CI/CD.

**Q5. What are the cloud benefits?**
> Scalability, global availability, zero infrastructure management, automatic HTTPS, free SSL, instant rollbacks, and pay-as-you-go pricing.

---

## 👨‍💻 Author

Built as a **Cloud Computing Assignment** project — demonstrating GitHub + Vercel CI/CD deployment.
