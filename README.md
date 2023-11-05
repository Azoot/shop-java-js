# Codecool Shop Web Application

This repository contains a simple web application for an online shop developed using Java and Thymeleaf. It allows users to view and shop for various products in different categories. Below, you'll find an overview of the application's structure and functionality.

## Table of Contents

- [Application Overview](#application-overview)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)

## Application Overview

The Codecool Shop is a web-based online shop where users can browse and purchase products in different categories. It includes features for viewing product details, adding items to the shopping cart, and viewing the shopping cart. The application is built using Java, Thymeleaf, and the Model-View-Controller (MVC) architecture.

## Prerequisites

Before running the application, make sure you have the following prerequisites installed on your system:

- Java Development Kit (JDK)
- Apache Maven (for building and managing dependencies)

## Installation

1. Clone this repository to your local machine:
   ```bash
   git clone <repository-url>
2. Navigate to the project directory:
    ```bash
      cd codecool-shop-web
    ```
3.Build the project using Maven:
```bash
mvn clean package
```
This will compile the source code and generate a JAR file.

# Usage

1. Start the application by running the generated JAR file:

```bash
Copy code
java -jar target/codecool-shop-web-1.0.jar
```
2. Open a web browser and access the application by navigating to http://localhost:8080.

3. Browse through the product categories and add items to your shopping cart.

4. You can view your shopping cart by clicking on the cart icon.

# Project Structure
The project structure is organized as follows:

- src/main/java: Java source code files.
- src/main/resources: Configuration files and HTML templates.
- static/css: CSS styles for the web pages.
- templates: HTML templates used by Thymeleaf.
- pom.xml: Maven project configuration file.
