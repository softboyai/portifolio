# JMV Kamanzi Portfolio

A personal portfolio website for Kamanzi Jean Marie Vianney, showcasing web development and AI projects.

## 📋 Project Overview

This portfolio website is built with modern HTML, CSS, and JavaScript to showcase my skills, projects, and services as a web developer and AI specialist based in Rwanda.

### 🌟 Features

- Responsive design for all devices
- Dark/light theme toggle
- Project showcase with links to live demos
- WhatsApp contact button with service options
- Interactive chatbot
- Contact form
- SEO optimized for Rwanda-specific searches

## 🚀 Deployment

### GitHub Deployment

1. Create a new GitHub repository
2. Initialize Git in your local project folder:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/softboyai/portfolio.git
   git push -u origin main
   ```

### Netlify Deployment

1. Create a Netlify account at [netlify.com](https://www.netlify.com/)
2. Deploy using one of these methods:

   **Deploy from GitHub:**
   - Log in to Netlify
   - Click "New site from Git"
   - Select GitHub and authorize Netlify
   - Select your repository
   - Configure build settings (leave blank for static site)
   - Click "Deploy site"

   **Deploy manually:**
   - Run `npm install -g netlify-cli` to install Netlify CLI
   - Run `netlify login` to authenticate
   - Run `netlify deploy` and follow prompts
   - For production deploy: `netlify deploy --prod`

## 📁 Project Structure

```
portfolio/
├── index.html              # Main HTML file
├── assets/
│   ├── css/
│   │   └── style.css       # Main stylesheet
│   ├── js/
│   │   ├── main.js         # Main JavaScript file
│   │   └── chatbot.js      # Chatbot functionality
│   ├── images/             # Image assets
│   │   ├── profile.jpg
│   │   └── projects/       # Project images
│   └── documents/          # Resume and other documents
├── sitemap.xml             # XML Sitemap for SEO
├── robots.txt              # Search engine instructions
└── README.md               # Project documentation
```

## 📱 Mobile Optimization

The website is fully responsive and optimized for all devices including:
- Mobile phones
- Tablets
- Desktops
- Large screens

## 🔍 SEO Features

- Semantic HTML structure
- Structured data (JSON-LD)
- Optimized meta tags
- Fast loading assets with lazy loading
- Mobile-friendly design
- Local SEO for Rwanda
- XML sitemap and robots.txt

## 🧰 Customization

### Updating Projects

Edit the `projects` section in `index.html` to add or modify your projects.

### Updating Skills

Edit the `skills` section in `index.html` to reflect your current skillset.

### Changing Color Scheme

Update the CSS variables in the `:root` section of `style.css`.

## 📞 Contact

- Phone: +250 787 878 745
- Email: kamanzijeanmarievianney15@gmail.com
- GitHub: [softboyai](https://github.com/softboyai)
- LinkedIn: [Jean Marie Vianney Kamanzi](https://www.linkedin.com/in/jean-marie-vianney-kamanzi-6a732a34b)

## 📝 License

This project is open source and available under the MIT License. 