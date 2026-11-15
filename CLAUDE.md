# python-practice

Personal fork of asabeneh/30-days-of-python, used to learn Python by working through the course.

## Layout

- Course material belongs to the upstream author: the numbered `NN_Day_*` folders, `readme.md` (the Day 1 lesson), `data/`, `files/`, `images/` and the translation folders. Read and run it, but do not edit it.
- Everything the user writes goes in `my_work/`, one folder per day: `my_work/day01/`, `my_work/day02/`, and so on. Each day has `examples.py` (typing along with the lesson) and `exercises.py` (the end-of-day exercises).
- `my_work/scratch/` is for throwaway experiments. `my_work/notes.md` is the user's own notes.
- New files and folders use lowercase names with underscores and zero-padded numbers, so they stay importable.

## Running code

- Windows, PowerShell. Python was installed with scoop.
- The virtual environment is `.venv` in the project root. Use its interpreter, `.venv\Scripts\python.exe`, or activate it in PowerShell with `.\.venv\Scripts\Activate.ps1`.
- Run scripts from the project root, for example `python my_work\day01\exercises.py`. The course examples use paths relative to the root.
- Install packages only into the venv.

## Git

- `origin` is the user's fork (The-Sam-Hill/30-Days-Of-Python). `upstream` is the author's repo. Push only to `origin`.
- Course updates come from `git pull upstream master`.
- GitHub authentication goes through `gh` over HTTPS.

## Working with the user

- The user is here to learn Python. Explain and guide; do not write exercise solutions unless asked.
- The user normally works on macOS and is new to Windows. When a command differs between the two, give the Windows form.
