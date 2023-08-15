# Getting Started - Installation & General Commands of MambaForge and Terminal

## Step 1: Set up your Terminal
I used a Windows computer for this project, and following these ![instructions](https://learn.microsoft.com/en-us/windows/terminal/install) to set up my own terminal. Then you can input commands directly into your computer to actually install MambaForge, update environments with new packages, and navigate through your directory to find the path of files to insert into JupyterLab, not to mention launch a locally hosted JupyterLab.

## Step 2: Install MambaForge
The first step I took was installing the package manager, mambaforge, so that I could create an environment, or container for necessary Python packages with the code and functions used throughout the project. Mambaforge is like a shinier, newer version of Conda (short for the manager, Anaconda), so if you already have conda installed you should still be fine. Just make sure to convert initial lines in commands from conda to mamba or vice versa depending on the manager you decide to download.

To install mambaforge, I used the following ![instructions](https://biapol.github.io/blog/mara_lampert/getting_started_with_mambaforge_and_python/readme.html) curteosy of Mara Lampert.

## Step 2: Know how to navigate your local computer directory.

This includes basic commands (all mine are for Windows, consult google or ChatGPT if you have a different operator) to input into your terminal:

1. How to open your command line - "cmd"
2. How to check your directories (folders) - "dir"
3. How to move to another directory (change directories) - "cd FOLDER_NAME"
4. How to go back to the previous directory - "cd .."
5. How to create a new python package environment; But first navigate to the directory you have the environment.yml file saved in which is available in the files on the repository - "mamba env create -f environment.yml" 
6. How to see what packages are in your environment - "pip list"
7. How to activate said environment - "mamba activate NAME_OF_ENVIRONMENT"
8. How to deactivate said environment - "mamba deactivate"
9. How to activate JupyterLab within that environment, after opening the environment - "jupyter lab"

## Step 3: Create an environment with the correct packages needed (I have provided the environment you will need in the files titled "..."):
