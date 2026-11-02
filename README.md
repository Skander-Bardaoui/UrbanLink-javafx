<p align="center">
  <img src="docs/banner.svg" width="100%" alt="UrbanLink Desktop banner" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1200&color=0891B2&center=true&vCenter=true&width=760&lines=Transport+management+on+the+desktop;JavaFX+%2B+JDBC;Users%2C+vehicles+%26+ratings" alt="Typing tagline" />
</p>

<p align="center">
  <img src="https://img.shields.io/github/languages/top/Skander-Bardaoui/UrbanLink-javafx?style=flat-square&color=0891B2" alt="" />
  <img src="https://img.shields.io/github/stars/Skander-Bardaoui/UrbanLink-javafx?style=flat-square&color=0891B2" alt="" />
  <img src="https://img.shields.io/github/last-commit/Skander-Bardaoui/UrbanLink-javafx?style=flat-square&color=67E8F9" alt="" />
  <img src="https://img.shields.io/badge/status-Academic-0891B2?style=flat-square" alt="" />
</p>

## Overview

A JavaFX desktop application for urban transport management, connected to MySQL through JDBC. It covers user administration, transport and vehicle management, and a rating system, with a structured MVC layout.

## Highlights

- JavaFX interface with a structured MVC architecture
- MySQL persistence through JDBC
- User and transport management screens
- Vehicle CRUD operations
- Ratings module with SQL schema included

## Tech stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=java,mysql,git&theme=dark&perline=8" alt="Tech stack" />
</p>

## Getting started

**Prerequisites:** JDK 17+, MySQL and Maven.

```bash
mysql -u root -p < users(1).sql
mysql -u root -p < ratings.sql
# update the JDBC URL and credentials in the project config
./mvnw javafx:run
```

## Documentation

- [Original project documentation](docs/README_ORIGINAL.md)

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0891B2,100:0A0A0C&height=110&section=footer" alt="footer" width="100%" />
</p>

<p align="center">
  Built by <a href="https://github.com/Skander-Bardaoui"><b>Skander Bardaoui</b></a> ·
  <a href="https://skander-bardaoui.netlify.app/">Portfolio</a> ·
  <a href="https://github.com/Skander-Bardaoui?tab=repositories">All repositories</a>
</p>
