🚀 CSE3232: Emerging Tools & Technology Hub

The "Single Source of Truth" Learning Experience Platform (LXP) for the CSE3232 course at Manipal University Jaipur.

📖 About The Project

This repository hosts the interactive learning hub for the Emerging Tools and Technology course. It is designed as a Single Page Application (SPA) that runs entirely in the browser without requiring a backend server or complex build steps (No Webpack/Node.js required).

It consolidates resources, cheat sheets, simulators, and project ideas into one unified dashboard.

✨ Features

Interactive Dashboard: Visualizes the syllabus, assessment plan, and course goals.

5 Technical Modules:

DevOps: Git branching visualization & GitHub Actions templates.

Containerization: Docker & Kubernetes architecture & commands.

Data Intelligence: Tableau & Power BI learning paths.

AI Engineering: RAG pipelines, LLMs, and Vector DBs.

Future Tech: Quantum Computing & Blockchain simulators.

Capstone Hub: A library of 30 integrated project ideas categorized by difficulty and track (MLOps, Web3, Cloud).

Embedded Simulators: Direct access to tools like LearnGitBranching, Quirk, and Remix IDE.

Zero-Install: Built using React and Tailwind via CDN for maximum portability.

⚡ Quick Start (Local)

Clone the repository:

git clone [https://github.com/your-username/cse3232-hub.git](https://github.com/your-username/cse3232-hub.git)


Open the file:
Simply double-click index.html to open it in your browser (Chrome/Edge/Firefox).

🚀 Deployment Guide (GitHub Pages)

This project is optimized for GitHub Pages.

Push index.html and README.md to your GitHub repository.

Go to the repository Settings.

Click on Pages in the left sidebar.

Under Build and deployment > Branch, select main (or master) and folder / (root).

Click Save.

Wait about 60 seconds. Your site will be live at https://your-username.github.io/cse3232-hub/.

🛠️ Content Management

All content is managed via JSON structures inside the index.html file. You do not need to recompile React code to make changes.

To add a new Lab Resource:

Open index.html.

Search for const courseLabs.

Add your new link object:

{ 
  id: 99, 
  title: "Lab X: New Topic", 
  url: "[https://example.com](https://example.com)", 
  desc: "Description here" 
},


To add a new Capstone Project:

Search for const allProjects.

Add your project object following the existing schema.

🤝 Contributing

Students are encouraged to contribute to this hub!

Fork the Project.

Add a resource or fix a typo in index.html.

Open a Pull Request.

📄 License

Distributed under the MIT License. See LICENSE for more information.

Built for CSE3232 @ MUJ
