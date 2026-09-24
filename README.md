# 🚚 MineralFlow - Logistics Management System

<p align="center">
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white" alt="Spring Boot" />
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white" alt="RabbitMQ" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Keycloak-430098?style=for-the-badge&logo=keycloak&logoColor=white" alt="Keycloak" />
</p>

## Overview

**MineralFlow** is a modern, modular logistics management system designed for the mineral distribution industry. It provides real-time tracking and control over warehouse inventory, truck scheduling, dispatch management, and shipment workflows.

This root repository serves as the single orchestration layer for the multi-service codebase using **Git Submodules**.

---

## 🏗️ Architecture & Submodules

The platform consists of two main decoupled components:

*   **[`backend/`](https://github.com/HopeyCodeDS/backend)**: Java Spring Boot core API managing logistics business rules, PostgreSQL data persistence, and asynchronous message broker processing via RabbitMQ.
*   **[`frontend/`](https://github.com/HopeyCodeDS/frontend)**: Modern React & TypeScript web interface built with Material-UI for real-time logistics monitoring and operational management.

---

## 🚀 Getting Started

### Cloning the Repository
Make sure to include the `--recurse-submodules` flag so Git fetches all submodules automatically:

```bash
git clone --recurse-submodules https://github.com/HopeyCodeDS/MineralFlow-Root.git
cd MineralFlow-Root
