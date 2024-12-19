## Requirements

- pyenv

- python==3.11.3

## Setup

Welcome to my project! There are some necessary first steps in order to be able to properly read through the Jupyter notebook that walks through the results of this project. There is a requirements file found in this repository which must be used when creating your virtual environment. 


## Set up your Environment
This repo contains a requirements.txt file with a list of all the packages and dependencies you will need.

Before you can start with plotly in Jupyter Lab you have to install node.js (if you haven't done it before).
- Check **Node version**  by run the following commands:
    ```sh
    node -v
    ```
    If you haven't installed it yet, begin at `step_1`. Otherwise, proceed to `step_2`.


### **`macOS`** type the following commands : 


- `Step_1:` Update Homebrew and install Node by following commands:
    ```sh
    brew update
    brew install node
    ```

- `Step_2:` Install the virtual environment and the required packages by following commands:

    ```BASH
    pyenv local 3.11.3
    python -m venv .venv
    source .venv/bin/activate
    pip install --upgrade pip
    pip install -r requirements.txt
    ```
### **`WindowsOS`** type the following commands :


- `Step_1:` Update Chocolatey and install Node by following commands:
    ```sh
    choco upgrade chocolatey
    choco install nodejs
    ```

- `Step_2:` Install the virtual environment and the required packages by following commands.

   For `PowerShell` CLI :

    ```PowerShell
    pyenv local 3.11.3
    python -m venv .venv
    .venv\Scripts\Activate.ps1
    pip install --upgrade pip
    pip install -r requirements.txt
    ```

    For `Git-Bash` CLI :
  
    ```BASH
    pyenv local 3.11.3
    python -m venv .venv
    source .venv/Scripts/activate
    pip install --upgrade pip
    pip install -r requirements.txt
    ```
 

 **`Note:`**
    If you encounter an error when trying to run `pip install --upgrade pip`, try using the following command:

   ```Bash
   python.exe -m pip install --upgrade pip
   ```

Once you have your virtual environment set up, you are free to properly browse the contents of this repository. The purpose of this repository is to present the results of the data analysis conducted based on the home data from King County, WA in the United States. After cleaning and observing some key aspects of the data, 3 hypotheses were proposed and tested in order to better understand the data.


After this, I explored the data further in order to be able to make recommendations to my fictitious client, Nicole Johnson, a buyer who wants a lively, central neighborhood, middle price range, and to buy within a year.


The most important details from the hypotheses, hypothesis testing, recommendations, and recommendation justifications are all readily available in a presentation format in the "king_county_project_presentation.pptx" powerpoint file in this repository. For a more detailed look at how these results came about, you can refer to the "project_notebook.ipynb" Jupyter notebook. (Note that there are many images used in the Jupyter notebook in order to present important findings. These images are stored under the 'images' folder).