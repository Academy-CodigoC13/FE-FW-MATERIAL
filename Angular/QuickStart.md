# Angular Quick Start Guide

This guide will walk you through the process of setting up a new Angular
project.

## Prerequisites

Before you begin, make sure you have the following installed:

- Node.js (v10.13 or later)
- npm package manager

You can verify that you are running the correct version of Node.js and npm by
running the following commands in your terminal:

```bash
node -v
npm -v
```

## Step 1: Install the Angular CLI

The Angular CLI is a command-line interface for Angular. You can install it
globally on your machine with the following command:

```bash
npm install -g @angular/cli
```

## Step 2: Create a new Angular project

Navigate to the directory where you want to create your new project, and run the following command:

```bash
ng new my-angular-app
```
Replace "my-angular-app" with the name you want for your project.

## Step 3: Serve the application
Navigate into your new project's directory:

```bash
cd my-angular-app
```

Then serve the application using the following command:

```bash
ng serve --open
```

## Step 4: Open your app in a browser
You can now navigate to http://localhost:4200/ in your browser to see your new Angular app in action.

## Step 5: Edit your first Angular component
Angular components are the fundamental building blocks of Angular applications. You can find your first component in `src/app/app.component.ts`.

### Next Steps

*Congratulations, you've set up your first Angular application! From here, you can start building out your application. Check out the official Angular documentation for more detailed guides and tutorials.*