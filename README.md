# Hi, I'm Carlos

Computer science student at WGU building full-stack web apps — React and TypeScript on the
front end, Python and Flask on the back end, with Java and Spring Boot from coursework.

## Projects

**[E-Commerce Storefront](https://github.com/calv511/ecommerce)** · [Live Demo](https://ecommerce-seven-delta-83.vercel.app) · React 19 · TypeScript · Firebase · Redux Toolkit
A single-page storefront running entirely on Firebase — Authentication for email/password,
Google, and guest sessions, and Cloud Firestore for users, products, carts, and orders.
Guest and signed-in carts reconcile by product ID on sign-in (larger quantity wins), Firestore
security rules scope every document to its owner and freeze placed orders, and debounced
writes keep redundant calls down. Deployed on Vercel.

**[Mechanic Shop API](https://github.com/calv511/mechanic_shop_api)** · Flask · SQLAlchemy · Marshmallow · MySQL · JWT
A REST API where customers book service tickets, mechanics get assigned to them, and parts
get pulled from inventory. JWT auth with role-separated customer and mechanic tokens — the
mechanic-only decorator returns 403 for a valid customer token. Parts on a ticket use an
association object with a quantity column, so re-adding a part accumulates instead of
duplicating a row. Rate limiting, response caching, pagination, and scrypt password hashing
throughout; a 60-request Postman collection covers every endpoint with 79 assertions.

**[Task Manager](https://github.com/calv511/task-manager)** · React 19 · TypeScript · Auth0
A task app with real authentication — Auth0 login, registration, and Google sign-in — plus
full CRUD, inline validation, and a focused task detail modal.

## Tech

**Languages:** Java, TypeScript, JavaScript, Python, SQL, HTML, CSS
**Front end:** React, Redux Toolkit, TanStack Query, React Router, Vite, Bootstrap
**Back end:** Flask, SQLAlchemy, Marshmallow, Spring Boot, REST APIs, JWT
**Data & platforms:** MySQL, PostgreSQL, Firebase Auth, Cloud Firestore, Vercel
**Tools:** Git, GitHub, Postman, Docker, Maven, npm

## Currently

Learning testing (pytest, Vitest) and CI with GitHub Actions, and looking for a software
engineering internship or entry-level role.

## Reach me

- Email: carlosalvarez214@gmail.com
- GitHub: [github.com/calv511](https://github.com/calv511)
