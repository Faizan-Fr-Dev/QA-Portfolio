Viewed media_1793098847830.png:1-800
Ran command: `python -c "from PIL import Image; img = Image.open(r'C:\Users\Faizan Butt\.gemini\antigravity\brain\8077e112-a55e-41c8-9031-f76b78ccb3de\.user_uploaded\media_1793098847830.png'); print(img.size)"`
Ran command: `powershell -Command "Add-Type -AssemblyName System.Drawing; $img = [System.Drawing.Image]::FromFile('C:\Users\Faizan Butt\.gemini\antigravity\brain\8077e112-a55e-41c8-9031-f76b78ccb3de\.user_uploaded\media_1793098847830.png'); Write-Output ('Width: ' + $img.Width + ' Height: ' + $img.Height)"`
Ran command: `Add-Type -AssemblyName System.Drawing
$img = [System.Drawing.Image]::FromFile('C:\Users\Faizan Butt\.gemini\antigravity\brain\8077e112-a55e-41c8-9031-f76b78ccb3de\.user_uploaded\media_1793098847830.png')
Write-Host "Width: $($img.Width) Height: $($img.Height)"
$img.Dispose()
`
Listed directory FP
Viewed README.md:1-173
Ran command: `curl -s https://api.github.com/users/Faizan-Fr-Dev/repos`

Here is your complete, ready-to-use **GitHub `README.md`** formatted to match the exact design, dark-mode aesthetic, card layouts, and visual hierarchy from your photo—using **only** your provided content without altering or removing anything.

You can copy the entire block below and paste it directly into your GitHub repository or profile `README.md`:

```markdown
<div align="left">
  <h1>Muhammad Faizan</h1>
  <p><b>Aspiring Manual QA Engineer | Final-Year Computer Science Student</b></p>
</div>

> Welcome to my Quality Assurance (QA) portfolio! This repository showcases my hands-on practice in manual software testing, web application testing, and REST API testing.  
> I am a final-year Computer Science student seeking opportunities as a **Manual QA Tester**, **QA Intern**, **QA Trainee**, or **Junior QA Engineer**. I focus on designing test scenarios, executing test cases, identifying defects, and documenting actual results against expected behavior.

---

### 📌 Profile and Summary

* 🎓 **Education:** Bachelor's Degree in Computer Science — University of Engineering & Technology, Lahore
* 📊 **CGPA:** 3.61 / 4.0
* 📍 **Location:** Lahore, Pakistan
* 🎯 **Role:** Aspiring Manual QA Engineer
* 🔍 **Interests:** Manual Testing, Functional Testing, Regression Testing, API Testing, and Defect Reporting
* 🎯 **Career Objective:** I am looking for an entry-level QA opportunity where I can contribute to software quality, collaborate with developers and testers, and continue developing my skills in manual testing and API testing.
* 💡 **What I Am Learning:** I am continuing to strengthen my software testing skills through hands-on practice with web applications and APIs, focusing on test design, defect investigation, clear documentation, and reliable verification of application behavior.

---

### 🛠 Technical Stack

<p align="left">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=postman,git,github,js,react,nodejs,express,mongodb,html,css,vscode" alt="Tech Stack Icons" />
  </a>
</p>

* **Manual Testing:** Functional Testing, Smoke Testing, Sanity Testing, Regression Testing, Retesting, Positive Testing, Negative Testing
* **Test Design:** Test Scenarios, Test Cases, Boundary Value Analysis, Equivalence Partitioning
* **API Testing:** Postman, REST APIs, HTTP Methods, HTTP Status Codes, JSON Payloads, Authentication Testing
* **QA Documentation:** Test Execution Reports, Bug Reports, Expected vs. Actual Results, Test Closure Reports
* **Tools:** Postman, Git, GitHub, Chrome DevTools
* **Additional Technical Knowledge:** HTML, CSS, JavaScript, React.js, Node.js, Express.js, MongoDB

---

### 🚀 QA Projects

<table>
  <tr>
    <td width="65%" valign="top">
      <h3>🛒 1. OpenCart E-commerce Manual Testing</h3>
      <p><b>Project Type:</b> Web Application Manual Testing</p>
      <p>Performed manual testing of an OpenCart e-commerce application, focusing on key user workflows and documenting test execution results and defects.</p>
      <h4>Testing Activities</h4>
      <ul>
        <li>Designed and executed test cases for registration, login, product search, product details, and shopping cart workflows.</li>
        <li>Recorded 491 test executions: 466 PASS, 11 FAIL, and 14 BLOCKED.</li>
        <li>Prepared defect reports documenting observed issues and relevant testing details.</li>
        <li>Compared actual results with expected results.</li>
        <li>Prepared test documentation, including test cases, execution results, bug reports, and a test closure report.</li>
      </ul>
      <p>
        <b>Testing Focus:</b> <code>Functional Testing</code> • <code>Negative Testing</code> • <code>Regression Testing</code> • <code>Defect Reporting</code> • <code>Test Documentation</code>
      </p>
      <p>
        <a href="https://github.com/Faizan-Fr-Dev/QA-Portfolio">
          <img src="https://img.shields.io/badge/Project_Repository-OpenCart_Manual_Testing-181717?style=for-the-badge&logo=github&logoColor=white" alt="OpenCart Repository" />
        </a>
      </p>
    </td>
    <td width="35%" valign="top" align="center">
      <br/>
      <img src="https://img.shields.io/badge/Total_Executions-491-blue?style=for-the-badge" alt="Total Executions" />
      <br/><br/>
      <img src="https://img.shields.io/badge/PASS-466-2ea44f?style=for-the-badge" alt="Pass" />
      <br/><br/>
      <img src="https://img.shields.io/badge/FAIL-11-cf222e?style=for-the-badge" alt="Fail" />
      <br/><br/>
      <img src="https://img.shields.io/badge/BLOCKED-14-d29922?style=for-the-badge" alt="Blocked" />
    </td>
  </tr>
</table>

<table>
  <tr>
    <td width="35%" valign="top" align="center">
      <br/><br/>
      <img src="https://img.shields.io/badge/Postman_Collection-27_Requests-FF6C37?style=for-the-badge&logo=postman&logoColor=white" alt="Postman Requests" />
      <br/><br/>
      <img src="https://img.shields.io/badge/Format-REST_&_JSON-0969da?style=for-the-badge" alt="REST and JSON" />
      <br/><br/>
      <img src="https://img.shields.io/badge/Auth-JWT_Testing-8957e5?style=for-the-badge" alt="Authentication" />
    </td>
    <td width="65%" valign="top">
      <h3>🍽️ 2. Tasty Foods REST API Testing</h3>
      <p><b>Project Type:</b> Manual API Testing using Postman</p>
      <p>Tested REST API endpoints for a food delivery application, covering customer-facing functionality and administrative operations.</p>
      <h4>Testing Activities</h4>
      <ul>
        <li>Worked with a Postman collection containing 27 API requests.</li>
        <li>Tested authentication, product catalog, search, orders, admin operations, newsletter, wishlist, and cart functionality.</li>
        <li>Tried valid and invalid inputs to examine API behavior.</li>
        <li>Inspected HTTP status codes and JSON request/response payloads.</li>
        <li>Compared actual responses against expected behavior and investigated unexpected results.</li>
      </ul>
      <p>
        <b>Testing Focus:</b> <code>Postman</code> • <code>REST APIs</code> • <code>Positive Testing</code> • <code>Negative Testing</code> • <code>Authentication Testing</code> • <code>JSON</code>
      </p>
      <p>
        <a href="https://github.com/Faizan-Fr-Dev/QA-Portfolio">
          <img src="https://img.shields.io/badge/Project_Repository-Tasty_Foods_API_Testing-181717?style=for-the-badge&logo=github&logoColor=white" alt="Tasty Foods API Repository" />
        </a>
      </p>
    </td>
  </tr>
</table>

---

### 💼 Professional Experience

<table>
  <tr>
    <td width="50%" valign="top">
      <h4>🏢 Full Stack Developer Intern — GenIteams</h4>
      <p>📅 <i>July 2026 – August 2026</i></p>
      <ul>
        <li>Developed features for a full-stack food delivery application using the MERN stack.</li>
        <li>Worked on customer-facing storefront and admin dashboard functionality.</li>
        <li>Developed REST APIs using Node.js and Express.js with MongoDB.</li>
        <li>Implemented JWT authentication and bcrypt password hashing.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h4>🏢 Front End Web Developer Intern — DevelopersHub Corporation</h4>
      <p>📅 <i>December 2025 – February 2026</i></p>
      <ul>
        <li>Developed features for a React-based web application.</li>
        <li>Implemented dashboards, scheduling modules, and reusable UI components.</li>
        <li>Worked on document management functionality, including file upload and preview.</li>
        <li>Enhanced role-based interfaces and authentication-related UI functionality.</li>
      </ul>
    </td>
  </tr>
</table>

---

### 📊 GitHub Contributions

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Faizan-Fr-Dev&theme=tokyo-night&hide_border=true&area=true" width="100%" alt="Faizan's Activity Graph" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Faizan-Fr-Dev&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117" width="48%" alt="GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Faizan-Fr-Dev&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117" width="48%" alt="Top Languages" />
</p>

---

### 🌐 Connect with Me

```json
{
  "name": "Muhammad Faizan",
  "role": "Aspiring Manual QA Engineer",
  "education": "Bachelor's in Computer Science @ UET Lahore",
  "location": "Lahore, Pakistan",
  "github": "https://github.com/Faizan-Fr-Dev",
  "linkedin": "https://www.linkedin.com/in/muhammad-faizan-a45b6b3a1/"
}
```

<p align="center">
  <a href="https://github.com/Faizan-Fr-Dev" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-Faizan--Fr--Dev-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
  &nbsp;&nbsp;
  <a href="https://www.linkedin.com/in/muhammad-faizan-a45b6b3a1/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-Muhammad_Faizan-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
</p>

<p align="center">
  <i>Thank you for visiting my QA portfolio!</i>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0052cc,100:2684ff&height=80&section=footer" width="100%" alt="Footer Wave" />
</p>
```
