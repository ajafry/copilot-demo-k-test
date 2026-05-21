# ✈️ GitHub Copilot Demo

> *"With great power comes great responsibility."* — Uncle Ben, Spider-Man  
> Welcome to the app that makes you feel like Tony Stark with an AI in your corner. 🦾

A **Streamlit** web app that showcases the top features of [GitHub Copilot](https://github.com/features/copilot) — your AI pair-programmer. Think of it as *The Matrix*: once you plug in, you'll never want to unplug.

---

## 🎬 What's Inside?

Like the MCU, this app has multiple phases — err, *pages*:

### 🏠 Home — *"I Am Iron Man"*
A hero banner displaying the **Top 10 GitHub Copilot Features**, from real-time code completions to full Agent Mode. It's like the Avengers roster, but for your IDE.

### 🧮 Calculator — *"Do You Feel Lucky, Punk?"*
A slick, node-style calculator built entirely in Streamlit. Type your expression, hit `=`, and let the numbers do the talking. No DeLorean required — but results are instantaneous.

### 💡 Code Generation Lab — *"May the Force Be With You"*
The interactive playground where **you** summon GitHub Copilot to generate code in real time. Open `views/codegen_lab.py` in VS Code, delete a `pass`, and watch Copilot conjure implementations like Gandalf with a keyboard.

---

## 🚀 Getting Started

> *"Every journey begins with a single step."* — Lao Tzu (and every action movie protagonist ever)

### Prerequisites

- **Python 3.13+** — *"Keep up or get left behind"* (Fast & Furious, probably)
- [GitHub Copilot](https://github.com/features/copilot) access (for the live demo magic ✨)

### Installation

1. **Clone the repo** — like Neo taking the red pill, there's no going back:

   ```bash
   git clone https://github.com/ajafry/copilot-demo-k-test.git
   cd copilot-demo-k-test
   ```

2. **Install dependencies** — *"I'll be back"* (but with packages installed this time):

   ```bash
   pip install -r requirements.txt
   ```

3. **Launch the app** — *"To infinity and beyond!"*:

   ```bash
   streamlit run app.py
   ```

4. Open your browser at `http://localhost:8501` and enjoy the show. 🍿

---

## 🗂️ Project Structure

```
copilot-demo-k-test/
├── app.py                 # Main entry point & sidebar navigation
├── requirements.txt       # Python dependencies
└── views/
    ├── __init__.py
    ├── home.py            # 🏠 Top-10 Copilot features showcase
    ├── calculator.py      # 🧮 Node-style calculator
    ├── codegen_lab.py     # 💡 Live code generation playground
    └── styles.py          # 🎨 Shared CSS styles & footer
```

---

## 🎸 Live Demo Walkthrough

> *"I've got the eye of the tiger, a fighter, dancing through the fire"* — Katy Perry, *Roar* (with a nod to Survivor's *Eye of the Tiger* 🐯)

Here's how to rock the **Code Generation Lab** during a live demo:

1. Open `views/codegen_lab.py` in **VS Code** with GitHub Copilot enabled.
2. Navigate to any stub function (e.g., `reverse_string`, `fizzbuzz`).
3. Delete the `pass` keyword, place your cursor, and let **Copilot autocomplete** the implementation.
4. Save the file.
5. Refresh the Streamlit app — your new function is live! 🎉

The lab currently includes these challenges for Copilot to solve:

| # | Challenge | Description |
|---|-----------|-------------|
| 1 | **Reverse a String** | Flip it and reverse it 🔄 |
| 2 | **Palindrome Check** | *"Was it a car or a cat I saw?"* — the classic 🐱 |
| 3 | **FizzBuzz** | The legendary interview rite of passage |
| 4 | **Celsius → Fahrenheit** | For all our imperial unit friends 🌡️ |
| 5 | **Count Vowels** | *"A E I O U — and sometimes Y"* |
| 6 | **Find Max** | Seek and ye shall find (the biggest number) |

---

## 🛠️ Tech Stack

| Tool | Role |
|------|------|
| [Streamlit](https://streamlit.io) `>=1.30.0` | Web framework (*"It just works"* — basically Steve Jobs) |
| Python 3.13+ | The one ring to run them all 💍 |
| GitHub Copilot | Your AI co-pilot (it's in the name!) |

---

## 🤝 Contributing

> *"Why so serious?"* — The Joker  
> We're not. Contributions are welcome! Feel free to open issues or PRs.

1. Fork the repo
2. Create your feature branch: `git checkout -b feature/amazing-new-thing`
3. Commit your changes: `git commit -m 'Add some amazing new thing'`
4. Push to the branch: `git push origin feature/amazing-new-thing`
5. Open a Pull Request and let GitHub Copilot review it 🤖

---

## 📜 License

This project is open source. Share it, remix it, use it to impress at your next hackathon — just like sampling a classic beat. 🎵

---

<div align="center">

*"The stuff that dreams are made of."* — The Maltese Falcon 🐦‍⬛

Built with ❤️ and a lot of ✨ AI magic ✨

</div>
