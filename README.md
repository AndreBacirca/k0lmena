<p align="center">
<img src="https://i.imgur.com/jrStTTp.png" width="400px">
</p>

# k0lmena Automation Framework

## ⚙️ Technologies

- TypeScript
- Playwright
- Cucumber
- Artillery

## 🛠️ Setting up development environment

### Prerequisites
You will need the following to run this Framework:

NodeJs:
```
https://nodejs.org/en/download/
```

Visual Studio Code:
```
https://code.visualstudio.com/download
```

Open the project and run `npm install` or `npm i` to install de dependencies and then `npx playwright install`.

## 🚀 Run the project

### Front:

Run tests with @Smoke tags: 
```
npm run test
```
Run all tests: 
```
npm run allTests
```

### Performance test:

Run Performance tests: 
```
npm run load
```

## 📋 Reports
After each execution, you can generate two types of reports

### Front Reports:

Complete report: 
```
npm run report
```

Cucumber default report: 
```
npm run report-default
```

### Performance Reports:

Local Performance report: 
```
npm run load-report
```

Performance report in the Cloud: 
```
npm run load-report-cloud
```

Note: To use the reports in the Cloud, is necessary to register in https://artillery.io and generate a KEY. This key should be replaced in the file `package.json`


## Architecture
This project contains all the logic inside of the source folder. Some of the folder you will find:

-- Features: Gherkin feature files with all the scenarios and steps.

-- Steps: Communication between features and steps functions.

-- Locators: Elements of the site to test. It could be xpath, classes, test id, etc.

-- Config: Files with general configurations of the project. Now contains the use of environments.

-- Utils: Files with reusable general functions of playwright.

## 📖 Documentation

[![Watch the video](https://img.youtube.com/vi/n7plezXinZ8/maxresdefault.jpg)](https://youtu.be/n7plezXinZ8)

## ⭐ License
This framework is Open Source :)

## 🐞 Known Issues
None for now...

## 👥 Contributors
- Gianella Vezzoni
- Danilo Vezzoni
- Maximiliano Pintos


