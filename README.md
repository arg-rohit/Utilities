# Utilities

A collection of utility modules for common operations.

### Usage
This module is designed to be used as a Git submodule. To include it in your project:

```bash
# Add the submodule to your project
git submodule add <repository-url> Utilities

# If already added, update to latest version
git submodule update --remote Utilities
```

### Updating Changes
When making changes to this utility:

1. Make your changes
2. Commit and push changes to the Utilities repository
3. Update the parent project to use the new version:
```bash
cd <parent-project>
git add Utilities
git commit -m "Update Utilities submodule"
git push
