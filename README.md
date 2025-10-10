

# 🚗 **ZIPAPP**
### *Game Day Golf Cart Ride-Sharing App*

A **cross-platform, Uber-style golf-cart transportation system** designed for  

**game days and crowded campus events** — when parking is distant and roads are closed.


Built to help **students, fans, and visitors** request quick, reliable rides directly from their phones.

---

</div>

## 🎯 What It Does

ZIPAPP connects **riders** and **drivers** through two intuitive portals — providing  
real-time tracking, optimized routing, and smooth communication even when traffic is restricted.

> “When stadiums are packed and walking isn’t an option, ZIPAPP bridges the last mile from far-away parking to the game.”

---

## 🧠 Overview

ZIPAPP is a **full-stack, cross-platform project** built with:
- **Flutter (Dart)** for the frontend  
- **Flask (Python)** API backend  
- **C++ routing engine** for path optimization  
- **SQL database** for trip and user data  

Developed as a **Senior Design Project at Auburn University**, ZIPAPP solves real mobility challenges faced during large campus events.

---

## 🧰 Tech Stack

| Layer | Technologies |
|-------|---------------|
| **Frontend** | Flutter (Dart), Firebase, Google Maps API |
| **Backend** | Flask (Python), C++ routing service |
| **Database** | SQLAlchemy ORM (SQLite / MySQL) |
| **Tools & CI/CD** | GitHub Actions, Firebase Hosting, Agile Development |

---

## 🚀 Key Features

- 🧭 Real-time GPS tracking and optimized routing  
- 👥 Dedicated rider and driver dashboards  
- 💳 In-app payment integration (Stripe / Google Pay in progress)  
- 🔒 Secure Firebase authentication  
- 🌐 Multi-platform support (Android, iOS, Web, Desktop)  
- 🏟️ Specifically optimized for **Auburn University game days**

---

## 🏗️ **Architecture**  

```mermaid
flowchart LR
    A[Flutter App] -->|REST API| B[Flask Server]
    B -->|SQL Queries| C[(Database)]
    B -->|Routing Data| D[C++ Engine]
    A -->|Firebase Auth| E[Firebase Services]
```


## 📦 Deliverables

| **File** | **Description** |
|-----------|-----------------|
| **Architectural Spike Presentation-2.pptx** | App architecture and system overview |
| **Cycle 1–3 Reports** | Agile sprint documentation and retrospectives |
| **Developer Manual.docx** | Setup, build, and deployment guide |
| **User Manual.docx** | Instructions for passengers and drivers |
| **Senior Design Architectural Spike.pdf** | Final design document summary |


# Install dependencies
flutter pub get

# Run the app
flutter run

Backend setup:
cd backend
python app.py

## 🏗️ Future Enhancements

- ✅ **Integrate live payment processing**
- ✅ **Implement driver analytics and performance dashboard**
- 🔲 **Machine-learning route prediction** for dynamic traffic rerouting
- 🔲 **Integration with campus maps and event systems**


# Screenshots
<img width="657" height="710" alt="Screenshot 2025-10-10 at 12 43 37 AM" src="https://github.com/user-attachments/assets/6a16645a-206c-4a4a-8546-4d15e6765e8b" />
<img width="657" height="565" alt="Screenshot 2025-10-10 at 12 42 54 AM" src="https://github.com/user-attachments/assets/7851c224-1274-40a4-880d-bf0f197d1ef3" />
<img width="657" height="710" alt="Screenshot 2025-10-10 at 12 43 41 AM" src="https://github.com/user-attachments/assets/cddc17fe-6252-4582-86ce-bc1e45b60aed" />
<img width="657" height="742" alt="Screenshot 2025-10-10 at 12 43 00 AM" src="https://github.com/user-attachments/assets/07298e43-054e-4265-a32c-826852b9653d" />
<img width="657" height="742" alt="Screenshot 2025-10-10 at 12 43 04 AM" src="https://github.com/user-attachments/assets/2a39e9f2-daf0-461a-b53b-348cd9747d27" />
<img width="657" height="742" alt="Screenshot 2025-10-10 at 12 43 11 AM" src="https://github.com/user-attachments/assets/4cd1380a-dfda-42fb-915d-48db05797af0" />
<img width="657" height="655" alt="Screenshot 2025-10-10 at 12 43 19 AM" src="https://github.com/user-attachments/assets/ffbaca3e-c524-426f-a6f5-6ca55bedb726" />
<img width="657" height="655" alt="Screenshot 2025-10-10 at 12 43 23 AM" src="https://github.com/user-attachments/assets/1b770d53-c74c-4aa3-b11d-34cc7c9eb32f" />
<img width="657" height="655" alt="Screenshot 2025-10-10 at 12 43 27 AM" src="https://github.com/user-attachments/assets/fe93318e-0d32-4639-a58b-a1deebc10092" />
<img width="657" height="710" alt="Screenshot 2025-10-10 at 12 43 32 AM" src="https://github.com/user-attachments/assets/1488635f-d7cc-4c51-8a88-3bd74925682a" />
<img width="657" height="710" alt="Screenshot 2025-10-10 at 12 43 44 AM" src="https://github.com/user-attachments/assets/b29b4905-fb83-428e-867d-18d0fc7246b1" />
<img width="657" height="710" alt="Screenshot 2025-10-10 at 12 43 48 AM" src="https://github.com/user-attachments/assets/6540404a-034b-4a95-9e20-ff0fe691a837" />
<img width="576" height="543" alt="Screenshot 2025-10-10 at 12 43 57 AM" src="https://github.com/user-attachments/assets/46d256bb-dcdd-4b06-bcaf-bf00f215a54a" />
<img width="576" height="543" alt="Screenshot 2025-10-10 at 12 44 03 AM" src="https://github.com/user-attachments/assets/c4adabdb-598e-4e51-99ed-78dde34a3feb" />
<img width="576" height="543" alt="Screenshot 2025-10-10 at 12 44 08 AM" src="https://github.com/user-attachments/assets/fe88b13a-e943-420d-8c67-71dd0d8ed7ed" />
<img width="576" height="509" alt="Screenshot 2025-10-10 at 12 44 17 AM" src="https://github.com/user-attachments/assets/0038d8c0-0c62-414b-b7fc-a0a55cae7a6a" />

# 📜 **License**
Developed for educational purposes as part of Auburn University’s Software Engineering Senior Design Project.
