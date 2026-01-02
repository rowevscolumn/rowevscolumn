# Welcome to the GitHub of Christopher Rowe

<div align="center">

[![Portfolio](https://img.shields.io/badge/Portfolio-D62598?style=for-the-badge&logo=google-chrome&logoColor=white)](https://rowevscolumn.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](www.linkedin.com/in/ChristopherJamesRowe)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mrchristopherrowe@gmail.com)

</div>

---

## 👋 Introduction

My name is Christopher and I'm a DevOps manager and aspiring data engineer and machine learning enthusiast based in Toronto, Canada. I've worked in the field of script writing with Perl and Python, text manipulation, semi-structured data, and databases for many years. I started working solely with Perl, but in 2019 I returned to University to study data science, NoSQL databases and machine learning.

Currently I work part-time at the same university as a Teaching Assistant, where I perform presentations on how to use multiple programs and processes, including MySQL, MongoDB, Python, and R. I love helping students have those "aha!" moments when complex concepts finally click.

My hobbies include playing games of all kinds (video games, board games, poker), watching sports (baseball, hockey, American football), and building data pipelines at 2am because "just one more feature."

---

## 🎯 Currently

```javascript
const christopher = {
    working_on: [
        "🌊 Building data pipelines with Apache Airflow",
        "🤖 Exploring LLMs and RAG implementations",
        "📊 Modernizing my GitHub portfolio",
        "🏠 Expanding my self-hosted homelab"
    ],
    learning: [
        "FastAPI ⚡",
        "Advanced Docker patterns 🐳",
        "Data engineering best practices"
    ],
    currently_reading: "Designing Data-Intensive Applications by Martin Kleppmann",
    currently_listening: "Zelda Lofi Beats 🎵",
    goals_2026: [
        "Contribute to open source projects",
        "Build innovative data engineering tools",
        "Reach 1000+ stars across all repositories",
        "Finally finish that side project (you know the one)"
    ],
    ask_me_about: [
        "Data pipelines and ETL workflows",
        "Python automation and scripting",
        "Neo4j and graph databases",
        "Why Super Metroid is objectively the best game ever made",
        "Teaching and mentoring in tech"
    ]
};
```

---

## 💻 About Me in Python

```python
import os
import sys
from datetime import datetime
from typing import List, Dict, Optional

class ChristopherRowe:
    """
    An aspiring data engineer who codes, teaches, and occasionally remembers to commit.

    Attributes:
        Personality traits, professional info, and strong opinions about GIFs.
    """
    def __init__(self, *args, **kwargs) -> None:
        # Personal Info
        self.first_name: str = "Christopher"
        self.last_name: str = "Rowe"
        self.pronouns: List[str] = ['he', 'him']
        self.location: Dict[str, str] = {
            'City': "Toronto",
            'Province': "Ontario",
            'Country': "Canada"
        }
        self.sports_team_cheered: Dict[str, str] = {
            'Baseball': "Toronto Blue Jays",
            'Hockey': "Toronto Maple Leafs",
            'Football': "Buffalo Bills"
        }
        self.languages: List[str] = ['en_US']

        # Favorites (The Important Stuff)
        self.favourite: Dict[str, str] = {
            'Colour': "#D62598",
            'Video Game': 'Super Metroid',
            'Movie Trilogy': 'Back To The Future',
            'Incense Scent': 'Lavender',
            'Tea': "Twining's Peppermint & Creamy Vanilla",
            'Ninja Turtle': 'Raphael',
            'Minecraft Wood Type': 'Spruce',
            'Pizza': 'Pepperoni, Sausage, Bacon, Tomato',
            'Zelda Game': 'Breath of the Wild'
        }

        # Professional Attributes
        self.current_role: str = "Teaching Assistant & Aspiring Data Engineer"
        self.open_to: List[str] = [
            'Job Opportunities',
            'Collaboration',
            'Coffee/Tea Chats',
            'Discussing tabs vs spaces'
        ]

        # Strong Opinions, Loosely Held
        self.is_iso8601_compliant: bool = True
        self.its_pronounced: str = 'gif'  # Fight me
        self.is_die_hard_a_christmas_movie: bool = True  # Obviously
        self.best_star_wars: str = 'Empire Strikes Back'
        self.pineapple_on_pizza: bool = True  # Some hills are worth dying on

        # Status
        self.currently_working_on: str = "Improving my GitHub presence in 2026"
        self.commits_this_year: int = 0  # But it's only January 1st!
        self.coffee_consumed_today: int = 0  # This will increase

    def __str__(self) -> str:
        return f"{self.first_name} {self.last_name} - {self.current_role}"

    def __repr__(self) -> str:
        return f"ChristopherRowe(location='{self.location['City']}', coffee_level='critical')"

    def greet(self, name: str = "friend") -> str:
        """Greet someone enthusiastically."""
        return f"Hey {name}! Want to talk about data pipelines? 🚀"

    def eat_delicious(self, food: str = "Tacos") -> str:
        """Consume delicious food. Yum!"""
        approved_foods = ["Tacos", "Pizza", "Burgers", "Sushi"]

        if food in approved_foods:
            return f"Yummm! {food} are the best!"

        return f"{food}? I'll try anything once!"

    def fix_procrastination(self) -> int:
        """
        Fix procrastination issues.

        Returns:
            int: 0, because TODO: Program this later
        """
        # TODO: Actually implement this someday
        # TODO: Add the TODO to the TODO list
        # TODO: Make a TODO list
        return 0

    def sleep(self) -> None:
        """
        Attempt to sleep.

        Raises:
            NotImplementedError: Always. Coffee exists.
        """
        raise NotImplementedError(
            "Sleep function not found. Please submit a pull request. "
            "Or just send coffee. ☕"
        )

    def debug_life(self) -> str:
        """When nothing else works, try the classics."""
        solutions = [
            "Have you tried turning it off and on again?",
            "Did you check the logs?",
            "Is it plugged in?",
            "Works on my machine 🤷",
            "Let me Google that for you..."
        ]
        import random
        return random.choice(solutions)

    def get_current_status(self) -> Dict[str, any]:
        """Check what I'm currently up to."""
        return {
            'working_on': self.currently_working_on,
            'learning': self.currently_learning,
            'mood': '😊',
            'coffee_level': 'Critically low',
            'bugs_fixed_today': 3,
            'bugs_created_today': 4  # Net progress: -1
        }

    def teach(self, topic: str) -> str:
        """Share knowledge with students."""
        return f"Let me explain {topic}... *opens 47 browser tabs*"

    def deploy_to_production(self, on_friday: bool = False) -> str:
        """Deploy code to production."""
        if on_friday:
            return "❌ Nice try. We don't deploy on Fridays."
        return "🚀 Deploying... *crosses fingers*"


# Initialize the instance
me = ChristopherRowe()

# Let's see what I'm up to
print(me.greet("GitHub"))
# Output: "Hey GitHub! Want to talk about data pipelines? 🚀"

print(me.get_current_status())
# Output: {'working_on': '...', 'coffee_level': 'Critically low', ...}
```

---

## 🚀 Featured Projects

<table>

<tr>

<td width="50%">

### 🌊 Airflow Data Pipelines

![Airflow](https://img.shields.io/badge/Apache%20Airflow-017CEE?style=for-the-badge&logo=Apache%20Airflow&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

Automated ETL workflows for cryptocurrency price tracking and analysis. Running on my home server with custom DAGs for data collection, transformation, and analysis.

**Tech Stack:** Python, Apache Airflow, Docker, PostgreSQL, Pandas

</td>

<td width="50%">

### 🏈 NFL Data Science Capstone

![ML](https://img.shields.io/badge/Machine%20Learning-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

Machine learning classification model predicting first down success in NFL running plays. Used multiple algorithms (Logistic Regression, Decision Trees, Random Forest, K-NN) with various sampling techniques.

**Tech Stack:** Python, Pandas, Scikit-learn, Jupyter, Matplotlib

[📂 View Repository →](https://github.com/rowevscolumn/capstone)

</td>
</tr>

<tr>

<td width="50%">

### 🏠 Homelab Docker Infrastructure

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)

Complete self-hosted infrastructure setup including MySQL, MongoDB, Neo4j, Airflow, Prometheus, Grafana, and media services. A learning playground for DevOps and infrastructure automation.

**Tech Stack:** Docker Compose, Prometheus, Grafana, Multiple Databases

</td>

<td width="50%">

### 🎮 Final Fantasy Tactics in Neo4j

![Neo4j](https://img.shields.io/badge/Neo4j-008CC1?style=for-the-badge&logo=neo4j&logoColor=white)
![Graph](https://img.shields.io/badge/Graph%20DB-4DB33D?style=for-the-badge&logo=neo4j&logoColor=white)

Exploring graph database concepts by loading and analyzing Final Fantasy Tactics game data in Neo4j. Understanding relationships between jobs, characters, and battle stages through graph queries.

**Tech Stack:** Python, Neo4j, Graph Databases, Jupyter

[📂 View Repository →](https://github.com/rowevscolumn/FinalFantasyTacticsInNeo4j)

</td>
</tr>

<tr>

<td width="50%">

### 📱 QR Code WiFi Generator

![QR](https://img.shields.io/badge/QR%20Code-000000?style=for-the-badge&logo=qr&logoColor=white)

Simple Python utility to generate WiFi QR codes for parties and gatherings. Because nobody wants to type a 32-character password on their phone.

**Tech Stack:** Python, QR Code Library, JSON

[📂 View Repository →](https://github.com/rowevscolumn/QRCodeForParties)

</td>

<td width="50%">

### 📊 Weight Loss Journey Tracker

![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)

Personal weight tracking application using Python and Pandas. Exports to CSV for Power BI visualization and analysis.

**Tech Stack:** Python, Pandas, Jupyter Widgets, CSV

[📂 View Repository →](https://github.com/rowevscolumn/WeightLossJourney)

</td>
</tr>
</table>

---

## 💻 Tech Stack

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white) ![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white) ![Scikit Learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white) ![Apache Airflow](https://img.shields.io/badge/Apache%20Airflow-017CEE?style=for-the-badge&logo=Apache%20Airflow&logoColor=white) ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white) ![Neo4j](https://img.shields.io/badge/Neo4j-008CC1?style=for-the-badge&logo=neo4j&logoColor=white)

![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white) ![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black) ![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)

</div>

---

## 🛠️ My Skills in YAML

```yaml
Programming Skills:

  Expert (Years of Professional Experience):
    - Python 🐍
    - Perl
    - SQL (MySQL, PostgreSQL, SQLite, Oracle SQL)
    - Pandas & NumPy
    - Jupyter Notebooks
    - XML / JSON / YAML
    - Data Wrangling & ETL
    - Text Processing & Manipulation

  Proficient (Used in Projects & Production):
    - Apache Airflow
    - Docker & Docker Compose
    - Git & GitHub
    - Neo4j (Graph Databases)
    - MongoDB (NoSQL)
    - Machine Learning (Scikit-learn)
    - Data Visualization (Matplotlib, Seaborn)
    - Web Scraping (BeautifulSoup, Scrapy)
    - Power BI
    - Linux / Ubuntu Server
    - Bash Scripting

  Currently Learning (Active in 2026):
    - Kubernetes ☸️
    - FastAPI ⚡
    - LangChain / LLMs 🤖
    - GraphQL
    - Terraform
    - pytest & Test-Driven Development
    - CI/CD Pipelines (GitHub Actions)
    - Advanced Docker Patterns

  On the Radar (Future Learning):
    - Rust 🦀
    - Go (Golang)
    - AWS / Azure Cloud Platforms
    - Apache Cassandra
    - dbt (Data Build Tool)
    - Streamlit
    - Apache Spark
    - TypeScript
    - Homemade pasta (Seriously, why is that a tough to make?)

Teaching & Mentoring:
    - MySQL & PostgreSQL
    - MongoDB & NoSQL Concepts
    - Python for Data Analysis
    - R Programming
    - Data Visualization Best Practices
    - Git & Version Control
```

---

## 📊 GitHub Stats

![Christopher's GitHub Stats](https://github-readme-stats.vercel.app/api?username=rowevscolumn&show_icons=true&theme=radical&hide_border=true&bg_color=0D1117&title_color=D62598&icon_color=D62598&text_color=E6EDF3)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=rowevscolumn&layout=compact&theme=radical&hide_border=true&bg_color=0D1117&title_color=D62598&text_color=E6EDF3)

![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=rowevscolumn&theme=radical&hide_border=true&background=0D1117&ring=D62598&fire=D62598&currStreakLabel=D62598)

[![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=rowevscolumn&theme=github-compact&bg_color=0D1117&color=D62598&line=D62598&point=E6EDF3&hide_border=true)](https://github.com/rowevscolumn)

---

## 🎲 Fun Facts About Me

```sql
-- Fun facts about Christopher, version 2.0
-- Now with more personality and questionable life choices

CREATE DATABASE IF NOT EXISTS christopher_db;
USE christopher_db;

CREATE TABLE fun_facts (
    id INT PRIMARY KEY AUTO_INCREMENT,
    category VARCHAR(50),
    fact VARCHAR(300),
    importance_level ENUM('critical', 'high', 'medium', 'low') DEFAULT 'medium',
    last_updated DATE
);

INSERT INTO fun_facts (category, fact, importance_level, last_updated) VALUES
    ('Movies', 'Can recite Spaceballs verbatim. Yes, the ENTIRE movie.', 'critical', '2026-01-01'),
    ('Music', 'Listens to Zelda Lofi when coding and needs deep concentration.', 'high', '2026-01-01'),
    ('Gaming', 'Always played healers in Overwatch.', 'medium', '2026-01-01'),
    ('Food', 'Burger order: No onions, extra pickles.', 'high', '2026-01-01'),
    ('Gaming', 'Still in the citadel in Hollow Knight: Silksong.', 'critical', '2026-01-01'),
    ('Code', 'Writes commit messages as if future me will actually remember context.', 'high', '2026-01-01'),
    ('Sports', 'Watches hockey, baseball, and football. Argues about playoffs year-round.', 'medium', '2026-01-01'),
    ('Design', 'Has a favorite hex color (#D62598) and uses it in every project.', 'high', '2026-01-01'),
    ('Teaching', 'Gets genuinely excited when students understand SQL JOINs.', 'critical', '2026-01-01'),
    ('Coffee', 'Usually does one coffee in the morning and green tea for the rest of the day.', 'critical', '2026-01-01')

-- Query for a random critical fact
SELECT fact FROM fun_facts
WHERE importance_level = 'critical'
ORDER BY RAND()
LIMIT 1;

-- Because life's too short for boring bios ✨
```

```javascript
const coffeeStats = {
    cups_per_day: 1,
    preferred_type: "Medium Roast",
    milk_or_black: "Black",
    productivity_multiplier: 1.5,
    without_coffee: "ERROR: Productivity not found",
    favorite_brewing_method: "French Press"
};

// WARNING: Do not attempt to interact before first coffee
if (coffeeStats.cups_per_day === 0) {
    throw new Error("Human not initialized. Please add coffee.");
}
```

### **My Top 10 Games of All Time:**

1. 👑 **Super Metroid** (SNES) - The undisputed GOAT
2. 🌆 **Mega Man 2 / Mega Man X** (NES/SNES) - Perfection, best soundtracks ever!
3. 💼 **Phoenix Wright: Ace Attourney** (DS) - Brilliant characters and stories
4. 🎯 **Portal 2** (PC) - Still working on Lemon grenades
5. 🗡️ **Chrono Trigger** (SNES) - Best JRPG ever made
6. 🏰 **Final Fantasy 6** (SNES) - I love 7, but 6 is still the best
7. 🧱 **Minecraft** (PC) - I'm a terrible builder, but love to escape
8. 🚶🏻‍➡️ **Stanley Parable** (PC) - Such a memorable experience
9. ⚔️ **Hades** (PC) - Yeah, I spent way too much time having fun
10. 🪦 **Castlevania: Sympathy of the Night** (PC) - One of the most creative games ever

**Currently Playing:** Hollow Knight Silksong

### **Hardware:**

- 💻 Desktop PC (Custom Built)
- 🖥️ BeeLink Mini PC (Homelab Server)
- ⌨️ Mechanical Keyboard (Because clickity-clack)
- 🖱️ Mouse: Logitech G502, or whichever is cheaper after I throw the mouse

**Software & Tools:**

- **Editor:** VS Code (with way too many extensions)
- **Terminal:** Windows Terminal
- **Theme:** Dark+ (Visual Studio Dark)
- **Browser:** Chrome (for development), Brave (for browsing)
- **Notes:** Obsidian (for organizing chaos)
- **Music:** Spotify (Zelda Lofi while working, 90's mix while on the treadmill)

**Must-Have VS Code Extensions:**

- Python
- Jupyter
- Docker
- GitHub Copilot (hi! 👋)
- Rainbow Brackets
- SqlTools
- TODO Highlight
- Trailing Spaces (Spaces at the end drive me nuts 😁 )

---

## 📫 Let's Connect

I'm always open to interesting conversations and opportunities!

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/rowevscolumn)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](www.linkedin.com/in/ChristopherJamesRowe)
[![Portfolio](https://img.shields.io/badge/Portfolio-D62598?style=for-the-badge&logo=google-chrome&logoColor=white)](https://rowevscolumn.github.io)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mrchristopherrowe@gmail.com)

</div>

### 💼 I'm Open To

- 🚀 **Job Opportunities** in Data Engineering, ML Engineering, or Backend Development
- 🤝 **Collaboration** on open source projects (especially data tools!)
- ☕ **Coffee Chats** about data, tech, video games, or life
- 📚 **Teaching & Mentoring** opportunities
- 🎤 **Speaking** at meetups or conferences
- 💡 **Consulting** on data engineering and pipeline architecture

### 💬 Ask Me About

- Building data pipelines with Apache Airflow
- Docker and containerization strategies
- Neo4j and graph databases
- Teaching technical concepts effectively
- Python best practices and automation
- Why Super Metroid is the greatest game ever made
- Homelab setups and self-hosting
- Coffee optimization techniques

**Best way to reach me:**

- 📧 Email me for professional inquiries
- 💬 Open an issue on one of my repos for technical discussions
- 🐦 Twitter/X for casual tech chat (coming soon!)

---

## 🤝 Contributing to My Projects

Found a bug? Have a cool idea? Want to improve something? I'd love your contribution!

**Steps:**

1. 🍴 Fork the repository
2. 🌿 Create a feature branch (`git checkout -b feature/amazing-feature`)
3. ✨ Make your changes (and make them awesome!)
4. ✅ Commit your changes (`git commit -m 'Add some amazing feature'`)
5. 📤 Push to the branch (`git push origin feature/amazing-feature`)
6. 🎉 Open a Pull Request

**Guidelines:**

- Write clear, descriptive commit messages (future you will thank you)
- Add tests if applicable
- Update documentation
- Follow the existing code style
- Be kind and respectful (we're all learning!)

---

**Last Updated:** January 1, 2026 | **Next Coffee:** Yes

*Thanks for stopping by! Now go forth and build something awesome!* 🚀

<!--
**rowevscolumn/rowevscolumn** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.
Thanks for visiting! May your code compile and your coffee be strong. ☕
-->
