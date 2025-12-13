# Week 0 — Tooling Warm-Up

Week 0 is all about laying the groundwork so you can focus on reinforcement learning experiments later. By the end of this week you should be confident with the tooling, comfortable iterating on notebooks, and ready to sprint into algorithms.

## Objectives

- Set up a reproducible Python environment for the cohort.
- Refresh core Python concepts that will appear in later weeks.
- Get hands-on with NumPy, Pandas, and Matplotlib.

## Before you start

- ✅ Python 3.10+ installed (`python --version`)


## Environment setup

```bash
cd WiDS-2024-Can-Computers-Think-main
python3 -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate
pip install notebook numpy pandas matplotlib tqdm
```
## Recommended resources

- Python refresher – [Programming with Mosh](https://youtu.be/_uQrJ0TkZlc?si=gfn-7_-chO-J60hD)
- NumPy quickstart – [Official user guide](https://numpy.org/doc/2.1/user/quickstart.html)
- Pandas primer – [Corey Schafer video](https://youtu.be/vmEHCJofslg?si=1efKYTqQRdDECaNE) and [docs tutorials](https://pandas.pydata.org/pandas-docs/version/0.15/tutorials.html)
- Matplotlib overview – [Official tutorials](https://matplotlib.org/stable/tutorials/index.html)
- Combined crash course – [NumPy/Pandas/Matplotlib playlist](https://youtube.com/playlist?list=PL9n0l8rSshSnragNblKDBsT8Xu3otp3jA&si=1zoqrRjvGLP4QMmU)


## Learning path

1. **Python refresher** → Work through `python-tutorial.ipynb`. Skim sections you already know, but run the code to ensure your setup works.
2. **NumPy essentials** → Complete `numpy-tutorial.ipynb`. Focus on array operations, broadcasting, random sampling, and vectorised maths.
3. **Pandas practice** → Explore `pandas-tutorial.ipynb`. Pay special attention to indexing, joins, and groupby operations.
4. **Matplotlib mini-project** → Use `matplotlib-tutorial.ipynb` to reproduce a plot from one of your past courses or the RL textbook.
5. **Stretch (optional)** → Recreate an analysis from a dataset you like. Summarise what you learned in two short bullet points.


## Looking ahead

Once you can comfortably read and modify the Week 0 notebooks, jump to `Week 1/README.md`, where you will start implementing the first reinforcement learning algorithms. 
