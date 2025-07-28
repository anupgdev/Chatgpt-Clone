# Next.js Chat Application with Supabase

This is a modern chat application built with Next.js 14 and Supabase, featuring real-time messaging and authentication.

## Tech Stack

- [Next.js 14](https://nextjs.org/) - React framework
- [Supabase](https://supabase.com/) - Backend and Authentication
- [Tailwind CSS](https://tailwindcss.com/) - Styling
- [TypeScript](https://www.typescriptlang.org/) - Type safety

## Getting Started

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```

3. Set up your environment variables:
   - Copy `.env.example` to `.env.local`
   - Fill in your Supabase project credentials:
     - `NEXT_PUBLIC_SUPABASE_URL`: Your Supabase project URL
     - `NEXT_PUBLIC_SUPABASE_ANON_KEY`: Your Supabase project anonymous key
     - `SUPABASE_SERVICE_ROLE_KEY`: Your Supabase service role key

4. Run the development server:
   ```bash
   npm run dev
   ```

5. Open [http://localhost:3000](http://localhost:3000) in your browser

## Deployment on Vercel

1. Push your code to a Git repository
2. Import your project to Vercel
3. Add your environment variables in the Vercel project settings
4. Deploy!

## Environment Variables

The following environment variables are required:

- `NEXT_PUBLIC_SUPABASE_URL`: Your Supabase project URL
- `NEXT_PUBLIC_SUPABASE_ANON_KEY`: Your Supabase project anonymous key
- `SUPABASE_SERVICE_ROLE_KEY`: Your Supabase service role key
- `NEXT_PUBLIC_SITE_URL`: Your site URL (http://localhost:3000 for development)

## Features

- Real-time chat functionality
- User authentication with Supabase
- Modern UI with Tailwind CSS
- Type-safe development with TypeScript
- Server-side rendering with Next.js

## License

MIT
