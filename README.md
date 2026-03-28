<div align="center">
	<img src="https://user-images.githubusercontent.com/placeholder/bingo-logo.png" alt="Soc Ops Bingo" width="120" />
  
	<h1>Soc Ops: Social Bingo for Mixers</h1>
	<p><strong>Break the ice. Make connections. Play to win.</strong></p>
	<p>
		<em>Find people who match the prompts. Mark your board. Get five in a row. <br>
		The ultimate in-person social bingo game—built for workshops, meetups, and fun events!</em>
	</p>
</div>

---

## 🎲 What is Soc Ops?

Soc Ops is a playful, interactive bingo game designed for real-world social events. Each player gets a unique board filled with prompts like “Has visited three continents” or “Can juggle.” Your mission: mingle, discover who matches each prompt, and race to complete a row, column, or diagonal!

<p align="center">
	<img src="https://user-images.githubusercontent.com/placeholder/bingo-board-demo.png" alt="Bingo Board Demo" width="400" />
</p>

---

## ✨ Features

- 🧩 **Dynamic Boards:** Every player gets a unique, randomized bingo board.
- 🤝 **Icebreaker Prompts:** Customizable questions spark real conversations.
- ⚡ **Fast, Responsive UI:** Built with custom CSS utilities for a modern, delightful experience.
- 🧑‍💻 **Agent-Powered:** Multi-agent backend for quiz generation and game logic.
- 📝 **Workshop Ready:** Step-by-step lab guides for learning, hacking, and extending.

---

## 📚 Lab Guide

| Part                                                                                             | Title                       |
| ------------------------------------------------------------------------------------------------ | --------------------------- |
| [**00**](https://copilot-dev-days.github.io/agent-lab-python/docs/step.html?step=00-overview)    | Overview & Checklist        |
| [**01**](https://copilot-dev-days.github.io/agent-lab-python/docs/step.html?step=01-setup)       | Setup & Context Engineering |
| [**02**](https://copilot-dev-days.github.io/agent-lab-python/docs/step.html?step=02-design)      | Design-First Frontend       |
| [**03**](https://copilot-dev-days.github.io/agent-lab-python/docs/step.html?step=03-quiz-master) | Custom Quiz Master          |
| [**04**](https://copilot-dev-days.github.io/agent-lab-python/docs/step.html?step=04-multi-agent) | Multi-Agent Development     |

> 📝 Lab guides are also available in the [`workshop/`](workshop/) folder for offline reading.

---

## 🚀 Quickstart

1. **Clone this repo:**
   ```sh
   git clone https://github.com/your-org/my-soc-ops-python.git
   cd my-soc-ops-python
   ```
2. **Install dependencies:**
   ```sh
   python -m uv sync
   ```
3. **Run the app:**
   ```sh
   python -m uv run uvicorn app.main:app --reload --host 0.0.0.0 --port 8000
   ```
4. **Open in your browser:**
   [http://localhost:8000](http://localhost:8000)

---

## 💡 Why Soc Ops?

- **Break the ice** at any event—no awkward silences!
- **Learn modern Python, FastAPI, and agent patterns** in a hands-on, creative way.
- **Customize everything:** Prompts, board size, and more.
- **Show off your frontend skills** with custom CSS utilities (see `app/static/css/app.css`).

---

## 🛠️ Contributing

We love contributions! Check out [`CONTRIBUTING.md`](CONTRIBUTING.md) for how to get started, and join us in making Soc Ops even more fun and useful.

---

<div align="center">
	<strong>Ready to play? <a href="https://copilot-dev-days.github.io/agent-lab-python/step.html?step=00-overview">Start the lab!</a></strong>
</div>
