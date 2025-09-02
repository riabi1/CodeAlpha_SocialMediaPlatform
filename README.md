
# 🌐 Socially – Full-Stack Social Media Platform


A modern social media application built with Next.js, React, and PostgreSQL. Socially enables users to share posts, interact with others, and explore personalized content—all within a sleek, responsive interface.
> ✨ Built for creators, powered by modern tools, and designed for scalability.
<p align="center">
  <img src="https://media2.giphy.com/media/v1.Y2lkPTc5MGI3NjExcXNnd3Q2cmF5MDlqMmVkNWxlNWZjNzdsd3JxdjJsb3B0MnY5bTlrZiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/FU4hwVczzPvnRgowCP/giphy.gif" alt="App Demo" />
</p>

<p align="center"> <!-- Core Tech --> <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white" /> <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" /> <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" /> <img src="https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white" /> <img src="https://img.shields.io/badge/Neon-00BFFF?style=for-the-badge&logo=postgresql&logoColor=white" /> <img src="https://img.shields.io/badge/Clerk-3B82F6?style=for-the-badge&logo=clerk&logoColor=white" /> <img src="https://img.shields.io/badge/UploadThing-10B981?style=for-the-badge&logo=data&logoColor=white" /> <img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white" /> </p>

## 🚀 Features

- 📝 Create and share posts with images or videos


- ❤️ Like, comment, and engage with other users

- 🔍 Explore trending content and user profiles
  
- 👤 Authenticated user experience via Clerk


- 📦 Upload media files securely with UploadThing


- 🧠 Serverless PostgreSQL database powered by Neon

- 🎨 Responsive UI built with Tailwind CSS
  
- ⚙️ Backend logic managed via Prisma ORM and Next.js API routes
  
- 🛡️ Protected routes and middleware for secure access
  
- 🚀 Deployed seamlessly on Vercel
## 🧱 Project Architecture

```txt
📦 Socially/
├── prisma/                    # Prisma schema and migrations
│   ├── schema.prisma
│   └── migrations/
├── public/                    # Static assets (favicon, screenshots)
│   ├── avatar.png
│   └── screenshot-for-readme.png
├── src/
│   ├── actions/               # Server actions (posts, profiles, users)
│   ├── app/                   # App Router structure
│   │   ├── api/               # API routes (tasks, uploadthing)
│   │   ├── fonts/             # Custom fonts
│   │   ├── notifications/     # Notification page
│   │   ├── profile/           # Dynamic profile pages
│   │   ├── tasks/             # Task page
│   │   ├── layout.tsx         # Global layout
│   │   └── page.tsx           # Home page
│   ├── components/            # UI components and layout
│   │   ├── ui/                # ShadCN-based UI elements
│   │   ├── CreatePost.tsx
│   │   ├── PostCard.tsx
│   │   ├── Sidebar.tsx
│   │   └── Navbar.tsx
│   ├── lib/                   # Utility functions and Prisma client
│   └── middleware.ts          # Route protection
├── .env                       # Environment variables
├── next.config.mjs            # Next.js configuration
├── tailwind.config.ts         # Tailwind setup
└── package.json               # Project metadata
└── 📖 README.md               # Project documentation
```


## 📦 Installation

```bash
# Clone the repository
git clone https://github.com/riabi1/CodeAlpha_SocialMediaPlatform.git

# Install dependencies
npm install

# Generate Prisma client
npx prisma generate

# Apply migrations
npx prisma migrate dev

# Run the development server
npm run dev

```

## 🔍 Future Enhancements
### 🧠 AI-powered feed personalization

### 🧪 End-to-end testing with Cypress
  
### 📊 Analytics dashboard for user engagement


## 🌐 Live View
https://code-alpha-social-media-platform-7y.vercel.app/

## 📬 Contact

Created with care by **Mohamed Ali Riabi**  
📧 [riabi.mar@gmail.com](mailto:riabi.mar@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/mohamedaliriabi/) | [Portfolio](https://flowcv.me/mohamed-ali-riabi)
