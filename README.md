<b>Technique used: cv2</b>
<b>Language used: Python</b>
<b>Tool used: jupyter notebook</b>
````
Original Image → Gray Scale → Invert → Blur → Invert → Pencil Sketch
````

## **Installation**

1. Create a virtual environment in the terminal
    ````
    python -m venv .venv
    ````

2. Select Python Interpreter
    ````
    CTRL + SHIFT + P
    > Python: Select Interpreter
    ````

3. Activate the virtual environment
    ````
    .venv\Scripts\activate
    ````

4. Install libraries
    ````
    pip install -r requirements.txt
    ````


## **Create requirements.txt with only packages being used**
 Ignore the virtual environment folder while updating requirements.txt
 
    
    pipreqs ./ --encoding=utf-8 --force --ignore .venv
    
