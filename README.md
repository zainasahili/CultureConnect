# CultureConnect : Global Cultural Awareness Database

## **Project Purpose and Goals:**
CultureConnect is a platform designed to make trusted, locally sourced cultural information accessible to everyone. Despite the reach of social media and globalization, many people still have limited exposure to other cultures—often leading to awkward interactions or unintentional insensitivity. CultureConnect seeks to close that gap by organizing reliable, locally verified cultural data by country, making it easier for anyone to learn, understand, and engage respectfully across cultures.

## **Goals:**

1. Build a relational database with sample cultural data for 3–5 countries
2. Include categories like holidays, greetings, values, dos/don’ts, and key historical facts
3. Use MySQL for core data, MongoDB for flexible descriptions, HTML/CSS for a lightweight frontend

## Initial ERD
![drawSQL-image-export-2025-05-30](https://github.com/user-attachments/assets/7281da13-5f6a-4944-b9b8-8be90b33becc)


## Initial System design Sketch

                                    Frontend: HTML/CSS 
                                               │
                                               ▼
                                  Backend API: Node.js
                                              │
             ┌────────────────────────────────┴────────────────┐
             ▼                                                 ▼
    MySQL: Countries, Facts, Categories    MongoDB: Full cultural descriptions

* Frontend calls backend APIs to fetch data
* Backend queries both MySQL and MongoDB
* MySQL handles structure (e.g., country/category relationships)
* MongoDB handles rich cultural text

## Daily Project Goals:

| **Date**     | **Goal**                                                         |
| ------------ | ---------------------------------------------------------------- |
| **May 29**   | Finalize project scope and ERD; set up GitHub repo               |
| **May 30**   | Create MySQL schema and seed with sample data (3 countries)      |
| **May 31**   | Set up MongoDB and connect both databases to backend             |
| **June 1–2** | Build basic backend API (read-only endpoints for now)            |
| **June 3–4** | Start simple HTML/CSS frontend to view country and category data |
| **June 5–6** | Add filtering by country and category on frontend                |
| **June 7–8** | Display MongoDB data alongside relational data                   |
| **June 9**   | Polish layout                       |
| **June 10**  | Add search feature or keyword filter                  |
| **June 11**  | Test full system flow (frontend → backend → database)            |
| **June 12**  | Finalize content and fix bugs                                    |
| **June 13**  | Write README and prepare presentation materials                  |
| **June 14**  | Practice demo and make final design tweaks                       |
| **June 15**  | Final day for fixes or late polish                              

