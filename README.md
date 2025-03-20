# Git Automation Tool 🚀

A simple yet powerful Git automation script that streamlines your version control workflow by combining git add, commit, and push into a single command with randomized professional commit messages.

## Features ✨

- **One-Command Git Operations**: Combines `git add .`, `git commit`, and `git push` in a single command
- **Random Professional Commit Messages**: Generates varied, descriptive commit messages with appropriate emojis
- **Zero Configuration**: Works immediately without any setup required
- **TypeScript Project Friendly**: Includes TypeScript-specific commit messages

## How It Works 🛠️

The Git Automation tool follows a simple workflow:

1. **Stages All Changes**: Runs `git add .` to include all modified files
2. **Creates Meaningful Commits**: Selects a random professional commit message with emoji from a predefined list
3. **Pushes to Remote**: Automatically pushes your commits to the remote repository

## Limitations 🚫

- Does not allow for custom commit messages (uses random selection only)
- Not intended for projects requiring detailed commit histories
- Does not handle merge conflicts automatically
- Does not monitor changes continuously (runs only when executed)

## Getting Started 🌟

### Prerequisites

- Git installed on your system
- Node.js installed

### Installation

1. Save the script as `git.js` in your project root

2. Make it executable (optional, for Unix/Linux/Mac):
   ```bash
   chmod +x git.js
   ```

## Usage 💻

Run the automation script using Node.js:

```bash
node git.js
```

That's it! The script will:
- Stage all changes
- Create a commit with a randomly selected message
- Push the changes to your remote repository

## When to Use ⚠️

This tool is best suited for:
- Personal projects where detailed commit messages aren't critical
- Quick iterations during early development
- Solo projects where you're the only contributor

Not recommended for:
- Enterprise or team projects requiring detailed change documentation
- Projects with strict commit message conventions
- Open source projects with multiple contributors

## License 📄

This project is available as open source under the terms of the MIT License.

---


Made with ❤️ by [Harshit Duggal](https://github.com/duggal1) 
