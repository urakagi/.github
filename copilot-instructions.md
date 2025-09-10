# GitHub Copilot Global Instructions

## Code Style and Quality

### General Principles
- Write clean, readable, and maintainable code
- Follow established conventions for the programming language being used
- Use descriptive variable and function names
- Keep functions small and focused on a single responsibility
- Add clear comments for complex logic or business rules

### Code Formatting
- Use consistent indentation (prefer spaces over tabs)
- Follow language-specific style guides (e.g., PEP 8 for Python, Google Style Guide for JavaScript)
- Use meaningful whitespace to improve readability
- Keep line lengths reasonable (typically 80-120 characters)

## Security Best Practices

### Input Validation and Sanitization
- Always validate and sanitize user inputs
- Use parameterized queries to prevent SQL injection
- Implement proper authentication and authorization
- Never hardcode secrets, API keys, or credentials

### Error Handling
- Implement comprehensive error handling
- Log errors appropriately without exposing sensitive information
- Provide meaningful error messages to users
- Use try-catch blocks where appropriate

## Documentation and Comments

### Code Documentation
- Write clear docstrings for functions and classes
- Document complex algorithms and business logic
- Keep comments up-to-date with code changes
- Use inline comments sparingly and only when necessary

### README and Project Documentation
- Include clear installation and usage instructions
- Document API endpoints and parameters
- Provide examples and use cases
- Maintain changelog for version releases

## Testing

### Test Coverage
- Write unit tests for core functionality
- Include integration tests for critical workflows
- Aim for meaningful test coverage, not just high percentages
- Test edge cases and error conditions

### Test Quality
- Use descriptive test names that explain what is being tested
- Keep tests simple and focused
- Mock external dependencies appropriately
- Ensure tests are deterministic and repeatable

## Performance and Efficiency

### Optimization
- Choose appropriate data structures and algorithms
- Avoid premature optimization
- Profile code when performance issues are identified
- Consider memory usage and resource consumption

### Database Interactions
- Use efficient queries and proper indexing
- Implement pagination for large datasets
- Use connection pooling where appropriate
- Avoid N+1 query problems

## Dependencies and Libraries

### Dependency Management
- Keep dependencies up-to-date and secure
- Use package managers and lock files
- Minimize unnecessary dependencies
- Document dependency requirements clearly

### Library Usage
- Prefer well-maintained and widely-adopted libraries
- Check license compatibility
- Understand the libraries you're using
- Have fallback plans for critical dependencies

## Version Control and Collaboration

### Git Practices
- Write clear, descriptive commit messages
- Use feature branches for development
- Keep commits atomic and focused
- Include relevant issue numbers in commit messages

### Code Reviews
- Write code that is easy to review
- Provide context in pull request descriptions
- Respond constructively to feedback
- Test changes thoroughly before submitting

## Environment-Specific Guidelines

### Development Environment
- Use environment variables for configuration
- Maintain separate configurations for different environments
- Document setup requirements clearly
- Use containerization when appropriate

### Production Considerations
- Implement proper logging and monitoring
- Use graceful error handling and fallbacks
- Consider scalability and load requirements
- Implement health checks and status endpoints

## Language-Specific Preferences

### Python
- Follow PEP 8 style guidelines
- Use type hints where appropriate
- Prefer list comprehensions and generator expressions
- Use virtual environments for dependency isolation

### JavaScript/TypeScript
- Use TypeScript when possible for better type safety
- Follow ESLint and Prettier configurations
- Use modern ES6+ features appropriately
- Implement proper module importing/exporting

### General Web Development
- Follow responsive design principles
- Implement proper accessibility features
- Use semantic HTML elements
- Optimize for performance and SEO

## Additional Guidelines

### Code Reusability
- Create reusable components and utilities
- Avoid code duplication through proper abstraction
- Use design patterns appropriately
- Document reusable components clearly

### Maintenance and Updates
- Write code that is easy to modify and extend
- Plan for future requirements and changes
- Implement proper configuration management
- Keep technical debt under control

## Emergency and Critical Issues

### Security Vulnerabilities
- Treat security issues with highest priority
- Follow responsible disclosure practices
- Implement immediate fixes and patches
- Document security considerations

### Production Issues
- Implement proper monitoring and alerting
- Have rollback plans ready
- Document incident response procedures
- Learn from failures and improve processes