# WiseUp — Frontend (Vite + React + TypeScript)

> **WiseUp** connects startups with experienced retirees to provide affordable, flexible domain-specific expertise — while giving retirees purpose, recognition and extra income.

---

## 📖 About this Project

WiseUp was conceived, designed, and implemented as part of the  
[Software Engineering for Business Applications (SEBA) Master’s course](https://wwwmatthes.in.tum.de/pages/1mqqqoqe7gapz/Software-Engineering-for-Business-Applications-SEBA-Master) at TUM.  

As part of this course, we:
- **Ideated** the concept and value proposition.  
- **Developed** a business plan and matching model.  
- **Created** customer journeys, personas, and UI mockups.  
- **Implemented** the platform as a working web application (frontend & backend).  

wiseup-matching contains the **frontend and Backend implementation** of that project.

---

## Contributors

This project was created by a team of four Master’s students:  

- [Jakob](https://github.com/jmoehler)  
- [Sebastian](https://github.com/sebastianmoelder)  
- [Michael](https://github.com/mschmidm)  
- [Renée](https://github.com/reneemschmitt1)  

---


## TL;DR

- **What**: Frontend of the WiseUp matchmaking platform.  
- **Why**: Startups lack budget for senior expertise; retirees want meaningful, flexible work. WiseUp matches both sides efficiently.  
- **How**: A smooth, passwordless UX with guided sign-up, search, automatic matches, and in-app chat.  

---

## 1) Problem We Solve

Early-stage startups need targeted expertise but cannot afford full-time hires or big-firm consulting. Meanwhile, many healthy, motivated retirees want to keep contributing on their own terms.  

WiseUp bridges that gap with a curated, two-sided marketplace and matching flow that turns **experience into momentum** for startups and **meaning into work** for retirees.

---

## 2) Customer Journey (Product Walkthrough)

Use these anchors to place your A3 screenshots in context.

1. **Landing Page**  
   Insert **[A3 — Figure 2: WebApp: Landing Page]** here.  

2. **Retiree Sign-Up (Magic Link)**  
   Insert **[A3 — Figure 4: WebApp: Sign Up Page]** and **[A3 — Figure 5: SignUp for Retirees]** here.  

3. **Onboarding Questionnaire**  
   Insert **[A3 — Figures 7–11: Questionnaire as Part of Sign Up]** here.  

4. **Retiree Home**  
   Insert **[A3 — Figure 13: WebApp: Retiree Homepage]** and **[A3 — Figure 14: Homepage with Tutorial]** here.  

5. **Startup Profile & Job Listings**  
   Insert **[A3 — Figure 16: WebApp: Startup Company Profile]** here.  

6. **Create New Job Posting**  
   Insert **[A3 — Figures 18 & 20: WebApp: Create a New Job Posting]** here.  

7. **Browse Retirees**  
   Insert **[A3 — Figure 22: WebApp: Browse for Retirees]** here.  

8. **Automatic Matches**  
   Insert **[A3 — Figures 24–26: WebApp: Automatically Created Matches]** here.  

9. **Subscription Upgrade Prompt**  
   Insert **[A3 — Figure 28: No Connections Left]** and **[A3 — Figure 29: Subscription Model Selection]** here.  

10. **Chat & Hiring**  
    Insert **[A3 — Figure 31: WebApp: Chat with Retiree]** here.  

11. **Profile Status Change**  
    Insert **[A3 — Figure 33: Retiree Profile incl. Current Status]** and **[A3 — Figure 35: Status Changed]** here.  

> **Note on Exposures**: “Exposures” position listings more prominently based on the startup’s Stripe plan (Gold at top, then Silver). Insert **[A3 — Figures 28–29]** where you describe plans.

---

## 3) Tech Stack

**Frontend**
- [React](https://react.dev/) + [TypeScript](https://www.typescriptlang.org/) (with [Vite](https://vitejs.dev/) as build tooling)  
- [shadcn/ui](https://ui.shadcn.com/) components  
- API client generated from Backend **OpenAPI** spec  
- Tooling: ESLint, Prettier, Docker (for local/dev)  

**Backend (consumed by this app)**  
- [Node.js](https://nodejs.org/) with TypeScript HTTP API  
- [OpenAPI](https://www.openapis.org/) specification as API contract  
- [Docker Compose](https://docs.docker.com/compose/) for containerized services  
- Passwordless, email-based sign-in (“magic link”) workflow  
- Matching, listings, chat, subscriptions (plans & exposures)  

---

## 4) Getting Started

Check the individual [Frontend README](https://github.com/wiseup-matching/frontend-public) and [Backend README](https://github.com/wiseup-matching/backend-public) for setup instructions.  

You need to configure `.env` files with the correct credentials.  

In order to run the entire application you’ll need:  
- [Brevo](https://www.brevo.com/) (emails)  
- [MongoDB](https://www.mongodb.com/) (database)  
- [Stripe](https://stripe.com/) (payments & subscriptions)  

---

## 5 License

This project is licensed under this [license](https://github.com/wiseup-matching/frontend-public/blob/main/LICENSE).
