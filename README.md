
# 🏃‍♂️ RunLab

**AI-Powered Running Analytics** — for endurance athletes and quantified-self fans who want more from their data.

---

## 📦 What's Included

| File | Description |
|------|-------------|
| `RunLab_Starter.ipynb` | Project setup, pace zones, task list |
| `RunLab_HR_Zones.ipynb` | Heart rate time-in-zone visualizations |
| `RunLab_Fitness_Tracking.ipynb` | VDOT tracking and performance trends |
| `RunLab_Training_Plan_vs_Actual.ipynb` | Compare planned vs actual km/week |
| `RunLab_AI_Summary.ipynb` | GPT-based summary of your training logs |
| `RunLab_Dashboard.ipynb` | Combined view of metrics with visuals |
| `config_template.py` | Loads OpenAI API key securely from `.env` |
| `README.md` | This guide |
| `index.html` | GitHub Pages landing site |

---

## 🛠️ Setup

```bash
# Conda environment setup
conda create -n runlab_env python=3.11
conda activate runlab_env
conda install jupyter pandas matplotlib seaborn ipykernel
python -m ipykernel install --user --name runlab_env --display-name "Python (runlab_env)"
jupyter notebook
```

- Copy `.env` from `.env.example` and paste your OpenAI API key

---

## 🌐 GitHub Pages

See the project homepage at:

👉 https://jonathanlangley.github.io/RunLab

---

## 🖼️ Screenshot

![RunLab Preview](runlab_preview.png)

---

## 🧠 Powered by AI

The notebook `RunLab_AI_Summary.ipynb` uses GPT-4 to summarize your weekly data and provide feedback or motivation.

---

## 👤 Author

Jonathan Langley · [GitHub Profile](https://github.com/jonathanlangley)

MIT License · Contributions welcome
