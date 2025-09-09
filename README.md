# Linkedin-JobTracker-AutoNotifie
Automate your LinkedIn job tracking and notifications with crewAI!
This project sets up a multi-agent AI system to monitor, track, and notify you about relevant LinkedIn jobs—powered by the flexible and powerful crewAI
 framework.

With just a few steps, you’ll have your intelligent crew of AI agents working together to save time and streamline your job application process.

📦 Installation
Requirements

Python: >=3.10 <3.14

Package Manager: UV
 (fast dependency management)

Setup

Install uv if not already installed:

pip install uv


Navigate to your project directory and install dependencies:

crewai install

⚙️ Customization

Before running the project, configure your environment and agents:

Add your OpenAI API key to the .env file:

OPENAI_API_KEY=your_api_key_here


Configure your agents and tasks:

src/linkedin_job_tracker_auto_notifier/config/agents.yaml → Define agents and their roles

src/linkedin_job_tracker_auto_notifier/config/tasks.yaml → Define tasks and objectives

src/linkedin_job_tracker_auto_notifier/crew.py → Add tools, logic, or custom args

src/linkedin_job_tracker_auto_notifier/main.py → Add custom inputs

▶️ Running the Project

Start your crew of AI agents from the project root:

crewai run


By default, the agents will collaborate to generate a report.md file in the root folder, showcasing a research task example (you can replace it with LinkedIn job tracking workflows).

🧠 Understanding Your Crew

The LinkedinJobTrackerAutoNotifier Crew is powered by multiple specialized AI agents. Each agent has unique:

Roles → What they do

Goals → Why they exist

Tools → How they achieve tasks

These configurations live in:

config/agents.yaml → Define capabilities

config/tasks.yaml → Define workflows

The agents collaborate seamlessly to achieve complex objectives—like monitoring LinkedIn jobs and sending smart notifications.

🤝 Support

For help, questions, or feedback:

📖 Documentation

💻 GitHub Repository

💬 Join our Discord

🤖 Chat with our Docs
