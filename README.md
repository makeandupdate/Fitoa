# Fitoa

**Studio automation platform with a digital credit engine for boutique fitness businesses.**

Fitoa helps boutique studios reduce operational overhead by replacing rigid membership workflows with a flexible, automated credit-based system. Instead of relying on manual approval flows and complex membership tiers, Fitoa streamlines booking, billing, and retention so studio owners can spend less time on administration and more time growing the business.

## Why Fitoa

Traditional studio management tools often depend on fixed membership plans, manual reconciliation, and staff intervention. Fitoa uses a digital credit model designed for faster operations and simpler management.

### Digital credits over memberships

- **Real-time credit deductions** for bookings and transactions
- **No manual accept/reject workflows**
- **Simplified operations** across classes, packs, and renewals
- **Better member retention** through automated inactivity follow-ups

### Built for high-volume studios

Fitoa is designed for studios running fast-paced, credit-based class schedules, including:

- Yoga
- HIIT
- Pilates
- Functional fitness

## Key features

- **Automated credit engine**  
  Credits are deducted automatically at the point of booking or transaction.

- **Retention workflows**  
  Automated win-back triggers can re-engage members who have been inactive for 14+ days.

- **In-studio payments**  
  Native Stripe Terminal support enables seamless in-person transactions.

- **Responsive frontend architecture**  
  Built for fast user interactions and clean navigation.

- **AI-ready discovery**  
  Includes a root-level `llms.txt` file for AI agent compatibility and discovery workflows.

## Tech stack

### Frontend
- React.js
- Headless architecture
- SEO-conscious rendering and structure

### Backend
- Node.js
- Firebase Firestore
- Real-time data handling

### Payments
- Stripe
- Stripe Terminal

## Project structure

```text
├── src/
│   ├── components/       # Reusable React UI components
│   ├── logic/            # Credit engine and automation handlers
│   └── styles/           # Performance-optimized CSS
├── public/
│   └── demo.html         # Interactive product demo
├── llms.txt              # AI discovery manifest
└── README.md             # Project documentation
