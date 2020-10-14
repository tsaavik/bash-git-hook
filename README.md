# bash-git-hook
A pre-commit bash hook for git, to prevent checking in broken bash scripts

Place the pre-commit file in your project/.git/hooks/
When you edit a bash script (no extension required) and attempt to commit it
the script will automatically check it for syntax errors and abort your commit
unless it passes.
