---
name: pullRequest
description: Safely manage Git changes in a team workflow by pulling before changes, reviewing modifications, creating meaningful commits, and pushing them to the remote branch.

---

# Pull Request Skill

## Workflow

Before making any code changes:

1. Check the current Git status.
2. Pull the latest changes from the remote branch.
3. Analyze the updated project state.
4. Never overwrite existing team changes.

After making changes:

1. Check `git status`.
2. Review the changes with `git diff`.
3. Analyze the changes.
4. Create a clear and meaningful commit message.
5. Commit the changes.
6. Push the commit to the remote branch.
7. Verify the final Git status.

## Rules

- Always pull before modifying code.
- Never use `git reset --hard`.
- Never force push.
- Do not overwrite another developer's changes.
- Keep commits focused and meaningful.
- Commit only the changes related to the current task.
- Verify the repository state after pushing.

