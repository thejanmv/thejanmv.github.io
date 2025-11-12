# GitHub Copilot Instructions

## Repository Overview

This is a GitHub Pages repository (`thejanmv.github.io`) used for hosting a personal website. The repository follows GitHub Pages conventions and best practices.

## Purpose

This repository hosts a static website that is automatically published to `https://thejanmv.github.io`.

## Technology Stack

- **Static Site**: HTML, CSS, JavaScript
- **Hosting**: GitHub Pages
- **Version Control**: Git

## Project Structure

```
.
├── .github/              # GitHub configuration files
│   └── copilot-instructions.md
├── README.md            # Repository documentation
└── (website files)      # HTML, CSS, JS, and assets for the site
```

## Coding Conventions

### General Guidelines

- Follow web standards and best practices
- Ensure cross-browser compatibility
- Write clean, semantic HTML
- Use modern CSS practices
- Ensure accessibility (WCAG 2.1 AA compliance)
- Optimize assets for web delivery

### HTML

- Use semantic HTML5 elements
- Include proper meta tags for SEO
- Ensure proper document structure
- Use meaningful IDs and classes

### CSS

- Use consistent naming conventions (e.g., BEM methodology)
- Organize styles logically
- Use CSS custom properties for theming
- Ensure responsive design (mobile-first approach)
- Minimize use of `!important`

### JavaScript

- Use modern ES6+ syntax
- Write modular, reusable code
- Handle errors gracefully
- Optimize for performance
- Add comments for complex logic

## Development Workflow

### Before Making Changes

1. Review existing code structure and conventions
2. Ensure changes align with the site's design and purpose
3. Test changes locally before committing

### Testing

- Test on multiple browsers (Chrome, Firefox, Safari, Edge)
- Verify responsive design on different screen sizes
- Check accessibility using browser dev tools
- Validate HTML and CSS

### Deployment

- Changes pushed to the main branch are automatically deployed to GitHub Pages
- Allow 1-2 minutes for changes to propagate

## Best Practices

1. **Keep it Simple**: This is a static site; avoid unnecessary complexity
2. **Performance**: Optimize images, minify CSS/JS when appropriate
3. **Accessibility**: Ensure all content is accessible to users with disabilities
4. **SEO**: Include proper meta tags, structured data, and semantic markup
5. **Security**: Use HTTPS links, implement CSP headers if needed
6. **Documentation**: Update README.md when making significant changes

## GitHub Pages Specific

- The site is served from the root directory or `/docs` folder (check repository settings)
- Jekyll is supported by default (though not required)
- Custom domains can be configured via CNAME file
- Site URL: `https://thejanmv.github.io`

## When Assisting with Code

- Maintain consistency with existing code style
- Provide complete, working examples
- Consider mobile responsiveness in all suggestions
- Ensure accessibility in all recommendations
- Test suggestions before providing them when possible
- Explain the reasoning behind recommendations

## Resources

- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [Web Content Accessibility Guidelines (WCAG)](https://www.w3.org/WAI/WCAG21/quickref/)
- [MDN Web Docs](https://developer.mozilla.org/)
