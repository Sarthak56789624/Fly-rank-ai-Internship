# Week 04 – Three Roads: Choosing My Portfolio Stack

## My Constraints

* **Budget:** Free only
* **Skill Level:** Intermediate. I am comfortable with HTML, CSS, JavaScript, Java, Python, React basics, GitHub, and AI tools, but I am still learning full-stack development.
* **Portfolio Requirements:** My portfolio should include:

  * Home/About Me
  * Skills
  * Projects (AI/ML, Android, Web Development)
  * Certifications
  * Internship Experience
  * Resume
  * Contact Information
* **Content Display Requirements:**

  * Image galleries for project screenshots
  * GitHub repository links
  * Live demo links where available
  * Detailed project descriptions
  * Easy navigation between projects
* **Dynamic Features Needed:** Not yet. A static portfolio is enough for now.

---

# Option 1 – HTML, CSS, JavaScript + GitHub Pages (Simplest)

### How I would build

Develop a responsive static website using HTML, CSS, and JavaScript.

### Free Hosting

GitHub Pages

### Backend Required

No

### Trade-off

Very easy to build and maintain, but adding new features later (blogs, contact forms, authentication, dashboards) requires more manual work.

---

# Option 2 – React + Vite + Netlify (Chosen)

### How I would build

Create reusable React components with Vite, organize projects into separate cards/pages, and deploy using Netlify.

### Free Hosting

Netlify

### Backend Required

No

### Trade-off

Slightly more setup than a static website, but much easier to scale, maintain, and improve in the future.

---

# Option 3 – MERN Stack (React + Node.js + Express + MongoDB Atlas)

### How I would build

Develop a complete full-stack portfolio with React frontend, Express/Node backend, and MongoDB Atlas database.

### Free Hosting

Netlify (Frontend)
Render (Backend)
MongoDB Atlas (Database)

### Backend Required

Yes

### Trade-off

Very powerful and flexible, but it takes significantly more time to build, deploy, debug, and maintain.

---

# Pressure Test

### What breaks if I pick the simplest?

Nothing important breaks today because I only need a portfolio. However, adding dynamic features later would require restructuring the project.

### What do I maintain if I pick the most powerful?

I would need to maintain the frontend, backend, database, APIs, deployments, environment variables, and security updates. That is unnecessary for my current needs.

### Can I finish in two weeks?

* HTML/CSS/JS: Yes
* React + Vite: Yes
* MERN Stack: Probably not without sacrificing quality.

### Does it show my work the way it needs to be shown?

Yes. React supports image galleries, project cards, GitHub links, live demos, certificates, and detailed project pages while keeping the interface clean and responsive.

---

# Final Decision (My Rationale)

I chose **React + Vite with Netlify** because it gives me the best balance between simplicity and future growth. It is completely free, does not require a backend, and is capable of displaying all my projects, screenshots, GitHub repositories, live demos, certificates, and resume in a professional way.

I considered building the portfolio using plain HTML, CSS, and JavaScript because it is the easiest option. However, I expect to add more projects over time, so React's component-based structure will make updates easier.

I also considered using the MERN stack. Although it is the most powerful option, I do not need a backend yet. It would increase development time and maintenance without providing meaningful benefits for a portfolio website.

**Can I maintain this?** Yes. React with Vite is simple enough for me to manage while still helping me improve my frontend skills.

**Does it show my work well?** Yes. It supports project galleries, screenshots, GitHub links, live demos, certifications, internship experience, and detailed project information in a clean and professional layout.

Therefore, **React + Vite + Netlify** is the best choice for my portfolio at this stage.
