# Gestionario
The goal of this project is to create a desktop application that will store
inventory management, stock modifications, and report generation.

## Features
* Product management: add, edit, and delete product information.
* Track inventory: record stock adjustment(purchase/sales) with quantity adjustments.
* Generate reports: 
  * Weekly inventory report: list all products with current quantities.
  * Monthly inventory report: summarize total inventory value at the end of the month (reports should be printed as csv).

## Getting Started
### 1. Prerequisites
* Install python - [Python3](https://www.python.org/downloads/)

### 2. Clone the repository
* `clone` the repository by clicking on the `code` green button and choosing either `HTTPS` or `SSH`

### 3. Install Editor or IDE
* Install any text editor [VS code](https://code.visualstudio.com/download) or IDE [PyCharm Community Edition](https://www.jetbrains.com/pycharm/download/) of your choice
* Open the project in the editor or IDE
* create a virtual environment to avoid clashing other projects

### 4. Run the application
* `run` the `requirements.txt` file on your `terminal` to install needed packages
    ```
  pip install -r requirements.txt
  ```
* If using PyCharm, press the green button on the gutter

## Further Development
* Allow setting minimum stock and generate low-stock alerts
* Implement user authentication for enhanced security