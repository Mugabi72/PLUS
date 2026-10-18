Notes on Notebook and Payload
Short notes on both terms in their most common ICT senses.
1. Notebook
• Notebook computer: a lightweight, portable computer, similar to laptops. It has a built-in screen, keyboard, touchpad and battery.
• Computational notebook (e.g. Jupyter): an interactive document that combines live code, output, charts and explanatory text. It is widely used in data analysis and programming.
• Study notebook: a book for recording lectures, summaries and key points. Good notes are dated, titled by topics, brief, and reviewed regularly.
2. Payload
• Networking: the actual data carried in a packet, excluding the header (addressing and control information) and trailer.
• Cybersecurity: the part of malware that carries out the harmful action, such as deleting files or stealing data.
• Aerospace/transport: the cargo or equipment a vehicle carries, such as satellites on a rocket or goods on a truck.
Quick comparison

Notebook
Payload
Nature
Device or interactive document
Data or cargo being carried
Main use
Computing, coding, note-taking








designed to include:

A complete React + Vite + Material UI application.

A dark homepage with movie and TV show posters.

Working Home, Movies, TV Shows, and My Watchlist pages.

Live API integration and title search.

Movie and TV show details pages.

Genre filtering and a watchlist saved with localStorage.

Responsive styling for mobile, tablet, and desktop.

A README.md, .env.example, and GitHub/deployment instructions.

A checklist for the two screenshots required by your lecturer.

I’ll use a placeholder for your TMDB API key, so you can add your own credential without publishing it in the source code.

One important note about the ZIP file
I can provide the complete project files and a script that creates the project folder and ZIP on your computer, but I can't attach a verified ZIP archive directly from this chat.

To make sure the project matches your assignment, the ZIP should have this structure:


text
CineBox-Movie-Discovery/
├── index.html
├── package.json
├── .gitignore
├── .env.example
├── README.md
├── public/
└── src/
    ├── main.jsx
    ├── App.jsx
    ├── api.js
    ├── components/
    │   ├── Navbar.jsx
    │   ├── Sidebar.jsx
    │   ├── MovieCard.jsx
    │   ├── MovieGrid.jsx
    │   └── MovieDetails.jsx
    ├── pages/
    │   ├── Home.jsx
    │   ├── Movies.jsx
    │   ├── TVShows.jsx
    │   └── Watchlist.jsx
    └── styles/
        └── styles.css
What you need to do first
Obtain your own TMDB API credential through the official TMDB website .

Install Node.js  on your computer.

Prepare the project files and run the application locally.


Method 1: The Quick Right-Click (Easiest)
When you originally installed Git, it usually added a shortcut to your mouse menu automatically. [1]


Open File Explorer and go to the folder you want.



Right-click on an empty space inside that folder.



If you are on Windows 11, click Show more options at the bottom of the menu.



Click Git Bash Here
Method 2: The Address Bar Trick (No Clicking Needed)
If you prefer using your keyboard or don't see the right-click menu option, you can launch it straight from the folder's path header:


Open your target folder in File Explorer.



Click directly on the Address Bar at the very top of the window (where the folder path is listed) to highlight the text.



Type bash and press Enter.
How to launch Git Bash from right-click context menu on Windows 10 | One - Tips EverydayHaryPhamDevYouTube



At its core, Git is a set of command line utility programs that are designed to execute on a Unix style command-line environment. Modern operating systems like Linux and macOS both include built-in Unix command line terminals. This makes Linux and macOS complementary operating systems when working with Git. Microsoft Windows instead uses Windows command prompt, a non-Unix terminal environment.
In Windows environments, Git is often packaged as part of higher level GUI applications. GUIs for Git may attempt to abstract and hide the underlying version control system primitives. This can be a great aid for Git beginners to rapidly contribute to a project. Once a project's collaboration requirements grow with other team members, it is critical to be aware of how the actual raw Git methods work. This is when it can be beneficial to drop a GUI version for the command line tools. Git Bash is offered to provide a terminal Git experience.
What is Git Bash?
Git Bash is an application for Microsoft Windows environments which provides an emulation layer for a Git command line experience. Bash is an acronym for Bourne Again Shell. A shell is a terminal application used to interface with an operating system through written commands. Bash is a popular default shell on Linux and macOS. Git Bash is a package that installs Bash, some common bash utilities, and Git on a Windows operating system.
How to install Git Bash
Git Bash comes included as part of the Git For Windows package. Download and install Git For Windows like other Windows applications. Once downloaded find the included .exe file and open to execute Git Bash.
How to use Git Bash
Git Bash has the same operations as a standard Bash experience. It will be helpful to review basic Bash usage. Advanced usage of Bash is outside the scope of this Git focused document.
How to navigate folders
The Bash command pwd is used to print the 'present working directory'. pwd is equivalent to executing cd on a DOS(Windows console host) terminal. This is the folder or path that the current Bash session resides in.
The Bash command ls is used to 'list' contents of the current working directory. ls is equivalent to DIR on a Windows console host terminal.
Both Bash and Windows console host have a cd command. cd is an acronym for 'Change Directory'. cd is invoked with an appended directory name. Executing cd will change the terminal sessions current working directory to the passed directory argument.
Git Bash commands
Git Bash is packaged with additional commands that can be found in the /usr/bin directory of the Git Bash emulation. Git Bash can actually provide a fairly robust shell experience on Windows. Git Bash comes packaged with the following shell commands which are outside the scope of this document: Ssh, scp, cat, find.
In addition the previously discussed set of Bash commands, Git Bash includes the full set of Git core commands discussed through out this site. Learn more at the corresponding documentation pages for git clone, git commit, git checkout, git push, and more.Git for WindowsWe bring the awesome Git VCS to Windowsgitforwindows.org


scp(1): secure copy - Linux man pagescp copies files between hosts on a network. It uses ssh(1) for data transfer, and uses the same authentication and provides the same security as ssh(1). ...linux.die.net






git add .
git commit -m "Updated website"
git push













