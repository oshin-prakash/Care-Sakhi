# Care-Sakhi
CareSakhi is an AI-powered platform redefining menstrual product access on college campuses. We streamline a direct supply chain that bypasses traditional bottlenecks and empower student/alumni distributors with smart logistics tools to deliver sustainable, reusable menstrual solutions.


**👩‍🎓 Students & Customers**

AI-smart store for seamless access to sustainable menstrual products

Predictive period tracking with personalized wellness insights

A complete educational space for menstrual and reproductive health

24/7 AI assistant for guidance, questions, and eco-tips

Rewards-enabled digital wallet for quick, secure payments

Live sustainability tracker showing your eco-impact

**🎯 Campus Distributors**

AI dashboards delivering powerful business and customer analytics

Earnings, growth, and trend insights at a glance

Gamified rewards to motivate and boost distributor engagement

Smart inventory tools to forecast demand and prevent shortages

Earn sustainably through a tech-enabled micro-entrepreneurship model

Mobile-optimized interface for managing your store anywhere

**🏥 Partner Pharmacies**

A dedicated portal to manage orders and product availability

Prescription-based support for health-aligned recommendations

Location-based visibility for customers searching nearby stock

Actionable analytics to refine product offerings and boost sales

****💻 Tech Stack Overview

**Frontend**

Built with React 18 and TypeScript for predictable, maintainable UI

Vite powers instant dev refresh and optimized builds

Styled with Tailwind CSS for rapid, responsive design

Navigation handled through React Router

Lucide React ensures crisp, scalable icons across the UI

**Backend**

Node.js + Express for a fast and extensible server layer

SQLite for simple yet efficient storage with full migration support

JWT + bcryptjs for secure, token-based authentication

REST API structure ensuring modularity and clean error reporting

**AI Features**

AI recommendation engine for product personalization

Predictive models for inventory and demand forecasting

Conversational AI chatbot offering assistance and guidance

Context-aware alerts for menstrual cycle updates and user actions


**📄 API Documentation**

Authentication Endpoints:
POST /api/auth/register    # User registration
POST /api/auth/login       # User authentication
POST /api/auth/refresh     # Token refresh
Product Management:
GET    /api/products       # List all products
GET    /api/products/:id   # Get product details
POST   /api/products       # Add new product (distributors)
PUT    /api/products/:id   # Update product

** 🚀 Quick Start**

### Prerequisites
- Node.js (v18 or later)
- npm or yarn
- Git

### Installation

```bash
# Clone the repository
git clone https://github.com/piyush-lingwal/Caresakhi.git

# Navigate to project directory
cd Caresakhi

# Install dependencies
npm install

# Set up environment variables
cp .env.example .env
# Edit .env with your configuration

# Start development server
npm run dev

# Open browser to http://localhost:5173
```

### Build for Production

```bash
# Create optimized production build
npm run build

# Preview production build locally
npm run preview
```

AI Features:
GET    /api/ai/recommend/:userId     # Get personalized recommendations
POST   /api/ai/chat                 # Chat with AI assistant
GET    /api/ai/insights/:userId     # Get health insights

