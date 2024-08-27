# GitHub Branch Management Guide

## 1. Create a New Branch

Create and switch to a new branch:

```
git checkout -b new-branch-name
```

## 2. Make Changes, Add, Commit, and Push

After making your changes:

```
git add .
git commit -m "Your commit message"
git push -u origin new-branch-name
```

## 3. Create a Pull Request (PR)

1. Go to the [active branches](https://github.com/Ed-Lovera/AI-PT-Project-1/branches) on GitHub
2. Click on your new branch
3. Click "New pull request"
4. Review changes and click "Create pull request"
5. Add a title and detailed description

## 4. Request a Review

1. In the new PR, find the "Reviewers" section on the right
2. Click "Add reviewers" or the gear icon
3. Type and select reviewer username(s) or team name(s)

## 5. Review Process

- Reviewers will be notified
- They can comment, approve, or request changes
- Continue pushing commits if changes are needed

## 6. Merge the Branch

After approval:
1. Click "Merge pull request" in the PR
2. Confirm the merge
3. Delete the branch if no longer needed

## Best Practices

- Respond promptly to reviewer comments
- Be open to feedback and suggestions
- Keep PRs focused and not too large
- Use clear, descriptive titles and descriptions
- Ensure your code works as expected before submitting