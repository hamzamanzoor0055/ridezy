# Ridezy — University Carpooling & Ride-Sharing Platform

**Course:** SEL-311 Software Construction (Fall 2026)  
**Institution:** Bahria University, Islamabad Campus  

## Project Overview
Ridezy is a full-stack, real-time university carpooling web application designed for students and faculty. Drivers publish campus commutes with exact interactive map pickup/drop-off pins, vehicle details, and fare splits, while passengers filter live rides by direction, city, university, date, and pickup area. Driver WhatsApp contacts remain masked until a booking request is explicitly accepted.

## Group Members
| Name | Enrollment Number | GitHub |
| :--- | :--- | :--- |
| Muhammad Hamza Manzoor | 09-131242-055 | [@hamzamanzoor0055](https://github.com/hamzamanzoor0055) |
| Abdul Momin | 09-131242-003 | *([@victor6273737](https://github.com/victor6273737/))* |

## Tech Stack
* **Frontend:** React (Vite), Tailwind CSS, Leaflet.js (OpenStreetMap)
* **Architecture:** 4-Layer Design (Presentation, Domain/Service OOP Layer, Repository Layer, Relational Persistence)
* **Database:** 4-Table Relational SQL Schema (`profiles`, `vehicles`, `rides`, `bookings`)
* **Authentication:** Email/Password & Google OAuth 2.0

## Documentation (`docs/`)
* `docs/Proposal.pdf` — Problem Formulation & Project Proposal
* `docs/SRS.pdf` — Software Requirements Specification (IEEE 830 aligned)
* `docs/SDS.pdf` — Software Design Specification (IEEE 1016 aligned)
* `docs/Low_Fidelity_Prototype.pdf` — Hand-drawn wireframes of key user flows

## How to Run Locally
1. Clone the repository:
   ```bash
   git clone [https://github.com/hamzamanzoor0055/ridezy.git](https://github.com/hamzamanzoor0055/ridezy.git)
   cd ridezy
