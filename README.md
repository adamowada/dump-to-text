# ChatGPT Dump to Text Python Script
Adam Owada

Hooray for GPT-4's 128k token limit! This Python script copies all of your project code 
into a text file for easy use with ChatGPT. See the provided `project_structure.txt` 
which is an example of the script ran inside this project.

*Attribution:* ChatGPT helped me with about 80% of the code.

## Usage
- Go to a desired project folder in your terminal and run `$ text`
- A new file named `project_structure.txt` will be created in the root of the project
- This will contain the tree of your project and the contents of all UTF-8 encoded files
- Feel free to add/modify the `IGNORE_DIRS` or `EXTENSIONS` variables inside `text` to ignore specified folders or
add extension mappings
- You can also run `$ text -c` or `$ text --copy` which will create `project_structure.txt` and copy 
the contents to your clipboard

## Install Instructions
1. Clone the repository or download the project as a .zip
2. Create a Python virtual environment
3. pip install from the requirements.txt
4. Make `text` executable: `$ chmod +x text`
5. Modify the shebang line 1 in `text` to point to your virtual environment's interpreter
6. Modify your .bashrc or .zshrc file to add the folder to your $PATH
7. Restart your terminal
8. You can now use `$ text`!
