 AI Jobs Market Analysis — SQL Project

 A structured SQL dataset of real-world AI & tech job listings scraped from Adzuna, covering roles across MLOps, Computer Vision, NLP, Data Science, and more — sourced from the United States job market (2024–2026).



 Project Overview

This project contains a curated SQL dataset of AI and technology job postings collected from the Adzuna job board. The data includes detailed information about job titles, companies, salaries, required skills, experience levels, remote work types, and job descriptions.

The goal of this project is to enable data-driven analysis of the AI job market — helping recruiters, job seekers, analysts, and researchers understand trends in AI hiring, salary distribution, in-demand skills, and geographic demand.



 Database Schema

The dataset is loaded into a table named `ai_jobs` within the `ai_jobs` database.

### Table: `ai_jobs`

| Column | Data Type | Description |
|---|---|---|
| `job_title` | VARCHAR | Title of the job position |
| `company` | VARCHAR | Name of the hiring company |
| `country` | VARCHAR | Country of the job listing |
| `city` | VARCHAR | City of the job listing |
| `salary_min` | DECIMAL | Minimum salary offered (USD) |
| `salary_max` | DECIMAL | Maximum salary offered (USD) |
| `currency` | VARCHAR | Currency of salary (primarily USD) |
| `remote_type` | VARCHAR | Work type: Remote / Hybrid / Onsite / Unspecified |
| `experience_level` | VARCHAR | Required experience level (Junior / Mid-level / Senior / Lead / Management) |
| `required_skills` | VARCHAR | Key skills mentioned in the posting (e.g., Python, AWS, SQL) |
| `posted_date` | DATE | Date the job was posted (DD-MM-YYYY) |
| `source` | VARCHAR | Job board source (Adzuna) |
| `job_description` | TEXT | Full or partial job description text |



 Job Categories Covered

The dataset includes jobs across the following AI and tech domains:

- **MLOps / LLMOps** — ML pipeline engineers, platform engineers, DevOps + ML hybrid roles
- **Computer Vision** — CV engineers, perception engineers, deep learning specialists
- **Natural Language Processing (NLP)** — NLP engineers, LLM fine-tuning specialists
- **Data Science & ML Engineering** — Applied scientists, ML engineers, data platform roles
- **AI Infrastructure** — Cloud engineers, GPU cluster engineers, AI deployment roles
- **Management & Leadership** — Engineering managers, directors, senior directors in AI



 Companies Featured

The dataset includes job postings from a wide range of organizations:

| Type | Examples |
|---|---|
| Big Tech | Google, Meta, NVIDIA, Oracle, JPMorgan Chase, Bloomberg |
| AI-First Startups | Mistral AI, TRM Labs, Galileo, CreatorIQ, Sesame |
| Defense Tech | Anduril Industries, Leidos, General Dynamics, Blue Origin |
| Healthcare AI | Intermountain Health, IMO Health, PathAI, Kouper Health |
| Robotics | Bonsai Robotics, Dexterity, Corvus Robotics, Maven Robotics |
| Universities & Research | Brandeis University, University of Miami |






 Tools & Technologies

| Tool | Purpose |
|---|---|
| **MySQL** | Database engine used to load and query the dataset |
| **SQL** | Data querying and analysis language |




 Repository Structure

📦 ai-jobs-sql-project/
 ┣ 📄 AI_JOBS.sql        — Full dataset with INSERT statements
 ┗ 📄 README.md          — Project documentation (this file)



 Key Insights from the Data

- **Salary Range:** AI roles in the dataset range from ~$41,000 (intern-level) to over $400,000 (senior/lead roles at top startups).
- **Top Employers:** JPMorgan Chase, Anduril Industries, Oracle, Warner Bros. Discovery, and Intermountain Health appear frequently.
- **Most Demanded Skills:** Python, AWS, SQL, PyTorch, TensorFlow, Kubernetes, and Computer Vision appear most often in `required_skills`.
- **Remote Availability:** A significant portion of listings are fully remote or hybrid, especially for senior-level roles.
- **Date Coverage:** Listings span from mid-2024 through early 2026, giving a current view of the AI job landscape.



 Author

**Chaitanya Bhendarkar**
Data Analyst | SQL • Python • Power BI • Excel

- 🔗 GitHub: [github.com/Chaitanya1704](https://github.com/Chaitanya1704)

---

## 📜 License

This project is intended for **educational and portfolio purposes only**. The job data was sourced from publicly available listings on Adzuna. No commercial use intended.



> ⭐ *If you found this project useful, consider giving it a star on GitHub!*
