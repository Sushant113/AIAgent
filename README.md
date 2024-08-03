This repository allows you to design, supervise, and execute both autonomous AI agents and teams of agents, leveraging the capabilities of XAgent for advanced reasoning and acting.

- **🔧 Autonomous AI Agents**: Design and oversee standalone AI agents that act autonomously based on their configuration.

- **🧠 Agent Memory**: Equip your AI agents with the ability to retain and recall information, enabling them to make more informed decisions.

- **🔗 Data Sources & Integration**:
  - Connect your AI agents to an array of data sources for efficient information retrieval and processing.
  - Integrate VectorDBs for enhanced data management and querying capabilities.
  - Employ the LlamaIndex (GPT Index) to boost the data framework for your LLM application.

<table align="center" border="0">
  <tr>
    <td align="center"><img src="./apps/ui/src/assets/images/postgres.png" width="50px"><br>Postgres</td>
    <td align="center"><img src="./apps/ui/src/assets/images/mySql.png" width="50px"><br>Mysql</td>
    <td align="center"><img src="./apps/ui/src/assets/images/uploadFile.png" width="50px"><br>Files</td>
    <td align="center"><img src="./apps/ui/src/assets/images/web_black.png" width="50px"><br>WebPage</td>
    <td align="center"><img src="./apps/ui/src/assets/images/notionLogo.png" width="50px"><br>Notion</td>
    <td align="center"><img src="./apps/ui/src/assets/images/google_analytics.png" width="50px"><br>Google Analytics</td>
    <td align="center"><img src="./apps/ui/src/assets/images/firebase.svg" width="50px"><br>Firebase</td>
  </tr>
</table>

- **🛠 Toolkits**: Empower your AI agents with our curated sets of tools, tailor-made for specific tasks.

<table align="center" border="0">
  <tr>
    <td align="center"><img src="./apps/ui/src/assets/tools/google.png" width="35px"><br>SERP</td>
    <td align="center"><img src="./apps/ui/src/assets/tools/webscrapping.png" width="35px"><br>Web Scraper</td>
    <td align="center"><img src="./apps/ui/src/assets/tools/DuckDuckGo.png" width="35px"><br>DuckDuckGo</td>
    <td align="center"><img src="./apps/ui/src/assets/tools/bing.png" width="35px"><br>Bing</td>
    <td align="center"><img src="./apps/ui/src/assets/tools/wikipedia.png" width="35px"><br>Wikipedia</td>
    <td align="center"><img src="./apps/ui/src/assets/tools/arxiv.jpeg" width="35px"><br>Arxiv</td>
    <td align="center"><img src="./apps/ui/src/assets/tools/openweather.svg" width="35px"><br>OpenWeather</td>
  </tr>
  <tr>
    <td align="center"><img src="./apps/ui/src/assets/tools/chart.png" width="35px"><br>Charts</td>
    <td align="center"><img src="./apps/ui/src/assets/tools/twilio.png" width="35px"><br>Twilio</td>
    <td align="center"><img src="./apps/ui/src/assets/tools/twitter.png" width="35px"><br>Twitter</td>
    <td align="center"><img src="./apps/ui/src/assets/tools/instagram.webp" width="35px"><br>Instagram</td>
    <td align="center"><img src="./apps/ui/src/assets/tools/slack.png" width="35px"><br>Slack</td>
    <td align="center"><img src="./apps/ui/src/assets/tools/gmail.png" width="35px"><br>Gmail</td>
    <td align="center"><img src="./apps/ui/src/assets/tools/googleCalendar.png" width="35px"><br>Google Calendar</td>
  </tr>
</table>

- **📊 Chart Generator**: Turn your data into insightful visualizations with our intuitive chart generator.

- **📄 Report Generator**: Streamline report creation with our user-friendly report generator tool.

- **🌐 Community Building**: Engage with a dynamic community to collectively enhance and refine your AI agents.

- **🖥 User Interface (UI)**: Utilize our sleek, user-friendly interface for building and managing your AI agents and their teams.

- **📡 APIs**: Robust APIs ensure smooth integration of AIAgent with other systems and support advanced customizations for your specific needs.

### Pre-requisites

- Docker 🐳
- Docker Compose

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Sushant113/AI_agent_for_SpecificTask
   ```

2. **Navigate to the project directory:**

   ```bash
   cd AIAgent
   ```

3. **Setup Git Hooks**

   ```bash
   chmod +x setup.sh
   ./setup.sh
   ```

4. **Create `.env` file from `.env.example` in `apps/server` directory and configure**
   - **Configure `Azure Web PubSub` using [our guide here](docs/azure.md)**
5. **Create `.env` file from `.env.example` in `zep` directory and configure**

6. 🐳 **Run Docker Compose:**

   ```bash
   docker-compose up --build
   ```

   This will build and start both the React UI and FastAPI services.

## Access the Services

- **React UI**: Open `http://localhost:3000` in your browser.
- **FastAPI Server**: Open `http://localhost:4000` in your browser or API client.

## Directory Structure

```
.
├── apps/
│ ├── ui/ # React UI Application
│ └── server/ # Python FastAPI Server
└── docker-compose.yml # Main Docker Compose File
```

## Tech Stack

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=FastAPI&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-6f7f6f?style=for-the-badge&logo=SQLAlchemy&logoColor=white)
![Xagent]
![Zep](https://img.shields.io/badge/Zep-7e56c2?style=for-the-badge&logo=zep&logoColor=white)
![Postgres](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-B73BFE?style=for-the-badge&logo=vite&logoColor=FFD62E)
![ESLint](https://img.shields.io/badge/eslint-3A33D1?style=for-the-badge&logo=eslint&logoColor=white)
![Prettier](https://img.shields.io/badge/prettier-1A2C34?style=for-the-badge&logo=prettier&logoColor=F7BA3E)

![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white)
![Microsoft Azure](https://img.shields.io/badge/Microsoft_Azure-0089D6?style=for-the-badge&logo=microsoft-azure&logoColor=white)
![AWS](https://img.shields.io/badge/Amazon_AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)

Note: This repository uses XAgent for advanced reasoning and acting, enhancing the capabilities of your autonomous AI agents.