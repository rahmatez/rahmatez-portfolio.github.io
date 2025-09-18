# Portfolio Website - Rahmatez

A modern, responsive portfolio website built with [Static Framework](https://static.devdojo.com) and styled with Tailwind CSS. This portfolio showcases my projects, experiences, and blog posts in a clean, professional design.

## 🌟 Features

- **Responsive Design** - Looks great on all devices
- **Modern UI** - Clean and professional layout
- **Blog System** - Write and publish blog posts
- **Project Showcase** - Display your portfolio projects
- **Experience Timeline** - Show your work experience
- **Contact Information** - Easy ways to get in touch
- **Fast Loading** - Optimized static site generation
- **SEO Friendly** - Built with best practices

## 🚀 Live Demo

- **GitHub Pages**: [https://rahmatez-portfolio.github.io/](https://rahmatez-portfolio.github.io/)
- **Vercel**: [Coming Soon]

## 🛠️ Built With

- [Static Framework](https://static.devdojo.com) - Static site generator
- [Tailwind CSS](https://tailwindcss.com) - Utility-first CSS framework
- [Tailwind Typography](https://tailwindcss.com/docs/typography-plugin) - Beautiful typographic defaults

## 📁 Project Structure

```
├── assets/                 # Static assets
│   ├── css/               
│   │   └── main.css       # Compiled Tailwind CSS
│   ├── images/            # Images and photos
│   └── js/                # JavaScript files
├── collections/           # Data collections
│   ├── experiences.json   # Work experience data
│   ├── projects.json      # Portfolio projects
│   └── content/
│       └── post.json      # Blog posts metadata
├── content/               # Content files
│   └── post/              # Blog post markdown files
├── includes/              # Reusable HTML components
├── layouts/               # Page layouts
├── pages/                 # Main pages
│   ├── index.html         # Homepage
│   ├── about.html         # About page
│   ├── posts.html         # Blog listing
│   └── projects.html      # Projects page
├── _site/                 # Generated static site
├── package.json
├── tailwind.config.js
└── vercel.json           # Vercel deployment config
```

## 🚀 Getting Started

### Prerequisites

- Node.js (version 14 or higher)
- npm or yarn

### Local Development

1. **Clone the repository**
   ```bash
   git clone https://github.com/rahmatez/rahmatez-portfolio.git
   cd rahmatez-portfolio
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start development server**
   ```bash
   npm run dev
   ```
   or
   ```bash
   npx @devdojo/static@1.0.31 serve
   ```

4. **Open in browser**
   ```
   http://localhost:8000
   ```

### Building for Production

```bash
npm run build
```
or
```bash
npx @devdojo/static@1.0.31 build
```

The built files will be in the `_site` directory.

## 🌐 Deployment

### GitHub Pages

1. Push your code to GitHub
2. Go to repository Settings > Pages
3. Set source to "Deploy from a branch"
4. Choose `main` branch and `/ (root)` folder
5. Your site will be available at `https://yourusername.github.io/repository-name`

### Vercel

1. Connect your GitHub repository to [Vercel](https://vercel.com)
2. Vercel will automatically detect the `vercel.json` configuration
3. Deploy with one click

### Manual Deployment

Upload the contents of the `_site` folder to any web server.

## 📝 Customization

### Adding New Blog Posts

1. Create a new markdown file in `content/post/`
2. Add metadata to `collections/content/post.json`
3. Run build command

### Adding Projects

Edit `collections/projects.json` to add your projects with:
- Title and description
- Technologies used
- Links to live demo and source code
- Project images

### Adding Work Experience

Edit `collections/experiences.json` to add your work history with:
- Company name and logo
- Position and duration
- Description of responsibilities

### Updating Personal Information

Edit the following files:
- `pages/index.html` - Homepage content
- `pages/about.html` - About page
- `includes/header.html` - Navigation and contact info

## 🎨 Styling

This project uses Tailwind CSS for styling. The main CSS file is located at `assets/css/main.css`.

To customize the design:
1. Edit `tailwind.config.js` for theme customization
2. Modify HTML classes in template files
3. Add custom CSS in `assets/css/main.css`

## 📄 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm start` - Start development server (alias)

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the ISC License - see the [LICENSE](LICENSE) file for details.

## 👤 Author

**Rahmat**
- GitHub: [@rahmatez](https://github.com/rahmatez)
- Website: [https://rahmatez-portfolio.github.io/](https://rahmatez-portfolio.github.io/)

## 🙏 Acknowledgments

- [DevDojo](https://devdojo.com) for the Static framework
- [Tailwind CSS](https://tailwindcss.com) for the amazing CSS framework
- Original Aria template design inspiration

---

⭐ **If you like this project, please give it a star!** ⭐
