# Main Card# Astro Starter Kit: Basics



A modern personal portfolio card built with Astro, showcasing projects and technical skills in a clean, responsive design.```sh

npm create astro@latest -- --template basics

## ✨ Features```



- **Portfolio Showcase**: Display your key projects with descriptions and links> 🧑‍🚀 **Seasoned astronaut?** Delete this file. Have fun!

- **Tech Stack Display**: Visual representation of your technical skills with icons

- **Responsive Design**: Built with Tailwind CSS and DaisyUI for modern styling## 🚀 Project Structure

- **Fast Performance**: Powered by Astro for optimal loading speeds

- **Type Safety**: Written in TypeScript for better development experienceInside of your Astro project, you'll see the following folders and files:



## 🚀 Project Structure```text

/

```text├── public/

/│   └── favicon.svg

├── public/├── src

│   └── teck-icons/          # Technology stack icons│   ├── assets

├── src/│   │   └── astro.svg

│   ├── components/│   ├── components

│   │   └── Card.astro       # Main card component│   │   └── Welcome.astro

│   ├── layouts/│   ├── layouts

│   │   └── Layout.astro     # Base layout template│   │   └── Layout.astro

│   └── pages/│   └── pages

│       └── index.astro      # Homepage│       └── index.astro

├── astro.config.mjs└── package.json

├── package.json```

├── tsconfig.json

└── global.cssTo learn more about the folder structure of an Astro project, refer to [our guide on project structure](https://docs.astro.build/en/basics/project-structure/).

```

## 🧞 Commands

## 🛠️ Tech Stack

All commands are run from the root of the project, from a terminal:

- **Framework**: [Astro](https://astro.build)

- **Styling**: [Tailwind CSS](https://tailwindcss.com) + [DaisyUI](https://daisyui.com)| Command                   | Action                                           |

- **Language**: TypeScript| :------------------------ | :----------------------------------------------- |

- **Icons**: Custom SVG tech stack icons| `npm install`             | Installs dependencies                            |

- **Deployment**: Ready for static hosting| `npm run dev`             | Starts local dev server at `localhost:4321`      |

| `npm run build`           | Build your production site to `./dist/`          |

## 🚀 Getting Started| `npm run preview`         | Preview your build locally, before deploying     |

| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |

### Prerequisites| `npm run astro -- --help` | Get help using the Astro CLI                     |



- Node.js (v18 or higher)## 👀 Want to learn more?

- npm or yarn

Feel free to check [our documentation](https://docs.astro.build) or jump into our [Discord server](https://astro.build/chat).

### Installation

1. Clone the repository:
```bash
git clone <your-repo-url>
cd main-card
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open your browser and visit `http://localhost:4321`

## 🧞 Available Scripts

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`     |
| `npm run build`           | Build your production site to `./dist/`         |
| `npm run preview`         | Preview your build locally, before deploying    |
| `npm run format`          | Format code with Prettier                       |
| `npm run format:check`    | Check code formatting                           |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check`|

## 🎨 Customization

### Adding Projects

Edit the `cards` array in `src/components/Card.astro`:

```typescript
const cards: Card[] = [
  {
    title: "Your Project",
    description: "Project description",
    imageSrc: "/your-image.png",
    linkHref: "https://your-project-link.com",
  },
  // Add more projects...
];
```

### Adding Tech Stack Icons

1. Add your SVG icons to the `public/teck-icons/` directory
2. Update the `techStack` array in `src/components/Card.astro`:

```typescript
const techStack = [
  { name: "Technology Name", imageSrc: "/teck-icons/YourIcon.svg" },
  // Add more technologies...
];
```

## 📦 Deployment

This project generates static files and can be deployed to any static hosting service:

- **Netlify**: Connect your GitHub repo for automatic deployments
- **Vercel**: Import project and deploy with zero configuration
- **GitHub Pages**: Use GitHub Actions for automated deployment
- **Cloudflare Pages**: Connect repository for edge deployment

Build the project for production:

```bash
npm run build
```

The built files will be in the `dist/` directory.

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🔗 Links

- [Astro Documentation](https://docs.astro.build)
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)
- [DaisyUI Components](https://daisyui.com/components/)

---

Built with ❤️ using [Astro](https://astro.build)