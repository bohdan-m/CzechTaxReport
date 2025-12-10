# **CzechTaxReport**

A lightweight full-stack web application designed to help individuals in Czechia generate a correct personal tax report based on the official **[DPFDP7](https://adisspr.mfcr.cz/dpr/adis/idpr_pub/epo2_info/popis_struktury_detail.faces?zkratka=DPFDP7)** form.
Built with **Python (Django REST Framework)** on the backend and **TypeScript + React + Vite** on the frontend.

Official XML templates from *Moje Daně* were used to ensure structure and formatting accuracy.

---

## **Features**

* Generate a tax report using official DPFDP7 form logic
* Clean API built with Django REST Framework
* Fast and responsive React + Vite frontend
* Automatic calculations based on user inputs
* Ready to run with Docker (backend + frontend)

---

## **Tech Stack**

* **Backend:** Python, Django, Django REST Framework
* **Frontend:** React, TypeScript, Vite
* **Database:** PostgreSQL
* **Containerization:** Docker & Docker Compose

---

## **Quick Start with Docker**

Run the entire project with a single command:

```bash
docker-compose up -d
```

This will automatically:

* Build all Docker images
* Run required setup commands
* Initialize the database
* Start both backend and frontend services

After startup, visit the frontend in your browser `http://localhost:5173`.

