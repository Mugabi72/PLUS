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


 More Notes on Notebook and Payload

 1. Notebook

Notebook computer
- Smaller and lighter than a full laptop; focuses on portability and battery life.
- Usually has less processing power and storage than a desktop.
- Components: display, keyboard, touchpad, battery, Wi-Fi/Bluetooth, USB ports.

Computational notebook (Jupyter, Google Colab)
- File format: `.ipynb` (JSON-based).
- Made of **cells**: *code cells* (run live) and *Markdown cells* (text, headings, formulas).
- A **kernel** runs the code (e.g. Python, R).
- Advantages: step-by-step execution, inline charts, easy to share and reproduce.
- Limitations: cells can be run out of order, which causes hidden errors, and notebooks are harder to version-control than plain scripts.
- Uses: data analysis, machine learning, teaching, research reports.

Study notebook: good note-taking methods
- *Cornell method*: page split into notes, cues and a summary.
- *Outline method*: headings with indented sub-points.
- *Mind map*: topics linked visually.
- Tips: date every entry, use abbreviations, highlight sparingly, and review within 24 hours.

 2. Payload

Networking
- A packet = **header + payload + trailer**.
- Header: source and destination addresses, protocol, sequence number.
- Trailer: error-checking data (e.g. CRC).
- Payload size is limited by the **MTU** (Ethernet is typically 1500 bytes).
- Header data is **overhead**: the smaller the payload relative to the header, the lower the efficiency.
- Encryption protocols such as IPsec/TLS can encrypt the payload so intermediaries cannot read it.

Web and APIs
- The payload is the data sent in the body of an HTTP request or response, often **JSON** or XML (e.g. a login form sent via POST).

Cybersecurity
- Malware has two parts: the **delivery mechanism** (how it spreads) and the **payload** (what it does).
- Payload effects include data theft, file encryption (ransomware), creating backdoors and deleting files.
- Defences: antivirus, firewalls, patching, user awareness, and deep packet inspection.

Aerospace and transport
- Payload is the revenue-earning load, such as satellites, crew or cargo, excluding the vehicle's own weight and fuel.
- Measured as **payload capacity** (e.g. a truck's maximum load in tonnes).

 Extended Comparison

| | Notebook | Payload |
|---|---|---|
| Nature | Device or interactive document | Data or cargo being carried |
| Main use | Computing, coding, note-taking | Data transmission, malware action, cargo |
| Key parts | Cells, kernel, screen, battery | Header/body/trailer (networking) |
| Example | Jupyter `.ipynb` file | Body of an HTTP POST request |
| Risk/limit | Out-of-order execution errors | MTU limit, malicious payloads |

If you meant the Git Bash or CineBox project parts of your text, tell me and I'll add notes on those instead.







Here is more content, continuing from your notes.

## 3. More on Notebook

**Types of notebook computer**
| Type | Features |
|---|---|
| Ultrabook | Very thin, light, long battery life, SSD storage |
| Chromebook | Runs ChromeOS, mostly web apps, low cost |
| 2-in-1 | Touchscreen that folds or detaches into a tablet |
| Netbook (old) | Very small, low power, now largely replaced |

Jupyter basics
- Run a cell: `Shift + Enter`
- Command mode: `Esc`. Edit mode: `Enter`
- Insert cell above/below:`A` / `B`
- Delete cell: `D D`
- Switch to Markdown/Code:`M` / `Y`

```python
# Example code cell
import pandas as pd
df = pd.read_csv("students.csv")
df.head()
```
```markdown
# Example Markdown cell
## Analysis of student results
```

Jupyter vs Google Colab
| | Jupyter | Google Colab |
|---|---|---|
| Runs on | Your computer or a server | Google's cloud |
| Setup | Install required | None, just a browser |
| Free GPU | No | Yes (limited) |
| Sharing | Share the file | Share a link, like Google Docs |

4. More on Payload

Packet structure (example sizes)
- Ethernet MTU: 1500 bytes
- IPv4 header: at least 20 bytes
- TCP header: at least 20 bytes
- Maximum TCP payload per packet is about 1460 bytes (1500 − 20 − 20)
- A UDP header is only 8 bytes, so UDP has less overhead.

```
| Header | Payload (data) | Trailer |
```

**HTTP payload example (JSON)**
```json
POST /login
{ "username": "elijah", "password": "********" }
```
The JSON in the body is the payload.

**Types of malware payload**
| Payload type | Action |
|---|---|
| Ransomware | Encrypts files and demands payment |
| Spyware | Secretly collects data |
| Backdoor | Opens hidden remote access |
| Wiper | Deletes or corrupts data |
| Botnet agent | Turns the device into a remote-controlled "zombie" |

Payload vs related terms
- Payload: what the malware does.
- Exploit how it gets in, by using a weakness.
- Vector: the route it travels, such as email or USB.

 5. Git Bash notes (from your text)

| Command | Purpose |
|---|---|
| `pwd` | Show current folder |
| `ls` | List files |
| `cd folder` | Change folder |
| `git init` | Start a repository |
| `git clone URL` | Copy a repository |
| `git status` | Show changes |
| `git add .` | Stage all changes |
| `git commit -m "message"` | Save a snapshot |
| `git push` | Upload to GitHub |
| `git pull` | Download latest changes |

**Typical workflow:** edit files → `git add .` → `git commit -m "Updated website"` → `git push`

 6. Likely exam questions
1. What is a computational notebook? An interactive document combining live code, output, charts and text.
2. What is a kernel? The engine that runs the code in a notebook.
3. Why can notebooks cause hidden errors? Cells can be run out of order.
4. What is a payload in networking?  The actual data in a packet, excluding header and trailer.
5. What does the header contain? Source and destination addresses, protocol and sequence number.
6. What is a malware payload? The part that carries out the harmful action.
7. Why does a small payload reduce efficiency? The header overhead stays the same, so more of the packet is overhead.
8. What does `git push` do? Uploads local commits to the remote repository.

7. More key terms
- Cell: a block of code or text in a notebook.
- Kernel:the program that executes notebook code.
- .ipynb`: the Jupyter notebook file format.
- MTU: the maximum packet size a network can carry.
- Overhead: extra data (headers) needed to deliver the payload.
- Encapsulation:  wrapping data with headers as it moves down network layers.
- Repository: a project folder tracked by Git.
- Commit:  a saved snapshot of changes.

I can merge sections 1 to 7 into one Word document, kept concise. Shall I do that?


Here is more material, continuing from section 7 in the same structure.

## 8. Notebook computers in more depth

| Component | Role |
|---|---|
| CPU | Processes instructions; mobile versions save power |
| RAM | Temporary memory for running programs |
| SSD / HDD | Permanent storage (SSD is faster and more durable) |
| Battery | Lithium-ion; typically lasts several hours |
| Display | LCD or LED screen; sizes usually 11 to 17 inches |
| Ports | USB, HDMI, audio jack, charging port |

**Advantages:** portable, built-in battery, takes less desk space.
**Disadvantages:** harder to upgrade, more costly than a desktop of equal power, can overheat, easier to lose or steal.

**Care tips**
- Do not block the air vents.
- Use a protective bag.
- Avoid draining the battery to 0% often.
- Keep the system and antivirus updated.

## 9. Notebook vs Laptop vs Desktop

| Feature | Notebook | Laptop | Desktop |
|---|---|---|---|
| Size | Smallest, thin | Medium to large | Fixed, large |
| Portability | Very high | High | None |
| Performance | Moderate | Good | Highest |
| Upgrade options | Limited | Some | Many |
| Power source | Battery and charger | Battery and charger | Mains only |

In everyday use, "notebook" and "laptop" are often treated as the same thing.

## 10. Working with data in a Jupyter notebook

```python
import pandas as pd
import matplotlib.pyplot as plt

df = pd.read_csv("students.csv")

print(df.shape)              # rows and columns
print(df.describe())         # summary statistics
print(df["mark"].mean())     # average mark

df["mark"].hist()
plt.title("Distribution of Marks")
plt.show()
```

| Library | Purpose |
|---|---|
| `pandas` | Tables and data analysis |
| `numpy` | Numerical calculations |
| `matplotlib` | Charts and graphs |
| `scikit-learn` | Machine learning |

**Good notebook practice**
- Run cells from top to bottom.
- Use **Kernel → Restart & Run All** before sharing, to confirm it works.
- Put a Markdown heading before each section.
- Keep imports in the first cell.

## 11. OSI and TCP/IP layers (where the payload travels)

| OSI layer | Data unit | Example |
|---|---|---|
| 7 Application | Data | HTTP, FTP, DNS |
| 6 Presentation | Data | Encryption, formats |
| 5 Session | Data | Session control |
| 4 Transport | Segment | TCP, UDP |
| 3 Network | Packet | IP |
| 2 Data Link | Frame | Ethernet, MAC |
| 1 Physical | Bits | Cables, Wi-Fi |

**Encapsulation:** as data moves down the layers, each layer adds its own header. The data from the layer above becomes the payload of the layer below. At the receiver, headers are removed in reverse (**decapsulation**).

## 12. HTTP request and response payloads

```
POST /api/students HTTP/1.1
Host: example.com
Content-Type: application/json

{ "name": "Mary", "mark": 85 }
```
- The first lines are **headers**.
- The JSON after the blank line is the **payload (body)**.

| Method | Has payload? | Use |
|---|---|---|
| GET | Usually no | Fetch data |
| POST | Yes | Send new data |
| PUT | Yes | Replace data |
| PATCH | Yes | Update part of the data |
| DELETE | Usually no | Remove data |

Common status codes: `200` OK, `201` Created, `400` Bad request, `401` Unauthorized, `404` Not found, `500` Server error.

## 13. Cybersecurity: protecting against malicious payloads

| Defence | How it helps |
|---|---|
| Antivirus / anti-malware | Detects and removes known malicious code |
| Firewall | Filters traffic by rules |
| Patching and updates | Closes weaknesses that exploits rely on |
| Email filtering | Blocks phishing attachments and links |
| Least privilege | Limits what malware can do if it runs |
| Backups | Allows recovery after ransomware or a wiper |
| User awareness | Avoid unknown links, attachments and USB drives |

**Stages of an attack (simplified):** delivery → exploitation → installation → payload execution → impact.

## 14. Payload in other contexts
- **Rocket/aircraft:** satellites, crew, cargo. Measured as payload capacity.
- **Drone:** camera, sensors or packages carried.
- **Truck:** goods carried, excluding the truck's own weight.
- **Payload in code (JSON Web Tokens):** the middle part of a JWT holds the claims, such as user ID and expiry.

## 15. Git and GitHub: more notes

| Command | Purpose |
|---|---|
| `git config --global user.name "Name"` | Sets your name for commits |
| `git config --global user.email "mail"` | Sets your email for commits |
| `git remote add origin URL` | Links local repo to GitHub |
| `git branch -M main` | Renames the branch to `main` |
| `git push -u origin main` | First push, sets upstream |
| `git diff` | Shows unstaged changes |
| `git log --oneline` | Short commit history |

**First-time upload of a project**
```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/username/repo.git
git push -u origin main
```

**`.gitignore` example**
```
node_modules/
.env
dist/
```
Keep API keys in `.env` and never upload them to GitHub.

## 16. Git Bash vs Command Prompt vs PowerShell

| Feature | Git Bash | Command Prompt | PowerShell |
|---|---|---|---|
| Shell type | Bash (Unix style) | Windows console | Windows scripting shell |
| List files | `ls` | `dir` | `ls` or `dir` |
| Current folder | `pwd` | `cd` | `pwd` |
| Git commands | Included | Needs Git installed | Needs Git installed |
| Best for | Git and Unix-style commands | Basic Windows tasks | Windows automation |

## 17. More exam questions

**Short answer**
1. **What is a notebook computer?** A lightweight portable computer with a built-in screen, keyboard, touchpad and battery.
2. **Name two advantages of a Jupyter notebook.** Step-by-step execution and inline charts.
3. **What is encapsulation?** Wrapping data with headers as it moves down the network layers.
4. **What is the difference between an exploit and a payload?** The exploit gets the malware in through a weakness; the payload is the harmful action it then performs.
5. **Which HTTP method normally carries a payload?** POST.
6. **Why should `.env` be in `.gitignore`?** It holds secret keys that must not be made public.
7. **What does Bash stand for?** Bourne Again Shell.

**Long answer**
1. Explain the structure of a network packet and why header overhead matters. *(Header, payload, trailer, MTU, efficiency.)*
2. Describe the types of malware payload and the defences against them. *(Ransomware, spyware, backdoor, wiper, botnet; antivirus, firewall, patching, backups.)*
3. Compare a Jupyter notebook with a normal script. *(Interactive, cells, inline output, out-of-order risk, version control.)*

## 18. More key terms
- **Decapsulation:** removing headers as data moves up the layers at the receiver.
- **Segment / Frame:** data units at the Transport and Data Link layers.
- **Latency:** the delay before data arrives.
- **Bandwidth:** the amount of data a connection can carry per second.
- **JSON:** a text format for structured data, written as key-value pairs.
- **API:** a set of rules that lets programs exchange data.
- **Vector:** the route malware uses to reach a device.
- **Ransomware:** malware that encrypts files and demands payment.
- **Upstream:** the remote branch a local branch tracks.

## 19. Quick revision summary
- **Notebook:** portable computer, Jupyter/Colab document, or study book
- **Jupyter:** cells and kernel, run top to bottom, restart and run all before sharing
- **Payload:** the useful data in a packet, request or malware, excluding headers
- **Network:** encapsulation adds headers, MTU limits size, header is overhead
- **Security:** exploit gets in, vector carries it, payload does the damage
- **Git:** add → commit → push, keep secrets in `.env` and `.gitignore`

Would you like sections 1 to 19 combined into one concise Word document?
