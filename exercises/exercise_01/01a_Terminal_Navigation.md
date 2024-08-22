# Exercise 01a: Terminal Navigation

## Objective
Practice navigating directories using basic terminal commands.

### Instructions

1. **Navigate to the Home Directory**: 
   - Command: `cd ~`
   
2. **Create a Directory Structure**:
   - Create a new directory named `meteo_exercises` inside your home directory.
   - Inside `meteo_exercises`, create two subdirectories: `week1` and `week2`.
   - Commands:
     ```bash
     mkdir meteo_exercises
     cd meteo_exercises
     mkdir week1 week2
     ```

3. **Navigate Between Directories**:
   - Practice moving between the `week1` and `week2` directories.
   - Commands: 
     ```bash
     cd week1
     cd ../week2
     ```

4. **List the Contents**:
   - List the contents of the `meteo_exercises` directory to ensure the structure is correct.
   - Command: `ls ../`
