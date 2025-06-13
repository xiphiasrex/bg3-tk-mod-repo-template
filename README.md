# bg3-tk-mod-repo-template


Git repo template for bg3 toolkit mod projects


## Required Dependencies
- Python runtime
  - https://www.python.org/downloads/
- Git
  - https://git-scm.com/downloads
  - There are other clients as well, I use https://desktop.github.com/download/
- Junctions
  - https://learn.microsoft.com/en-us/sysinternals/downloads/junction
  - This is not an installer, but an executable.  Either place somewhere that is in your path
    or make a note of the path to where this is kept


## Usage
1. Create a project in the Baldur's Gate 3 Toolkit
2. Clone this repo to a non-protected directory (not in something like Program Files)
   1. You can give a name to the local repo to reflect the specific mod
3. Update properties at the top of `repo-setup.py` and save
4. Run `python repo-setup.py`
5. Going forward you should be able to commit/push/pull/etc. like any other git repo
