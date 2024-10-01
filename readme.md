# LaTeX Development in VS Code with Dev Container

This project provides a Docker-based development environment for creating **ATS-optimized resumes** tailored for **big tech giants** using LaTeX, with Visual Studio Code's **Remote - Containers** feature. It allows you to create, edit, and compile professional-grade resumes or any other LaTeX documents inside a containerized environment.

## Features

- Full LaTeX environment with `texlive-full`, `texlive-latex-extra`, and `latexmk`
- LaTeX compilation and live preview using **LaTeX Workshop** extension in VS Code
- Focus on **Applicant Tracking System (ATS)** optimized resume templates suitable for **software engineering roles at top tech companies**
- Customizable Docker-based development environment
- Consistent and isolated LaTeX environment across machines

## Prerequisites

1. **Visual Studio Code**: Download and install [VS Code](https://code.visualstudio.com/).
2. **Docker**: Install [Docker](https://www.docker.com/) for your operating system.
3. **Dev Containers - Extension**: Install the "Dev Containers" extension in VS Code.

## Project Setup

1. **Clone the Repository**:
   Clone this repository or create your own project folder where you'll store the `.tex` file(s) for your ATS-optimized resume.

   ```bash
   git clone https://github.com/pritampathak96/latex-resume-template
   cd ./latex-resume-template
2. **Open Command Pallete**:
   Open command pallete (CTRL + SHIFT + P), search for "Dev Containers: Reopen in Container"
