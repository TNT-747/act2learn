# Act2Learn

**Act2Learn** is a collaborative digital platform that transforms academic support into a lever for sustainable development. By combining personalized learning with civic engagement, Act2Learn addresses critical **Sustainable Development Goals (SDGs)**, bridging the gap between academic success and social responsibility.

## 🎯 Project Mission & Impact

According to our strategic analysis, Act2Learn focuses on transversal impact across multiple SDGs:

### Quality Education (Core Mission)
* Reinforces fundamental skills (Math, Science, Languages).
* Provides personalized support to reduce learning inequalities.
* Prepares youth for 21st-century skills (critical thinking, digital literacy).

### Industry, Innovation & Infrastructure
* Introduces students to digital technologies, robotics, and programming.
* Builds a scientific and technical culture from a young age.

### Reduced Inequalities
* Offers accessible support for students from disadvantaged socio-economic backgrounds.
* Promotes inclusion for students with specific needs.

### Partnerships for the Goals
* Acts as a collaborative ecosystem connecting schools, NGOs, and volunteers.
* Mobilizes mentors to strengthen the local and national educational fabric.

## 🏗 Architecture

The system follows a microservices-style architecture managed within a single repository:

* **frontend-react**: The user interface for students, mentors, and admins.
* **backend-java**: The core logic handling mentorship matching, progress tracking, and partnerships.
* **ai-engine**: Intelligent models for personalized learning paths and predictive analysis.

## 📂 Project Structure

```plaintext
act2learn-monorepo/
├── ai-engine/          # Python (Analytics & Personalization)
├── backend-java/       # Spring Boot (Business Logic)
├── frontend-react/     # React (User Experience)
├── docker-compose.yml  # Local orchestration
└── README.md           # Project Documentation
