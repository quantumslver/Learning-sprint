# Learning Sprint — Cold Atom Python + LaTeX Prep

This repo is part of a daily sprint (16–30 June 2025) to build core coding skills for Cold Atom PhD research.  
Goal: become fluent in Python (NumPy, Matplotlib, SciPy) and LaTeX — no excuses, no delays.

---

## 📅 Day 1 — 16 June 2025

### ✅ Task
- Plot basic **projectile motion** using Python
- Learn how to use `matplotlib` for plotting
- Set up Git & GitHub with SSH
- Push working code to live repo

### 📓 Physics
Equation used:  
\[
y(t) = ut + \frac{1}{2}at^2
\]

Where:
- `u`: initial velocity (user input)
- `a`: acceleration (gravity = –9.8 m/s²)
- `t`: time vector using `np.linspace`
- `y`: vertical position

### ⚠️ Struggles + Fixes
| Problem | How I fixed it |
|--------|----------------|
| Didn’t know how to start coding | Googled syntax + asked ChatGPT |
| `input()` gave string errors | Wrapped it in `float(input(...))` |
| Plot wasn’t showing points | Used `'rx'` to show red dots |
| Git setup was a nightmare | Finally got SSH key working, pushed repo |

### 🧠 Reflection
> Didn’t know shit about Python or Git.  
> But still finished the task, made a working plot, committed it, and pushed it live.  
> Not fast, not clean — but DONE.

---

## 🔧 Folder Contents

| File | Description |
|------|-------------|
| `proj_motion.ipynb` | Simulates vertical projectile motion and plots `y vs t` |
| `README.md` | This file — logs my daily sprint progress |

---

## 🔮 Coming Up

- [ ] Day 2: NumPy vector ops + converting sim to full array math
- [ ] Day 3: Matplotlib styling + RK4 simulation
- [ ] More physics-based Python projects

---

## ⚔️ Motivation

> I'm not a CS guy. I'm a physics student with no background.  
> But I will build real tools for research — and I’ll leave all excuses behind.

