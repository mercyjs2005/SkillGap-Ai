# SkillGap AI

**Live demo:** [skillgap-hazel.vercel.app](https://skillgap-hazel.vercel.app/)

A full-stack preparation platform for students and early-career developers. It brings together resume analysis, skill-gap reporting, role matching, learning paths, coding and scenario assessments, and project interview practice.

## Features

- Resume analysis with structured feedback and missing-keyword suggestions
- Job-description matching and personalized skill-gap reports
- Readiness dashboard and learning path
- Coding and scenario assessments with AI feedback
- Project-based interview practice
- Authentication, profile settings, assessment history, and admin tools

## Tech stack

- Next.js App Router, React, TypeScript, Tailwind CSS
- PostgreSQL with Prisma
- Gemini and Groq APIs

## Run locally

1. Install dependencies with `pnpm install`.
2. Copy `.env.example` to `.env` and fill in the values.
3. Generate the Prisma client and initialize the database:

   ```sh
   pnpm exec prisma generate
   pnpm exec prisma db push
   ```

4. Start the development server with `pnpm dev`.

## Environment variables

See `.env.example` for the required database, JWT, and AI provider configuration. Use a long, unique `JWT_SECRET`; do not commit your local `.env` file.

## Group project credit

This repository carries forward the collaborative Skillgap group project developed with [@prakharsf27](https://github.com/prakharsf27). The source project is [prakharsf27/Skillgap](https://github.com/prakharsf27/Skillgap).

