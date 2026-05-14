# 🚀 Streamline — Landing Page

A clean, modern **product landing page** built with **Next.js 15**, **React 19**, and **TypeScript**. Styled with Tailwind CSS and shadcn/ui, it's fully responsive, accessible, and ready to deploy.

---

## 📁 Project Structure

```
streamline-landing-page/
├── app/               # Next.js App Router pages & layouts
├── components/        # Reusable UI sections & components
├── hooks/             # Custom React hooks
├── lib/               # Utility functions & helpers
├── public/            # Static assets (images, icons, fonts)
├── styles/            # Global CSS styles
├── components.json    # shadcn/ui component config
├── next.config.mjs    # Next.js configuration
├── tailwind.config.js # Tailwind CSS configuration
├── tsconfig.json      # TypeScript configuration
└── package.json       # Project metadata & dependencies
```

---

## 🛠️ Tech Stack

| Category        | Technology                            |
|-----------------|---------------------------------------|
| Framework       | Next.js 15.1.0                        |
| Language        | TypeScript 5                          |
| UI Library      | React 19                              |
| Styling         | Tailwind CSS 3 + tailwindcss-animate  |
| Component Kit   | shadcn/ui (Radix UI primitives)       |
| Icons           | Lucide React                          |
| Theming         | next-themes (dark / light mode)       |
| Forms           | React Hook Form + Zod                 |
| Charts          | Recharts 2.15.0                       |
| Carousel        | Embla Carousel React                  |
| Notifications   | Sonner (toast)                        |
| Date Utilities  | date-fns                              |
| Package Manager | pnpm                                  |

---

## ⚙️ Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18 or higher)
- [pnpm](https://pnpm.io/) — install via `npm install -g pnpm`

### Installation

```bash
# Clone the repository
git clone https://github.com/pranjalisr/streamline-landing-page.git
cd streamline-landing-page

# Install dependencies
pnpm install
```

### Running the Dev Server

```bash
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

---

## 📜 Available Scripts

| Command        | Description                          |
|----------------|--------------------------------------|
| `pnpm dev`     | Start the development server         |
| `pnpm build`   | Build the app for production         |
| `pnpm start`   | Start the production server          |
| `pnpm lint`    | Run ESLint across the project        |

---

## ✨ Features

- 🎨 **Modern design** — clean, polished landing page layout
- 🌙 **Dark / Light mode** — powered by `next-themes`
- 📱 **Fully responsive** — mobile-first, works on all screen sizes
- ♿ **Accessible** — built on Radix UI accessible primitives
- 🎠 **Carousel support** — via Embla Carousel React
- 🔔 **Toast notifications** — via Sonner
- ⚡ **App Router** — Next.js 15 file-based routing
- 🧩 **Component-driven** — modular shadcn/ui components throughout

---

## 📦 Key Dependencies

| Package                   | Purpose                          |
|---------------------------|----------------------------------|
| `next`                    | React framework (App Router)     |
| `react` / `react-dom`     | UI rendering                     |
| `tailwindcss`             | Utility-first CSS                |
| `@radix-ui/*`             | Accessible UI primitives         |
| `lucide-react`            | Icon library                     |
| `next-themes`             | Dark/light theme switching       |
| `react-hook-form` + `zod` | Form handling & validation       |
| `recharts`                | Data visualization               |
| `embla-carousel-react`    | Carousel / image slider          |
| `sonner`                  | Toast notifications              |
| `clsx` + `tailwind-merge` | Conditional class utilities      |
| `cmdk`                    | Command palette                  |
| `vaul`                    | Drawer / bottom sheet component  |
| `date-fns`                | Date formatting utilities        |

---

## 🚢 Deployment

This project is optimized for deployment on [Vercel](https://vercel.com/):

```bash
# Build for production
pnpm build
```

Or click below to deploy instantly:

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/pranjalisr/streamline-landing-page)

---

## 👩‍💻 Author

**Pranjali** — [@pranjalisr](https://github.com/pranjalisr)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
