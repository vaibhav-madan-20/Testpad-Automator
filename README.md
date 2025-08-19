# Testpad automator

[Testpad link](https://login.testpad.chitkara.edu.in/login)

### Files

`main.ipynb` - Completes Testpad using provided answers

`answers_extractor.ipynb` - Extracts and saves solutions to already completed questions

### Steps to run

1) Use this command to install required library:-

`python -m pip install selenium==4.22.0`

2) Create a .env file like following:-

```
TESTPAD_EMAIL=<email>
TESTPAD_PASSWORD=<password>
```

3) Run `main.ipynb` to complete course

It will complete the course `COURSE_NAME` in main.ipynb file. As of now, two courses are supported - the ones in `TestpadSolutions2` folder.

Run `answers_extractor.ipynb` if you want to download and save already completed answers.

These scripts use Firefox browser.