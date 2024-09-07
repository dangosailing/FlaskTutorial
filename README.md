 Misc
 -----------------------------------------------------------
 - Don´t install packages globally. Install them in the portable virtualenv to make sure they won´t conflict and can be reapplied 
 for new projects

- Windows and Mac have different procedures for handling installation and activating the virtual environment

 - It´s important to make sure the terminal environment and interpreter are set to the virtual environment you created
 run >pip show flask to see where the module is listed. Make sure it´s sourced to the project folder 

 
 Notes
 -----------------------------------------------------------
 Activate virtualenv(win)
 1. source venv/Scripts/activate

Handling flask not found by pylance
1. Firstly, create a virtual environment on your terminal.
2. Then install Flask by running pip install flask.
3. After installing, press CTRL+SHIFT+P.
4. Search for Python Interpreter.
5. Select your virtual environment.

URL for development server:
http://localhost:5000/