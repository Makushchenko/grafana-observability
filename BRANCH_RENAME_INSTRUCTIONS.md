# Branch Rename Instructions

## Default Branch Rename: master → main

This repository currently has "master" as the default branch, but it should be renamed to "main" to follow modern conventions.

### To complete the branch rename:

1. **Repository Settings**: Go to the repository settings on GitHub
2. **Default Branch**: Navigate to the "Default branch" section
3. **Switch**: Click on the switch icon next to the current default branch
4. **Select**: Choose "main" as the new default branch (or create it if it doesn't exist)
5. **Update**: Confirm the change

### After renaming:

- All pull requests will automatically target the new "main" branch
- Clone URLs will use "main" as the default branch
- GitHub Pages and other services will automatically use the new default branch
- Update any CI/CD configurations that explicitly reference "master"

### Note:

This change is typically handled by repository administrators through GitHub's web interface and cannot be done through git commands in a pull request.