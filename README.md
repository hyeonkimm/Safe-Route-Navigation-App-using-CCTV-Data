# CCTV-based Safe Route Navigation App

A mobile application that provides **safer walking routes by utilizing CCTV location data and the TMap API**.

The system visualizes nearby CCTV cameras along walking routes and allows users to select CCTV locations to generate alternative paths with improved safety.


## > Project Background

This project was inspired by a **hit-and-run traffic accident involving an acquaintance**.

During the investigation, the presence of **nearby CCTV cameras played a crucial role in identifying the suspect**, which allowed the case to be solved more efficiently.

This experience highlighted the importance of **surveillance infrastructure in improving public safety**.  
As a result, this project was developed to explore how **CCTV location data can be integrated into navigation services to provide safer routes for pedestrians.**


## > Project Overview

Conventional navigation services usually provide the **shortest or fastest route**, but they do not consider **public safety factors**.

This project aims to provide **safer pedestrian routes** by incorporating **CCTV location data** into the navigation process.

The application visualizes CCTV locations around the route and allows users to **recalculate routes that pass near selected CCTV points**, increasing perceived safety during travel.

## > Key Features

#### 1️. Basic Walking Route Search
- Uses **TMap API** to generate a standard pedestrian route
- Displays the route on the map interface

#### 2️. CCTV Visualization
- Displays CCTV locations near the route
- Users can identify nearby surveillance infrastructure

#### 3️. CCTV-based Route Recalculation
- Users select CCTV points along the route
- The system recalculates a walking path that passes through those locations

#### 4️. Route and CCTV Data Storage
- Stores calculated routes and related CCTV information
- Allows users to review CCTV information along their traveled route and trace their path in case of an incident

---

# System Architecture
```
User
 ↓
Mobile App
 ↓
Route Request
 ↓
TMap API
 ↓
Basic Walking Route
 ↓
CCTV Data Processing
 ↓
Map Visualization
 ↓
User selects CCTV
 ↓
Route Recalculation
 ↓
Route & CCTV Data Storage
```
---

# Future Improvements
Future work focuses on improving safety-aware navigation using public safety infrastructure data.
- Automatic safe route recommendation using nearby CCTV location data
- Night-time safe route recommendation considering streetlights and emergency safety bells
- Safety score calculation for routes based on surrounding safety infrastructure

---

# Screenshot
<div align="center">
<img width="200" height="355" alt="image" src="https://github.com/user-attachments/assets/9ca94faa-e009-46b0-ad97-1bb7c9e77830" />
<img width="200" height="355" alt="image" src="https://github.com/user-attachments/assets/dd953629-99cc-4e07-81a5-3606e1a74fd1" />
<br><br>
<img width="200" height="355" alt="image" src="https://github.com/user-attachments/assets/a3315249-89eb-48c7-935b-bac1c6b0fecc" />
<img width="200" height="355" alt="image" src="https://github.com/user-attachments/assets/aa1f4d30-2788-441c-a3e5-62e277458e2a" />
<img width="200" height="355" alt="image" src="https://github.com/user-attachments/assets/5da32f7c-f3bd-4e8d-996f-4e9dd69153df" />
</div>
