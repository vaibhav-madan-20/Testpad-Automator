# Testpad automator

<a href="https://login.testpad.chitkara.edu.in/login">
<img src="https://login.testpad.chitkara.edu.in/images/chitkara_logo_primary.png"><br/>
Testpad link
</a>


### Files

`main.ipynb` - Completes a Testpad course using solutions provided in `Testpad-Solutions`. It will complete the course named `COURSE_NAME` in main.ipynb file. As of now, there are solutions for two courses in `Testpad-Solutions`

`answers_extractor.ipynb` - Extracts and downloads solutions for already completed questions. Saves the solutions inside folder named `COURSE_NAME`.

### Steps to run

1) Use this command to install the required library:-
`python -m pip install selenium==4.22.0`

2) Create a .env file like following:-
```
TESTPAD_EMAIL=<testpad_email>
TESTPAD_PASSWORD=<testpad_password>
```

3) 
- Run `main.ipynb` to complete a course
- Run `answers_extractor.ipynb` to download solutions to already completed questions.

Both these scripts use Firefox browser.