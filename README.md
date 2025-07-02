# ✨ SaaS Code Editor – Powered by Next.js 15

An advanced SaaS-based online code editor with multi-language support, execution history, VSCode themes, smart outputs, webhook support, and a beautiful developer-focused UI.

---

## 🚀 Highlights

- ⚙️ **Tech Stack**: Next.js 15 + Convex + Clerk + TypeScript
- 💻 **Online IDE**: Supports 10 programming languages
- 🎨 **Theme Customization**: 5 beautiful VSCode-like themes
- ✨ **Smart Output**: Displays success & error results clearly
- 💎 **Pricing**: Supports Free and Pro plans
- 🤝 **Code Sharing**: Share your code with the community
- 🔍 **Filtering & Search**: Find code fast with advanced tools
- 👤 **User Profiles**: Track your own code execution history
- 📊 **Stats Dashboard**: Visual insights into usage & history
- 🔠 **Font Controls**: Choose your preferred font size
- 🔗 **Webhook Support**: Easily connect with external services
- 🌐 **Professional Deployment**: Ready for production with guided walkthrough

---

## 🛠️ Tech Stack

| Layer        | Technologies                        |
|--------------|-------------------------------------|
| Frontend     | Next.js 15, TypeScript              |
| Auth         | Clerk                               |
| Backend      | Convex                              |
| Styling      | TailwindCSS, VSCode Themes          |
| Payments     | Lemon Squeezy (Pro Plan Integration)|
| Deployment   | Vercel, Convex Dashboard            |

---

## 🧪 .env Setup

### 🔑 Local `.env` file

```env
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key
CONVEX_DEPLOYMENT=your_convex_deployment_id
NEXT_PUBLIC_CONVEX_URL=your_public_convex_url
```

### Add these env to Convex Dashboard

```env
CLERK_WEBHOOK_SECRET=your_clerk_webhook_secret
LEMON_SQUEEZY_WEBHOOK_SECRET=your_lemon_squeezy_webhook_secret
```

---

# ▶️ Run the App Locally
- npm install
- npm run dev
