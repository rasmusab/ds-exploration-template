_Are you in a data science team where people put analysis code, throwaway code, etc., in many different places? Or maybe they don't put that code anywhere at all?!_ 😱

_Then, copy-paste this simple repo, customize the folder structure, delete this note, and then there's at least someplace that code can go, while you're noodling on a better solution._ 😉

# Data Science Exploration

A place for non-production scripts, notebooks, and other throwaway code. Don't bother with branches and pull requests, unless you want a review, as this is more of a Dropbox folder masquerading as a GitHub repo.

### Folders

- *analyses*: Notebooks/scripts for fully written analyses.
- *prototypes*: A place to put prototypes/tests/POCs for things that _might_ go into production.
- *scratchpad*: If you are too lazy to figure out where to put your script/notebook, put it here.
- *templates*: Notebook and script templates that can kick-start an exploration.
- *utils*: Utility scripts, and other useful bits and pieces. However, remember the rule of this repo: **no production stuff**.

When adding new content:
* Be generous with sub-folders. Any new piece of content should live in its own subfolder.
* Be generous with timestamps and, especially for folders, follow [Jennifer Bryan's file naming conventions](https://youtu.be/ES1LTlnpLMk): `1985-02-06_descriptive-name-of-content`, where the date is when you created the file/folder.
