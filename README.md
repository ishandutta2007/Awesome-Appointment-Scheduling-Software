# 📅 Awesome Appointment Scheduling Software

![Awesome Appointment Scheduling Software Banner](./assets/banner.svg)

<p align="center">
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a><a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Appointment-Scheduling-Software"><img src="https://img.shields.io/github/stars/ishandutta2007/Awesome-Appointment-Scheduling-Software?style=social" alt="Stars"/></a>
  <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>
</p>

**Curated List of SaaS Platforms, Self-Hosted Booking Pages, Group Polling & Calendar Synchronization Software**

*Empowering professionals, enterprise sales teams, service businesses, and self-hosting enthusiasts to automate booking workflows.*

**Last updated: October 2026**

---

## 💡 Overview & Market Insights

The appointment scheduling software market is estimated at **~$5.5 Billion** and is **moderately fragmented**. While enterprise giants (Microsoft, HubSpot) and dominant category leaders (Calendly, Acuity) hold significant market share in hosted SaaS, the rapid rise of self-hosted, privacy-focused open-source platforms (Cal.com, Rallly, Easy!Appointments) prevents a single "winner-take-all" outcome. 

This repository tracks top-tier **SaaS platforms** and production-ready **open-source GitHub projects** for appointment scheduling, automated calendar booking, and meeting coordination.

---

## 📋 Table of Contents

- [🏢 SaaS & Hosted Platforms](#-saas--hosted-platforms)
- [💻 Open-Source GitHub Projects](#-open-source-github-projects)
  - [Full-Featured Platforms](#full-featured-platforms)
  - [Group Polling & Coordination](#group-polling--coordination)
  - [Niche & Resource Scheduling](#niche--resource-scheduling)
- [⭐ Star History](#-star-history)
- [❤️ Support & Sponsorship](#-support--sponsorship)
- [🤝 How to Contribute](#-how-to-contribute)
- [⚠️ Disclaimer](#%EF%B8%8F-disclaimer)

---

## 🏢 SaaS & Hosted Platforms

Below is a comparison of leading commercial SaaS appointment scheduling platforms, ordered by company size (valuation / market capitalization).

| Product | Enterprise Size / Market Cap / Revenue | Starting Paid Tier Pricing | Free Tier / Free Trial Limits | Key Highlights & Description |
| :--- | :--- | :--- | :--- | :--- |
| **[Microsoft Bookings](https://www.microsoft.com/en-us/microsoft-365/business/scheduling-and-booking-app)** | **~$3.1 Trillion** (Market Cap) | $6.00 / user / month (via M365 Business Basic) | Included with Microsoft 365 Business subscriptions | Deeply integrated into Outlook & Teams; ideal for M365 enterprises. |
| **[HubSpot Meetings](https://www.hubspot.com/products/sales/meetings)** | **~$11.0 Billion** (Market Cap) / **$3.1B** Rev | $15.00 / seat / month (Sales Hub Starter) | Free Plan (1 custom meeting link, HubSpot branding) | Built directly into HubSpot CRM for automated lead logging and scheduling. |
| **[Calendly](https://calendly.com/)** | **~$3.0 Billion** (Valuation) | $10.00 / user / month (Standard Plan) | Free Plan (1 active event type, 1 connected calendar) | The category leader for seamless 1-on-1 and team calendar booking. |
| **[Acuity Scheduling](https://acuityscheduling.com/)** | **~$2.5 Billion** (Parent Squarespace Valuation) | $16.00 / month (Emerging Plan) | 7-day Free Trial (Unlimited features during trial) | Popular with client service businesses; offers intake forms & payments via Stripe/PayPal. |
| **[Chili Piper](https://www.chilipiper.com/)** | **~$625 Million** (Valuation) | $15.00 / user / month (Form Concierge Starter) | 14-day Free Trial (Focused on sales demo requests) | Specialized inbound lead routing and instant qualification for revenue teams. |
| **[YouCanBookMe](https://youcanbook.me/)** | **~$50 Million** (Estimated Valuation) | $6.00 / calendar / month (Paid Plan) | Free Plan (1 booking page, 1 calendar linked, basic features) | Simple, cost-effective scheduling for solo professionals and small teams. |
| **[Setmore](https://www.setmore.com/)** | **~$30 Million** (Estimated Valuation) | $5.00 / user / month (Pro Plan) | Free Plan (Up to 4 users, 100 payments via Square) | Free appointment scheduling with staff management and booking pages. |
| **[Doodle](https://doodle.com/)** | **~$25 Million** (Estimated Valuation) | $6.95 / user / month (Pro Plan) | Free Plan (Group polls with ads, limited customization) | The pioneer in group scheduling polls to find consensus meeting times. |
| **[SimplyBook.me](https://simplybook.me/)** | **~$20 Million** (Estimated Valuation) | $9.90 / month (Basic Plan) | Free Plan (Up to 50 bookings/month, 1 provider, 1 custom feature) | Comprehensive booking website builder for service businesses with POS options. |
| **[Appointlet](https://www.appointlet.com/)** | **~$10 Million** (Estimated Valuation) | $8.00 / user / month (Premium Plan) | Free Plan (Unlimited event types & bookings, Appointlet branding) | Sales-focused scheduling tool with Salesforce, Zapier, and Slack integrations. |

---

## 💻 Open-Source GitHub Projects

Open-source alternatives offer complete data ownership, privacy compliance, and self-hosted customization. Sorted below by **GitHub Star Count** (descending).

### Full-Featured Platforms

- **[Cal.com](https://github.com/calcom/cal.com)** [![GitHub Stars](https://img.shields.io/github/stars/calcom/cal.com?style=social&color=white)](https://github.com/calcom/cal.com/stargazers)
  - **License**: AGPL-3.0
  - **Description**: The flagship open-source Calendly alternative. Features multi-calendar sync (Google, Outlook, CalDAV, Apple), team round-robin routing, Stripe payment workflows, webhooks, and REST APIs. Node.js + PostgreSQL stack.

- **[Easy!Appointments](https://github.alextselegidis/easyappointments)** [![GitHub Stars](https://img.shields.io/github/stars/alextselegidis/easyappointments?style=social&color=white)](https://github.com/alextselegidis/easyappointments/stargazers)
  - **License**: GPL-3.0
  - **Description**: Ultra-lightweight self-hosted appointment scheduler for service providers (clinics, salons, consultancies). Runs on PHP + MySQL in two Docker containers on a 1 GB VPS. Supports Google Calendar bidirectional sync.

### Group Polling & Coordination

- **[Rallly](https://github.com/lukevella/rallly)** [![GitHub Stars](https://img.shields.io/github/stars/lukevella/rallly?style=social&color=white)](https://github.com/lukevella/rallly/stargazers)
  - **License**: AGPL-3.0
  - **Description**: Open-source Doodle alternative for group scheduling polls. Voters do not need accounts. Includes guest comments and consensus voting. Node.js + PostgreSQL + Traefik stack.

### Niche & Resource Scheduling

- **[LibreBooking](https://github.com/LibreBooking/app)** [![GitHub Stars](https://img.shields.io/github/stars/LibreBooking/app?style=social&color=white)](https://github.com/LibreBooking/app/stargazers)
  - **License**: GPL-3.0
  - **Description**: Open-source reservation system for managing shared resources (conference rooms, equipment, lab spaces, vehicles).

- **[Alf.io](https://github.com/alfio-event/alf.io)** [![GitHub Stars](https://img.shields.io/github/stars/alfio-event/alf.io?style=social&color=white)](https://github.com/alfio-event/alf.io/stargazers)
  - **License**: GPL-3.0
  - **Description**: Open-source event attendance, ticket reservation, and badge printing system designed for tech conferences and workshops.

- **[Hi.Events](https://github.com/hi-events/hi-events)** [![GitHub Stars](https://img.shields.io/github/stars/hi-events/hi-events?style=social&color=white)](https://github.com/hi-events/hi-events/stargazers)
  - **License**: AGPL-3.0
  - **Description**: Modern open-source event management and ticketing platform built with Laravel and React. Great alternative to Eventbrite.

- **[Nextcloud Appointments](https://github.com/SergeMonterde/appointments)** [![GitHub Stars](https://img.shields.io/github/stars/SergeMonterde/appointments?style=social&color=white)](https://github.com/SergeMonterde/appointments/stargazers)
  - **License**: AGPL-3.0
  - **Description**: Native appointment booking app for Nextcloud, integrating directly with Nextcloud Calendar and user accounts.

- **[Zammad](https://github.com/zammad/zammad)** [![GitHub Stars](https://img.shields.io/github/stars/zammad/zammad?style=social&color=white)](https://github.com/zammad/zammad/stargazers)
  - **License**: AGPL-3.0
  - **Description**: Open-source customer support and helpdesk system featuring integrated calendar scheduling and appointment tracking.

---

## ⭐ Star History

[![Star History Chart](https://star-history.dera.page/svg?repos=ishandutta2007/Awesome-Appointment-Scheduling-Software&type=date&legend=top-left)](https://star-history.dera.page/#ishandutta2007/Awesome-Appointment-Scheduling-Software&type=date&legend=top-left)

---

## ❤️ Support & Sponsorship

Thank you for exploring and using this curated list! If this repository has saved you time or helped you find the right scheduling software, please consider supporting the project:

- ⭐ **Star** this repository to help others discover it.
- 🔀 **Fork** and contribute new tools or updates.
- 📢 **Share** with your colleagues, teams, and developer community.
- ☕ **Buy Me a Coffee**: Support ongoing open-source curation on the [GitHub Sponsor Dashboard](https://github.com/sponsors/ishandutta2007).

---

## 🤝 How to Contribute

1. Fork this repository.
2. Add or update entries in `README.md` maintaining table and section structure.
3. Ensure links, licensing, and pricing details are accurate.
4. Submit a Pull Request with a clear description of your changes.

---

## ⚠️ Disclaimer

- This list is community-curated for informational purposes and does not constitute formal endorsement.
- Appointment scheduling platforms handle sensitive personal and calendar data; ensure compliance with GDPR, CCPA, and regional privacy laws before deployment.
- **Open-source ecosystem maturity**: Self-hosted solutions like **Cal.com**, **Easy!Appointments**, and **Rallly** offer complete data sovereignty and powerful features, though enterprise SaaS platforms provide managed uptime and turnkey CRM integrations out of the box.

---

<p align="center">
  Made with ❤️ for consultants, service businesses, sales teams, and self-hosting enthusiasts.
</p>
