<div align="center">

# Ravi Pareek

**Software Engineer · Backend & Systems**

B.E. Computer Engineering · Thapar Institute of Engineering and Technology

</div>

I build backend services with Spring Boot and Node.js, and I like understanding the machine underneath them. My capstone, **SAGA-16**, is a 16-bit CPU with its own simulator, operating system and live debugging workstation. Right now I'm building an **API gateway** with Spring Boot, Redis and Kafka.

## About me

- Computer Engineering undergraduate at Thapar Institute of Engineering and Technology (2023 – present)
- Focused on backend development, scalable systems and systems programming
- 250+ data structures and algorithms problems solved
- Open to software engineering internships and collaborations

## Featured projects

### [BAREMETAL / SAGA-16](https://github.com/Ravipareek05/baremetal-saga16)

University capstone: a complete computing stack built from scratch. It includes a custom 16-bit CPU, a cycle-accurate simulator, an operating system written in the CPU's own assembly language, and a browser workstation that boots it live.

![C](https://img.shields.io/badge/C-21262D?style=flat-square&logo=c&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-21262D?style=flat-square&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-21262D?style=flat-square&logo=nodedotjs&logoColor=white)
![React](https://img.shields.io/badge/React-21262D?style=flat-square&logo=react&logoColor=white)
![WebSockets](https://img.shields.io/badge/WebSockets-21262D?style=flat-square)

<a href="https://github.com/Ravipareek05/baremetal-saga16">
  <img src="https://raw.githubusercontent.com/Ravipareek05/baremetal-saga16/HEAD/docs/screenshots/02-shell-help.png" alt="SAGA-16 workstation: the OS shell running on the simulator, with live registers and kernel state" width="100%">
</a>

- **CPU and simulator:** 16-opcode, 8-register ISA with a hardware stack, modelled by a cycle-accurate C99 simulator that matches an independent TypeScript model cycle-for-cycle on 600 random programs.
- **Anomaly detection:** flags stack overflow and underflow, invalid jumps, null-zone access, bus errors and runaway loops while programs run.
- **Operating system:** boot ROM, a kernel with 16 system calls, a relocating loader that rejects bad checksums and privileged instructions, a first-fit allocator, a shell and user programs (including Snake).
- **Live telemetry:** a Node.js backend streams schema-validated machine state over WebSockets to a React workstation that shows registers, memory, system calls and anomalies as they happen.
- **Testing:** 350+ automated checks, from C unit tests and OS integration tests to an end-to-end run in headless Chrome.

✅ CPU, simulator, OS and dashboard complete and tested · 🗓️ Next: Verilog RTL on a DE10-Lite FPGA (not started)

### Smart API Gateway & Microservices Platform

A single entry point in front of a set of microservices that handles routing, security and traffic control in one place.

![Java](https://img.shields.io/badge/Java-21262D?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-21262D?style=flat-square&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-21262D?style=flat-square&logo=springsecurity&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-21262D?style=flat-square&logo=redis&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache_Kafka-21262D?style=flat-square&logo=apachekafka&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-21262D?style=flat-square&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-21262D?style=flat-square&logo=mongodb&logoColor=white)
![React](https://img.shields.io/badge/React-21262D?style=flat-square&logo=react&logoColor=white)

- Centralised API management and request routing
- JWT-based authentication
- Configurable routing rules and rate limiting
- Redis-backed caching
- Asynchronous analytics through Kafka
- Separate storage for configuration and event data (MySQL, MongoDB)

🚧 In development · repository not yet public

### More projects

- **[CampusPlay](https://github.com/Ravipareek05/CampusPlay)**: college e-sports platform with tournament creation and sign-up, leaderboards, an admin panel, bulk player import from CSV and a JWT-secured Express API.<br>`Node.js` `Express` `MongoDB` `JWT`
- **Full-Stack Job Portal**: MERN job board with Clerk authentication and Sentry error and performance monitoring; optimised search endpoints cut average query time by 40%.<br>`React` `Node.js` `Express` `MongoDB` `Clerk` `Sentry`
- **[Smart Placement Platform](https://github.com/Ravipareek05/smart-placement-platform)**: coding-practice platform with an admin-managed problem bank, progress tracking, a Monaco editor and a judge that runs submissions against test cases in per-language Docker containers (C++, Java, Python, JavaScript).<br>`React` `Express` `Prisma` `Docker`
- **[Chess with Minimax AI](https://github.com/Ravipareek05/Minimax-Based-Chess-AI-Engine)**: full chess rules, including castling, en passant and promotion, against an AI that uses minimax search with alpha-beta pruning and heuristic evaluation.<br>`Python` `Pygame`
- **[Nmap Scanner](https://github.com/Ravipareek05/Nmap-scanner)**: Python CLI for SYN, UDP and full port scans, with custom port ranges and saved reports.<br>`Python` `Nmap`

## Tech stack

**Languages**<br>
![Java](https://img.shields.io/badge/Java-21262D?style=flat-square&logo=openjdk&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-21262D?style=flat-square&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-21262D?style=flat-square&logo=c&logoColor=white)
![Python](https://img.shields.io/badge/Python-21262D?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-21262D?style=flat-square&logo=javascript&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-21262D?style=flat-square)

**Backend**<br>
![Spring Boot](https://img.shields.io/badge/Spring_Boot-21262D?style=flat-square&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-21262D?style=flat-square&logo=springsecurity&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-21262D?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-21262D?style=flat-square&logo=express&logoColor=white)
![REST APIs](https://img.shields.io/badge/REST_APIs-21262D?style=flat-square)
![JWT](https://img.shields.io/badge/JWT-21262D?style=flat-square&logo=jsonwebtokens&logoColor=white)

**Data and messaging**<br>
![MySQL](https://img.shields.io/badge/MySQL-21262D?style=flat-square&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-21262D?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-21262D?style=flat-square&logo=redis&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache_Kafka-21262D?style=flat-square&logo=apachekafka&logoColor=white)

**Frontend**<br>
![React](https://img.shields.io/badge/React-21262D?style=flat-square&logo=react&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-21262D?style=flat-square&logo=tailwindcss&logoColor=white)
![HTML](https://img.shields.io/badge/HTML-21262D?style=flat-square&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-21262D?style=flat-square&logo=css&logoColor=white)

**Tools**<br>
![Git](https://img.shields.io/badge/Git-21262D?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-21262D?style=flat-square&logo=github&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-21262D?style=flat-square&logo=postman&logoColor=white)
![Sentry](https://img.shields.io/badge/Sentry-21262D?style=flat-square&logo=sentry&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-21262D?style=flat-square&logo=n8n&logoColor=white)
![OpenAI API](https://img.shields.io/badge/OpenAI_API-21262D?style=flat-square)

## Currently learning

- **Spring Boot and Spring Security**, by building the API gateway
- **Redis and Apache Kafka**, for caching and asynchronous event pipelines
- **Next:** Verilog and FPGA design, to take SAGA-16 from simulator to hardware

## GitHub stats

<div align="center">

<img height="150" src="https://github-readme-stats.vercel.app/api?username=Ravipareek05&show_icons=true&hide=stars,prs,issues&hide_rank=true&theme=github_dark&hide_border=true" alt="GitHub stats">
<img height="150" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Ravipareek05&layout=compact&hide=html,css&langs_count=6&theme=github_dark&hide_border=true" alt="Most used languages">

</div>

## Connect with me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-21262D?style=flat-square&logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0iI2ZmZiIgZD0iTTIwLjQ0NyAyMC40NTJoLTMuNTU0di01LjU2OWMwLTEuMzI4LS4wMjctMy4wMzctMS44NTItMy4wMzctMS44NTMgMC0yLjEzNiAxLjQ0NS0yLjEzNiAyLjkzOXY1LjY2N0g5LjM1MVY5aDMuNDE0djEuNTYxaC4wNDZjLjQ3Ny0uOSAxLjYzNy0xLjg1IDMuMzctMS44NSAzLjYwMSAwIDQuMjY3IDIuMzcgNC4yNjcgNS40NTV2Ni4yODZ6TTUuMzM3IDcuNDMzYy0xLjE0NCAwLTIuMDYzLS45MjYtMi4wNjMtMi4wNjUgMC0xLjEzOC45Mi0yLjA2MyAyLjA2My0yLjA2MyAxLjE0IDAgMi4wNjQuOTI1IDIuMDY0IDIuMDYzIDAgMS4xMzktLjkyNSAyLjA2NS0yLjA2NCAyLjA2NXptMS43ODIgMTMuMDE5SDMuNTU1VjloMy41NjR2MTEuNDUyek0yMi4yMjUgMEgxLjc3MUMuNzkyIDAgMCAuNzc0IDAgMS43Mjl2MjAuNTQyQzAgMjMuMjI3Ljc5MiAyNCAxLjc3MSAyNGgyMC40NTFDMjMuMiAyNCAyNCAyMy4yMjcgMjQgMjIuMjcxVjEuNzI5QzI0IC43NzQgMjMuMiAwIDIyLjIyMiAwaC4wMDN6Ii8+PC9zdmc+Cg==)](https://www.linkedin.com/in/ravi-pareek-05825237b/)
[![Email](https://img.shields.io/badge/Email-21262D?style=flat-square&logo=gmail&logoColor=white)](mailto:pareekravi5102003@gmail.com)

<div align="right">

![Profile views](https://komarev.com/ghpvc/?username=Ravipareek05&style=flat-square&color=21262D&label=Profile+views)

</div>
