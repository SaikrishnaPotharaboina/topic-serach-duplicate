# ⚠️ NOTE  
This is a **duplicate project** created only for submission purposes.  
The **original full project (with complete code)** is already available in my GitHub main repository.  
I used this duplicate because of **file size / MB issue**, but **both projects work the same** and give the **same output**.  
This duplicate contains a readable version of the code for checking.

###
TopicSearch
Overview
TopicSearch is a React-based searching component that displays a list of topics with live filtering. It includes visible topics (shown by default) and hidden topics (only appear when searched). The UI is fully styled using inline CSS.

Features
Live search filtering
Visible and hidden topics
Case-insensitive matching
Inline CSS styling
"No topics found" message
Clean and responsive UI
Project Structure
src/ App.js TopicSearch.jsx index.js

public/ index.html

package.json
README.md

Getting Started
Prerequisites
Node.js
npm or yarn
Installation
Clone the repository: git clone

Enter the project folder: cd

Install dependencies: npm install

Run the App
npm start

The app will open at: http://localhost:3000/

How It Works (Step-by-Step)
The user types inside the search input.
useState stores the search text.
Visible topics + hidden topics are combined.
The filter function checks all topics for matches.
Matching topics are displayed dynamically.
If no matches exist, a "No topics found" message appears.
Code Explanation
useState manages the search input.
visibleTopics contains topics shown on load.
hiddenTopics contains topics revealed only on search.
combinedTopics merges both lists.
filter() performs case-insensitive search.
Inline CSS provides all UI styling.
Conditional rendering displays results or no-results message.
Customization
You can modify:

Visible topics list
Hidden topics list
Inline styles
Filtering logic
UI layout
Examples
Input: "quantum" → Quantum Computing
Input: "robotics" → Robotics Engineering
Input: "xyz" → No topics found

Deployment (Optional)
You can deploy using:

GitHub Pages
Netlify
Vercel
Author
Saikrishna GitHub: https://github.com/SaikrishnaPotharaboina

License
MIT License
