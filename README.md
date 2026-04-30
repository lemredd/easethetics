<h1 align="center">
  <img align="center" src="https://app.easethetics.ph/static/image/EasetheticsLogoWhite.png" alt="Easethetics Logo" width="200"/>
</h1>
<p align="center">
  <strong>Clinic Management SaaS for Aesthetics & Beauty Clinics</strong>
</p>
<p align="center">
  <strong>NOTE:</strong> This repository serves only as proof of my contributions with the project.
</p>

## Main System
### Features

| Module | Description |
|--------|-------------|
| **Appointments** | Booking, scheduling, short links via Easebook |
| **Patient Charts** | Medical records, prescriptions, attachments |
| **Point of Sale** | Transactions, sessions, payments, discounts, gift events |
| **Inventory** | Products, stock groups, batch tracking, supplier management |
| **Services** | Service catalog, categories, consumables, commissions |
| **Memberships** | Tiers, points accrual, packages, spending tracking |
| **Employees** | Attendance, schedules, leave, commission tracking |
| **Accounting** | Purchases, expenses, sales reports |
| **Invoicing** | Subscriptions, billing, payment transactions |
| **Promotions** | Buy X get Y deals, time-limited discounts |
| **Marketing** | SMS & email campaigns |
| **E-Commerce** | Easemart storefront, cart, delivery, returns |
| **Support** | Ticketing system, live chat |
| **Mobile API** | GraphQL for Easelife/Easebook apps, FCM push notifications |

### Tech Stack
```
Backend      Django · Graphene (GraphQL) · DRF (REST)
Database     MySQL (AWS RDS) · SQLite (development)
Cache        Redis
Queue        Celery + RabbitMQ
Frontend     Django Templates · Tailwind CSS · jQuery · TypeScript
```

## Easebook
Convenient appointment scheduling for end users.

### Features

| Sub-feature | Description |
|-------------|-------------|
| **Booking Form** | Multi-step appointment booking form with schedule and patient information |
| **Form Validation** | Zod schema validation for all form fields |
| **User Experience** | Multi-step form with smooth transitions |
| **Existing Patient Handling** | Existing patient detection and confirmation dialog |
| **Consent Management** | Comprehensive consent information and agreement |
| **Appointment Success** | Success page with appointment details |
| **Clinic Information** | Dynamic clinic and branch display |
| **API Integration** | REST and GraphQL API proxy endpoints |
| **Data Transformation** | Form data transformation for API submission |
| **Error Handling** | Comprehensive error handling and user feedback |
| **Accessibility** | Accessible form controls and UI elements |
| **Internationalization** | Basic date/time localization support |
| **State Management** | React hook form integration |
| **Routing** | Dynamic shortlink-based routing |
| **Analytics** | Basic appointment tracking |

### Tech Stack
```
Frontend    Next.js · Tanstack Query · shadcn/ui · axios
```

### Easesupport
In-house web application to support business clients with concerns.

### Features
| Sub-feature | Description |
|-------------|-------------|
| **Authentication** | Secure user authentication and session management |
| **Dashboard** | Comprehensive overview and analytics |
| **Clinic Management** | Complete clinic administration |
| **Ticket System** | Customer support ticket management |
| **Chat System** | Real-time communication features |
| **Easelife Travel** | Travel package management |
| **Easemart E-commerce** | Online store management |
| **Invoice Management** | Comprehensive invoicing system |
| **User Management** | User administration features |
| **Advertisement Management** | Marketing and promotion tools |
| **Financial Management** | Comprehensive financial tools |
| **Reporting** | Advanced reporting capabilities |
| **Real-time Features** | Live updates and notifications |
| **API Integration** | Backend service integration |
| **UI Components** | Reusable interface elements |
| **Responsive Design** | Mobile and desktop compatibility |
| **Accessibility** | Inclusive design features |
| **Internationalization** | Multi-language support |
| **State Management** | Advanced state handling |
| **Security** | Comprehensive security measures |
| **Performance** | Optimized performance |
| **Error Handling** | Robust error management |
| **Analytics** | Usage tracking and insights |

## Overall Contributions
- Implemented Easebook
- Streamlined SMS and email campaign sending processes, enhancing accuracy in queue status and analytics.
- Collaborated with developer teammates to improve user interface, gaining massive user engagement.
- Collaborated with mobile developers in implementing and integrating GraphQL API for convenient data fetching.
- Supported with client feature requests and resolving bugs (Collaboration with marketing team).
- Integrated AI with n8n, boosting marketing leads by 10%.
