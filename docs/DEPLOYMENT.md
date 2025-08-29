# 🛠️ Wideboard Development Guide

A guide for developers who want to contribute to Wideboard or understand the codebase.

![Wideboard Hero](https://i.ibb.co/nsXrzMkL/image.png)

> **A Spacie Original Project** - Build the future of productivity

---

## 🚀 Development Setup

### Prerequisites
- **Node.js** 18.0.0 or higher
- **npm** 8.0.0 or higher (or **yarn** 1.22.0+)
- **Git** for version control
- **VS Code** (recommended) with TypeScript support


## 🏗️ Project Architecture

### Tech Stack
- **Frontend**: Next.js 15, React 19, TypeScript 5
- **Styling**: Tailwind CSS 4, Shadcn/ui components
- **State Management**: Zustand with persistence
- **AI Integration**: OpenRouter API
- **Build Tool**: Vite (Next.js 15)

---

## 🚀 Performance

### Optimization Techniques
- **Code Splitting**: Use dynamic imports for large components
- **Memoization**: Cache expensive calculations
- **Lazy Loading**: Load components on demand
- **Image Optimization**: Use Next.js Image component

---

## 🔒 Security

### Best Practices
- **Input Validation**: Validate all user inputs
- **API Key Security**: Store keys in environment variables
- **XSS Prevention**: Sanitize user-generated content
- **CSRF Protection**: Implement proper CSRF tokens

---

## 📚 Resources

### Documentation
- [Next.js Documentation](https://nextjs.org/docs)
- [React Documentation](https://react.dev)
- [TypeScript Handbook](https://www.typescriptlang.org/docs)
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)

### Useful Tools
- **React Developer Tools**: Browser extension for debugging
- **TypeScript Playground**: Test TypeScript code online
- **Tailwind CSS IntelliSense**: VS Code extension
- **ESLint & Prettier**: Code quality and formatting

---

## 🤝 Contributing

Contact me via ice@spacie.net

### Commit Messages
Use conventional commit format:
```
feat: add new widget system
fix: resolve task creation bug
docs: update API documentation
style: improve button styling
refactor: simplify store logic
test: add widget tests
```

---

## 🐛 Debugging

### Common Issues
- **Build Errors**: Check TypeScript types and imports
- **Runtime Errors**: Use browser dev tools and console
- **Performance Issues**: Profile with React DevTools
- **Styling Problems**: Inspect with browser dev tools

### Debug Tools
- **Console Logging**: Strategic console.log statements
- **React DevTools**: Component inspection and profiling
- **Network Tab**: Monitor API calls and responses
- **Performance Tab**: Analyze rendering performance

---

## 🚀 Getting Help

- **Issues**: [GitHub Issues](https://github.com/yourusername/wideboard/issues)
- **Discussions**: [GitHub Discussions](https://github.com/yourusername/wideboard/discussions)
- **Documentation**: Check this guide and main README
- **Community**: Join our developer community

---

**Made with ❤️ by the Spacie Team**

*Build the future of productivity*

---

*Last updated: August 2025*
*Documentation version: 2.0.0*
