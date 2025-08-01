# Making Data Science Count Research Group Website

Welcome to the repository for the Making Data Science Count Research Group website, hosted at [makingdatasciencecount.com](https://makingdatasciencecount.com).

## About

The Making Data Science Count Research Group is based in the College of Education, Health, and Human Sciences at the University of Tennessee, Knoxville. Our mission is to leverage collective efforts to study science education, computer and data science education, educational technology, and related domains using diverse theoretical and methodological approaches across K-12, post-secondary, and informal learning contexts.

## Website Structure

This website is built with [Quarto](https://quarto.org/) and includes:

- **Home Page**: Welcome message and recent blog posts
- **About Us**: Faculty, doctoral students, and alumni information
- **Projects**: Current research projects and collaborations
- **Resources**: Software, publications, and other research outputs
- **Blog Posts**: Updates about conferences, presentations, and research activities

## Contributing

We welcome contributions from collaborators, students, and the broader research community. Here are several ways you can contribute:

### Types of Contributions

#### 📝 Content Contributions
- **Blog Posts**: Share updates about research, conferences, or educational insights
- **Project Updates**: Add information about new or ongoing research projects
- **Resource Additions**: Add links to papers, software, datasets, or other resources
- **Profile Updates**: Update team member information or add new members

#### 🛠️ Technical Contributions
- **Website Improvements**: Enhance design, functionality, or accessibility
- **Bug Fixes**: Report or fix broken links, formatting issues, or display problems
- **Performance Optimizations**: Improve loading times or mobile responsiveness

#### 📚 Documentation
- **Improve this README**: Help make contribution guidelines clearer
- **Add Comments**: Improve code documentation in configuration files

### Getting Started

#### Prerequisites
- [Quarto](https://quarto.org/docs/get-started/) (latest version recommended)
- [R](https://www.r-project.org/) or [Python](https://python.org) (if your content includes computational code)
- Git and a GitHub account
- A text editor (VS Code, RStudio, etc.)

#### Local Development Setup

1. **Fork and Clone the Repository**
   ```bash
   git clone https://github.com/YOUR-USERNAME/mdsc-blog.git
   cd mdsc-blog
   ```

2. **Preview the Website Locally**
   ```bash
   quarto preview
   ```
   This will start a local server (usually at `http://localhost:4200`) where you can see your changes in real-time.

3. **Make Your Changes**
   - Edit existing `.qmd` files or create new ones
   - Follow the existing structure and formatting conventions
   - Test your changes locally before submitting

4. **Build the Website** (optional, for testing)
   ```bash
   quarto render
   ```

### Content Guidelines

#### Adding Blog Posts
1. Create a new folder in `posts/` with a descriptive name (e.g., `posts/my-conference-2024/`)
2. Add an `index.qmd` file with the following front matter:
   ```yaml
   ---
   title: "Your Post Title"
   author: "Your Name"
   date: "YYYY-MM-DD"
   categories: [category1, category2]
   ---
   ```
3. Write your content in Markdown below the front matter
4. Add any images to the same folder and reference them with relative paths

#### Updating Team Information
- Edit `about-us.qmd` to add new members or update existing information
- Follow the existing format for consistency
- Include a brief bio and contact information where appropriate

#### Adding Projects or Resources
- Edit `projects.qmd` or `resources.qmd` respectively
- Use the existing formatting patterns
- Include relevant links and descriptions

### Style Guidelines

- **Writing Style**: Academic but accessible; avoid excessive jargon
- **Formatting**: Use consistent heading levels (`##` for main sections, `###` for subsections)
- **Links**: Use descriptive link text rather than "click here" or bare URLs
- **Images**: Include alt text for accessibility (`![Alt text](image.jpg)`)
- **Code**: If including code, use appropriate syntax highlighting

### File Structure

```
mdsc-blog/
├── _quarto.yml           # Main configuration file
├── index.qmd            # Home page
├── about-us.qmd         # Team information
├── projects.qmd         # Research projects
├── resources.qmd        # Software and publications
├── posts/               # Blog posts directory
│   ├── _metadata.yml    # Posts configuration
│   └── [post-folders]/  # Individual post directories
├── img/                 # Images and assets
└── style.scss          # Custom styling
```

### Technical Notes

- **Configuration**: Main site settings are in `_quarto.yml`
- **Styling**: Custom CSS/SCSS goes in `style.scss`
- **Images**: Store in the `img/` directory or within individual post folders
- **Freeze**: Computational content is frozen (see `posts/_metadata.yml`)

### Submission Process

1. **Fork the Repository** on GitHub
2. **Create a Feature Branch** for your changes:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. **Make Your Changes** and test locally
4. **Commit Your Changes** with descriptive messages:
   ```bash
   git add .
   git commit -m "Add: Brief description of your changes"
   ```
5. **Push to Your Fork**:
   ```bash
   git push origin feature/your-feature-name
   ```
6. **Create a Pull Request** with:
   - Clear description of changes
   - Any relevant screenshots (for visual changes)
   - Mention if this addresses any specific issues

### Review Process

- Pull requests will be reviewed by group members
- We may suggest changes or ask questions
- Once approved, changes will be merged and automatically deployed

### Questions or Issues?

- **Technical Issues**: Open a GitHub issue with details about the problem
- **Content Questions**: Contact [Joshua M. Rosenberg](mailto:jmrosenberg@utk.edu)
- **General Inquiries**: Use the contact information on our [About Us](https://makingdatasciencecount.com/about-us.html) page

### Code of Conduct

We are committed to fostering an inclusive and respectful environment. All contributors are expected to:
- Be respectful and professional in all interactions
- Provide constructive feedback
- Acknowledge others' contributions
- Focus on what is best for the research community

## License

This website content is available under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) unless otherwise specified.

## Acknowledgments

This website is built with [Quarto](https://quarto.org/) and hosted on GitHub Pages. We thank the open-source community for the tools that make this project possible.

---

Thank you for your interest in contributing to the Making Data Science Count Research Group website! 🎓✨