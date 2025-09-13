# Contributing to No Hope for Humanity

Thank you for your interest in contributing to this project! This document provides guidelines and information for contributors.

## 🎯 Project Vision

This project aims to create a simple, elegant, and accessible blog platform that serves as a digital exhibit space. We prioritize:

- **Simplicity**: Clean, minimalistic design and functionality
- **Performance**: Fast loading times and efficient code
- **Accessibility**: Inclusive design for all users
- **Maintainability**: Clear, well-documented code

## 🚀 Getting Started

### Development Environment Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/nibertinvestments/nohopeforhumanity.git
   cd nohopeforhumanity
   ```

2. **Start local development server**
   ```bash
   python3 -m http.server 8000
   ```

3. **Open in browser**
   Navigate to `http://localhost:8000`

### Project Structure Understanding

```
nohopeforhumanity/
├── index.html          # Main page - landing and blog listing
├── blog-*.html         # Individual blog posts
├── LICENSE             # MIT License
├── README.md           # Project documentation
└── CONTRIBUTING.md     # This file
```

## 🎨 Design Guidelines

### CSS Standards
- Use CSS custom properties (variables) for theming
- Follow mobile-first responsive design principles
- Maintain dark mode compatibility
- Keep animations subtle and purposeful
- Use system font stack for optimal performance

### HTML Standards
- Write semantic HTML5
- Ensure accessibility with proper ARIA labels
- Maintain consistent document structure
- Include appropriate meta tags

### JavaScript Guidelines
- Use vanilla JavaScript (no frameworks required)
- Write clean, commented code
- Optimize for performance
- Ensure cross-browser compatibility

## 🔧 Development Workflow

### Making Changes

1. **Fork the repository**
2. **Create a feature branch**
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. **Make your changes**
4. **Test thoroughly**
   - Check on multiple browsers
   - Verify mobile responsiveness
   - Test dark mode functionality
5. **Commit with clear messages**
   ```bash
   git commit -m "Add: brief description of changes"
   ```
6. **Push and create pull request**

### Commit Message Guidelines

Use clear, descriptive commit messages:

- `Add: new feature or content`
- `Fix: bug fixes or corrections`
- `Update: modifications to existing features`
- `Remove: deletion of features or content`
- `Docs: documentation changes`

Examples:
- `Add: search functionality to blog posts`
- `Fix: mobile navigation alignment issue`
- `Update: Instagram embed styling`
- `Docs: improve setup instructions in README`

## 📝 Content Guidelines

### Adding Blog Posts

1. **Copy existing template**
   ```bash
   cp blog-1.html blog-new.html
   ```

2. **Update content sections**
   - Page title in `<title>` tag
   - Instagram embed code (if applicable)
   - Blog post content and text
   - Any specific styling needed

3. **Add to main index**
   - Edit `index.html`
   - Add new blog link in the `#Exhibits` section
   - Follow existing pattern for consistency

### Content Standards
- Write clear, engaging content
- Use proper grammar and spelling
- Include relevant Instagram embeds when appropriate
- Maintain consistent tone and style
- Ensure content is appropriate for all audiences

## 🧪 Testing

### Manual Testing Checklist

Before submitting changes, verify:

- [ ] **Cross-browser compatibility**
  - Chrome/Chromium
  - Firefox
  - Safari (if available)
  - Edge

- [ ] **Responsive design**
  - Mobile phones (320px+)
  - Tablets (768px+)
  - Desktop (1024px+)

- [ ] **Functionality**
  - Search works correctly
  - Navigation links function
  - Instagram embeds load properly
  - Dark mode toggles correctly

- [ ] **Performance**
  - Fast loading times
  - No JavaScript errors in console
  - CSS renders correctly

- [ ] **Accessibility**
  - Proper heading structure
  - Alt text for images
  - Keyboard navigation works
  - High contrast ratios

## 🐛 Bug Reports

When reporting bugs, include:

1. **Clear description** of the issue
2. **Steps to reproduce** the problem
3. **Expected behavior** vs actual behavior
4. **Browser and device** information
5. **Screenshots** if applicable

Use this template:

```markdown
**Bug Description:**
Brief description of the issue

**Steps to Reproduce:**
1. Go to...
2. Click on...
3. See error...

**Expected Behavior:**
What should happen

**Actual Behavior:**
What actually happens

**Environment:**
- Browser: Chrome 91.0
- Device: Desktop/Mobile
- Screen size: 1920x1080
```

## 💡 Feature Requests

For new feature suggestions:

1. **Check existing issues** to avoid duplicates
2. **Describe the feature** clearly
3. **Explain the use case** and benefits
4. **Consider implementation** complexity
5. **Align with project vision**

## 📋 Code Review Process

### For Contributors
- Ensure your code follows the style guidelines
- Include clear commit messages
- Test thoroughly before submitting
- Be open to feedback and suggestions

### For Reviewers
- Focus on code quality and maintainability
- Check for adherence to project standards
- Verify functionality and performance
- Provide constructive feedback

## 🎉 Recognition

Contributors will be acknowledged in:
- Project documentation
- Release notes for significant contributions
- Special thanks in relevant blog posts

## 📞 Getting Help

If you need assistance:

1. **Check existing documentation** first
2. **Search issues** for similar questions
3. **Create a new issue** with clear details
4. **Be patient and respectful** in communications

## 🤝 Code of Conduct

### Our Standards

- **Be respectful** and inclusive
- **Welcome newcomers** and help them learn
- **Focus on constructive feedback**
- **Assume positive intent**
- **Keep discussions professional**

### Unacceptable Behavior

- Harassment or discrimination
- Spam or irrelevant content
- Personal attacks or inflammatory language
- Publishing private information without permission

## 📜 License

By contributing, you agree that your contributions will be licensed under the MIT License that covers the project.

---

**Thank you for contributing to No Hope for Humanity!**

Your efforts help create a better, more accessible web experience for everyone.