# Act2Learn

**Act2Learn** is a collaborative digital platform that transforms academic support into a lever for sustainable development. [cite_start]By combining personalized learning with civic engagement, Act2Learn addresses critical **Sustainable Development Goals (SDGs)**, bridging the gap between academic success and social responsibility[cite: 2, 3].

## 🎯 Project Mission & Impact

According to our strategic analysis, Act2Learn focuses on transversal impact across multiple SDGs:

* ** Quality Education (Core Mission)**
    * [cite_start]Reinforces fundamental skills (Math, Science, Languages)[cite: 20].
    * [cite_start]Provides personalized support to reduce learning inequalities[cite: 21].
    * [cite_start]Prepares youth for 21st-century skills (critical thinking, digital literacy)[cite: 22].

* ** Industry, Innovation & Infrastructure**
    * [cite_start]Introduces students to digital technologies, robotics, and programming[cite: 43].
    * [cite_start]Builds a scientific and technical culture from a young age[cite: 43].

* ** Reduced Inequalities**
    * [cite_start]Offers accessible support for students from disadvantaged socio-economic backgrounds[cite: 47].
    * [cite_start]Promotes inclusion for students with specific needs[cite: 48].

* ** Partnerships for the Goals**
    * [cite_start]Acts as a collaborative ecosystem connecting schools, NGOs, and volunteers[cite: 71].
    * [cite_start]Mobilizes mentors to strengthen the local and national educational fabric[cite: 72].

## Architecture

The system follows a microservices-style architecture managed within a single repository:

* **frontend-react**: The user interface for students, mentors, and admins.
* **backend-java**: The core logic handling mentorship matching, progress tracking, and partnerships.
* **ai-engine**: Intelligent models for personalized learning paths and predictive analysis.

## Project Structure

```plaintext
act2learn-monorepo/
├── ai-engine/          # Python (Analytics & Personalization)
├── backend-java/       # Spring Boot (Business Logic)
├── frontend-react/     # React (User Experience)
├── docker-compose.yml  # Local orchestration
└── README.md           # Project Documentation
