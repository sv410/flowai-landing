# FlowAI Landing Page

A modern, responsive landing page for FlowAI built with Next.js, TypeScript, and Tailwind CSS.

## 🚀 Features

- **Modern Design**: Clean and professional UI with smooth animations
- **Responsive**: Fully responsive design that works on all devices
- **Fast Performance**: Built with Next.js for optimal performance
- **TypeScript**: Type-safe development with TypeScript
- **Component Library**: Using Radix UI components with custom styling
- **Dark/Light Mode**: Theme switching support
- **Authentication Pages**: Login and signup page templates

## 🛠️ Tech Stack

- **Framework**: [Next.js 15](https://nextjs.org/)
- **Language**: [TypeScript](https://www.typescriptlang.org/)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/)
- **Components**: [Radix UI](https://www.radix-ui.com/)
- **Icons**: [Lucide React](https://lucide.dev/)
- **Package Manager**: [pnpm](https://pnpm.io/)

## 📦 Installation

1. Clone the repository:
```bash
git clone https://github.com/sv410/flowai-landing.git
cd flowai-landing
```

2. Install dependencies:
```bash
pnpm install
```

3. Run the development server:
```bash
pnpm dev
```

4. Open [http://localhost:3000](http://localhost:3000) in your browser.

## 🚀 Deployment

### Deploy to Vercel (Recommended)

1. Push your code to GitHub
2. Visit [Vercel](https://vercel.com)
3. Import your GitHub repository
4. Deploy with one click!

### Deploy to Netlify

1. Push your code to GitHub
2. Visit [Netlify](https://netlify.com)
3. Connect your GitHub repository
4. Set build command: `pnpm build`
5. Set publish directory: `.next`
6. Deploy!

## 📁 Project Structure

```
flowai-landing/
├── app/                    # Next.js app directory
│   ├── globals.css        # Global styles
│   ├── layout.tsx         # Root layout
│   ├── page.tsx           # Home page
│   ├── login/             # Login page
│   └── signup/            # Signup page
├── components/            # React components
│   ├── flowai/           # FlowAI specific components
│   │   ├── hero.tsx      # Hero section
│   │   ├── navbar.tsx    # Navigation bar
│   │   └── sections/     # Page sections
│   └── ui/               # Reusable UI components
├── hooks/                # Custom React hooks
├── lib/                  # Utility functions
├── public/               # Static assets
└── styles/               # Additional styles
```

## 🎨 Customization

### Colors
Edit the color palette in `tailwind.config.js` and `app/globals.css`.

### Components
All UI components are in the `components/ui/` directory and can be customized.

### Content
Main page content is in `app/page.tsx` and component files in `components/flowai/`.

## 📱 Pages

- **Home**: Main landing page with hero, features, and pricing sections
- **Login**: User authentication page
- **Signup**: User registration page

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/amazing-feature`
3. Commit your changes: `git commit -m 'Add amazing feature'`
4. Push to the branch: `git push origin feature/amazing-feature`
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**sv410** - [GitHub Profile](https://github.com/sv410)

## 🔗 Links

- **Repository**: https://github.com/sv410/flowai-landing
- **Live Demo**: [Coming Soon]

---

Built with ❤️ using Next.js and TypeScript