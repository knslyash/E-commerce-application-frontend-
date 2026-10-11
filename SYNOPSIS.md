# Project Synopsis

## Title
**ShopFront** — A Modern E-Commerce Frontend Application

## Overview
ShopFront is a frontend-only e-commerce web application that replicates the core browsing and shopping experience of a modern online store. It focuses purely on client-side implementation — UI/UX, state management, routing, and responsive design — without a custom backend. Product and order data are served via a mock/public REST API or local JSON, making the project easy to run, demo, and extend.

## Problem Statement
Most e-commerce tutorials either couple frontend and backend tightly or skip real-world concerns like cart persistence, filtering, and responsive design. ShopFront isolates the frontend layer to demonstrate strong UI engineering, state management, and component architecture — skills directly relevant to frontend/full-stack interviews.

## Objectives
- Build a production-quality, responsive e-commerce UI from scratch
- Implement client-side state management for cart, wishlist, and filters
- Demonstrate routing, lazy loading, and performance optimization
- Practice component reusability and clean architecture patterns
- Integrate with a public/mock API for realistic data flow

## Core Features
- **Product Catalog** — grid/list views, category and price filters, search, sorting
- **Product Details** — image gallery, variants (size/color), reviews section
- **Cart & Wishlist** — add/remove/update quantity, persisted via localStorage
- **Checkout Flow (UI only)** — address form, order summary, mock payment step
- **Authentication (UI only)** — login/signup forms with client-side validation
- **Responsive Design** — mobile-first layout, works across breakpoints
- **Dark/Light Theme** — user-toggleable theme persisted across sessions

## Tech Stack
| Layer | Technology |
|---|---|
| Framework | React + TypeScript |
| Build Tool | Vite |
| Styling | Tailwind CSS |
| State Management | Redux Toolkit / Zustand |
| Routing | React Router |
| HTTP Client | Axios / Fetch API |
| Data Source | Fake Store API / DummyJSON (mock backend) |
| Testing | Vitest + React Testing Library |
| Deployment | Vercel / Netlify |

## Scope & Limitations
- No real backend, database, or payment gateway — all transactional flows are simulated
- Authentication is UI-only (no real session/token backend)
- Intended as a portfolio/demo project, not production-ready for real transactions

## Target Outcomes
- A polished, deployable demo suitable for a portfolio and LinkedIn showcase
- A reusable component library (buttons, cards, modals, forms)
- Clean Git history with meaningful commits, suitable for FAANG resume discussion
