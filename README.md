# Hi, I'm Abram

Welcome to my GitHub profile!  
I'm a **third-year Bachelor student at HEIG-VD** majoring in **Data Engineering**.  
I enjoy learning, coding, and tackling technical challenges. Outside of class, I'm passionate about sports.

---

## Featured projects

### [Sterna](https://github.com/Samurai-05/Sterna) — group project (HEIG-VD PDG 2026)
A mobile-first application that turns geolocated photos into a personal and shared map of discoveries. Photos become discoveries placed on an interactive map, progressively revealing the countries explored, and groups can build a shared map together while each discovery keeps its author.  
Developed by a team of four students.

**My role:**
- **Interactive map:** built the MapLibre + OpenFreeMap map showing explored and unexplored countries, with high-resolution borders, disputed-territory handling, a globe view when zoomed out, and zoom-dependent points of interest
- **Geospatial backend:** server-side country detection with PostGIS, a points-of-interest catalog covering every country, and a "confirm-to-unlock" feature for landmarks photographed from a distance, with search radii adapted to each category
- **Adding discoveries:** location proposed automatically from the photo's EXIF GPS data, with manual correction on a map picker
- **Accounts and groups:** profile settings, full account deletion with cleanup of related data, joining a group by scanning a QR code
- **Infrastructure and quality:** PostgreSQL/PostGIS and MinIO setup with Docker Compose, unit and end-to-end tests, technical documentation

**Stack:** React, TypeScript, Vite (PWA + Capacitor), Node.js / NestJS, PostgreSQL + PostGIS, MinIO, MapLibre GL JS, OpenStreetMap, Docker Compose, Nginx  
Website: [sterna-app.ch](https://www.sterna-app.ch/)

### Skilder Capture — prototype (following the Design Thinking and Sprint course)
A "teach by doing" prototype: a domain expert works normally, the tool observes locally (clicks, screenshots, active windows, voice annotations), reconstructs the workflow, asks only the questions it cannot answer itself, and turns the expert's reasoning into a validated, reusable skill. Spoken explanations such as "I restart the check because the target value is not reached" become executable, testable decision rules.  
Everything runs locally by default, with an optional local LLM to name steps in business vocabulary. Exports to the native format of the Skilder platform.

**Stack:** Python, Qt, pydantic, Ollama (local LLM), faster-whisper, pytest (140+ tests), ruff, black, GitHub Actions CI

---

## Currently learning (3rd year)
- **Machine learning:** supervised and unsupervised learning, simulation and optimization, ML project management
- **Data:** data governance, data access methods, business intelligence
- **Performance:** numerical computing and hardware acceleration
- **Innovation:** design thinking, international innovation management, group project
- **Planned electives:** error-correcting codes, biocomputation, explainable AI, machine intelligence, generative AI engineering
- **Coming up:** Bachelor thesis

---

## Background (1st and 2nd year)
- **Computer science:** programming, algorithms and data structures, object-oriented programming, concurrent programming, operating systems, computer architecture, networking, information security
- **Data and cloud:** relational databases, web application development, cloud computing, data storage and processing infrastructures, data preparation and visualization
- **Mathematics:** analysis, discrete mathematics, probability and statistics, graphs and networks, artificial neural networks
- **Software engineering:** software development processes, ethics and legal aspects, IT project

---

## Skills
- **Languages:** Python, TypeScript, JavaScript, Java, C, C++, SQL, R
- **Tools:** Docker, AWS, Git, GitHub Actions, PostgreSQL / PostGIS, MapLibre, Qt
- **Software development:** object-oriented design, concurrency, testing, software engineering processes
- **Data:** relational and spatial databases, data preparation, visualization, statistical analysis
- **Machine learning:** neural networks, supervised and unsupervised methods, local LLMs
- **Infrastructure:** cloud computing, data storage and processing

---

## Interests
- Data engineering, data science and machine learning
- Modeling and quantitative analysis
- Sports: cycling, tennis, skiing, snowboarding
