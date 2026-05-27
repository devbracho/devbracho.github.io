P1ro's Portfolio
Welcome to my personal portfolio, showcasing my expertise as a system administrator and DevOps enthusiast. This site highlights my best GitHub projects, Coursera certifications, and professional journey in Linux, Python, and cloud technologies. Built with React and Tailwind CSS, it’s hosted on GitHub Pages at https://p1ro.github.io.
About
I’m a seasoned system administrator with over 10 years of experience in Linux server management, Python scripting, and DevOps practices. I specialize in automating processes, deploying cloud infrastructure, and tackling complex technical challenges. Currently, I’m advancing my skills in DevOps tools like Docker, Kubernetes, and AWS, aiming for a full-time DevOps role.
Features

About Section: A brief bio and GitHub stats showcasing my contributions.
Projects Section: Highlights key projects like syspynfo, odoo-examples, remove_file_comments, and ppdisbot, with descriptions and tech stacks.
Courses Section: Displays Coursera certifications in AWS, DevOps, and Python.
Contact Section: Links to my LinkedIn, Upwork, and GitHub, plus a downloadable resume.
Dark Mode: Responsive design with a dark theme, styled using Tailwind CSS.
SEO: Optimized meta tags for better discoverability.

Tech Stack

Frontend: React (via CDN), JavaScript, JSX
Styling: Tailwind CSS (dark mode enabled)
Hosting: GitHub Pages
Dependencies: Babel (for JSX), GitHub Readme Stats (for contribution visuals)

Setup Instructions
To run or modify this portfolio locally:

Clone the Repository:
git clone https://github.com/P1ro/p1ro.github.io.git
cd p1ro.github.io


Install Dependencies:No local dependencies are required since React and Tailwind CSS are loaded via CDNs. However, ensure you have a static server for local development (e.g., using Python or Node.js).

Run Locally:Use a simple HTTP server to preview the site:
python3 -m http.server 8000

Open http://localhost:8000 in your browser.

Deploy to GitHub Pages:

Push changes to the main branch (or gh-pages if configured).
Enable GitHub Pages in the repository settings under Settings > Pages, selecting the main branch.
Visit https://p1ro.github.io to see the live site.


Add Resume (optional):

Place a resume.pdf file in the repository root for the download link in the Contact section to work.



Project Structure
p1ro.github.io/
├── index.html        # Main portfolio page with React components
├── resume.pdf        # (Optional) Resume file for download
└── README.md         # This file

Customization

Styling: Modify Tailwind CSS classes in index.html or add a custom config via ?with=config in the Tailwind CDN URL.
Content: Update project details, course links, or bio in the React components within index.html.
Features: Add interactivity (e.g., project filters) by extending React components or include Google Analytics by adding their script to the <head>.

Contributing
Contributions are welcome! To suggest improvements:

Fork the repository.
Create a new branch (git checkout -b feature-name).
Make changes and commit (git commit -m "Add feature").
Push to the branch (git push origin feature-name).
Open a pull request.

Contact
Reach out via:

LinkedIn
Upwork
GitHub

License
© 2025 P1ro. All rights reserved.