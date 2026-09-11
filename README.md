# EATSENCE.AI

> **AI-Powered Nutrition Intelligence Platform**  
> *Personalized nutrition. Smarter eating. Better health.*

---

<p align="center">

![License](https://img.shields.io/badge/License-MIT-green)
![Next.js](https://img.shields.io/badge/Next.js-15-black)
![React](https://img.shields.io/badge/React-19-61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-5.8-blue)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-4.0-38BDF8)
![AI Powered](https://img.shields.io/badge/AI-Gemini%20%7C%20OpenAI-purple)
![Status](https://img.shields.io/badge/Status-Production%20Ready-success)

</p>

---

# 🥗 What is EATSENCE.AI?

**EATSENCE.AI** is an intelligent nutrition ecosystem that transforms the way people understand food.

Instead of simply counting calories, Eatsence leverages **Artificial Intelligence**, **Computer Vision**, **Nutrition Science**, and **Personal Health Analytics** to create a personalized dietary companion capable of understanding an individual's lifestyle, health goals, and eating habits.

Whether you're trying to:

- Lose weight
- Gain muscle
- Control diabetes
- Improve gut health
- Track macros
- Build healthy habits
- Plan meals
- Understand food quality

EATSENCE.AI provides personalized insights instead of generic recommendations.

---

# 🚀 Vision

> Build the world's most intelligent AI Nutrition Assistant that understands every meal, every habit, and every health goal.

Our vision is to replace traditional calorie trackers with an AI that actually thinks, learns, and guides users toward sustainable healthy lifestyles.

---

# 🌍 Mission

- Democratize access to professional nutrition guidance.
- Make healthy eating effortless through AI.
- Help millions reduce lifestyle diseases.
- Deliver personalized food intelligence in seconds.
- Build a future where everyone has an AI dietician.

---

# ✨ Key Features

## 🤖 AI Nutrition Coach

An intelligent assistant available 24/7.

It can:

- Answer nutrition questions
- Suggest healthier alternatives
- Explain food ingredients
- Recommend meals
- Generate grocery lists
- Track nutritional progress
- Create weekly diet plans
- Explain scientific nutrition concepts

---

## 📷 AI Food Recognition

Upload a food image and the AI automatically detects:

- Food name
- Ingredients
- Serving size
- Calories
- Protein
- Fat
- Carbohydrates
- Fiber
- Vitamins
- Minerals

Powered by modern Computer Vision models.

---

## 🍽 Smart Meal Planner

Generate meal plans based on:

- Age
- Gender
- Weight
- Height
- Activity level
- Fitness goals
- Medical conditions
- Food allergies
- Dietary preferences
- Budget
- Cuisine

Supports:

- Indian
- Mediterranean
- Keto
- Vegan
- Vegetarian
- Jain
- Paleo
- High Protein
- Low Carb
- DASH
- Gluten-Free

---

## 📊 Nutrition Dashboard

Track:

- Calories
- Macros
- Water intake
- Fiber
- Sugar
- Sodium
- Protein
- Weight
- BMI
- Body Fat %
- Weekly trends
- Monthly reports

Interactive charts make health tracking simple.

---

## 🎯 Goal Tracking

Supports:

- Weight Loss
- Muscle Gain
- Body Recomposition
- Fat Loss
- Diabetes Management
- PCOS Nutrition
- Pregnancy Nutrition
- Child Nutrition
- Senior Nutrition
- Heart Health

---

## 🧬 Personalized Recommendations

AI learns from:

- Eating habits
- Meal timings
- Favorite foods
- Activity patterns
- Sleep quality
- Health records
- Progress history

Every recommendation becomes smarter over time.

---

## 📈 Progress Analytics

Visual reports include:

- Weekly nutrition score
- Monthly calorie balance
- Protein consistency
- Water intake trends
- Healthy eating score
- Diet adherence
- Goal completion rate

---

## 🛒 Smart Grocery Generator

Automatically creates shopping lists based on:

- Meal plans
- Family members
- Budget
- Pantry inventory
- Expiring ingredients

---

## ⏰ Meal Reminders

Smart notifications for:

- Breakfast
- Lunch
- Dinner
- Snacks
- Water
- Supplements
- Workout nutrition

---

## 💊 Supplement Advisor

Suggests:

- Protein powders
- Vitamins
- Minerals
- Omega-3
- Electrolytes

> *Recommendations are educational and should not replace professional medical advice.*

---

## 🥼 Health Integration

Future integrations include:

- Apple Health
- Google Fit
- Fitbit
- Garmin
- Samsung Health
- WHOOP
- Oura Ring

---

## 🧠 AI Habit Analysis

Tracks:

- Late-night eating
- Sugar consumption
- Junk food frequency
- Meal skipping
- Water habits
- Protein deficiency
- Fiber intake

Provides actionable improvements.

---

# 🏗 Architecture

```
                    User
                      │
                      ▼
            Next.js Frontend
                      │
        ┌─────────────┴─────────────┐
        ▼                           ▼
 Authentication               AI Services
 Clerk/Auth.js          OpenAI • Gemini • Ollama
        │                           │
        └─────────────┬─────────────┘
                      ▼
                API Layer
                      │
        ┌─────────────┼─────────────┐
        ▼             ▼             ▼
 PostgreSQL      Redis Cache    File Storage
        │
        ▼
 Nutrition Database
        │
        ▼
 Analytics Engine
```

---

# 🛠 Tech Stack

## Frontend

- Next.js 15
- React 19
- TypeScript
- TailwindCSS
- Framer Motion
- Shadcn UI
- React Hook Form
- Zod

---

## Backend

- Node.js
- Next.js API Routes
- Prisma ORM
- PostgreSQL
- Redis
- REST API

---

## AI Stack

- OpenAI GPT
- Google Gemini
- Ollama (Local AI)
- Computer Vision Models
- OCR Engine
- Nutrition Knowledge Graph

---

## Authentication

- Clerk
- NextAuth
- Google OAuth
- Apple Login

---

## Cloud

- Vercel
- Docker
- GitHub Actions
- Cloudflare
- AWS S3

---

# 📂 Project Structure

```
eatsence-ai/
│
├── app/
├── components/
├── features/
│   ├── ai-chat/
│   ├── meal-planner/
│   ├── food-scanner/
│   ├── dashboard/
│   ├── analytics/
│   └── grocery/
│
├── hooks/
├── lib/
├── prisma/
├── public/
├── styles/
├── types/
├── utils/
├── api/
├── middleware/
└── docs/
```

---

# ⚡ Performance

- ⚡ Server Components
- ⚡ Edge Runtime
- ⚡ Image Optimization
- ⚡ Lazy Loading
- ⚡ AI Response Streaming
- ⚡ Cached Nutrition Database
- ⚡ Optimized API Calls

---

# 🔒 Security

- JWT Authentication
- OAuth 2.0
- Secure Cookies
- API Rate Limiting
- SQL Injection Protection
- XSS Protection
- CSRF Protection
- Data Encryption
- HIPAA-inspired Privacy Practices
- GDPR Ready

---

# 📱 Responsive Design

Optimized for:

- Desktop
- Tablet
- Mobile
- Progressive Web App (PWA)

---

# 🌟 Future Roadmap

### Phase 1

- AI Nutrition Chat
- Food Scanner
- Dashboard
- Meal Planner
- User Authentication

### Phase 2

- Voice Nutrition Coach
- Barcode Scanner
- Grocery Automation
- Health Device Sync

### Phase 3

- AI Dietician
- Restaurant Meal Analysis
- Family Accounts
- Corporate Wellness

### Phase 4

- AI Chef
- Smart Kitchen Integration
- Wearable AI
- Predictive Health Analytics

---

# 🎯 Target Users

- Fitness Enthusiasts
- Athletes
- Busy Professionals
- Students
- Families
- Dieticians
- Nutritionists
- Doctors
- Corporate Wellness Programs
- Healthcare Organizations

---

# 📊 Use Cases

- Daily Nutrition Tracking
- Weight Loss Planning
- Muscle Gain Programs
- Clinical Nutrition
- Diabetes Management
- Meal Preparation
- Grocery Planning
- Healthy Habit Formation
- Food Education

---

# 🤝 Contributing

We welcome contributions from developers, designers, nutrition experts, and AI researchers.

```bash
# Fork the repository

# Clone your fork
git clone https://github.com/yourusername/eatsence-ai.git

# Install dependencies
pnpm install

# Start development
pnpm dev

# Run tests
pnpm test
```

---

# 📦 Installation

```bash
# Clone repository
git clone https://github.com/yourusername/eatsence-ai.git

# Enter project
cd eatsence-ai

# Install dependencies
pnpm install

# Configure environment
cp .env.example .env.local

# Start development server
pnpm dev
```

Open:

```
http://localhost:3000
```

---

# 🔧 Environment Variables

```env
DATABASE_URL=
OPENAI_API_KEY=
GEMINI_API_KEY=
NEXTAUTH_SECRET=
NEXTAUTH_URL=
REDIS_URL=
CLERK_SECRET_KEY=
CLERK_PUBLISHABLE_KEY=
AWS_ACCESS_KEY=
AWS_SECRET_KEY=
S3_BUCKET=
```

---

# 🧪 Testing

```bash
pnpm test
pnpm lint
pnpm typecheck
pnpm build
```

---

# 📸 Screenshots

```
Coming Soon
```

---

# 💡 Why EATSENCE.AI?

Unlike traditional calorie trackers, EATSENCE.AI combines:

- Artificial Intelligence
- Personalized Nutrition
- Real-Time Analytics
- Computer Vision
- Behavioral Science
- Health Intelligence

to deliver a truly intelligent nutrition experience.

---

# 📜 License

Licensed under the **MIT License**.

---

# 👨‍💻 Author

**Avinash Hugar**

AI Developer • Full Stack Developer • Founder

---

# ⭐ Support

If you find this project useful:

- ⭐ Star the repository
- 🍴 Fork the project
- 🐛 Report issues
- 💡 Suggest features
- 🤝 Contribute to development

---

# 💚 "Eat Smarter. Live Better. Powered by AI."

**EATSENCE.AI** is more than a nutrition tracker—it's an intelligent health companion designed to help people make informed food choices, build sustainable habits, and achieve long-term wellness through the power of AI.
