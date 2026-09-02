# Utility Readings Management PWA — Case Study

<p>
  <img src="https://img.shields.io/badge/Status-Pilot_Case_Study-2F855A?style=flat-square" alt="Pilot case study">
  <img src="https://img.shields.io/badge/Next.js-Web_Application-111827?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js">
  <img src="https://img.shields.io/badge/TypeScript-Language-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/Supabase-Data_Platform-3ECF8E?style=flat-square&logo=supabase&logoColor=white" alt="Supabase">
  <img src="https://img.shields.io/badge/Tailwind_CSS-Responsive_UI-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" alt="Tailwind CSS">
</p>

Case study of a role-based progressive web application created to centralize water and electricity readings, historical records and operational follow-up across multiple properties.

> **Portfolio notice:** This public repository contains project documentation and sanitized visuals only. Source code, credentials, internal records and implementation details are intentionally excluded.

## Overview

This project was developed as an internal pilot during my internship at **Prologis**. Its purpose was to replace a fragmented utility-reading workflow with a clearer digital experience for capturing, consulting and comparing operational information.

The application brings readings, historical imports and maintenance follow-up into a single responsive interface designed for different types of users.

## The challenge

Utility information can become difficult to review when readings are distributed across spreadsheets, reporting periods and individual properties. The project focused on making that information easier to capture, find and compare while respecting each user's level of access.

The main product goals were:

- Centralize water and electricity readings
- Organize records by property and reporting period
- Make historical information easier to consult
- Compare readings between periods
- Import existing records from Excel files
- Support role-based access to application functions
- Track readings and related maintenance incidents
- Provide a responsive experience for desktop and mobile use

## My contribution

I participated in the analysis, design and development of the pilot application. My work included:

- Translating an operational process into application screens and workflows
- Building responsive interfaces with Next.js, React and TypeScript
- Connecting application views to Supabase services
- Implementing experiences that adapt to user roles and permissions
- Supporting historical-data import and period-comparison workflows
- Organizing the capture and consultation of utility readings
- Testing the pilot and refining the interface based on its intended use
- Preparing technical documentation for the project

## Core capabilities

### Utility readings

- Capture water and electricity readings
- Consult records by property and period
- Review historical information from one interface
- Compare values across reporting periods

### Data continuity

- Import previously collected records from Excel
- Preserve access to historical information
- Reduce repeated manual consultation across separate files

### Access and operations

- Role-based views and permissions
- Maintenance-incident follow-up
- Responsive navigation across supported devices
- Centralized access to operational information

## Technology stack

| Area | Technology |
|---|---|
| Web framework | Next.js, React |
| Language | TypeScript |
| Styling | Tailwind CSS |
| Data and services | Supabase |
| Application type | Progressive Web App (PWA) |
| Development workflow | Git, npm |

## Product flow

1. An authorized user accesses the application.
2. The interface presents the options available for that user's role.
3. The user captures a new reading or consults existing records.
4. Historical information can be filtered and compared by reporting period.
5. Related operational incidents can be reviewed as part of the workflow.

## Design priorities

- **Clarity:** present operational data without unnecessary complexity
- **Consistency:** use repeatable patterns for capture, consultation and comparison
- **Responsiveness:** support practical use across different screen sizes
- **Traceability:** preserve historical context when reviewing information
- **Controlled access:** adapt available actions to each user role

## Visual preview

The following screenshots use fictional demonstration data and illustrate the main application workflows.

### Monthly reading capture

<p align="center">
  <a href="./assets/monthly-reading-capture.png">
    <img
      src="./assets/monthly-reading-capture.png"
      width="900"
      alt="Monthly water and electricity reading capture interface"
    >
  </a>
</p>

<p align="center">
  <sub>Monthly data capture with live validation, calculated consumption fields and evidence uploads.</sub>
</p>

### Monthly sheets and QR workflow

<p align="center">
  <a href="./assets/monthly-sheets-qr-workflow.png">
    <img
      src="./assets/monthly-sheets-qr-workflow.png"
      width="900"
      alt="Monthly utility sheets and QR-assisted workflow"
    >
  </a>
</p>

<p align="center">
  <sub>QR-assisted access, reporting-period selection and monthly record organization.</sub>
</p>

### Role-based administration

<p align="center">
  <a href="./assets/admin-role-profile.png">
    <img
      src="./assets/admin-role-profile.png"
      width="900"
      alt="Administrator profile and role-based access interface"
    >
  </a>
</p>

<p align="center">
  <sub>Administrator account with role information, property coverage and permission-specific navigation.</sub>
</p>

### Printable utility report

<p align="center">
  <a href="./assets/printable-utility-report.png">
    <img
      src="./assets/printable-utility-report.png"
      width="900"
      alt="Printable monthly water and electricity report"
    >
  </a>
</p>

<p align="center">
  <sub>Structured monthly utility records prepared for review, printing or PDF export.</sub>
</p>

## Outcome

The project was delivered as an internal pilot that demonstrates how a recurring operational process can be transformed into a centralized web workflow.

Because this is a portfolio case study, no unverified performance metrics or production-usage claims are included. Future updates may add measurable outcomes only when they can be shared and verified.

## Privacy and repository scope

This repository intentionally does **not** include:

- Application source code
- Environment files or credentials
- Supabase project identifiers or private configuration
- Database schemas, migrations or access policies
- Internal property, employee or customer information
- Real utility readings, spreadsheets or maintenance records
- Company documents, certificates, evidence files or backups
- Internal URLs, screenshots with identifiable data or proprietary branding assets

The content is limited to a high-level description of the problem, my contribution, the technology stack and sanitized interface previews.

## What I learned

This project strengthened my experience with:

- Building responsive applications with Next.js and TypeScript
- Structuring interfaces around real operational workflows
- Connecting frontend experiences with Supabase services
- Designing role-aware application behavior
- Presenting historical data and period comparisons clearly
- Turning business requirements into maintainable product features
- Documenting a private project responsibly for a technical portfolio

## Author

**Carlos Constantino**  
Junior Frontend Developer

- Portfolio: https://portafoliofrann.netlify.app/
- LinkedIn: https://www.linkedin.com/in/fcoocarlos/
- GitHub: https://github.com/frannnkkyy

## Disclaimer

This case study is presented for portfolio purposes. It is not an official Prologis product page, and no affiliation, endorsement or ownership of company branding is implied.
