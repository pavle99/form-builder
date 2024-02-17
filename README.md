# Form Builder

<img width="1293" alt="Screenshot 1" src="https://github.com/pavle99/form-builder/assets/73827472/f6b46c16-cc09-4dd9-84e2-2b582ac0a7e9">
<img width="1294" alt="Screenshot 2" src="https://github.com/pavle99/form-builder/assets/73827472/4a2cf5a5-9810-45a0-b6c0-e1c67d7ebabc">
<img width="1289" alt="Screenshot 3" src="https://github.com/pavle99/form-builder/assets/73827472/9067c607-8e8b-4809-8ef1-e230bcf67075">

## Table of Contents

- [Introduction](#prerequisites)
- [Link to website demo](#installation)
- [Tech Stack](#tech-stack)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Running the application](#running-the-application)

## Introduction

A responsive fullstack form builder application built using Next.js for frontend and backend, Prisma ORM and Clerk for auth. The application allows you to create and customize forms with a wide variety of fields, both editable and non-editable, as well as publish them and preview their statistics.

## Link to website demo

[FormBuilder](https://form-builder-pavle99.vercel.app/)

## Tech Stack

- [TypeScript](https://www.typescriptlang.org/)
- [Next.js](https://nextjs.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [ShadCN/ui](https://ui.shadcn.com/)
- [Prisma](https://www.prisma.io/)
- [Clerk](https://www.clerk.dev/)
- [DnD-Kit](https://dndkit.com/)

## Prerequisites

Install the following prerequisites:

1. [Node.js 18.17.0 or higher](https://nodejs.org/en/)
2. [Visual Studio Code](https://code.visualstudio.com/download)

## Installation

### 1. Install dependencies

From the **root** directory run:

```bash
pnpm install
``` 

### 2. Create and populate the `.env` file like this:

```bash
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

NEXT_PUBLIC_CLERK_SIGN_IN_URL=
NEXT_PUBLIC_CLERK_SIGN_UP_URL=
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=

POSTGRES_PRISMA_URL=
POSTGRES_URL_NON_POOLING=
```

### 3. Run the Prisma migration

```bash
pnpx prisma migrate dev --name init
```

## Running the application

To run the application, run the following command:

```bash
pnpm run dev
```
