# ALXprodev-advanced_git
This repository showcases advanced Git practices as part of the ALX Professional Developer program. It adheres to the GitFlow branching model and incorporates automated Git hooks to ensure consistency and enhance team collaboration.

📁 Project Structure
login-page
README.md — Documentation for the login page component

signup-page
README.md — Documentation for the signup page component
README.md — This file

⚙️ Implemented Git Hooks
✅ Pre-commit Hook
Purpose: Ensures that each subdirectory in the repository has a README.md file.
Behavior: Blocks commits if any directory is missing a README.md, upholding documentation standards.

✅ Post-merge Hook
Purpose: Records all successful merges into the main branch.
Behavior: After a merge into the main branch, it adds a log entry with details about the merge.

🌱 GitFlow Branching
This repository employs the GitFlow workflow:
main: Stable, production-ready code
develop: Active development branch
feature/, release/, hotfix/: Temporary branches for specific tasks within GitFlow
