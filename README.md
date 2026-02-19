Movit App — AI-Assisted UI Prototype
🔗 Live App Link

👉 https://fluffy-capybara-pjwpjrv4qg45h9679-8080.app.github.dev/

🧠 Objective

The objective of this project is to develop a high-fidelity mobile application interface for the Movit app using AI-Assisted Development.
The application focuses on movie browsing and discovery.
No backend was implemented — mock data was used.

📐 App Scope (The “What”)

The Movit application includes 4 main screens:

Login Screen

Home / Feed Screen

Movie Detail Screen

Profile / Settings Screen

⭐ Complex Component Included

Horizontal movie carousel

Card-based layout

Reusable movie component

Navigation between screens

🧩 Technology Used

React Native (Expo)

JavaScript

Mock JSON Data

AI Tools (ChatGPT)

⚙️ The Process (The “How”)

AI tools were used to generate more than 50% of the code, including layouts, styling, and mock data.

However, the student manually:

Reviewed generated code

Split large components into reusable files

Fixed layout issues

Adjusted spacing and typography

Improved accessibility and responsiveness

Debugged navigation errors

This demonstrates a Human-in-the-Loop process where the student acts as the Architect and AI as the Laborer.

🧱 Phase 1 — Atomic Design (Planning)

Before using AI, the UI was broken down into components:

🔹 Atoms

Buttons

Text fields

Icons

Images

🔹 Molecules

Movie Card

Profile Header

Input Form

Navigation Tabs

🔹 Organisms

Movie Carousel

Feed List

Detail Layout

🤖 Phase 2 — Iterative Prompting

Instead of asking AI for entire screens, smaller components were generated first.

✅ Best Prompt #1

Act as a mobile UI designer.
Create a reusable MovieCard component in React Native.
It should display movie poster, title, rating, and release year.
The card should have rounded corners and a shadow effect.
Use a dark theme suitable for a movie app.

✅ Best Prompt #2

Create a horizontal carousel using FlatList in React Native.
Each item should use the MovieCard component.
Enable smooth scrolling and spacing between cards.

✅ Best Prompt #3

Design a Login Screen for a movie app using React Native.
Include email and password inputs, a login button, and a modern dark theme layout.
Ensure it is responsive and centered vertically.

❌ Failed Prompt

Make a full movie app home screen.

❗ Why it failed:

Generated messy code

Too large and unstructured

No reusable components

Hard to maintain

This showed that AI performs better with specific component-level prompts.

🧽 Phase 3 — Human Polish (Manual Refinement)

AI-generated code required manual improvements:

Standardized padding to 16px

Adjusted font sizes for readability

Fixed overflow on small screens

Improved color contrast

Cleaned redundant code

Organized files into proper structure
