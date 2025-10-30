> Welcome to Dmenu Noter, a bash script that runs Dmenu with different functionalities to create and view your notes and library. With Dmenu Noter, you can easily organize your notes and access them directly from the Dmenu application launcher.

## ⚙️ Usage

To use Dmenu Noter, simply run the command rofi-noter in your terminal. This will open Dmenu with the available functionalities:

- 📑 Create Note
  - Basic (Markdown)
  - LaTeX
  - Beamer (Presentation)
  - R Markdown
- 🔖 View Notes
- 📚 View Library
- 📜 View Articles
-  Sync
- 󰌱 Diary

You can put your note templates inside the templates directory.

## Configuration

Dmenu Noter is customizable to suit your needs. You can change the following parameters in the script:

- **directory**: For each Functionality
- **EDITOR**: The file editor you want to open your files in
- **TERMINAL**: The terminal you want to open your notes in

## Dependencies

Before using Dmenu Noter, make sure the following dependencies are installed on your system:

- [dmenu]
- [zathura]
- [rsync]

## Installation

To install Dmenu Noter, clone the repository and run the installation script:

```bash
git clone https://github.com/Angel-Altuve/dmenu-noter.git
cd dmenu-noter
cp ./dmenu-noter ~/.local/bin
```
