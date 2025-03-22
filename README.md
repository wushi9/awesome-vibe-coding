🌍 *[English](README.md) ∙ [简体中文](README.zh.md)*

# Vibe Coding

[![Visit Vibe Coding](https://img.shields.io/badge/Visit-Vibe%20Coding-blue)](https://vibecodingcase.com/)

## About

Vibe Coding is an AI-Assisted Programming Cases & Tools Directory platform. We help developers discover and share the latest AI-assisted programming tools, cases, and best practices.

🌐 **[Visit Vibe Coding](https://vibecodingcase.com/)**

## Features

- 🔍 **Comprehensive Directory**: Curated collection of AI programming tools and cases
- 🎯 **Categorized Content**: Well-organized categories for easy navigation
- 📱 **Responsive Design**: Optimized for all devices and screen sizes
- 🌙 **Dark Mode**: Built-in dark mode support
- 🌍 **Internationalization**: Multi-language support (English, Chinese)
- 🔄 **Regular Updates**: Constantly updated with new tools and cases

## Technology Stack

- ⚛️ **Framework**: Next.js
- 🎨 **Styling**: Tailwind CSS
- 🌐 **i18n**: next-intl
- 🎭 **Theming**: next-themes
- 📊 **Analytics**: Google Analytics
- 🖼️ **Image Optimization**: Next.js Image
- 🔒 **Security**: Built-in XSS protection and security headers

## Categories

- AI Coding Assistant
- Game Cases
- Game Engines
- Analytics
- Database
- Deployment
- Domain
- Frontend Frameworks
- Insights
- Promotion
- SEO
- Storage
- Template
- UI
- Version Control
- Utils

## Development

### Prerequisites

- Node.js (v18 or higher)
- pnpm (recommended) or npm

### Installation

1. Clone the repository:
```bash
git clone [repository-url]
cd vibecodingcase
```

2. Install dependencies:
```bash
pnpm install
```

3. Create a `.env.local` file:
```bash
NEXT_PUBLIC_GA_ID=your-ga-id
```

4. Start the development server:
```bash
pnpm dev
```

### Build

```bash
pnpm build
```

### Production

```bash
pnpm start
```

## Contributing

We welcome contributions! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Built with [Next.js](https://nextjs.org/)
- Styled with [Tailwind CSS](https://tailwindcss.com/)
- Hosted on [Vercel](https://vercel.com/)

## Contact

For support or inquiries, please email us at: iamcoreychiu+devtoolsetsupport@gmail.com

## Awards & Recognition

[![ImgLab Awards](https://imglab.dev/badge-logo.svg)](https://imglab.dev/en/s/vibecodingcase_com)
[![Uneed Badge](https://www.uneed.best/EMBED3.png)](https://www.uneed.best/tool/vibe-coding-directory)

---

Made with ❤️ by the Vibe Coding Team

## 🏗️ Project Structure

```
vibecodingcase/
├── src/
│   ├── app/                 # App router pages
│   ├── components/         # React components
│   ├── lib/               # Utility functions
│   └── styles/            # Global styles
├── public/               # Static assets
├── data/                # Content data
│   ├── md/             # Markdown articles
│   └── json/           # Tool listings
│       ├── en/        # English content
│       └── zh/        # Chinese content
└── messages/          # i18n translation files
```

## 🛠️ Built With

- [Next.js 14](https://nextjs.org/) - React framework
- [Tailwind CSS](https://tailwindcss.com/) - CSS framework
- [next-intl](https://next-intl-docs.vercel.app/) - Internationalization
- [next-themes](https://github.com/pacocoursey/next-themes) - Theme management
- [Radix UI](https://www.radix-ui.com/) - UI components
- [Lucide Icons](https://lucide.dev/) - Icon set

## 📝 Content Management

### Adding New Tools

1. Navigate to `data/json/[locale]/tools/`
2. Choose or create appropriate category file
3. Add tool entry following the template:

```json
{
  "name": "Tool Name",
  "description": "Tool description",
  "url": "https://tool-url.com",
  "tags": ["tag1", "tag2"],
  "add_date": "YYYY-MM-DD"
}
```

### Adding New Articles

1. Create markdown file in `data/md/`
2. Add frontmatter:

```markdown
---
title: 'Article Title'
date: 'YYYY-MM-DD'
description: 'Article description'
---

Article content...
```

## 🌍 Internationalization

- Add translations in `messages/[locale].json`
- Support new language:
  1. Add locale in `middleware.ts`
  2. Create translation file
  3. Add content files in `data/json/[locale]/`

## 🤝 Contributing

1. Fork the repository
2. Create feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add AmazingFeature'`)
4. Push to branch (`git push origin feature/AmazingFeature`)
5. Open Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📞 Contact

- Website: [vibecodingcase.com](https://vibecodingcase.com)
- Email: support@vibecodingcase.com

## 🙏 Acknowledgments

- [Andrej Karpathy](https://twitter.com/karpathy) for Vibe Coding concept
- All contributors and tool providers

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=iamcorey/devtoolset&type=Date)](https://star-history.com/#iamcorey/devtoolset&Date)
