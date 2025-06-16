# Notion Clone 🚀

A modern, feature-rich Notion clone built with Next.js 13, featuring real-time collaboration, authentication, and a beautiful UI.

![Notion Clone Preview](public/preview.png)

## ✨ Features

- 📝 Rich text editor with BlockNote
- 👥 Real-time collaboration
- 🔐 Secure authentication with Clerk
- 🎨 Beautiful UI with Tailwind CSS
- 🌙 Dark/Light mode support
- 📱 Fully responsive design
- 🚀 Real-time updates with Convex
- 📤 File uploads with EdgeStore
- 🎯 Modern React patterns and hooks

## 🛠️ Tech Stack

- **Framework:** [Next.js 13](https://nextjs.org/)
- **Authentication:** [Clerk](https://clerk.dev/)
- **Database:** [Convex](https://www.convex.dev/)
- **Styling:** [Tailwind CSS](https://tailwindcss.com/)
- **UI Components:** [Radix UI](https://www.radix-ui.com/)
- **State Management:** [Zustand](https://github.com/pmndrs/zustand)
- **Rich Text Editor:** [BlockNote](https://www.blocknote.dev/)
- **File Storage:** [EdgeStore](https://edgestore.dev/)
- **Form Validation:** [Zod](https://zod.dev/)

## 🚀 Getting Started

### Prerequisites

- Node.js 18+ 
- npm or yarn
- Convex account
- Clerk account
- EdgeStore account

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/notion-clone.git
cd notion-clone
```

2. Install dependencies:
```bash
npm install
# or
yarn install
```

3. Set up environment variables:
Create a `.env.local` file in the root directory and add the following:
```env
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/

NEXT_PUBLIC_CONVEX_URL=your_convex_url
NEXT_PUBLIC_EDGE_STORE_ACCESS_KEY=your_edgestore_access_key
NEXT_PUBLIC_EDGE_STORE_SECRET_KEY=your_edgestore_secret_key
```

4. Run the development server:
```bash
npm run dev
# or
yarn dev
```

5. Open [http://localhost:3000](http://localhost:3000) in your browser.

## 📁 Project Structure

```
notion-clone/
├── app/                 # Next.js app directory
├── components/         # Reusable UI components
├── convex/            # Convex backend functions
├── hooks/             # Custom React hooks
├── lib/               # Utility functions and configurations
├── public/            # Static assets
└── types/             # TypeScript type definitions
```

## 🎨 UI Components

The project uses a combination of custom components and Radix UI primitives for a consistent and accessible user interface. Key components include:

- Document editor
- Navigation sidebar
- User settings
- File upload interface
- Search functionality
- Command palette

## 🔒 Authentication

Authentication is handled by Clerk, providing:
- Email/password authentication
- Social login options
- Protected routes
- User management

## 💾 Database

Convex is used for the backend, providing:
- Real-time updates
- Document storage
- User data management
- Collaborative features

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📫 Contact

Your Name - [@yourtwitter](https://twitter.com/yourtwitter)

Project Link: [https://github.com/yourusername/notion-clone](https://github.com/yourusername/notion-clone)

---

Made with ❤️ by [Your Name]
