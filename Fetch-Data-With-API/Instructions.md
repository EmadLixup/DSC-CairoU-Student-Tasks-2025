# 🎯 Task: GitHub User Search App
<img src="design/preview.jpg" alt="Design preview for the GitHub user search" width="100%" hight="600"/>

## 👋 Welcome!

In this task, you'll build a GitHub User Search App using **React**, **JavaScript**, **CSS** and the **GitHub Users API**
Get it looking as close to the design as possible.

---

## 🧠 What You'll Learn

- Fetching data from an API
- Handling errors and loading states
- React components and state management
- Responsive design
- Light/Dark mode support

---

## 🧪 Your Challenge

Build an app that allows users to search GitHub profiles by username using:

https://api.github.com/users/{username}

Example:  
`https://api.github.com/users/octocat`

---

## ✅ User Stories

Your users should be able to:

- [ ] See hover states for all interactive elements.
- [ ] Search GitHub users by username.
- [ ] See relevant profile data:
  - Name
  - Username
  - Bio
  - Location
  - Website
  - Twitter
  - Company

---

## 💡 Bonus Features

- [ ] Detect and apply light/dark theme based on system preferences (`prefers-color-scheme`)
- [ ] Allow manual toggle between light and dark modes
- [ ] Responsive design for mobile, tablet, and desktop

---

## 🧾 Behavior Expectations

- First load should display **Octocat’s** profile.
- Show **error message** if user is not found when a new search is made.
- If the name is missing, use the **username** in its place.
- If bio is empty, display:  
  `"This profile has no bio"`
- If location, website, Twitter, or company is empty, display:  
  `"Not Available"`
- Make links clickable:
  - Website, Twitter, and Company
  - Remove `@` before linking to the company on GitHub  
    Example: `@github` → `https://github.com/github`

---

## 💼 Assets & Design

All required design assets are in the `assets/` folder. Try to match the design closely.

---

## 🧱 Tools You Can Use

- HTML, CSS, JavaScript
- React.js
- Tailwind CSS or Bootstrap (optional)

---

## 🚀 Deployment (Optional)

You can deploy your project using:

- [GitHub Pages](https://pages.github.com/)
- [Vercel](https://vercel.com/)
- [Netlify](https://www.netlify.com/)

---

## ✍️ Extra Notes

We recommend writing a custom `README.md` for your project after you're done to explain your work and what you’ve learned. We've provided a template inside the [`README-template.md`](./README-template.md) file in this starter code.

The template provides a guide for what to add. A custom `README` will help you explain your project and reflect on your learnings. Please feel free to edit our template as much as you like.

You can use GPT or any AI tool to create it for you.

Once you've added your information to the template, rename the `README-template.md` file to `README.md`. That will make it show up as your repository's README file.

---

## 🙌 Have Fun!

If you need help, ask your instructor or the community for feedback.

Good luck and happy coding! 🚀
