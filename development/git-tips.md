# Git Tips and Tricks

A collection of useful Git commands and workflows.

## Common Commands

### Viewing History
```bash
# Show commit history with graph
git log --oneline --graph --all

# Show changes in a specific commit
git show <commit-hash>
```

### Branching
```bash
# Create and switch to a new branch
git checkout -b <branch-name>

# Delete a local branch
git branch -d <branch-name>
```

### Undoing Changes
```bash
# Undo last commit but keep changes
git reset --soft HEAD~1

# Discard local changes to a file
git checkout -- <file>
```

## Best Practices

1. Write clear, descriptive commit messages
2. Commit often with small, logical changes
3. Pull before pushing to avoid conflicts
4. Use branches for new features

## Resources

- [Pro Git Book](https://git-scm.com/book/en/v2)
- [GitHub Guides](https://guides.github.com/)
