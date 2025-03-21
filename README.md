# Personal Portfolio Website

A modern, responsive portfolio website built with Next.js, TypeScript, and Tailwind CSS.

## Features

- 🎨 Modern and clean design
- 🌙 Dark mode support
- 📱 Fully responsive
- ⚡ Fast performance
- 📝 Easy to customize
- 📬 Contact form with API route

## Getting Started

1. Clone the repository:
```bash
git clone <your-repo-url>
cd portfolio
```

2. Install dependencies:
```bash
npm install
```

3. Customize your portfolio:
   - Edit `src/config/portfolio.ts` with your personal information
   - Add your project images to the `public` directory
   - Update the styling in `src/app/globals.css` if needed

4. Run the development server:
```bash
npm run dev
```

5. Open [http://localhost:3000](http://localhost:3000) in your browser.

## Customization

### Personal Information
Edit `src/config/portfolio.ts` to update:
- Your name and title
- Social media links
- Work experience
- Projects
- Skills

### Styling
The website uses Tailwind CSS for styling. You can:
- Modify colors in `tailwind.config.js`
- Update component styles in `src/app/page.tsx`
- Add custom CSS in `src/app/globals.css`

### Contact Form
The contact form is set up with a basic API route. To make it functional:
1. Update the API route in `src/app/api/contact/route.ts`
2. Add email service integration (e.g., SendGrid, Nodemailer)
3. Add form validation and spam protection

## Deployment

### GitHub Pages Deployment

1. Push your code to GitHub:
```bash
git add .
git commit -m "Initial commit"
git push origin main
```

2. Enable GitHub Pages:
   - Go to your repository settings
   - Navigate to "Pages" section
   - Under "Source", select "GitHub Actions"
   - The site will be automatically deployed when you push to the main branch

3. Your site will be available at: `https://<your-github-username>.github.io/portfolio`

### Manual Build
To build the site locally:
```bash
npm run build
```
The static files will be generated in the `out` directory.

## License

MIT
