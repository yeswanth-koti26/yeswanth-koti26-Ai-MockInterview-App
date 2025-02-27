[Link to the Application](https://yeswanth-koti26-ai-mock-interview-app.vercel.app/)

![image](https://github.com/user-attachments/assets/1dbd2777-d6d6-48bb-86c9-30aecb65a822)


This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.js`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

# AI Interview Mocker

## **Project Overview**
**AI Interview Mocker** is a Next.js-based web application designed to simulate AI-powered interview experiences. It utilizes modern web technologies, including **Clerk** for authentication, **Google Generative AI** for AI-driven responses, and **Drizzle ORM** with **NeonDB** for database management.

## **Tech Stack**
- **Frontend:** Next.js 14, React 18
- **Styling:** Tailwind CSS
- **Authentication:** Clerk
- **Database:** Neon Database (PostgreSQL) with Drizzle ORM
- **AI Integration:** Google Generative AI
- **Voice Features:** `react-hook-speech-to-text`, `react-webcam`
- **UI Components:** Radix UI, Lucide Icons
- **Others:** `moment`, `uuid`, `clsx`

## **Getting Started**

### **1. Clone the Repository**
```bash
 git clone <repository_url>
 cd AI-Interview-mocker-main
```

### **2. Install Dependencies**
```bash
 npm install
```

### **3. Configure Environment Variables**
Create a `.env.local` file in the root directory and add the following variables:
```bash
 NEXT_PUBLIC_CLERK_FRONTEND_API=<your-clerk-api-key>
 DATABASE_URL=<your-neon-database-url>
 GOOGLE_AI_API_KEY=<your-google-gen-ai-key>
```

### **4. Run the Development Server**
```bash
 npm run dev
 # or
yarn dev
 # or
pnpm dev
 # or
bun dev
```
Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

### **5. Build & Start for Production**
```bash
 npm run build
 npm run start
```

### **6. Database Setup**
- **Apply Database Migrations**
  ```bash
  npm run db:push
  ```
- **Open Drizzle Studio for Database Management**
  ```bash
  npm run db:studio
  ```

## **Git Commands for Cloning & Working with the Repository**
```bash
 # Clone the repository
 git clone <repository_url>

 # Navigate to the project directory
 cd AI-Interview-mocker-main

 # Create a new branch (if needed)
 git checkout -b feature-branch

 # Add & commit changes
 git add .
 git commit -m "Your commit message"

 # Push changes
 git push origin feature-branch
```


## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.

## **License**
This project is licensed under the **MIT License**.
