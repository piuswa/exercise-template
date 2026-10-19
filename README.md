# General Homework LaTeX Template

This repository contains the LaTeX template for university homework exercises.

## 📝 Creating a New Exercise

To set up a new homework exercise, follow these steps:

1. **Copy the template:** Duplicate the `Example` folder and rename it to `ExerciseX` (where `X` is the assigned homework number).
2. **Rename the source file:** Inside your newly created folder, rename the `.tex` file to match the exercise number (e.g., `ExerciseX.tex`).
3. **Update the variables:** Open the `.tex` file, locate the definitions block, and update the following commands with your specific details:
   * `\newcommand{\authorname}{Team Member 1 \\ Team Member 2}`
   * `\newcommand{\semester}{XXXX Semester 20XX}`
   * `\newcommand{\course}{Lecture Name}`
   * `\newcommand{\homeworkNumber}{X}`

Once these steps are complete, your template is ready and you can begin writing the exercise.

## ⚙️ Automated Workflows

This repository uses GitHub Actions to streamline the review process.

When a **Pull Request** is created, an automated workflow will:
* Detect any modifications to `.tex` files.
* Automatically compile the updated LaTeX files into PDFs.
* Post a comment on the Pull Request with a direct link to preview the rendered documents.