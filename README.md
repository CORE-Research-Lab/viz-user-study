# Visual Representations in Programming Learning

This repository hosts a web-based interface for an exploratory user study on visual representations in programming learning. Participants compare Python Tutor and Multiple Representations (MER) Tool to solve programming tasks and answer related questions.

## 🎯 Project Overview
This project is part of a research study to investigate how different visual representations support students in understanding programming concepts. Participants complete tasks using two tools:
- **Python Tutor**: Step-by-step code visualization.
- **Multiple Representations (MER) Tool**: Interactive visual representations.

The app displays side-by-side visuals and questions, allowing participants to directly compare the tools.

---

## 🛠️ Features
- **Interactive Interface:** Large visual embeds for each tool.
- **Side-by-Side Comparison:** View Python Tutor and MER Tool results.
- **Task Navigation:** Move between multiple programming tasks.
- **Group Assignment:** Supports two experimental conditions (Group A and Group B).

---

## 🚀 Getting Started
### 1. **Clone the Repository:**
```bash
git clone https://github.com/your-username/visual-representations.git
cd visual-representations
```

### 2. **Run the Web App:**
Simply open the `index.html` file in your browser:
```bash
open index.html
# Or double-click the file to open in your browser.
```

### 3. **Customize Group Assignment:**
In `index.html`, find the line:
```javascript
const group = "A"; // Change to "B" for Group B.
```
Modify this value to assign the participant group.

### 4. **Update Visual Embeds:**
Replace URLs in the arrays inside `index.html`:
```javascript
const pythonTutorLinks = ["url1", "url2", "url3"];
const merLinks = ["url1", "url2", "url3"];
```
---

## 📝 Contributing
We welcome contributions to improve this project! Feel free to submit issues or pull requests.

### How to Contribute:
1. Fork the repository.
2. Create a new branch.
3. Make changes and test locally.
4. Submit a pull request.

---

## 📜 License
This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

---

## 💡 Acknowledgments
- **Python Tutor:** https://pythontutor.com/
- **MER Tool:** Developed by CORE Research Lab
- University of Toronto, Department of Computer Science
