#  AI-Based Biometric Voting System
(NOTE: ALL THE SUPPORTING DOCUMENTS AND LINKS ARE ATTACHED AT THE END OF THE FILE)

An advanced and secure voting platform using biometric authentication (fingerprint + face recognition) to ensure transparency, speed, and efficiency in elections. Designed to eliminate fraud, reduce manual effort, and deliver real-time results.

##  Features

-  Biometric Verification (Fingerprint + Face)
-  Fraud-Proof Voting
-  Vote in Under a Minute
-  Results in Less Than an Hour
-  No Booth Slips or Manual ID Checks
-  Digital Vote Logs for Transparency
-  Constituency-wise Candidate Upload by Officials
-  Massive Reduction in Time & Government Resource Usage

##  Why This System?

| Aspect                     | Traditional Voting System                             | AI-Based Voting System                         |
|----------------------------|--------------------------------------------------------|------------------------------------------------|
| Booth Setup & Slips        | Takes 2–4 months; manual slip distribution            | Not required                                   |
| Voting Time per Person     | 4–7 minutes                                           | 45 seconds – 1 minute                          |
| Result Declaration         | After 1 month                                         | Within an hour                                 |
| Workforce Usage            | Involves large-scale staff and resource deployment   | Minimal human effort, tech-driven process      |
| Security & Fraud           | Prone to impersonation, fake votes                   | Tamper-proof via biometric authentication      |
| Transparency               | Limited traceability                                 | Full digital logs and traceable voting records |

##  Technologies Used

- **Frontend**: React.js / Vite
- **Backend**: Node.js / Express / FastAPI
- **Database**: Supabase 
- **Biometrics**: Fingerprint Sensor, Face Recognition APIs
- **AI/ML**: Facial match confidence, vote fraud detection
- **Cloud Deployment**: Render

TEAM NAME - QUANTUM SPARKS Checkpoint 1 – Tasks Completed:
Folder structure initialized:
client/ for frontend (React + Vite)
Project initialized using npm init -y
Basic config files added (vite.config.ts, tailwind.config.ts)
Installed frontend and backend dependencies
Created initial components (App.tsx)
Git repository initialized and first commit made

Checkpoint 2 – Tasks Completed:
Added essential project metadata and configuration:
package.json
package-lock.json
README.md
FREE_TECHNOLOGIES_INTEGRATED.md
Documented the list of integrated technologies
Described setup steps and project overview in README.md
Committed all above files as part of second milestone

Checkpoint 3 – Tasks Completed:
Completed and committed all key frontend components:
admin/ – components for admin login and dashboard
public/ – user-side components
ui/ – reusable UI elements
voting/ – core voting interface
Added logic components:
age-verification.tsx
language-provider.tsx and language-selector.tsx
recaptcha.tsx for bot prevention
Frontend logic is now modular, responsive, and ready to be integrated with backend and Ethereum logic

Checkpoint 4 – Tasks Completed:
Integrated essential custom React hooks:
use-admin-auth, use-citizens, use-language, use-mobile, and use-toast
Added reusable blockchain and client utilities in lib/:
blockchain.ts for Ethereum functions
supabaseClient.ts for database interaction
queryClient.ts for React Query setup
utils.ts for general helpers
Created all core frontend pages:
Admin Dashboard & Login
Public Portal & Voting Portal
Not Found / 404 fallback
Frontend now fully structured and logic-ready

Checkpoint 5 – Tasks Completed:
Database structure and schema finalized
Added migration SQL file:
0000_whole_argent.sql defining all table structures
Included Drizzle/ORM meta data:
Snapshot and migration journal JSON files under migrations/meta/
Database now ready for integration with backend APIs and frontend components

Checkpoint 1 DAY 2 – Tasks Completed:
Created and structured the complete backend in server/ folder
Integrated database connection logic via db.ts (e.g., Supabase)
Set up index.ts as the main server entry point
Defined API routes in routes.ts for admin actions, vote handling, etc.
Added storage.ts to manage file upload or related storage features
Configured vite.ts for dev-server support and environment setup
Prepared the server to handle real-time requests from frontend
Backend is now ready to be connected with the frontend and database

Checkpoint 2 Day 2- Tasks Completed:
Built the complete frontend with the guidance of the wireframe we made on Day 1.
Added core shared files used by both frontend and backend:
languages.ts: language options and display mapping
schema.ts: shared data types and form validation schema
voting-utils.ts: helper logic for vote formatting, checks, etc.
These files improve code reusability, consistency, and scalability across the app

Checkpoint 3  Day 2 -Tasks Completed:
 Connected Supabase database with the project using db.ts
 Verified data flow from frontend to Supabase through API calls
 MVP version of the project is now running successfully on local
 User login, voting, recaptcha, and Ethereum hash generation are working
 Data is stored in Supabase tables created from migrations
 Environment setup with .env variables is complete and secure

 CHECKPOINT 4  Day 2 -Tasks Completed:
Deployment Achieved:
Project successfully deployed on Render
Connected to Supabase database in production
Frontend and backend build processes completed
.env keys securely configured
Full flow tested live: user registration, voting, hash verification, DB write
MVP now live and publicly accessible

# The supporting documents/links

1. MVP Link

https://ai-and-blockchain-based-voting-system.onrender.com

2. MVP Explanation Video

https://drive.google.com/file/d/1L_9yEL8PyceOv2WMLpPFXcx4xERC0wAn/view?usp=drivesdk

3. Wireframes

 Public/Voting Portal - https://app.visily.ai/projects/0b3689d0-b35e-438a-833a-73453880ec7c/boards/1951334/presenter?play-mode=Prototype

Admin Portal - https://app.visily.ai/projects/0e7c2689-d8f0-4f43-a9a2-e263624fd2f0/boards/1951414/presenter?play-mode=Prototype

4. Prototype Performance Report

https://drive.google.com/file/d/1ZukQYZ31XYxDFkGVZzrGWij2J8tF8HZm/view?usp=drivesdk

5. MVP SNAPSHOTS

https://drive.google.com/file/d/1Zw6YqnTxGpK4P5h7PzorbkZVfCuSCHH0/view?usp=drivesdk

6. PPT LINK

https://docs.google.com/presentation/d/1rbye9CFBkj_mtHNsgDT-bd49GE2J_itX/edit?usp=sharing&ouid=105230393775856530307&rtpof=true&sd=true