🐺 CS-360: Mobile Architecture & Programming
🌙 SmartInventory: Mobile Database-Driven Foundation
📌 Overview
Repository Purpose: Contains projects and assignments for CS-360: Mobile Architecture & Programming at SNHU.

Application Goal: Develop SmartInventory, a mobile app designed to bridge the gap between physical warehouse inventory and digital records.

Core Problem Solved: Eliminates the need for manual stock audits in environments with poor connectivity via an offline-first interface and automated local notifications.

🎯 Course Competencies
CS-30421: Apply mobile application development principles and best practices.

CS-30422: Apply user-centered design principles and industry standards.

CS-30423: Develop and launch a fully functional mobile application.

🛠 Tech Stack & Tools
Language: Java.

IDE: Android Studio.

Database: SQLite/Room.

Architecture: Model-View-ViewModel (MVVM).

Testing Device: Samsung (SM-A176U) for debugging and verification.

📂 Project Highlights
CS360 M2MP1 (MWood).docx: Proposed initial application, identified key user roles, and established offline functionality requirements.

CS360_ProjectOne_Option1_MWood.docx: Defined technical architecture, data flow, and background observer logic for stock monitoring.

MatthewWood.Option1.InventoryAPP: Project Two implementation of core user components and mobile data architecture in Android Studio.

SmartInventoryMobile: Project Three launch plan, deployment strategy, and code maintenance commitment.

CS360 M7 P3Option 1 (MWood).docx: Finalized documentation detailing value proposition for stakeholders.

📖 Module Eight Reflection
App Requirements and Goals: The SmartInventory app was designed to provide a reliable, offline-first mobile solution for warehouse workers. The primary goal was to bridge the gap between physical inventory on the floor and digital records, addressing the need for accurate, real-time stock tracking in environments with poor Wi-Fi or cellular service.

User-Centered UI: Necessary features included a login/registration screen for security, a grid-based dashboard for quick status scanning, and automated background notification logic. Designs were successful because they utilized high-contrast text and 48dp x 48dp touch targets to ensure usability in harsh warehouse lighting and facilitate efficient, one-handed operation.

Coding Approach: I utilized the Model-View-ViewModel (MVVM) architecture to decouple the UI from database logic, ensuring the interface remained responsive during background operations. This strategy of separating concerns is highly applicable to future projects to maintain stable, testable codebases.

Testing and Functionality: Testing was conducted on a Samsung (SM-A176U) device to verify app behavior in a real-world environment. This process is critical for ensuring that hardware constraints do not impede app performance, and it revealed the necessity of robust background observers for accurate inventory monitoring.

Innovation and Challenges: I had to innovate to overcome the limitations of offline connectivity by hardcoding the zero-count notification trigger directly into a background database observer. This provided the necessary automation for Procurement Specialists without requiring a cloud-based sync.

Successful Demonstration of Skills: I was particularly successful in the implementation of the notification subsystem. This component effectively demonstrated my ability to integrate background tasks with local database management to solve specific operational efficiency problems.

⚖️ Academic Integrity & AI Disclosure
Academic Purpose: Completed for SNHU academic purposes.

AI Usage: Generative AI tools used as supplemental aids for brainstorming and formatting, per university policy.

🚀 Getting Started
Clone Command: git clone https://github.com/ShAd0w-R3BeL/CS-360.git

🌙 Contact
Name: Matthew Wood

Email: matthew.wood16@snhu.edu

LinkedIn: Matthew R. Wood
