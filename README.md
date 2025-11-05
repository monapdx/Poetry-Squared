# 🌿 Poetry√  
### *poetic symmatry*  

**Poetry√** is an experimental writing app for poets and language lovers who want to explore the structure and beauty of *square stanza poems* — an intricate poetic form where every word appears across both rows and columns in a 6×6 grid. The app combines language, logic, and design to help writers visualize and refine this challenging art form.

<img src="https://raw.githubusercontent.com/monapdx/Poetry-Squared/refs/heads/main/poetry-squared.png" width="">

---

## ✨ Features  

- 🎨 **6×6 Interactive Word Grid** – Enter a six-word sentence to automatically populate the rows and columns.  
- 🌈 **Color-Coded Word Types** – Each word’s background color reflects its part of speech:  
  - 🔴 Nouns  
  - 🔵 Verbs  
  - 🟢 Adjectives  
  - 🟡 Pronouns  
  - ⚪ Others / Unknown  
- ⚠️ **Contextual Warnings** – The app detects when neighboring word types may produce incoherent phrases.  
- 💫 **Smooth Animations** – Words fade and scale into the grid as you build your poem.  
- 📱 **Responsive Design** – Works beautifully on desktop, tablet, and mobile.  
- 📤 **Export as Image** – Instantly save or share your completed word grid as a PNG.  

---

## 🚀 Getting Started  

### 1. Clone this repository  
```bash
git clone https://github.com/yourusername/poetry-root.git
cd poetry-root
```

### 2. Open the project  
Just open `index.html` in your web browser — no build step required.  

---

## 🧠 How It Works  

1. Type a **six-word sentence** and hit enter.  
2. The app fills the **first row and column** symmetrically.  
3. Each additional sentence fills the next row/column pair.  
4. [Compromise.js](https://github.com/spencermountain/compromise) identifies word types to apply color-coding and structure feedback.  
5. Click **“Export as Image”** to save your creation as a shareable PNG.  

---

## 🧩 Tech Stack  

- **HTML5** – Structure  
- **CSS3 / Flexbox** – Layout and responsiveness  
- **JavaScript (ES6)** – Logic and interactivity  
- **Compromise.js** – Part-of-speech tagging  
- **html2canvas** – Grid image export  

---

## 🖼️ Example  



| *I* | *write* | *soft* | *words* | *into* | *light* |
| *write* |  |  |  |  |  |
| *soft* |  |  |  |  |  |
| *words* |  |  |  |  |  |
| *into* |  |  |  |  |  |
| *light* |  |  |  |  |  |

*(Each word appears across and down — forming linguistic symmetry.)*

---

## 💡 Future Ideas  

- AI-based coherence scoring for sentences  
- Custom color palettes for visual poets  
- Export to PDF or social snippet  
- Random word generator for creative prompts  

---

## 🧑‍💻 Contributing  

Contributions are welcome!  
1. Fork the repo  
2. Create a feature branch (`git checkout -b feature/new-feature`)  
3. Commit your changes  
4. Push and open a pull request  

---

## 📜 License  

MIT License © 2025 Ashly Lorenzana 
