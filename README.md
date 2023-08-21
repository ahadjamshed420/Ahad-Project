
# Ahad Automation Task

The project has created with the cucumber framework which used the one feature file with multiple scenarios. Log4j2 and Allure Report has also been implemented in the framework.

# Test Scenarios

- Scenario 1 : Successfull login with valid credentials
- Scenario 2: Successfull login with valid credentials with DTT
- Scenario 3: Successfull Order Placing journey


# Feature File

Created one Feature file which have three scenarios.


### Background
All the common steps adeed under the Background


### Scenario 1: Successfull login with valid credentials
Scenario 1 is all about the user getting login to the application with valid credentials and then logout the application.

### Scenario 2: Successfull login with valid credentials with DTT
DDT has been used in scenario 2 for the username and password, and the scenario is all about the user getting login to the application with valid credentials and then logout the application.

### Scenario 3: Successfull Order Placing journey
The complete order placed journey has been covered in this scenario where assertions have also been used after every action.

# PageObject
A separate class has been created for all the pages where all the methods and assertions has putted. All the element's addresses have been put in the separate Enum file and called to the page classes.

# Step Defination
### Base class
In a Base class where initialize all the variables and extend this class to all page object class and step def classe.
### StepDef class
In the stepdef class where mentioned all the steps method which are mentioned in the feature file and call all the method from the page object classes.

# Runner
The configuration has been added to the Runner class which are mentioned the feature file link, tags, and plugin for allure report

# Log4j2
log4j2 has been implemented in the framework for logging. Once the script will run the file name called app.log would be auto generated under the ResultLogs folder.

# Allure report
Allure report has been configured in the framework. Below are the steps to run the Allure Report.
1. Once the script has run the folder name allure-results would be create on the root project directory.
2. Right-click on the allure-results folder and go to option Open in >>Explorer, the project local folder would open
3. Type the allure serve on the folder command line. The Allure Report would be generated.
4. If any test case would be failed the screenshot will also be attached to the report beside the test step.
## Screenshots

![App Screenshot]()


## API Reference

#### Get all items

```http
  GET /api/items
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **Required**. Your API key |

#### Get item

```http
  GET /api/items/${id}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Id of item to fetch |

#### add(num1, num2)

Takes two numbers and returns the sum.


## Appendix

Any additional information goes here


## Authors

- [@octokatherine](https://www.github.com/octokatherine)


## Badges

Add badges from somewhere like: [shields.io](https://shields.io/)

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/)
[![AGPL License](https://img.shields.io/badge/license-AGPL-blue.svg)](http://www.gnu.org/licenses/agpl-3.0)


## Contributing

Contributions are always welcome!

See `contributing.md` for ways to get started.

Please adhere to this project's `code of conduct`.


## Demo

Insert gif or link to demo


## Deployment

To deploy this project run

```bash
  npm run deploy
```

## Color Reference

| Color             | Hex                                                                |
| ----------------- | ------------------------------------------------------------------ |
| Example Color | ![#0a192f](https://via.placeholder.com/10/0a192f?text=+) #0a192f |
| Example Color | ![#f8f8f8](https://via.placeholder.com/10/f8f8f8?text=+) #f8f8f8 |
| Example Color | ![#00b48a](https://via.placeholder.com/10/00b48a?text=+) #00b48a |
| Example Color | ![#00d1a0](https://via.placeholder.com/10/00b48a?text=+) #00d1a0 |

