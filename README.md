# MyCoach app

An AI-powered web app that transforms your New Year’s resolution into a SMART (Specific, Measurable, Achievable, Relevant, Time-bound) version.

## What it does  
- User enters a resolution.  
- Back-end calls Google Gemini (via `@google/genai`) to enhance it.  
- Front-end (React/Next.js) displays the improved resolution in Markdown.  
- Minimal UI: textarea → button → result.  
- Ready for deployment on Vercel.

## Tech Stack  
- Front-end: React + Next.js  
- Back-end: Node.js / Express (via Next.js API routes)  
- AI: Gemini model (`gemini-2.5-flash`)  
- Deployment: Vercel serverless functions  
