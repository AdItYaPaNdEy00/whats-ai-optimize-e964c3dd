🚀 WhatsApp Campaign Optimizer

A React-based dashboard for managing and analyzing WhatsApp marketing campaigns with A/B testing support.

📌 Overview

The WhatsApp Campaign Optimizer is a frontend application designed to help marketers:

Manage campaign workflows
Test multiple message variants
Analyze campaign performance through a visual dashboard

The application focuses on providing a clean interface for campaign tracking, A/B testing, and performance analysis.

✨ Features
📢 Campaign Management
Create and organize marketing campaigns
Manage multiple message variants
Track campaign progress
🧪 A/B Testing Interface
Compare different message variations
Visual comparison of performance
Helps identify better-performing messages
📊 Analytics Dashboard
View campaign insights
Performance metrics visualization
Clean and intuitive UI
👥 Customer Management
Maintain customer data
Organize users for campaigns
💬 Message Preview UI
Preview messages before sending
WhatsApp-style interface simulation
⚖️ Compliance View
Monitor campaign standards
Ensure structured communication
🛠️ Tech Stack
Frontend
React (TypeScript)
Vite
Tailwind CSS
Component-based architecture
Tooling
ESLint
PostCSS
whatsapp-campaign-optimizer/
│
├── public/
│   └── favicon.ico / assets
│
├── src/
│   ├── assets/                # Static assets (images, icons)
│   │
│   ├── components/            # Reusable UI components
│   │   ├── Dashboard.tsx
│   │   ├── CampaignManager.tsx
│   │   ├── ABTesting.tsx
│   │   ├── Analytics.tsx
│   │   ├── CustomerManagement.tsx
│   │   ├── ChatPreview.tsx
│   │   ├── Compliance.tsx
│   │   └── ui/                # Prebuilt UI components (buttons, cards, etc.)
│   │
│   ├── pages/                 # Page-level components (routing level)
│   │   ├── Index.tsx          # Main entry page (dashboard wrapper)
│   │   └── NotFound.tsx       # 404 page
│   │
│   ├── hooks/                 # Custom React hooks
│   │   └── use-toast.ts       # Toast notification logic
│   │
│   ├── lib/                   # Utility libraries/config
│   │   └── utils.ts           # Helper functions (classNames, etc.)
│   │
│   ├── App.tsx                # Root component (routing + layout)
│   ├── main.tsx               # Entry point (React DOM render)
│   ├── index.css              # Global styles (Tailwind)
│   │
│   └── vite-env.d.ts          # TypeScript environment types
│
├── index.html                # Root HTML file
├── package.json              # Dependencies & scripts
├── tailwind.config.ts        # Tailwind configuration
├── postcss.config.js         # PostCSS config
├── vite.config.ts            # Vite config
├── tsconfig.json             # TypeScript config
├── tsconfig.node.json        # Node-specific TS config
└── eslint.config.js          # Linting rules
⚙️ Installation & Setup
1. Clone the repository
git clone https://github.com/YOUR_USERNAME/whatsapp-campaign-optimizer.git
cd whatsapp-campaign-optimizer
2. Install dependencies
npm install
3. Run the development server
npm run dev
4. Open in browser
http://localhost:5173/
🧠 Core Concept

This project is based on improving marketing effectiveness through:

A/B testing
Campaign performance tracking
Data-driven decision making

It provides a structured way to evaluate which messaging strategies perform better.

🚀 Future Enhancements
Backend integration (FastAPI / Node.js)
AI-based optimization (Multi-Armed Bandits)
Database integration (MongoDB)
Authentication system
Real-time analytics
🤝 Contribution

Contributions are welcome.
Feel free to fork and improve the project.

📜 License

MIT License

