# NoOne - Developer Portfolio Management Tool

## Project Overview
**NoOne** is an open-source tool designed to manage and host developer portfolio websites. It integrates a variety of modern technologies to provide a seamless and powerful experience for both developers and their audiences.

### Tech Stack:
1. **Frontend:**
   - **Next.js + TypeScript:** For server-side rendered (SSR) frontend.
   - **Shadcn + Tailwind CSS:** For styling the frontend with a modern and responsive design.

2. **Backend:**
   - **NestJS:** As the backend framework to manage content such as work experience, summaries, and projects.
   - **Node.js Utility:** To convert HTML resume themes into PDF, accessible through a unique URI.

3. **Package Management:**
   - **Nx + Vite:** For managing packages in a monorepo setup, including portfolio themes, resume themes, utilities, NestJS backend, and Node.js utility.

4. **Deployment:**
   - **Docker:** To package the entire application into a container for consistent deployment across environments.
   - **AWS:** For hosting the Docker image and providing scalable infrastructure.

5. **Authentication:**
   - **AWS Cognito:** For handling authentication securely and efficiently.

## 15-Day Implementation Plan

### Week 1: Setting Up and Understanding Basics

- [ ] **Day 1: Set Up Nx Monorepo with Vite+React+TypeScript**
  - **Task:** Install Nx, create a new workspace, and set up Vite, React, and TypeScript within the Nx monorepo.
  - **Focus:** Organizing multiple packages within a single repository.
  - **Resources:** [Nx Documentation](https://nx.dev/getting-started/intro)

- [ ] **Day 2: Configure Nx for Next.js**
  - **Task:** Set up Next.js within the Nx monorepo.
  - **Focus:** Configuring Next.js with TypeScript and ensuring it works within the Nx structure.
  - **Resources:** [Nx Next.js Plugin](https://nx.dev/packages/next)

- [ ] **Day 3: Setting Up NestJS Backend**
  - **Task:** Set up NestJS within the Nx monorepo.
  - **Focus:** Creating basic NestJS modules, controllers, and services for managing content such as work experience, summaries, and projects.
  - **Resources:** [NestJS Documentation](https://docs.nestjs.com/)

- [ ] **Day 4: Styling with Tailwind CSS**
  - **Task:** Set up Tailwind CSS with Next.js within the Nx monorepo.
  - **Focus:** Applying styles using Tailwind CSS, creating responsive layouts.
  - **Resources:** [Tailwind CSS Documentation](https://tailwindcss.com/docs)

- [ ] **Day 5: Introduction to Shadcn Components**
  - **Task:** Integrate Shadcn components with Next.js and Tailwind CSS.
  - **Focus:** Using Shadcn components for UI consistency and styling.

- [ ] **Day 6: Building Basic Portfolio Management Backend with NestJS**
  - **Task:** Implement CRUD operations for managing portfolio content in NestJS.
  - **Focus:** Controllers, services, TypeORM entities.

- [ ] **Day 7: Frontend Integration with Portfolio Management**
  - **Task:** Connect the frontend with the NestJS backend to display and manage portfolio content.
  - **Focus:** API integration, state management.

### Week 2: Building Core Features

- [ ] **Day 8: Adding User Authentication with AWS Cognito**
  - **Task:** Set up AWS Cognito for authentication and integrate it with the frontend and backend.
  - **Focus:** User login, registration, and authentication.
  - **Resources:** [AWS Cognito Documentation](https://docs.aws.amazon.com/cognito/index.html)

- [ ] **Day 9: Node.js Utility for PDF Conversion**
  - **Task:** Develop a Node.js service to convert HTML resume templates to PDF.
  - **Focus:** HTML to PDF conversion, unique URI generation.

- [ ] **Day 10: Integrating PDF Generation with Frontend**
  - **Task:** Integrate the PDF generation service with the frontend to allow users to download their resumes.
  - **Focus:** Frontend API calls, file downloads.

- [ ] **Day 11: Setting Up GitHub Actions for Static Resume Updates**
  - **Task:** Configure GitHub Actions to run on every release and update the static resume file.
  - **Focus:** Automating resume updates, CI/CD pipeline.
  - **Resources:** [GitHub Actions Documentation](https://docs.github.com/en/actions)

- [ ] **Day 12: Setting Up Docker for Deployment**
  - **Task:** Create Dockerfiles for the frontend, backend, and utilities.
  - **Focus:** Containerizing the application for consistent deployment.
  - **Resources:** [Docker Documentation](https://docs.docker.com/get-started/)

- [ ] **Day 13: Deploying to AWS**
  - **Task:** Deploy the Docker containers to AWS.
  - **Focus:** Setting up AWS infrastructure, deploying containers, configuring environment variables.
  - **Resources:** [AWS Deployment Guide](https://aws.amazon.com/getting-started/hands-on/deploy-react-app-cicd-amplify/)

### Week 3: Final Touches and Deployment

- [ ] **Day 14: Final Testing and Documentation**
  - **Task:** Conduct thorough testing of the application and write comprehensive documentation.
  - **Focus:** End-to-end testing, API documentation, user guides, deployment checklist.
  - **Resources:** [API Documentation Tools](https://swagger.io/), [Testing Strategies](https://reactjs.org/docs/testing.html), [NestJS Testing](https://docs.nestjs.com/fundamentals/testing)

- [ ] **Day 15: Deployment and Monitoring**
  - **Task:** Ensure deployment is stable and set up monitoring for the application.
  - **Focus:** Deployment verification, setting up monitoring tools.
  - **Resources:** [AWS CloudWatch](https://aws.amazon.com/cloudwatch/), [Docker Monitoring](https://docs.docker.com/config/containers/runmetrics/)

### Final Features

**Portfolio Management:**
- CRUD operations for portfolio content.
- Displaying portfolio details on the website.
- Integrating with NestJS for content management.

**Resume Download:**
- HTML to PDF conversion for resumes.
- Unique URI for PDF download.
- API integration for seamless resume updates.

**Static Resume Updates:**
- Automating resume updates using GitHub Actions.
- Storing updated resumes as static files.

**Authentication:**
- AWS Cognito for secure authentication.
- User login and registration.

**Deployment:**
- Dockerized containers for consistent deployment.
- Hosted on AWS for scalability and reliability.

