# CodeLadder 🪜

# CodeLadder

An interactive programming-learning platform that helps beginners understand code step by step.

### 🚀 Live Demo

[**Open CodeLadder Application**](https://profound-cranachan-ab9cb7.netlify.app)

### ✨ Features
- Learn programming through step-by-step challenges
- Convert plain-English problems into flowcharts, pseudocode, and Python
- Practice Python in the browser
- Identify and understand common programming mistakes


### Find the missing concept. Climb toward confident coding.

CodeLadder is an interactive coding-learning platform designed to help beginners understand **why they make programming mistakes**, rather than simply showing them the correct answer.

It guides learners from a problem described in plain English through a flowchart, pseudocode, and Python implementation. By analyzing incorrect predictions, CodeLadder identifies potential gaps in fundamental programming concepts and provides targeted explanations and practice.

## 🎯 The Problem

Beginners often struggle to connect problem statements with programming logic. They may understand individual syntax rules but still find loops, variables, conditions, and list indexing difficult to apply together.

Traditional practice tools often emphasize whether an answer is correct, leaving learners unsure about the underlying concept they need to improve.

## 💡 Our Solution

CodeLadder introduces a step-by-step learning ladder that helps learners:

- Understand a problem before writing code.
- Visualize the solution using flowcharts.
- Translate logic into pseudocode.
- Predict program output before running Python.
- Identify concepts associated with incorrect answers.
- Receive explanations, examples, and progressive hints.

## ✨ Features

- **Four-stage learning ladder:** Plain-English problem, flowchart, pseudocode, and Python.
- **Concept diagnosis:** Feedback focused on loops, variables, conditions, and indexing.
- **Interactive flowcharts:** Explore program logic and highlight corresponding code lines.
- **Python execution:** Run practice programs in the browser using Pyodide.
- **Guided coding assistant:** Ask for hints and explanations using a built-in rule-based assistant.
- **Personalized onboarding:** Select learning goals, experience level, interests, and preferred learning style.
- **Study Circles prototype:** Explore concept-based learning groups and sample discussions.
- **Responsive interface:** A dark, interactive learning experience with animated elements.

## 🧠 How It Works

1. **Describe:** Read a programming problem in plain English.
2. **Visualize:** Explore the flowchart and predict how the logic behaves.
3. **Translate:** Connect the flowchart to pseudocode.
4. **Implement:** Inspect and run the corresponding Python program.
5. **Diagnose:** Review incorrect predictions and receive targeted concept explanations.

## 🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| HTML5 | Application structure |
| CSS3 | Styling, layouts, and animations |
| JavaScript | Interactive application logic |
| Mermaid.js | Flowchart rendering |
| Pyodide | Running Python in the browser |
| Browser Local Storage | Persisting prototype Study Circle data |

## 🚀 Getting Started

### Prerequisites

- A modern web browser.
- An internet connection for loading the external Mermaid.js and Pyodide libraries.

### Installation

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/CodeLadder.git
cd CodeLadder
```

Open `index.html` in your browser.

Alternatively, start a local development server:

```bash
python -m http.server 8000
```

Visit:

```text
http://localhost:8000
```

Replace `YOUR_USERNAME` with your GitHub username and update the repository URL if your repository has a different name.

## 📂 Project Structure

```text
CodeLadder/
├── index.html
├── README.md
├── LICENSE
├── .gitignore
└── screenshots/
    ├── home.png
    ├── learning-ladder.png
    └── diagnosis.png
```

The screenshot files and supporting repository files should be added when available.

## 🧪 Example Learning Tasks

- Class Grade Calculator
- Find the Topper
- Count Passing Students
- Find a Student's Position

These tasks help learners practice loops, variable updates, conditional logic, and list indexing.

## 🔭 Future Improvements

- AI-powered tutoring with a secure backend.
- Adaptive exercises based on learner performance.
- Persistent learner profiles and progress tracking.
- Real-time collaborative Study Circles.
- Expanded exercises and programming language support.
- Automated testing and accessibility improvements.

## ⚠️ Current Limitations

- The coding assistant currently uses predefined rules rather than a live AI model.
- Study Circle members and discussions include sample data; this is not yet a production community platform.
- Learner progress is not yet backed by a user account system.
- Flowchart rendering and Python execution depend on externally loaded browser libraries.

## 🤝 Contributing

Contributions, suggestions, and bug reports are welcome. Fork the repository, create a feature branch, make your changes, and open a pull request.

## 📄 License

Choose an open-source license and add its full license text to the repository before publishing.

---

**CodeLadder — Turn programming mistakes into learning opportunities.**
