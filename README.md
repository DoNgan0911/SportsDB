# Sports Tournament Registration Platform

A relational database project designed to support sports tournament registration, scheduling, and reporting for universities and sports organizations.

## 📌 Project Overview

The **Sports Tournament Registration Platform** is a MySQL-based database system that manages:
- Sports and tournaments
- Team and player registrations
- Match scheduling and results
- Venues and referees
- Analytical reports for organizers and participants

This project was developed as part of **Course 4707.501** and demonstrates database design, implementation, and SQL querying best practices.

## 🎯 Objectives

- Design a **normalized relational database** for tournament management  
- Implement the database using **MySQL**
- Populate tables with meaningful sample data
- Generate **analytical SQL reports** for decision-making
- Demonstrate real-world business rules through database constraints

## 👥 User Roles

- **Tournament Organizers**
  - Create, edit, and delete tournaments
  - Register teams
  - Schedule matches
  - Update match results
  - Generate participation reports

- **Teams & Players**
  - View tournaments and match schedules
  - Manage team rosters
  - View performance history

- **Spectators**
  - View upcoming matches
  - View match results

## 🧩 Database Design

### Main Entities
- Sport
- Tournament
- Team
- Player
- Match
- Venue
- Referee
- TeamTournament (junction table)

### Business Rules (Highlights)
- A sport can have multiple tournaments
- Teams can participate in multiple tournaments
- Each match involves exactly two teams
- A match belongs to one tournament and one venue
- Match results determine win/loss records

## 🛠 Technologies Used

- **Database:** MySQL 8.0
- **Tools:** MySQL Workbench, Jupyter Notebook
- **Language:** SQL

## 📊 Sample Reports & Queries

- Match schedules for a given tournament
- Department participation report
- Sport participation report
- Team win/loss statistics
- Match results summary

## 🚀 How to Run the Project

1. Install **MySQL Workbench 8.0**
2. Create a new MySQL connection
3. Run the SQL schema scripts to create tables
4. Run the data insertion scripts
5. Execute the provided SQL queries to generate reports

## 📂 Repository Structure (Suggested)

