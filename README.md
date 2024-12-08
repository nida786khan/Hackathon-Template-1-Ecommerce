# Hackathon-Template-1-Ecommcerce-web
![hackathon 1](https://github.com/user-attachments/assets/c3b0fe92-524d-4fe1-b8e8-f2eb83007c9f)





UIUX hackathon - Nextjs Design Jam 2024 Announcement

https://github.com/panaverse/learn-nextjs/blob/main/HACKATHONS/Nextjs_Design_Jam_2024/Nextjs_Design_Jam_2024.pdf

Start Time: Sunday, December 8th, 01:45 AM (midnight, between Saturday and Sunday)
Duration: 24 hours
Objective: Create a pixel-perfect, responsive UI based on your assigned Figma template. 

Submission Guidelines
1. Deadline: Submit your project within the allocated time (Monday, December 9th, 01:44 AM, GMT + 5).
2. Extended Deadline (-24 points): If you encounter issues, request an extension before the end of the hackathon for an additional 24 hours (until December 10th Tuesday, 01:44 AM).
3. Submission Format: Use the link https://forms.gle/vqEsQPaW8btsvnTC7 to submit:
- Source code repository lin…

# Shopco

Shopco is an open-source project that converts a Figma design of an e-commerce website into a fully responsive front-end application. It utilizes **Next.js 14 App Router**, **TypeScript**, **Tailwind CSS**, **Redux**, **Framer Motion**, and **ShadCN UI** to deliver a modern, scalable, and optimized solution based on industry standards.

## Table of Contents

- [Shopco](#shopco)
  - [Table of Contents](#table-of-contents)
  - [Overview](#overview)
  - [Features](#features)
  - [Technologies](#technologies)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Project Structure](#project-structure)
  - [Contributing](#contributing)
 


## Overview

Shopco bridges the gap between design and development by converting Figma designs into production-ready code. The project follows best practices for **SEO**, **performance optimization**, and **accessibility**, making it a perfect foundation for developers looking to create scalable and maintainable e-commerce front-ends.


<!-- [![Shopco Screenshot](https://github.com/mohammadoftadeh/repo-assets/blob/main/shopco-cover.png?raw=true)](https://next-ecommerce-shopco.vercel.app/) -->

## Features

- **Next.js 14**: Server-side rendering (SSR), Static Site Generation (SSG), optimized routing, and API integrations.
- **TypeScript**: Strongly typed code for better error detection and maintainability.
- **Tailwind CSS**: Utility-first CSS framework for rapid UI development.
- **Redux**: State management for managing the shopping cart and other global states.
- **Framer Motion**: Smooth animations and transitions for an enhanced user experience.
- **ShadCN UI**: Beautifully styled, accessible, and customizable UI components.
- **Fully Responsive**: Mobile-first design ensuring the layout adapts across devices.
- **Performance Optimized**: Best practices followed for fast loading and interaction.
- **Accessible**: Built with accessibility standards to provide an inclusive experience.

## Technologies

- **Next.js 14** - A popular React framework with built-in SSR and optimization.
- **TypeScript** - A superset of JavaScript for strong typing and code consistency.
- **Tailwind CSS** - A utility-first CSS framework for fast, responsive design.
- **Redux** - A state management library used for the shopping cart and global app state.
- **Framer Motion** - A library for animations and interactions in React.
- **ShadCN UI** - A collection of beautiful, accessible, and customizable UI components.
- **Figma** - The design tool used as the source of the project’s layout. The [Figma file]https://www.figma.com/design/YUR8kary0dXj39RSTmNolR/Recommended by Sir Ali Aftab Sheikh And Sir Fahad Khan.

## Installation

To get started with Shopco locally, follow these steps:

1. **Install dependencies:**

   ```bash
   npm install
   ```

   ```bash
   yarn install
   ```

2. **Run the development server:**

   ```bash
   npm run dev
   ```

   ```bash
   yarn dev
   ```

3. **Open in your browser:**
   Navigate to [http://localhost:3000](http://localhost:3000) to view the app.

## Usage

- To explore or modify the code, navigate through the `components`, `features`, and `app` directories.
- The shopping cart logic is managed using **Redux**. You can find the store configuration and cart actions in the `src/lib/features` directory.
- **ShadCN UI** components are used across the app. They can be customized in the `src/components/ui` directory.
- You can easily modify and extend the project to suit your needs, whether for personal use or professional projects.

## Project Structure

```bash
Shopco/
│
├── public/                # Static assets
├── src/
│   ├── app/               # Next.js App Router
│   ├── components/        # Reusable components (including ShadCN UI components)
│   └── lib/
│       ├── features/      # The Redux logics for features (e.g., shopping cart)
│       ├── hooks/         # Custom React hooks
│       ├── store.ts       # Redux store
│       ├── utils.ts       # Utility functions
│   ├── styles/            # Tailwind CSS styles (global, utilities and fonts)
│   ├── types/             # TypeScript types
│
├── components.json         # ShadCN UI configuration
├── next.config.mjs         # Next.js configuration
├── package.json            # Node.js dependencies and scripts
├── postcss.config.mjs      # Post CSS configuration
└── README.md               # Project documentation
├── tailwind.config.js      # Tailwind CSS configuration
├── tsconfig.json           # TypeScript configuration
```

## Contributing

Contributions are welcome! If you'd like to contribute, Please follow these steps to contribute to Shopco:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature-name`).
3. Make your changes.
4. Push to the branch (`git push origin feature/your-feature-name`).
5. Open a pull request.