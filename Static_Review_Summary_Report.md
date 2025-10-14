# 🧪 Static Review Summary Report

## 👤 Student Information

- **Full Name:** [Your Full Name]  
- **Cohort:** [e.g., October 2025]  
- **Date:** [Submission Date]  

---

## 🧪 What I Reviewed

| Review Type           | Description                                                                 |
|-----------------------|-----------------------------------------------------------------------------|
| Documentation Review  |The requirements.md document is well-structured, separating Functional Requirements (FR) and Non-Functional Requirements (NFR). Each requirement is clearly numbered and concise, covering key system behaviors such as image display, filtering, and lightbox interaction.
Strengths:
Clear and consistent formatting using functional and non functional numbering.
Logical grouping of requirements under image display, filtering, and lightbox.
Improvement Areas:
Add measurable performance goals gallery loads within 3 or 2 seconds.
Specify supported browsers Chrome, Firefox, Edge..
Add explicit accessibility requirements — alt text, keyboard navigation
| Code Review           | 
Strengths:
Clean and readable code structure.
Proper use of classes and IDs for CSS/JS hooks.
Filtering logic is intuitive and easy to extend.
Improvement Areas:
Add comments explaining key JavaScript functions.
Use external CSS and JS files to improve maintainability.
Implement responsive design for mobile device
| SonarQube Analysis    | Code Smells: Minor – mostly due to inline JavaScript and repeated DOM queries.
Security Issues: None detected.

---

## 🐛 Issues Identified

| Issue Type            | Description                                                                 |
|-----------------------|-----------------------------------------------------------------------------|
| Manual Code Review    |There’s no input validation when filtering images — leading to potential empty display states.
| SonarQube             | SonarQube flagged several code smells, including duplicated document object model query statements and missing semicolons in inline scripts. |
| Best Practices      |The gallery also doesn’t include responsive meta tags, limiting usability on mobile devices.

**GitHub Issues Filed:**  
https://github.com/AWOUREMILY/wk3-test/issues/1  
https://github.com/AWOUREMILY/wk3-test/issues/2 


---

## 💬 Reflection

1. **What did you learn from reviewing this code?**  
   the requirements.md review, I gained a better understanding of how to structure and document functional and non-functional requirements clearly.
 reviewing gallery.html, I realized that accessibility and performance improvements are often overlooked in simple projects but are crucial for good web design.
2. **Which part of the code or documentation had the most issues?**  
   The gallery.html file had the most issues, especially related to inline JavaScript, lack of accessibility tags (alt, aria), and repetitive document object model queries. These problems likely occurred because the initial focus was on achieving basic functionality rather than applying best practices in web development.
3. **What testing strategy worked best for you?**  
  SonarQube was very effective at detecting maintainability concerns and code smells such as repeated DOM operations

4. **What was challenging during this assignment?**  
   The most challenging part was interpreting some of the SonarQube results and understanding which issues were critical versus minor. It also took time to identify how accessibility could be improved without changing the layout. Learning to connect documentation feedback, code issues, and GitHub issue tracking in one workflow was a valuable experience.

---

## ✅ Checklist

- [ ] I reviewed the `requirements.md` document for clarity and completeness.  
- [ ] I performed a manual review of `gallery.html`, identifying at least 3 issues.  
- [ ] I analyzed the code using SonarQube and documented at least 3 key issues.  
- [ ] I filed at least 3 GitHub issues based on my findings.  
- [ ] I completed this Static Review Summary and reflected on the process.
![alt text](<Summary - wk3-test in AWOUREMILY SonarQube Cloud - Google Chrome 10_13_2025 8_17_21 PM.png>)