<h1 align="center">LegradiK</h1>
<p align="center">
  Python Developer &nbsp;·&nbsp; Automation &nbsp;·&nbsp; Web Applications &nbsp;·&nbsp; Greater Manchester, UK
</p>
<p align="center">
  <a href="https://legradik.github.io/" target="_blank">
    <img src="https://img.shields.io/badge/Portfolio-legradik.github.io-1a9e9e?style=for-the-badge&logo=googlechrome&logoColor=white" />
  </a>
  &nbsp;
  <a href="https://github.com/LegradiK/LegradiK/raw/main/LegradiK_CV.pdf">
    <img src="https://img.shields.io/badge/Download%20CV-PDF-e05c2a?style=for-the-badge&logo=adobeacrobatreader&logoColor=white" />
  </a>
  &nbsp;
  <a href="mailto:legradi.kaho@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact%20Me-6a5acd?style=for-the-badge&logo=maildotru&logoColor=white" />
  </a>
  &nbsp;
  <a href="https://github.com/LegradiK?tab=repositories" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-LegradiK-2b2b2b?style=for-the-badge&logo=github&logoColor=white" />
  </a>
</p>

---

I'm a self-driven Python developer with a background in customer-facing roles, now focused on building practical automation tools and web applications. I enjoy working through real problems methodically, from debugging CI pipelines to designing clean, modular code. Fluent in English and Japanese.

---

## Skills

<p>
  <img src="https://skillicons.dev/icons?i=python,flask,html,css,js,sqlite,git,github,vscode,linux" />
</p>

`Python` `Flask` `Playwright` `GitHub Actions` `CI/CD` `REST APIs` `Jinja2` `D3.js` `SQLite` `HTML/CSS` `JavaScript` `Git`

---

## Selected Projects

### [KS1 Learning Hub](https://github.com/LegradiK/ks1_learning_hub)
**🔗 Live site: [kidslearninggames.pythonanywhere.com](https://kidslearninggames.pythonanywhere.com/)**<br/>
**Demo login:** username `test` · PIN `1234`

A unified Flask web app where children aged 4–7 can learn, play and log their reading in one place, aligned with the UK KS1 curriculum. Built with Flask blueprints and an app factory pattern, with a shared design system across every section.

**Platform features**
* **Child accounts:** each child signs in with their name and a 4-digit PIN, and their progress is saved to their own account
* **Progress report:** time spent and answers given in each game, plus the number of books read, available from the player menu
* **Subject-based landing page:** content is grouped into School Subjects, Brain Games and My Bookshelf

**My Bookshelf**
* Children search for books and add the ones they've read or are reading, with covers and details fetched automatically from the Google Books API
* Star ratings, short reviews, reread counts and a want-to-read list
* Originally built as a standalone reading tracker, then merged into the hub and restyled to match it

**Games**
* **Letter Quest:** KS1 crossword puzzle with a custom grid engine and a 674-word JSON bank across 22 categories
* **Word Wizard:** phonics quiz using Puter AI for text-to-speech, with a Web Speech API fallback and colour-coded letter feedback
* **Math Drill:** arithmetic practice with four operations, difficulty levels and session-based score tracking
* **Story Detective:** mystery-themed reading comprehension with gap-fill stories and tap-to-place word banks, split into Year 1 and Year 2 levels; stories live in a separate data module so new ones can be added without touching game logic
* **Also:** Sudoku, Coin Counter, Clock Master and Match Pairs, covering logic, money, telling the time and memory

`Python` `Flask` `Flask Blueprints` `Jinja2` `JavaScript` `Google Books API` `Web Speech API` `AI Integration` `Authentication`

---

### [Library Book Renewal Automation](https://github.com/LegradiK/library_books_renewal_automation)
Automated renewal of library books across two platforms (Spydus and BorrowBox) using Python and Playwright. Deployed via GitHub Actions on a daily schedule with secure multi-user credential handling, environment-scoped secrets and screenshot-based CI debugging.

`Python` `Playwright` `GitHub Actions` `CI/CD` `Secrets Management`

---

### [Menu Planner](https://github.com/LegradiK/menu-planner-2)
**🔗 Live site: [kahopythonbookshelf.pythonanywhere.com](https://kahopythonbookshelf.pythonanywhere.com/)** *(free hosting, so the first load may take 30–60s)*
 
A Flask web app that plans a week of meals and turns them into a shopping list. It draws on a library of 130 recipes (mains, desserts and bread) and works out a balanced menu, using each recipe's portion "weight" to decide how many dishes fill the week.
 
* **Menu builder:** generate a random weekly menu or hand-pick recipes, then search, add or delete recipes through the site
* **Smart shopping list:** collects ingredients across the whole menu, cleans up names with regex (dropping descriptors, percentages and notes in brackets), merges duplicates and sorts everything into supermarket categories
* **User accounts and calendar:** Flask-Login authentication with hashed passwords, and a SQLite database (via SQLAlchemy) that saves each confirmed menu to a calendar so past weeks can be reused
* **Weekly email:** a scheduled GitHub Actions workflow emails a fresh menu and shopping list every Friday, with credentials kept in GitHub Secrets
* **Code quality:** CSRF-protected forms with Flask-WTF, modular structure with Flask blueprints, and Pylint run in CI
  
`Python` `Flask` `SQLite` `SQLAlchemy` `Flask-Login` `Flask-WTF` `GitHub Actions` `Jinja2`

---

### [Horizon Intelligence: Space Dashboard](https://github.com/LegradiK/all_about_space_web_app)
Flask and Jinja2 web dashboard aggregating live data from multiple public APIs, including NASA APOD, EPIC, NeoWs, Launch Library 2, AuroraWatch UK and ISS tracking. Features interactive D3.js visualisations and structured data rendering.

`Python` `Flask` `REST APIs` `D3.js` `Jinja2`

---

<h3 align="left">Available for hire</h3>
<p align="left">
  I bring a rare combination of technical ability and strong communication skills, built across software projects, multilingual customer support and cross-cultural collaboration.<br/><br/>
  If you're looking for someone who writes clean code, debugs methodically, and communicates clearly with both technical and non-technical teams, I'd love to hear from you.<br/><br/>
  <a href="mailto:legradi.kaho@gmail.com">
    <img src="https://img.shields.io/badge/Get%20In%20Touch-Email-0077B5?style=for-the-badge&logo=maildotru&logoColor=white" />
  </a>
</p>
