---
title: "Shoptopus E-Commerce Platform"
date: 2026-01-01
summary: "Open-source e-commerce platform that evolved from a Laravel stack into a Spring Boot self-hosted distribution"
tags:
  - E-Commerce
  - Full-Stack
  - Java
  - Laravel
  - Open Source
tech_stack:
  - Laravel 10
  - Spring Boot
  - PostgreSQL
  - React
  - Next.js
  - Docker
  - Jenkins
  - Stripe
  - AWS
links:
  - type: live
    url: https://shoptopus.co.uk
    label: Website
  - type: code
    url: https://github.com/rolandtreiber/shoptopus
    label: Laravel Repository
  - type: code
    url: https://github.com/Shoptopus/shoptopus-selfhost
    label: Spring Self-host Repository
featured: true
status: "Active"
role: "Creator and Lead Developer"
duration: "2021 - Present"
team_size: 1
highlights:
  - "Created the original open-source Laravel e-commerce platform"
  - "Reworked the 2026 self-hosted distribution around Spring Boot"
  - "Packaged storefront and admin portal assets for self-hosted deployment"
  - "Built Docker, PostgreSQL, Flyway, MailHog and snapshot workflows"
---

Shoptopus is a comprehensive e-commerce platform I started building in 2020. The original Laravel version is open source, and the current self-hosted distribution rewrites the platform around Spring Boot for people who want to run Shoptopus on their own infrastructure.

## What I Built

- Planned, designed, architected and built the majority of the platform features
- Implemented complex API integrations including payment processors, ChatGPT and social media platforms
- Built and secured the server environment from the ground up
- Created Dockerized development and deployment workflows
- Configured Jenkins CI pipelines and automated test execution
- Added a self-hosted Spring Boot distribution with PostgreSQL migrations, packaged storefront/admin assets and configurable media storage

## Technical Scope

The original Shoptopus stack includes Laravel, MySQL store/log databases, Elasticsearch/Kibana support, Laravel Scout search, Postman collections, Larastan, audit tooling and store snapshot workflows.

The Spring self-hosted version includes a backend API, PostgreSQL migrations for main and logs databases, packaged storefront and admin portal assets, Docker Compose support for PostgreSQL and MailHog, automatic Flyway migrations, root admin bootstrapping, optional multi-store behavior and snapshot configuration.

## Quality

The project is fully Dockerized and has a strong automated test base, including 841 passing tests in the resume snapshot for the original platform.
