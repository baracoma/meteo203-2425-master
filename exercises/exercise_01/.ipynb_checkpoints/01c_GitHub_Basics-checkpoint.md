# Exercise 01c: GitHub Basics

## Objective
Practice using GitHub to clone repositories, manage files, and push changes.

### Instructions

1. **Clone the Master Repository**:
   - Clone the master repository provided by your instructor (e.g., `meteo203-2425-master`) into your home directory.
   - Command:
     ```bash
     git clone https://github.com/INSTRUCTOR_USERNAME/meteo203-2425-master.git
     ```

2. **Set Up Your Own Repository**:
   - Create your own private repository on GitHub named `meteo203-2425-lastname`.
   - Clone your repository into the `meteo_exercises/week1` directory.

3. **Add a New File to Your Repository**:
   - Navigate into your cloned repository.
   - Create a new file named `exercise_results.txt` and add some content to it.
   - Commands:
     ```bash
     cd meteo203-2425-lastname
     echo "These are my exercise results." > exercise_results.txt
     ```

4. **Commit and Push Your Changes**:
   - Use Git to add, commit, and push your new file to GitHub.
   - Commands:
     ```bash
     git add exercise_results.txt
     git commit -m "Add exercise results file"
     git push origin master
     ```

5. **Verify the Upload**:
   - Go to your GitHub repository in your web browser to verify that the `exercise_results.txt` file has been uploaded.
