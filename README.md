This MERN stack project, Talent IQ, is a sophisticated video calling and real-time coding platform designed for technical interviews. 
It integrates several modern services to handle complex features like secure code execution and live video.

1. Core Frontend Stack
React: The functional foundation of the UI.
Tailwind CSS & daisyUI: Used for rapid, responsive styling. The project features a dark, high-contrast theme suitable for code editors.
TanStack Query (React Query): Manages server state, providing efficient data fetching, caching, and synchronization between the client and the Node.js API.
Lucide React: Provides the sleek iconography used throughout the dashboard and editor.

2. Backend & Database
Node.js & Express: Powers the API layer, handling routing and middleware.
MongoDB: Stores user profiles, interview history, and a library of practice problems.
Clerk Auth: Handles the entire authentication flow. It is synced with the database using Webhooks to ensure user data stays consistent across services.

3. Specialized Video & Collaboration Tools
GetStream: * Video SDK: Powers the 1-on-1 video calls, screen sharing, and recording features.
Chat SDK: Enables the real-time messaging sidebar during interviews.
Monaco Editor: The same engine that powers VS Code is embedded here to provide syntax highlighting and a native coding experience for the candidate.
Isolated Code Execution: When a user runs code, it is sent to a secure, sandboxed environment to prevent malicious scripts from affecting the server.

4. Advanced Infrastructure
Inngest: Manages background jobs and asynchronous workflows (e.g., processing interview results or sending automated feedback) without blocking the main thread.
CodeRabbit: An AI-powered tool used during the development phase to perform automated Pull Request (PR) analysis and suggest code optimizations.
Sevalla: The hosting platform used for the Deployment phase, chosen for its ease of use with full-stack JavaScript applications.



Feature,Technology Used
Real-time Sync,WebSockets (via Stream)
Async Tasks,Inngest
Database Ops,Mongoose (ODM)
UI Components,daisyUI
Auth Strategy,JWT / Session Management via Clerk


✨ Highlights:  
🧑‍💻 VSCode-Powered Code Editor  
🔐 Authentication via Clerk  
🎥 1-on-1 Video Interview Calls Powered by Stream Video  
🧭 Dashboard with Live Stats  
🔊 Mic & Camera Toggle, Screen Sharing & Recording  
💬 Real-time Chat Messaging by Stream
⚙️ Secure Code Execution in Isolated Environment
🎯 Auto Feedback — Success / Fail based on test cases
🎉 Confetti on Success + Notifications on Fail
🧩 Practice Problems Page (solo coding mode)
🔒 Room Locking — allows only 2 participants
🧠 Background Jobs with Inngest (async tasks)
🧰 REST API with Node.js & Express
⚡ Data Fetching & Caching via TanStack Query
🤖 CodeRabbit for PR Analysis & Code Optimization
🧑‍💻 Git & GitHub Workflow (branches, PRs, merges)
🚀 Deployment on Sevalla (free-tier friendly)
