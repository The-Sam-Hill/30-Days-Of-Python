# Notes

## Every new terminal

Start in the project root (`python-practice`) and turn on the virtual environment:

    .\.venv\Scripts\Activate.ps1

The prompt should now start with `(.venv)`.

## Run a file

Always from the project root, because the course examples use paths relative to it:

    python my_work\day01\examples.py

## Save work to GitHub

    git add my_work
    git commit -m "Day 1 exercises"
    git push

## Get course updates from the author

    git pull upstream master

## If a command is "not recognized"

The terminal is running with an old PATH. Refresh it for this window, then activate the venv again:

    $env:Path = [Environment]::GetEnvironmentVariable('Path','Machine') + ';' + [Environment]::GetEnvironmentVariable('Path','User')

## Things I learned

-
