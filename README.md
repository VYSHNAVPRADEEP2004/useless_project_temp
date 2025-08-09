# [Project Name] 🎯


## Basic Details
### Team Name: [Name]


### Team Members
- Team Lead: VyshnavPradeep - Cochin University College Of Engineering Kuttanad
- Member 2: SooryaAP - Cochin University College Of Engineering Kuttanad


### Project Description
Our Project is a useless os called Turmoil OS that is used to prank the user who uses it.
Composed of annoying features and demotivating elements for the user.
This project is a cross-platform desktop application built using Electron.js.  
It uses standard web technologies (HTML, CSS, JavaScript) for the user interface while leveraging Node.js for backend logic.  
The app structure follows Electron’s separation of processes:
- Main Process (application lifecycle control)
- Renderer Process (UI rendering and user interaction)
- Preload Script (secure communication bridge)
Build scripts for Windows and Linux/macOS automate packaging into installable files.


### The Problem (that doesn't exist)
There is no Operating System that is uses as a prank OS so our operating system will serve the purpose and gives an hilarious experience to the users who uses it.

### The Solution (that nobody asked for)
The solution to the problem is a hilarious operating system that can be used when the boredom strikes the user composed of funny elements
and annoying features

## Technical Details
📦 Technology Stack:
- Framework: Electron.js
- Frontend: HTML (UI layout), CSS (styling), JavaScript (interaction logic)
- Backend: Node.js APIs in Electron main process
- Scripts: 
  - build.bat (Windows build automation)
  - build.sh (Linux/macOS build automation)
- Package Management: npm (package.json, package-lock.json)

🧩 Core Components:
1. main.js:
   - Initializes the app
   - Creates main window
   - Handles lifecycle events (open, close, quit)
2. preload.js:
   - Secure API bridge between frontend and backend
   - Runs before renderer loads
3. uselessos.html:
   - Defines UI structure
4. uselessos.css:
   - Styles the UI
5. uselessos.js:
   - Handles frontend events and UI logic
6. build.bat / build.sh:
   - Packages the application for release

⚙ Application Flow:
1. npm start → Electron starts main process
2. main.js creates app window → loads uselessos.html
3. preload.js injects APIs
4. Renderer process runs uselessos.js for interactivity
5. User interacts → renderer updates UI or calls backend
6. build scripts package for OS-specific distribution

### Technologies/Components Used
For Software:
- Languages used :bat,Shell Script,Java Script,html,css
- Frameworks used: Electron + Node.js
- electron-builder v24.0.0


### Implementation

For Software:

# Installation
npm install
chmod +x *.sh

# Run
npm start

### Project Documentation
For Software:

# Screenshots (Add at least 3)
<img width="1919" height="1022" alt="image" src="https://github.com/user-attachments/assets/4fb80629-bed5-4e38-b90a-90897bf3be2c" />
<img width="1062" height="668" alt="image" src="https://github.com/user-attachments/assets/d86f8739-2ff6-4280-8293-2cfcc48388d3" />
<img width="1015" height="698" alt="image" src="https://github.com/user-attachments/assets/ff75bcd5-93c8-4ead-9f78-53d69318bc3b" />
<img width="1314" height="816" alt="image" src="https://github.com/user-attachments/assets/10ae8823-732a-43a9-b4d9-4ff694811717" />
<img width="1044" height="706" alt="image" src="https://github.com/user-attachments/assets/548f6bbb-7867-4c06-ad7c-b14338824f60" />
<img width="1916" height="924" alt="image" src="https://github.com/user-attachments/assets/51706a7a-4c02-4b31-9382-7d65d9da6b24" />
<img width="986" height="636" alt="image" src="https://github.com/user-attachments/assets/31619a00-193e-4691-a04f-10c741a1a5ab" />
<img width="1635" height="741" alt="image" src="https://github.com/user-attachments/assets/bd896c1e-dfd5-45e9-828a-3158e504c712" />





# Diagrams

uselessproject/
│
├── build.bat              # Windows build script
├── build.sh               # Linux/macOS build script
├── main.js                 # Electron main process (app entry point)
├── preload.js              # Preload script (secure bridge to Node APIs)
├── uselessos.html          # Frontend HTML (UI layout)
├── uselessos.css           # Frontend CSS (styling)
├── uselessos.js            # Frontend JS (UI logic & events)
├── package.json            # Project metadata & npm scripts
├── package-lock.json       # Locked dependency versions
├── README.md               # Documentation
└── .gitignore              # Git ignore rules

main.js → Initializes Electron, creates the application window, and loads uselessos.html.

preload.js → Injects safe APIs into the web page without exposing insecure Node features.

uselessos.html, uselessos.css, uselessos.js → Define the interface, style, and behavior of the app’s UI.

Build scripts (build.bat / build.sh) → Package the app for different operating systems into installable binaries.



## Team Contributions

- VyshnavPradeep : Development of overall structure,functionalities and GUI
- Soorya AP      : Creation of bat,Script files and node files





