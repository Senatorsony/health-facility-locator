# health-facility-locator
Outsourced feature development and project management framework for Health Facility Locator with Google Maps API.
# Health Facility Locator — Outsourced Feature Development & Project Management Framework

## Executive Summary & Overview
This repository serves as the central version control hub and project management showcase for outsourcing the **Health Facility Locator** feature. The initiative integrates the Google Maps API into a web/mobile platform to enable real-time location detection, spatial facility mapping, and multi-attribute search filtering.

---

## 1. Feature Specifications & Requirements

### Core Functionality
* **Google Maps API Integration:** Render interactive map interfaces with dynamic location markers and auto-centering on user GPS coordinates.
* **Facility Category Filtering:** Filter nearby facilities across four primary categories:
  * Hospitals
  * Clinics
  * Laboratories
  * Pharmacies
* **Service-Level Filtering:** Refine facility results based on specialized healthcare services:
  * Immunization / Vaccination
  * Radiology / Diagnostic Imaging

---

## 2. GitHub Version Control & Issue Management Strategy

Project progress is managed using a **GitHub Kanban Board** (`Backlog` → `To Do` → `In Progress` → `Under Review` → `Done`). Development follows a branch-and-pull-request (PR) workflow where every PR must reference a specific Task ID before code review and merging.

### Task Breakdown (`TSK-01` – `TSK-05`)
| Task ID | Issue Title | Priority | Scope & Acceptance Criteria |
| :--- | :--- | :--- | :--- |
| **`TSK-01`** | `[Setup] Initialize repository structure & API configuration` | High | Configure base environment, secure Google Maps API keys via `.env`, and set up CI/CD linting. |
| **`TSK-02`** | `[Feature] Integrate Google Maps API & user location detection` | High | Render map canvas, implement browser/device geolocation, and auto-pin nearby facilities. |
| **`TSK-03`** | `[Feature] Implement facility category filtering UI & logic` | High | Build filtering controls for Hospitals, Clinics, Laboratories, and Pharmacies. |
| **`TSK-04`** | `[Feature] Add service-level filtering (Immunization & Radiology)` | Medium | Enable multi-select attributes to isolate facilities providing specific medical services. |
| **`TSK-05`** | `[QA] PR Code Review, acceptance criteria verification & testing` | High | Conduct security audit, cross-browser responsiveness tests, and merge PRs to main. |

---

## 3. Financial & Progress Management (Google Sheet Tracking)

All financial metrics, time tracking, and milestone releases are cross-referenced with GitHub Task IDs using a master Google Sheet tracker:

* **Task & Milestone Tracking:** Features automated completion percentage metrics, status dropdowns, estimated vs. actual hours, and cost variances.
* **Budget & Milestone Schedule:** Structured milestone payouts tied to code review approvals on GitHub.
* **Ancillary Cost Management:** Dedicated tracking buffer for Google Maps Platform API usage (utilizing the \$200 free monthly Cloud credit) and platform transaction fees.

---

## 4. Freelancer Talent Sourcing & Risk Mitigation

To balance technical execution risk against budget constraints, candidates are evaluated across distinct engineering specializations:

1. **Full-Stack Lead (React/Node):** Senior developer for end-to-end web integration and spatial database queries.
2. **Mobile App Specialist (Flutter):** Cross-platform engineer for native mobile device deployment.
3. **Geospatial Backend Engineer (Python/GeoDjango):** Developer focused on spatial search query latency and API optimization.
4. **Frontend UI/UX Specialist (Vue/Tailwind):** Designer focusing on map styling, responsive filter modals, and pin clustering.
5. **MVP Prototype Developer (JavaScript/PHP):** Cost-effective option for rapid prototyping under direct PM supervision.

---

## 5. Quick Links & Submission Deliverables

Deliverables Summary:
a) Fiverr Project Brief: Available as a formatted PDF in the attached documentation and embedded within the GitHub repository README.
b) Public GitHub Repository & Board: Features 5 granular tasks (TSK-01 to TSK-05) managed across active Kanban workflow columns (Backlog, Ready, In progress, In review, Done).
c) Google Sheet Tracker: Multi-tab project management dashboard featuring executive KPI cards, automated progress formulas, milestone budget schedules, and API expense monitoring.
d) Candidate Selection: 5 verified Fiverr candidate profiles matched to specialized engineering roles with technical risk evaluations.

Selected Fiverr Candidate Profiles:
1. Senior Full-Stack Lead: https://www.fiverr.com/chamindachanaka/create-web-based-inventory-system-for-you-withing-few-days
2. Mobile App Specialist: https://www.fiverr.com/rustamali750/build-geolocation-tracking-app-and-google-map-location-tracking-mobile-app
3. Geospatial Backend Engineer: https://www.fiverr.com/aissam_gis
4. Frontend UI/UX Specialist: https://www.fiverr.com/chamindachanaka/create-web-based-inventory-system-for-you-withing-few-days
5. MVP Prototype Developer: https://www.fiverr.com/herry_crave/integrate-google-map-api-into-your-website

Warm regards,

* **Project Lead:** Sunny Ogoigbe (Software Project Manager Candidate)
