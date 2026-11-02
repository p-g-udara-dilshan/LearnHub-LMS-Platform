🎓 LearnHub — Learning Management System (LMS)
A React and TypeScript learning management system prototype focused on modern educational user interfaces.

Project status: Personal development project · June 2025 · Not currently live
Preview note: The screenshot shows a UI concept; on-screen statistics and ratings are illustrative sample content, not verified platform usage data.

📖 Overview
LearnHub explores the design of a digital learning platform with separate administrator and student experiences. The project is centered on clean interface design, reusable React components, TypeScript, responsive layouts, and common learning-management workflows.

It is presented as a development prototype, not as a production deployment.
✨ Project scope and interface concepts
The following workflows are described in the project materials. Their end-to-end implementation cannot be independently verified from the currently published repository snapshot.
👨‍🏫 Administrator experience
- Course creation, content organization, and course management views
- Student enrollment management workflows
- Dashboard and learning-activity overview concepts
👩‍🎓 Student experience
- Course discovery, learning materials, and video lesson interfaces
- Quiz and immediate-feedback workflows
- Learning-progress visualization
- Discussion forum and community-interaction concepts
- Role-oriented navigation and account experiences
🎨 User interface
- Responsive layouts for different screen sizes
- Reusable, component-oriented frontend structure
- Accessible, consistent page layout and navigation as design goals
🛠️ Technology stack
Category	Tools
UI library	React 18
Language	TypeScript
Styling	Tailwind CSS
Development/build tooling	Vite
Client-side routing	React Router
Icons	Lucide React


These technologies are listed in the published package.json. The public snapshot does not show a backend or persistent database implementation.
📸 Screenshots
Landing page

UI preview from the project. Example ratings, learner counts, and success metrics are placeholder content.
📂 Repository status
At the time this README was prepared, the public repository contained project configuration files (including package.json, Vite, Tailwind, and TypeScript configuration) and documentation, but the application src/ directory was not visible. For that reason, a complete working build cannot be verified from the public repository alone.

If you have the original application source code, add it to the repository before presenting this as a runnable project. Do not upload secrets, .env credentials, or real user information.
💻 Run locally (after adding the application source)
git clone https://github.com/Udara-Dilshan/learnhub-lms-platform.git
cd learnhub-lms-platform
npm install
npm run dev
These commands describe the Vite setup but may not launch the application until missing frontend source files are included. Check the console output and npm run build after restoring the code.

🚧 Suggested next steps
- [ ] Add the application source (src/) and any required public assets.
- [ ] Document which features work end-to-end versus which are UI demonstrations.
- [ ] Add screenshots of student and admin views, if available.
- [ ] Add application setup, test instructions, and demo data guidance.
- [ ] Verify accessibility, responsiveness, authentication behavior, and error handling.
- [ ] Replace sample statistics with clearly labeled demo data or real verified figures.
- [ ] Update the deployment URL only when an accessible, working demo is available.
👤 Author
Udara Dilshan
GitHub · LinkedIn
This repository documents a personal learning and frontend development project. Features and visuals should not be interpreted as evidence of a live educational service.
