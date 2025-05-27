# Eric Zhao's Portfolio (wip)

Visit the live site: [https://ericezzhao.github.io/](https://ericezzhao.github.io/)

wip personal portfolio website that is AI-powered to showcase my education and work career 

## About

I am a master's data science student at NYU working on AI and ML topics. Currently, I am an AI intern @ Austal USA and a graduate research assistant @ Kiani Neural Lab.

## Features

- Interactive AI chat interface powered by Google's Generative AI (Gemma model, will change)
- Built with Next.js 14 and React
- Responsive design with Tailwind CSS
- Deployed on GitHub Pages
- Frieren themed cause why not

## Technical Implementation

### AI Chat Interface with Google's Generative AI
- **API Integration**
  - Implemented using Google's Generative AI API
  - Configured with the Gemma model
  - Set up secure API key management
  - Implemented error handling for API rate limits and timeouts

- **Response System**
  - Implemented context management to maintain conversation history
  - Used streaming responses for real-time interaction
  - Optimized response formatting for natural conversation flow

### Frontend Architecture

#### Next.js 14 Implementation
- **App Router & Server Components**
  - Utilized Next.js 14's App Router for improved routing
  - Implemented Server Components for better performance
  - Used Client Components where interactivity was needed
  - Configured proper metadata for SEO optimization

- **Static Site Generation**
  - Set up `next.config.js` for static exports
  - Configured proper asset handling for static deployment
  - Implemented proper image optimization
  - Managed dynamic routes and API endpoints

#### React Components
- **Component Architecture**
  - Built reusable components for chat interface
  - Implemented proper state management using React hooks
  - Used Context API for global state management
  - Created custom hooks for API interactions

- **Performance Optimization**
  - Implemented proper code splitting
  - Used React.memo for component memoization
  - Optimized re-renders with useCallback and useMemo
  - Implemented proper user-friendly design choices

#### Tailwind CSS Implementation
- **Responsive Design**
  - Used Tailwind's utility classes for responsive layouts
  - Implemented dark mode support
  - Included animations and transitions

### Deployment Process

#### GitHub Pages Setup
- **Static Site Deployment**
  - Configured GitHub Actions workflow for automated deployment
  - Set up proper branch settings (gh-pages)
  - Implemented `.nojekyll` file to prevent Jekyll processing
  - Managed static asset paths and routing

- **CI/CD Pipeline**
  - Automated build and deployment process
  - Implemented proper caching for faster builds
  - Added environment variable management
  - Set up proper error handling in the pipeline

## Development Process

### Key Learnings
1. **Next.js Static Exports**
   - Configured `next.config.js` for static site generation
   - Implemented proper asset handling for static deployment
   - Managed dynamic routes and API endpoints
   - Learned about the limitations of static exports with API routes

2. **GitHub Pages Deployment**
   - Set up GitHub Actions workflow for automated deployment
   - Configured proper branch settings (gh-pages)
   - Implemented `.nojekyll` file to prevent Jekyll processing
   - Managed static asset paths and routing
   - Learned about GitHub Pages limitations and workarounds

3. **AI Integration**
   - Implemented secure API key management
   - Created character-based response system
   - Optimized response formatting and context handling
   - Managed API rate limiting and error handling
   - Learned about streaming responses and real-time updates

4. **Performance Optimization**
   - Implemented proper image optimization
   - Configured proper caching strategies
   - Optimized bundle sizes and loading times
   - Ensured responsive design across devices
   - Learned about Core Web Vitals and performance metrics

## Local Development

1. Clone the repository (if public, else just build)

2. Install dependencies:
   ```bash
   npm install
   ```

3. Set up environment variables:
   - Create a `.env.local` file
   - Add your Google AI API key: `GEMINI_API_KEY=your_api_key`
   - Never commit API keys or sensitive information to the repository

4. Run the development server:
   ```bash
   npm run dev
   ```

5. Build for production:
   ```bash
   npm run build
   ```

## Security Best Practices

- API keys and sensitive information are stored in environment variables
- GitHub Secrets are used for CI/CD pipeline
- Regular security audits of dependencies
- No sensitive information in public files
- Private repository with public README only

## Contacts

- LinkedIn: [Eric Zhao](https://www.linkedin.com/in/zhaoez/)
- GitHub: [@ericezzhao](https://github.com/ericezzhao)

## License

This project is open source and available under the MIT License.
