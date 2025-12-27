---- >8 ----
!!! FIRST TIME INSTRUCTIONS !!!
1. The user has initialized this project from a template!  Let's fill in details
2. Update pyproject.yaml with the project name and description based on the user description
3. Depending on if this is a library or a command line app, create the scaffolding in PROJECTNAME/ accordingly
4. Run 'uv lock' to generate a lockfile
5. Delete these instructions from AGENTS.md, you only run these the first time!
---- >8 ----
- Do NOT attempt to install packages unless the user has explicitly told you to do so.  Only the packages specified in
  pyproject.toml are available.  If you really want another package, ask the user about it.
- There are no nested AGENTS.md files, this is the only agents file
- Use "ruff check" to check lint, "ruff format" to autoformat files and
  "pyrefly" to typecheck.
- If you are instructed to make a PR, use conventional commits for the PR title, and include the original user prompt VERBATIM in the description.
