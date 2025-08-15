# Testpad automator

[Testpad](https://login.testpad.chitkara.edu.in/login)

## Steps to run

1) Use this command to install required library:-

`python -m pip install selenium==4.22.0`

2) Create a .env file like following:-

```
TESTPAD_EMAIL=<email>
TESTPAD_PASSWORD=<password>
```

3) Run the `main.ipynb` file (This requires Firefox browser)

It will complete the course `COURSE_NAME` in main.ipynb file. As of now, two courses are supported - the ones in `TestpadSolutions2` folder.