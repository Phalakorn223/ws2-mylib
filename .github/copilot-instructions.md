# GitHub Copilot Rules for my-story-shelves

## General Guidelines
1. **Code Review**
   - Always review Copilot-suggested code before implementation
   - Test all suggested code thoroughly
   - Ensure code meets project standards and TypeScript/React best practices
   - Verify suggestions work with existing components and hooks

2. **Security & Privacy**
   - Do not use Copilot for generating sensitive code (user authentication, data encryption)
   - Avoid using Copilot with private or confidential information
   - Be cautious with security-related code suggestions
   - Never expose API keys or sensitive configuration

3. **Code Quality**
   - Use Copilot as an assistance tool, not a replacement for coding
   - Maintain consistent TypeScript types and interfaces
   - Follow React hooks rules and component patterns
   - Ensure proper error handling in book management functions
   - Keep components modular and reusable

4. **Project-Specific Standards**
   - Follow existing component structure (components/, pages/, hooks/)
   - Use shadcn-ui components when available
   - Maintain Tailwind CSS class naming conventions
   - Follow established state management patterns with React Query
   - Keep consistent with current routing structure

5. **Best Practices**
   - Use TypeScript types for book and lending management
   - Follow React component composition patterns
   - Implement proper form validation
   - Maintain responsive design principles
   - Use proper error boundaries and loading states

6. **Documentation**
   - Document all new components and functions
   - Add JSDoc comments for TypeScript interfaces
   - Include usage examples for reusable components
   - Document state management patterns
   - Keep README updated with new features

## Specific Areas for Copilot Usage
1. **Component Development**
   - Book management forms and modals
   - Search and filter implementations
   - UI components following shadcn-ui patterns
   - Responsive layout solutions

2. **TypeScript Types**
   - Book and user interfaces
   - API response types
   - State management types
   - Component prop types

3. **Utility Functions**
   - Date formatting for lending
   - Search and filter logic
   - Form validation
   - Error handling

## Code Standards
- Use functional components with hooks
- Implement proper TypeScript types
- Follow Tailwind CSS class structure
- Maintain consistent file organization
- Use proper naming conventions
- Include error handling
- Write clean, maintainable code

## Testing Guidelines
- Write unit tests for utility functions
- Test component rendering
- Include error case testing
- Verify form validation
- Test responsive behavior

## Issue Reporting
If you encounter issues with GitHub Copilot:
1. Document the specific problem
2. Note the component or feature affected
3. Record any error messages
4. Share alternative solutions tried
5. Collaborate with team on fixes
