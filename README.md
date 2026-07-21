<img width="2217" height="1249" alt="Vanell-homepage" src="https://github.com/user-attachments/assets/41eff82d-02af-4318-934d-903815926960" />

# Vanell Coffee — Ecommerce Platform (Case Study)

Freelance full-stack project for a coffee roasting business — an e-commerce platform with integrated payments, inventory management, and business analytics.

> **Note:** This was built as client work, and the codebase has been handed over to the client, so it isn't available as a public repository. This case study describes the project, my role, and the technical approach.

## What it does

- Public-facing storefront for browsing and purchasing single-origin coffee (product pages with origin story, tasting notes, brew recommendations, and multiple size/price options)
- Shopping cart and checkout flow
- Secure payment processing via **Stripe**
- Admin **Inventory Dashboard** for the business owner:
  - Real-time stock tracking (green beans vs. roasted stock)
  - **Low stock alerts** with reorder actions
  - Automated **Slack notifications** via an n8n workflow when stock drops below a set threshold; the team is notified in Slack so they can review and reorder manually
  - Stock movement and distribution charts
  - Product, supplier, and stock in/out management
  - **Reports & Analytics** module

## My role

Built end-to-end as a freelance full-stack developer: the customer-facing storefront, cart/checkout, Stripe integration, and the full admin inventory dashboard with reporting.

## Tech Stack

- **Frontend:** React 18 (Vite), Zustand for state management, Axios
- **Backend:** Express.js, TypeScript, JWT authentication
- **Database:** MongoDB (Atlas)
- **Automation:** n8n (Slack notification workflow for low-stock alerts)
- **Payments:** Stripe API

## Screenshots
<img width="2067" height="4863" alt="Product-page" src="https://github.com/user-attachments/assets/5229cecf-3551-4486-bb22-0e2209c64fce" />
<img width="2067" height="1635" alt="Check out page" src="https://github.com/user-attachments/assets/cbb10472-7f8a-41f2-a812-db133e106a20" />
<img width="2067" height="1156" alt="Admin dashboards" src="https://github.com/user-attachments/assets/2ff9aa9a-5bea-43c1-bcea-0ac8e70f85a2" />







