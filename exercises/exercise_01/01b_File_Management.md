# Exercise 01b: File Management

## Objective
Learn to manage files using terminal commands.

### Instructions

1. **Create Files in the Directories**:
   - In the `week1` directory, create a file named `week1_notes.txt`.
   - In the `week2` directory, create a file named `week2_notes.txt`.
   - Commands:
     ```bash
     cd week1
     touch week1_notes.txt
     cd ../week2
     touch week2_notes.txt
     ```

2. **Copy and Rename Files**:
   - Copy `week1_notes.txt` from `week1` to `week2` and rename it to `week1_backup.txt`.
   - Command:
     ```bash
     cp ../week1/week1_notes.txt week1_backup.txt
     ```

3. **Delete Files**:
   - Delete `week1_backup.txt` from the `week2` directory.
   - Command: `rm week1_backup.txt`
