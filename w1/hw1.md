# Software Development Week 1 Homework

**Objective:**  
(Re)install Python, set up Visual Studio Code with the Python extension, create and activate a virtual environment (venv), install a Python package, and verify the installation by printing the package version.

---

### Instructions

#### Step 1: Python Installation  
- Download and install the latest version of Python from the official website: https://www.python.org/downloads/  
- Ensure Python is added to your system PATH during installation.

#### Step 2: Verify Python Installation  
- Open your Command Prompt (Windows) or Terminal (Linux/macOS) and run:  
  ```
  python --version
  ```  
  or  
  ```
  python3 --version
  ```  
- Confirm that the correct version of Python is displayed.

#### Step 3: Install Visual Studio Code & Python Extension  
- Download and install Visual Studio Code from https://code.visualstudio.com/  
- Open VS Code and go to the Extensions view (left sidebar)  
- Search for "Python" by Microsoft and install the extension.

#### Step 4: Create and Activate a Virtual Environment

**For Windows Command Prompt:**

1. Navigate to your project folder or create a new one:  
   ```
   mkdir myproject
   cd myproject
   ```
2. Create a virtual environment:  
   ```
   python -m venv venv
   ```
3. Activate the virtual environment:  
   ```
   venv\\Scripts\\activate
   ```

**For Linux/macOS Terminal:**

1. Navigate to your project folder or create a new one:  
   ```
   mkdir myproject
   cd myproject
   ```
2. Create a virtual environment:  
   ```
   python3 -m venv venv
   ```
3. Activate the virtual environment:  
   ```
   source venv/bin/activate
   ```

#### Step 5: Install Matplotlib Package  
With the virtual environment activated, run:  
```
pip install matplotlib
```

#### Step 6: Verify Matplotlib Installation  
- Create a Python file named `main.py` inside your project folder with the following content:
  ``` python
  import matplotlib
  print("Matplotlib version:", matplotlib.__version__)
  ```

- Run the script with:  
  ```
  python main.py
  ```
- Confirm that the Matplotlib version is printed correctly.

---


You may need to install Python vscode extention;
https://marketplace.visualstudio.com/items?itemName=ms-python.python

### Deliverables

- A screenshot showing Python version confirmation in your command line.  
- A screenshot of Visual Studio Code with the Python extension installed.  
- Confirmation screenshot of the virtual environment activated in the terminal/command prompt.  
- A screenshot or copy of the terminal output after running `main.py` showing the Matplotlib version.  
- A screenshot the `main.py` file you created.

---

If you face any issues during the installation or setup, make sure to check the official documentation or ask in the course discussion forum.
