Statistical Thinking (248)
For raw project instructions see: http://syllabus.africacode.net/projects/data-science-specific/statistical-thinking/

<h2> Getting started </h2>

<strong>Creating a virtual enviroment (Optional):</strong> <br>
It is recommended to create a virtual environment for every project, it allows you to install only the versions
of a module used in a project. Virtual environments can be crated with the following codes, on the command line.

- <strong>Linux/MacOS: </strong> <br>
    - installation: <br>
        sudo pip install virtualenv <br>
    - Create a virtual environment: <br>
        virtualenv virtualenv_name <br>
    - Inside my_project folder create a new virtualenv: <br>
        virtualenv env <br>
    - Activate virtualenv: <br>
        source virtualenv_name/bin/activate <br>

- <strong>Windows: </strong> <br>
    - installation: 
         pip install virtualenv 
    - create a virtual environment:
         virtualenv myenv
    - Activate virtualenv:
         myenv\Scripts\activate

<strong>Installing Dependencies:</strong> <br>
    This notebook requires multiple modules installed. To install them; <br>
     pip install -r requirements.txt <br>
    For Linux users: <br>
    The <a href="https://pypi.org/project/kaleido/">Kaleido</a> module in the requirements.txt is to load the px.line image.
