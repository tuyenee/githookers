# Githookers
Githook ultilities  

## 1. Run ESLint test before git commit
Filename: /src/pre-commit
### 1.1 Prerequisities
- ESLint is installed and configured
### 1.2 Installation
- Copy `pre-commit` file into your `/.git/hooks/` folder
- `chmod +x pre-commit` if needed
### 1.3 Usage
- `pre-commit` will be triggered when `git commit`
- `pre-commit` will run ESLint test **only** on the files that have been modified/added and to be commited
- If ESLint test fails, commit will not be allowed
