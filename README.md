Customer Support Ticketing Portal
A role-based web application where customers can raise support tickets, agents can respond, and admins can monitor all activity in a clean, Amazon-style UI.

Features
Customer dashboard to create tickets with title, description, category, and priority.
Ticket list with clear badges for status and priority.
Agent dashboard to view open tickets and send replies.
Admin dashboard to see all tickets across users and statuses.
Responsive layout with centered cards, shared header, and footer.
​

Tech Stack
React (functional components, hooks) for the frontend.
CSS with flexbox and grid for responsive layouts.
JavaScript (ES6+) for client-side logic.
​

Installation / Setup
option 1:Clone the repository:
git clone https://github.com/your-username/your-repo-name.git
Navigate into the project folder:
cd your-repo-name

Install dependencies:
npm install

Start the development server:
npm start


Option 2: Download ZIP and extract

Go to the GitHub repository page and click the green Code button.
Click Download ZIP to download the project as a compressed file.
Extract (unzip) the downloaded file on your computer.​
​Open a terminal in the extracted folder.
Run npm install and then npm start to launch the app.


Usage
Open the app in your browser (usually at http://localhost:3000).
Use the customer view to create new support tickets and see their status.
​Switch to the agent view to read tickets and send replies.
Use the admin view to monitor all tickets by status and priority.
​Add screenshots of each dashboard (customer, agent, admin) to make this section clearer.


Project Structure
src/components – Reusable UI components (forms, ticket cards, header, footer).
​src/pages – Page-level components for customer, agent, and admin dashboards.
​src/styles.css – Global styling and layout definitions.
customer-support-ticketing-portal/
├── public/                 # Static assets and index.html
├── src/                    # Application source code
│   ├── components/         # Reusable UI components (header, footer, ticket cards, forms)
│   ├── pages/              # Page components (Customer, Agent, Admin dashboards, Auth pages)
│   ├── hooks/              # Custom React hooks (if any, e.g., auth or data hooks)
│   ├── utils/              # Helper functions and constants
│   ├── styles.css          # Global styles and layout
│   ├── App.js              # Main application component and routing
│   └── index.js            # React entry point
├── package.json            # Project metadata and dependencies
├── README.md               # Project documentation
└── .gitignore              # Files and folders ignored by Git
​

Contributing
This project is primarily for learning and practice. If you’d like to suggest improvements, feel free to open an issue or submit a pull request.
