# Developer Relations Portfolio Website

A clean, responsive portfolio website built with HTML, CSS, and JavaScript, showcasing my Developer Relations work and projects. The site features an interactive data visualization component and real-time chat capabilities.

## Open for DevRel Opportunities! 🚀

I'm actively seeking Developer Relations roles where I can combine my passion for teaching, community building, and technical communication. With a background in:

- Technical Education & Curriculum Development
- Community Building & Event Organization
- Project Management & Cross-functional Leadership
- Full-stack Development & System Architecture
- Content Creation & Public Speaking

I bring a unique blend of technical expertise and communication skills to help companies build and nurture their developer communities. Some key achievements include:

- Developed and led a financial literacy program for Title 1 charter schools
- Created and managed virtual event series reaching diverse developer audiences
- Built knowledge centers and content hubs to maximize community engagement
- Volunteered in Central America teaching software development
- Designed and implemented automated training programs with measurable success metrics

### Let's Connect!

- 💼 Open to full-time DevRel positions
- 🤝 Available for consulting projects
- 🎤 Interested in speaking opportunities
- 📚 Looking to collaborate on technical content creation

If you're looking for someone who can help your company build strong relationships with developers while driving product adoption and community growth, let's talk! You can reach me through:

## Features

- **Responsive Design**: Adapts seamlessly to different screen sizes
- **Interactive Project Showcase**: Display of key projects with descriptions and links
- **Dynamic Data Visualization**: Interactive chart built with D3.js showing mileage and cost data
- **Real-time Chat**: Integration with Consolto for live chat and video calls
- **Modal Interface**: Clean modal implementation for project details
- **Google Analytics**: Built-in tracking capabilities
- **PWA Support**: Service Worker implementation for offline capabilities

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6+)
- D3.js for data visualization
- Font Awesome for icons
- Google Analytics
- Consolto for chat functionality

## Project Structure

```
├── index.html            # Main HTML file
├── manifest.json         # PWA manifest
├── service-worker.js     # Service worker for PWA
└── README.md            # This file
```

## Key Components

1. **Header Section**
   - Navigation menu
   - Personal introduction

2. **Portfolio Section**
   - Project cards with descriptions
   - Interactive visualization modal
   - Links to live projects

3. **Contact Section**
   - Social media links
   - Email contact
   - Real-time chat integration

4. **Data Visualization**
   - Interactive D3.js chart
   - Date range filtering
   - Tooltip information

## Setup and Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/devrel-portfolio.git
   ```

2. Navigate to the project directory:
   ```bash
   cd devrel-portfolio
   ```

3. Open index.html in your browser:
   - Double click the file or
   - Use a local server:
     ```bash
     python -m http.server 8000
     ```
     Then visit `http://localhost:8000`

## Customization

### Updating Projects

Edit the project cards section in `index.html`:

```html
<div class="project-card">
  <h3>Your Project Title</h3>
  <p>Project description...</p>
  <a href="project-link">View Project</a>
</div>
```

### Modifying the Chart Data

Update the data array in the JavaScript section:

```javascript
const data = [
  { date: "2024-01", mileage: 25, cost: 100 },
  // Add or modify entries as needed
];
```

### Styling

The site uses CSS variables for easy theme customization:

```css
:root {
  --primary-color: #2C3E50;
  --secondary-color: #ECF0F1;
  --accent-color: #E74C3C;
  --background-color: #F5F5F5;
  --text-color: #333;
}
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact

Ready to discuss how I can help your team succeed in Developer Relations? Reach out through:

- 💼 LinkedIn: [Brand Anthony McDonald](https://l.awews.com/brand-am-linkedin)
- 💻 GitHub: [dapperAuteur](https://i.til.show/dapperauteur-github)
- [Blog](https://i.til.show/i-write-code-blog)
- 📧 Email: a@awews.com
- 💬 Portfolio Chat: Visit my portfolio and use the chat bubble to connect in real-time

Whether you're looking to build a DevRel team, need consulting on developer community initiatives, or want to discuss potential collaborations, I'm excited to explore how we can work together to achieve your goals.

---
Built with ❤️ by Brand Anthony McDonald