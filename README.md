# Worldmark

A map-based mobile app that layers human presence over the world using photo-based marks.

Photos are pinned to real GPS locations and viewed chronologically to understand how places change over time.

---

## Core Idea

Google Maps as the base layer, with a human presence overlay built from time-anchored photos.

No feeds  
No reviews  
No social graph  

---

## Platform

- iOS  
- Android  

Single cross-platform codebase.

---

## Tech Stack

**Mobile**
- React Native (TypeScript)
- Google Maps SDK

**Backend**
- Java (Spring Boot)
- PostgreSQL + PostGIS
- REST APIs
- Object storage for images

---

## High-Level Structure

### Mobile App

worldmark-app/ ├── ios/ ├── android/ └── src/

### Backend

worldmark-backend/ ├── auth/ ├── photomark/ ├── map/ ├── like/ └── common/

---

## Status

Early development (v1).

---

Made with ♥️ by Shivansh Bagga
