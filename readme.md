🧩 LeetCode Problem Page – UI Clone

A pixel-perfect LeetCode “Problem + Code Editor” page clone built using HTML5, CSS3, and Bootstrap Icons. This project recreates the typical LeetCode interface for problem description and JavaScript coding environment. 

leetcode

🎯 Project Overview

This clone replicates:

Top navigation bar with:

LeetCode logo

Problem set title: “30 Days of JavaScript”

Navigation icons (back, forward, shuffle)

Action buttons (bug, play, submit, notes, settings, timer, premium, etc.)

Split layout using CSS Grid:

Left Panel – Problem statement, examples, constraints, reactions (like/dislike), comments, save, external link, help. 

leetcode

Right Panel – Code editor area UI with:

Language dropdown (JavaScript)

Code snippet for createHelloWorld function

Footer status (saved, cursor position)

TestCase / Test result bar at the bottom. 

leetcode

All icons are from Bootstrap Icons, installed via npm.

🛠 Tech Stack
Technology	Usage
HTML5	Page structure and semantic layout
CSS3	Custom styling, grid layout, dark theme
Bootstrap Icons	Icons for buttons, status, and controls

Dependency defined in package.json: 

package

"dependencies": {
  "bootstrap-icons": "^1.13.1"
}

📦 Installation & Setup

Clone this repository:

git clone <your-repo-link>
cd LeetCode-UI-Clone


Install dependencies:

npm install


This will install bootstrap-icons into node_modules. 

package-lock

Run the project:

Just open the HTML file in your browser:

leetcode.html


Or use a simple live server (like VS Code Live Server extension).

📁 Project Structure
/your-project
│── leetcode.html        # Main UI page
│── package.json         # Dependencies (bootstrap-icons)
│── package-lock.json    # Locked dependency tree
│── /images
│    └── leetcode.jpg    # Logo image used in header
│── /node_modules
     └── bootstrap-icons

✨ Key UI Features

Fully designed dark theme layout 

leetcode

LeetCode-like:

Tabs: Description, Note, Editorial, Solution, Submission

Problem content with examples & constraints

Reaction and actions footer (like, dislike, comments, star, share, help)

Code editor UI with:

JS code template for createHelloWorld

Status footer (Saved, Ln 1, Col 4)

“Login / Sign up to run or submit” banner

Test case section at the bottom-right (TestCase → Test result)

🚀 Possible Improvements

Make layout fully responsive for mobile

Add syntax highlighting using a library (e.g., Prism.js, Monaco)

Add functional run/submit buttons with JavaScript

Dynamically load problems from a JSON file or API

Convert this to a React/Next.js component playground

📜 License

This project uses bootstrap-icons, which are MIT licensed via npm.