# TangMoc v3 Next.js Project Documentation

## Project Structure

```
project-folder/
├── public/            # Static files
├── src/               # Source files
│   ├── components/    # React components
│   ├── pages/         # Next.js pages
│   ├── styles/        # Global styles
│   └── utils/         # Utility functions
├── package.json       # Project metadata and dependencies
└── Dockerfile         # Docker configuration
```

## Installation Guide

1. **Clone the repository**:
   ```bash
   git clone https://github.com/thohdztk8/deploye_demo.git
   cd deploye_demo
   ```
2. **Install dependencies**:
   ```bash
   npm install
   ```
3. **Start the development server**:
   ```bash
   npm run dev
   ```
   The application will be available at `http://localhost:3000`.

## Features
- Server-side rendering and static site generation
- API routes for backend functionality
- File-system based routing
- Built-in CSS and Sass support
- Support for TypeScript

## Docker Setup

1. **Build the Docker image**:
   ```bash
   docker build -t tangmoc-app .
   ```
2. **Run the Docker container**:
   ```bash
   docker run -p 3000:3000 tangmoc-app
   ```
   Access the application at `http://localhost:3000`.

## Deployment Instructions for Vercel

1. **Sign in to Vercel** and create a new project.
2. **Import your GitHub repository** containing the TangMoc v3 project.
3. **Configure the build settings** if necessary (default settings usually work).
4. **Deploy your project**. Once deployed, you will get a live URL for your application.