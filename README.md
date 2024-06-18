# NoOne - Developer Portfolio Management Tool

## Project Overview
**NoOne** is an open-source tool designed to manage and host developer portfolio websites. It integrates a variety of modern technologies to provide a seamless and powerful experience for both developers and their audiences.

### Tech Stack:
1. **Frontend:**
   - **Next.js + TypeScript:** For server-side rendered (SSR) frontend.
   - **Shadcn + Tailwind CSS:** For styling the frontend with a modern and responsive design.

2. **Backend:**
   - **Strapi:** As the CMS to manage content such as work experience, summaries, and projects.
   - **Node.js Utility:** To convert HTML resume themes into PDF, accessible through a unique URI.

3. **Package Management:**
   - **Nx + Vite:** For managing packages in a monorepo setup, including portfolio themes, resume themes, utilities, Strapi CMS, and Node.js utility.

4. **Deployment:**
   - **Docker:** To package the entire application into a container for consistent deployment across environments.
   - **AWS:** For hosting the Docker image and providing scalable infrastructure.

5. **Authentication:**
   - **AWS Cognito:** For handling authentication securely and efficiently.

## 15-Day Implementation Plan

### Week 1: Setting Up and Understanding Basics

- [ ] **Day 1: Set Up Development Environment**
  - **Task:** Install Node.js, npm, and set up a basic Next.js application.
  - **Focus:** Project setup, environment configuration.
  - **Resources:** [Node.js Installation](https://nodejs.org/), [Create Next.js App](https://nextjs.org/docs/getting-started)

- [ ] **Day 2: Introduction to Strapi**
  - **Task:** Learn about Strapi and set it up.
  - **Focus:** Setting up Strapi, creating content types for work experience, summaries, projects.
  - **Resources:** [Strapi Documentation](https://strapi.io/documentation)

- [ ] **Day 3: Integrate Strapi with Next.js**
  - **Task:** Connect Strapi CMS with Next.js frontend.
  - **Focus:** Fetching data from Strapi and displaying it in Next.js.
  - **Resources:** [Using Strapi with Next.js](https://strapi.io/blog/nextjs-react-hooks-strapi)

- [ ] **Day 4: Styling with Tailwind CSS**
  - **Task:** Set up Tailwind CSS with Next.js.
  - **Focus:** Applying styles using Tailwind CSS, creating responsive layouts.
  - **Resources:** [Tailwind CSS Documentation](https://tailwindcss.com/docs)

- [ ] **Day 5: Introduction to Shadcn Components**
  - **Task:** Integrate Shadcn components with Next.js and Tailwind CSS.
  - **Focus:** Using Shadcn components for UI consistency and styling.

- [ ] **Day 6: Setting Up Nx Monorepo**
  - **Task:** Set up Nx to manage the monorepo for your project.
  - **Focus:** Organizing multiple packages within a single repository.
  - **Resources:** [Nx Documentation](https://nx.dev/getting-started/intro)

- [ ] **Day 7: Configuring Vite for Fast Builds**
  - **Task:** Integrate Vite for faster builds and optimized development workflow.
  - **Focus:** Configuring Vite in the Nx monorepo.
  - **Resources:** [Vite Documentation](https://vitejs.dev/)

### Week 2: Building Core Features

- [ ] **Day 8: Building Basic To-Do List Backend**
  - **Task:** Implement CRUD operations for a to-do list in Strapi.
  - **Focus:** Controllers, services, TypeORM entities.

- [ ] **Day 9: Frontend Integration with To-Do List**
  - **Task:** Connect the frontend with the Strapi backend to display and manage to-do lists.
  - **Focus:** API integration, state management.

- [ ] **Day 10: Adding User Authentication with AWS Cognito**
  - **Task:** Set up AWS Cognito for authentication and integrate it with the frontend and backend.
  - **Focus:** User login, registration, and authentication.
  - **Resources:** [AWS Cognito Documentation](https://docs.aws.amazon.com/cognito/index.html)

- [ ] **Day 11: Node.js Utility for PDF Conversion**
  - **Task:** Develop a Node.js service to convert HTML resume templates to PDF.
  - **Focus:** HTML to PDF conversion, unique URI generation.

- [ ] **Day 12: Integrating PDF Generation with Frontend**
  - **Task:** Integrate the PDF generation service with the frontend to allow users to download their resumes.
  - **Focus:** Frontend API calls, file downloads.

- [ ] **Day 13: Implementing Real-time Updates with WebSockets**
  - **Task:** Implement real-time updates for to-do lists using WebSockets.
  - **Focus:** WebSocket gateway, real-time data handling.

- [ ] **Day 14: Setting Up Docker for Deployment**
  - **Task:** Create Dockerfiles for the frontend, backend, and utilities.
  - **Focus:** Containerizing the application for consistent deployment.
  - **Resources:** [Docker Documentation](https://docs.docker.com/get-started/)

- [ ] **Day 15: Deploying to AWS**
  - **Task:** Deploy the Docker containers to AWS.
  - **Focus:** Setting up AWS infrastructure, deploying containers, configuring environment variables.
  - **Resources:** [AWS Deployment Guide](https://aws.amazon.com/getting-started/hands-on/deploy-react-app-cicd-amplify/)
