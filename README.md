CodeLadder
Climb from plain words to real code. We find the missing rung.

CodeLadder is a beginner-friendly programming logic practice platform that helps learners understand how a problem moves from a plain-language description to a flowchart, pseudocode, and Python code. Instead of only showing code, it helps learners reason through each step, answer prediction questions, and identify concepts they may need to practise.
Overview
Beginners can find it difficult to translate a problem statement into a working algorithm. CodeLadder breaks that process into smaller, connected stages and provides explanations when learners make mistakes.
Features
- Step-by-step problem solving: Move through the stages: Describe, Flowchart, Pseudocode, Python, and Diagnosis.
- Practice tasks: Work through examples such as a class grade calculator, finding the topper, counting passing students, and finding a student's position.
- Interactive prediction questions: Answer multiple-choice questions about program logic and expected outcomes.
- Instant feedback: See explanations for correct and incorrect answers.
- Concept explanations: Review loops, variables, conditions, and indexing with examples.
- Guided helper: Ask for hints and explanations using the built-in CodeLadder Guide. It uses rule-based responses rather than a live AI API.
- Flowchart interaction: Explore flowcharts rendered with Mermaid.
- Python execution support: The prototype uses Pyodide to run Python in the browser when available.
- Study Circles prototype: Explore sample community posts and members; browser local storage is used for supported local persistence.
- Responsive layout: The interface adapts to smaller screens.
Technologies
- HTML5
- CSS3
- JavaScript
- Mermaid — flowchart rendering
- Pyodide — Python runtime in the browser
Mermaid and Pyodide are loaded from CDNs, so an internet connection is generally needed for those integrations.
Getting Started
Requirements
- A modern web browser
- An internet connection for the Mermaid and Pyodide CDN resources
- No separate backend server is required for the basic prototype
Installation
1. Clone the repository:
   git clone YOUR_GITHUB_REPOSITORY_URL
2. Open the project folder:
   cd YOUR_REPOSITORY_NAME
3. Open index.html in a modern browser.
   If browser restrictions affect module loading, start a simple local web server from the project directory:
   python -m http.server 8000
4. Visit http://localhost:8000 in your browser.
Replace YOUR_GITHUB_REPOSITORY_URL and YOUR_REPOSITORY_NAME with your repository's actual URL and folder name.
How to Use
1. Open CodeLadder in your browser.
2. Choose one of the available practice tasks.
3. Read the problem description and understand what the program needs to do.
4. Explore the flowchart to follow the decision-making and repetition steps.
5. Review the pseudocode to understand the algorithm in plain language.
6. Study the Python solution and answer the prediction questions.
7. Read the feedback and concept explanations to understand mistakes.
8. Use Ask the guide for a hint or an explanation of concepts such as loops and indexing.
Project Structure
The current prototype is primarily contained in a single HTML file:
CodeLadder/
└── index.html
The page contains the styling, task data, learning flow, and JavaScript logic.
Screenshots
Screenshots are not included in this README because no verified screenshots of the running prototype are available here. To add your own, create a screenshots/ folder in the repository and insert images like this:
![CodeLadder home screen](screenshots/home.png)
![CodeLadder practice task](screenshots/practice-task.png)
Use screenshots captured from the actual running project.
Current Scope and Limitations
- This is a prototype focused on programming logic practice, not a complete course platform.
- The built-in guide uses predefined, rule-based responses; it does not connect to a live AI model.
- Study Circles uses sample content and local browser storage, not a shared online community backend.
- Python execution depends on the browser successfully loading Pyodide.
- Progress and community data are not backed by a user account or cloud database.
Future Improvements
- Add more programming logic challenges and guided practice.
- Improve progress tracking and concept-level recommendations.
- Add user accounts and cloud-based progress storage.
- Connect learners through a real-time collaborative community.
- Expand testing, accessibility, and offline support.
Contributing
Contributions and suggestions are welcome.
1. Fork the repository.
2. Create a branch for your change.
3. Make and test your changes.
4. Submit a pull request describing the improvement.
License
No license has been specified yet. Add a LICENSE file before presenting the project as open source.
CodeLadder — Find the missing rung in your programming logic.
