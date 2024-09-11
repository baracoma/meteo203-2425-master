
# Exercise: Create a Basic Plot and Upload to GitHub

### Objective
In this exercise, you will create a basic plot using the `meteo203` environment. You will then commit your work and push it to your GitHub repository using SSH. This exercise will help you practice the essential skills of data visualization and version control.

### Initialize Github

1. **Create a GitHub Repository**:
   - Login to [GitHub](https://github.com/)
   - Click on **new** and fill out your repository details below
        - Name: `meteo203-2425-lastname`
        - Set the repository to private
        - Initialize with a **README.md** file (leave this blank)
2. **Setup your local directories**
   ``` bash
   mkdir meteo203-2425-lastname
   cd meteo203-2425-lastname
   git init
   git branch -m main # rename master branch to main
   mkdir exercises


   ``` 
4. **Link your local and remote repositories**
   ``` bash
    git remote add origin git@github.com:username/meteo203-2425-lastname.git
    
    ```
   - Don't forget to replace `username` and `lastname` with yours.
5. **Clone the remote repository**:
    ``` bash
   git pull origin main


   ``` 
7. **Double click on README.md and edit**
8. **Upload updated README.md**
    ```bash 
    git add README.md
    git commit -m "Initial commit: updated README.md"
    git push -u origin main


    ```

### Create a Plot

1. **Navigate to your project, and then exercises folder in the jupyter lab interface**
1. **Create a New Jupyter Notebook**:
   - Open a new Jupyter notebook within the `meteo203` environment.
   - Name the notebook `01_BasicPlot.ipynb`.

2. **Import Required Libraries**:
   - Start by importing the necessary libraries for creating a plot.

   ```python
   
   import numpy as np
   import matplotlib.pyplot as plt
   
   
   ```
   
7. **Generate Data for the Plot**:
    - Create data for a sine wave.
    
    ```python
    
    x = np.linspace(0, 2 * np.pi, 100)
    y = np.sin(x)
    
    
    ```

8. **Create the Plot**:
    - Plot the sine wave using Matplotlib.
    
    ```python
    
    plt.plot(x, y)
    plt.title('Sine Wave')
    plt.xlabel('x')
    plt.ylabel('sin(x)')
    plt.grid(True)
    plt.show()
    
    
    ```
    
5. **Save Your Notebook**:
    - After completing the plot, save your notebook as `01_BasicPlot.ipynb`.

6. **Prepare to Upload to GitHub**:
    - Ensure that your notebook is saved in the correct directory (e.g., `~/my_courses/meteo203/submissions/`).
    - Open the terminal within JupyterHub.

7. **Check the Status of Your Repository**:
    - In the terminal, navigate to your repository directory and check the status:
    ```bash
    
    git status
    
    
    ```

8. **Commit Your Notebook**:
    - Add the notebook to the staging area:
    ```bash
    
    git add submissions/01_BasicPlot.ipynb
    
    
    ```
    
    - Commit the notebook with a descriptive message:
    ```bash
    
    git commit -m "Added exercise 01_BasicPlot notebook"
    
    
    ```

9. **Push Your Changes to GitHub**:
    - Push your changes to the main branch of your GitHub repository:
    ```bash
    
    git push origin main
    
    
    ```

### Submission

- Ensure that your `01_BasicPlot.ipynb` notebook is successfully uploaded to your GitHub repository.
- Once uploaded, verify the file on GitHub to ensure it was committed correctly.

### Summary

This exercise helps you practice creating basic plots and reinforces your understanding of version control using Git and GitHub. By completing this exercise, you will have a better grasp of both data visualization and managing your work with GitHub.
