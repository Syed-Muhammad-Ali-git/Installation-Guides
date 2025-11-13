# Installation Guides

This repository contains step-by-step guides for installing and using various web development tools and frameworks. Below is a summary of each guide file, including what it contains, its purpose, and how to follow the instructions.

## 1. next-js-guide.txt

### What it contains:

- Instructions for installing the latest version of Next.js using `npx create-next-app-latest`.
- Explanation of the default options, which include TypeScript, Tailwind CSS, ESLint, app folder directory, and latest versions of dependencies.
- Note that Next.js is an advanced version of React.js, so learning React.js first is recommended.
- Advanced features of Next.js:
  - File-based routing using `page.tsx` files.
  - Using `Link` from `next/link` for navigation instead of `<a>` tags.
  - Creating `not-found.tsx` for 404 pages.
  - Creating `error.tsx` for error pages.
  - Using `loader.tsx` for loading states.
  - Nested routing with dynamic folders like `[avator]`.
- Emphasis on case sensitivity in file and folder names.

### Purpose:

To guide users on setting up a Next.js project and understanding its key features for building advanced React applications.

### How to follow:

1. Run `npx create-next-app-latest` in the terminal.
2. Choose the default option when prompted.
3. Learn React.js basics if new to it.
4. Use the advanced features as described for routing, error handling, and nested pages.

## 2. nextjs-deploy-without-repo.txt

### What it contains:

- Guide to deploy a Next.js project on Vercel directly from local machine without GitHub.
- Prerequisites: Node.js installed, Vercel account.
- Steps:
  1. Install Vercel CLI globally: `npm install -g vercel`.
  2. Login to Vercel: `vercel login`.
  3. Navigate to project folder.
  4. Run `vercel` to deploy, answering prompts.
  5. Get the live URL.
- Optional: Redeploy with `vercel --prod`.
- Benefits: No GitHub required, full Next.js support, free hosting.

### Purpose:

To enable quick deployment of Next.js applications to Vercel without needing a Git repository.

### How to follow:

1. Ensure Node.js is installed and you have a Vercel account.
2. Install Vercel CLI and login.
3. In your Next.js project directory, run `vercel` and follow the prompts.
4. Access your deployed app via the provided URL.
5. For updates, run `vercel --prod` in the project folder.

## 3. React-js-installation-guide.txt

### What it contains:

- Step-by-step guide to install React.js (version 19) using Vite.
- Steps:
  1. Visit the Vite guide website.
  2. Run `npm create vite@latest myfolder` in cmd.
  3. Select React and choose JavaScript or TypeScript.
  4. Navigate to the created folder and run `npm install`.
  5. Run `npm run dev` to start the development server.
- Review of all steps.

### Purpose:

To help users quickly set up a new React.js project using Vite as the build tool.

### How to follow:

1. Open command prompt.
2. Run `npm create vite@latest myfolder` (replace 'myfolder' with your desired folder name).
3. Select React and your preferred language.
4. Change directory to the new folder: `cd myfolder`.
5. Run `npm install` to install dependencies.
6. Run `npm run dev` to start the app and open the provided link in browser.

## 4. tailwind-installation-guide-html.txt

### What it contains:

- Guide to install Tailwind CSS version 4 with CLI for HTML projects.
- Steps:
  1. Create `index.html` and run `npm init -y`.
  2. Install Tailwind: `npm install tailwindcss @tailwindcss/cli`.
  3. Create `src/input.css` with `@import "tailwindcss";`.
  4. Run the watch command: `npx @tailwindcss/cli -i ./src/input.css -o ./src/output.css --watch`.
  5. Link `output.css` in `index.html`.
  6. Test with sample Tailwind classes.
  7. Ensure the watch is running (look for "done in 1ms" messages).
  8. Add a build script in `package.json` for convenience.

### Purpose:

To set up Tailwind CSS for styling HTML projects using the CLI, enabling utility-first CSS without a framework.

### How to follow:

1. Create an `index.html` file.
2. Initialize npm: `npm init -y`.
3. Install Tailwind: `npm install tailwindcss @tailwindcss/cli`.
4. Create `src/input.css` and add `@import "tailwindcss";`.
5. Run the watch command to generate `output.css`.
6. Link `output.css` in `index.html`.
7. Add Tailwind classes to HTML elements and open in browser.
8. Optionally, add the build script to `package.json` for easier running.
