---
title: ''
summary: ''
date: 2026-01-05
type: landing

sections:
  - block: dev-hero
    id: hero
    content:
      username: me
      greeting: "Hi, I'm"
      show_status: true
      show_scroll_indicator: true
      typewriter:
        enable: true
        prefix: "I build"
        strings:
          - "Java and Spring cloud systems"
          - "Laravel and React products"
          - "secure e-commerce platforms"
          - "mobile apps that ship"
        type_speed: 70
        delete_speed: 40
        pause_time: 2500
      cta_buttons:
        - text: View Projects
          url: "#projects"
          icon: arrow-down
        - text: Get In Touch
          url: "#contact"
          icon: envelope
    design:
      style: centered
      avatar_shape: circle
      animations: true
      background:
        color:
          light: "#fafafa"
          dark: "#0a0a0f"
      spacing:
        padding: ["6rem", "0", "4rem", "0"]

  - block: portfolio
    id: projects
    content:
      title: "Selected Projects"
      subtitle: "Production systems, products and platforms I have built or led"
      count: 0
      filters:
        folders:
          - projects
      buttons:
        - name: All
          tag: '*'
        - name: E-Commerce
          tag: E-Commerce
        - name: Mobile
          tag: Mobile
        - name: Full-Stack
          tag: Full-Stack
        - name: Java
          tag: Java
      default_button_index: 0
    design:
      columns: 3
      background:
        color:
          light: "#ffffff"
          dark: "#0d0d12"
      spacing:
        padding: ["4rem", "0", "4rem", "0"]

  - block: tech-stack
    id: skills
    content:
      title: "Tech Stack"
      subtitle: "Certified Java, Spring and AWS expertise, plus the tools I use to ship full-stack products"
      categories:
        - name: Backend
          items:
            - name: Java
              icon: devicon/java
            - name: Spring Boot
              icon: devicon/spring
            - name: PHP
              icon: devicon/php
            - name: Laravel
              icon: devicon/laravel
        - name: Frontend
          items:
            - name: React
              icon: devicon/react
            - name: Next.js
              icon: devicon/nextjs
            - name: Vue.js
              icon: devicon/vuejs
            - name: TypeScript
              icon: devicon/typescript
        - name: Mobile
          items:
            - name: React Native
              icon: devicon/react
            - name: Kotlin
              icon: devicon/kotlin
            - name: Firebase
              icon: devicon/firebase
            - name: Xcode
              icon: devicon/xcode
        - name: Cloud and Data
          items:
            - name: AWS
              icon: devicon/amazonwebservices
            - name: Docker
              icon: devicon/docker
            - name: MySQL
              icon: devicon/mysql
            - name: MongoDB
              icon: devicon/mongodb
    design:
      style: grid
      show_levels: false
      background:
        color:
          light: "#f5f5f5"
          dark: "#08080c"
      spacing:
        padding: ["4rem", "0", "4rem", "0"]

  - block: resume-experience
    id: experience
    content:
      title: Experience
      date_format: Jan 2006
      items:
        - title: Senior Software Engineer
          company: Spyrosoft / BBC
          company_url: ''
          company_logo: ''
          location: Remote to London
          date_start: '2025-05-01'
          date_end: ''
          description: |2-
            * Contract senior Java engineer in the BBC Media Services Packaging and Access team
            * Delivered work for BritBox UHD VOD content delivery
            * Implemented custom IMF validation using Netflix Photon
            * Implemented and deployed FMP4 HLS manifest creation affecting 43 live channels
            * Set up an AWS Lambda subtitle processor to validate and repair broken subtitle files
        - title: Lead Developer
          company: Fortium Technologies
          company_url: https://www.fortium.com
          company_logo: ''
          location: Bridgend
          date_start: '2023-11-01'
          date_end: '2025-03-31'
          description: |2-
            * Managed backend and frontend developers
            * Contributed to securing a 250k grant by creating proof-of-concept work and supporting the application
            * Participated in strategy meetings with clients including Disney
            * Built a way to serve a full Linux desktop in-browser using Apache Guacamole and Spring Boot
            * Planned and managed new projects using Next.js, AWS SAM and Java 17
        - title: Contract Full-Stack Software Engineer
          company: SoCrowd
          company_url: ''
          company_logo: ''
          location: Birmingham
          date_start: '2023-02-01'
          date_end: '2023-09-30'
          description: |2-
            * Improved app user retention by 15% through feature upgrades and 30 critical bug fixes
            * Containerized an application made of eight fragments so they could run together cleanly
            * Planned a new API and MySQL database structure
            * Introduced React into a new project and promoted Laravel 9 best practices
            * Developed Java microservices using Spring Boot and promoted TDD
        - title: Senior Full-Stack Software Engineer
          company: Media Exchange Group
          company_url: ''
          company_logo: ''
          location: Remote to London
          date_start: '2021-09-01'
          date_end: '2023-02-28'
          description: |2-
            * Promoted to project lead within five months
            * Built CI/CD automation for four AWS environments
            * Interviewed, hired and mentored team members
            * Led the project through launch, onboarding BBC and Deutsche Welle
            * Delivered Java Spring Boot microservices, Laravel, Next.js and Vue.js features
        - title: Senior Full-Stack Software Engineer
          company: Worktribe
          company_url: ''
          company_logo: ''
          location: Bristol
          date_start: '2020-03-01'
          date_end: '2021-09-30'
          description: |2-
            * Contributed to a real-time messaging application
            * Implemented Firebase push notifications in a React Native application
            * Fixed critical bugs across core software versions
            * Built strong domain knowledge in education and research software
        - title: Senior Backend Developer
          company: LOQBOX
          company_url: ''
          company_logo: ''
          location: Bristol
          date_start: '2018-12-01'
          date_end: '2020-03-31'
          description: |2-
            * Implemented automatic card payments for half a million active users
            * Laid the foundation for automated payment processing services and backend APIs
            * Used Laravel and AWS services in a live FinTech environment
            * Mentored two team members and improved team performance
    design:
      columns: '1'
      background:
        color:
          light: "#ffffff"
          dark: "#0d0d12"
      spacing:
        padding: ["4rem", "0", "4rem", "0"]

  - block: collection
    id: blog
    content:
      title: Publications
      subtitle: 'Writing, teaching and technical walkthroughs'
      text: ''
      filters:
        folders:
          - blog
        exclude_featured: false
      count: 3
      order: desc
    design:
      view: card
      columns: 3
      background:
        color:
          light: "#f5f5f5"
          dark: "#08080c"
      spacing:
        padding: ["4rem", "0", "4rem", "0"]

  - block: contact-info
    id: contact
    content:
      title: Get In Touch
      subtitle: "Let's talk about Java, cloud, full-stack product delivery or engineering leadership"
      text: |-
        I am interested in senior engineering, contract and technical leadership opportunities where pragmatic architecture, clear communication and hands-on delivery matter.
      email: hello@thecaringdeveloper.com
      autolink: true
    design:
      columns: '1'
      background:
        color:
          light: "#ffffff"
          dark: "#0d0d12"
      spacing:
        padding: ["4rem", "0", "4rem", "0"]

  - block: cta-card
    content:
      title: "Open to Senior Engineering Opportunities"
      text: |-
        Certified Spring, AWS and Oracle Java developer with broad full-stack delivery experience across media, FinTech and e-commerce.

        Download my latest resume or get in touch to discuss where I can help.
      button:
        text: 'Download Resume'
        url: uploads/resume.pdf
        new_tab: true
    design:
      card:
        css_class: 'bg-gradient-to-br from-primary-200 via-primary-100 to-secondary-200 dark:from-primary-600 dark:via-primary-700 dark:to-secondary-700'
        text_color: dark
      background:
        color:
          light: "#f5f5f5"
          dark: "#08080c"
      spacing:
        padding: ["4rem", "0", "6rem", "0"]
---
