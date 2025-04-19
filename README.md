Bound for Tides - Godot 4 Project
This is a Godot 4 project for Bound for Tides, a game in development.
Project Setup

Engine: Godot 4
Repository: https://github.com/foresthump/Bound-forTides-godot-
Directory: Contains Godot project files (e.g., project.godot, scenes Frank scenes, scripts).

How to Commit and Push Changes via Git Bash
To commit and push changes to this repository using Git Bash, follow these steps:

Navigate to the Project Directory (if not already there):
cd /d/godot/bound-for-tides-v1

Stage Changes:

Stage all modified or new files (respects .gitignore):
git add .

To stage specific files (e.g., a new scene):
git add path/to/file.tscn

Commit Changes:

Create a commit with a descriptive message:
git commit -m "Your descriptive message (e.g., Added new player scene)"

Push Changes to GitHub:

Push the committed changes to the master branch:
git push origin master

If prompted, enter your GitHub username and personal access token.

Verify on GitHub:

Visit https://github.com/foresthump/Bound-forTides-godot- to confirm your changes are reflected.

Notes

Ensure your .gitignore includes Godot-specific files (e.g., \*.import/, export_presets.cfg).
If you encounter authentication issues, use a personal access token or set up SSH keys.
If the remote branch is main instead of master, replace master with main in the push command.

Contributing

Add new scenes, scripts, or assets in the Godot project.
Follow the commit and push steps above to share updates.
