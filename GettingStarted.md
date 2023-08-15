# Getting Started - Installation & General Commands of MambaForge and Terminal

## Step 1: Set up your Terminal
I used a Windows computer for this project, and following these ![instructions](https://learn.microsoft.com/en-us/windows/terminal/install) to set up my own terminal. Then you can input commands directly into your computer to actually install MambaForge, update environments with new packages, and navigate through your directory to find the path of files to insert into JupyterLab, not to mention launch a locally hosted JupyterLab.

## Step 2: Install MambaForge
The first step I took was installing the package manager, mambaforge, so that I could create an environment, or container for necessary Python packages with the code and functions used throughout the project. Mambaforge is like a shinier, newer version of Conda (short for the manager, Anaconda), so if you already have conda installed you should still be fine. Just make sure to convert initial lines in commands from conda to mamba or vice versa depending on the manager you decide to download.

To install mambaforge, I used the following ![instructions](https://biapol.github.io/blog/mara_lampert/getting_started_with_mambaforge_and_python/readme.html) curteosy of Mara Lampert.

## Step 3: Know how to navigate your local computer directory.

This includes basic commands (all mine are for Windows, consult google or ChatGPT if you have a different operator) to input into your terminal:

1. How to open your command line - "cmd"
2. How to check your directories (folders) - "dir"
3. How to move to another directory (change directories) - "cd FOLDER_NAME"
4. How to go back to the previous directory - "cd .."
5. How to see what packages are in your environment - "pip list"
6. How to activate said environment - "mamba activate NAME_OF_ENVIRONMENT"
7. How to deactivate said environment - "mamba deactivate"
8. How to activate JupyterLab within that environment, after opening the environment - "jupyter lab"

## Step 3: Create an environment with the correct packages needed (I have provided the environment you will need in the files titled "environment.yml"):
Whether you have forked this repo or are chosing which files to download, navigate to the directory that contains the "environment.yml" file in your terminal.
Then input the following code: "mamba env create -f environment.yml" 
The name of this environment is AOS, which you will input in any code above that included "NAME_OF_ENVIRONMENT". You can also add packages to this environment, but make sure it does not interfere with the version of other installed packages as this includes all the code you will need to access Argo data.

## Step 4: Download ANDRO and EM-APEX data 
1. The ANDRO data was too large a file to upload to this repo, so I recommend downloading it from ![SEANOA](https://www.seanoe.org/data/00360/47077/); I used the "Data Release 2022" which was a .dat file! 
2. EM-APEX data may have more restricted access, for now the actual data files are available to those who request access in a google drive folder - https://drive.google.com/drive/u/0/folders/1BvXYwmgoX-ykYWAyKgMihT0gSBF3FFqH. The data you will want to download to run my code on your own include the "vel_gps_interpolated.parquet" and "ctd_points_allexperiments.parquet" files; for permission to access please contact either James Girton at girton@uw.edu or Emilio Mayorga at Emilio Mayorga at emiliom@uw.edu.

## Step 5: Optional 
For more information on Argo as a program, you can also fork this ![repo](https://github.com/emiliom/argoonlineschool/tree/em_notebook_fixes) that my mentor, Emilio Mayorga, provided that has fixed many of the existing coding errors that ARGO Online School had with its existing notebooks as of August 2023. It also contains the environment file you needed in Step 3. This Argo Online school provides more information about the Argo float program, data management, and other means of accessing data that I did not utalize in depth but might be helpful for other projects.
