# Recipe App

## Table of Contents
- [Introduction](#introduction)
- [Getting Started](#getting-started)
- [Application Features](#application-features)
- [Disclaimers](#disclaimers)

## Introduction
The Recipe App is an web application that allows users to search, filter, view, and favorite both meal and drink recipes. The project was developed by a group of 5 students as part of our learning experience. It is mobile-only and runs in the web browser. This application relies on two third-party APIs to fetch all the recipes, one for meals and another for drinks. It is built using React (JavaScript), SCSS for styling, localStorage for data persistence and React hooks for sharing it among components.

## Getting Started
To get started with the Recipe App, follow the steps below:

### Cloning the Repository
  - Clone the repository and enter the created folder
  ```bash
  git clone <repository_url>
  cd recipe-app
  ```
### Install Dependencies and Start the Application

  - run the npm installation command
  ```bash
  npm install
  ```
  - start the application by executing the start script
  ```bash
  npm start
  ```
  - A window should open on you web browser

### Configuring for mobile view

  - With the application running on the browser, enter inspection mode by pressing `F12` to
  - Once in the developer tools, activate the mobile view by either:
    - Pressing CTRL + SHIFT + M.
    - Clicking on the phone/tablet icon located on the right side (if available, it should appear after performing the previous step).

## Application Features

  1. Search for Recipes: users can search for their favorite recipes using keywords.
  2. Filter Recipes: users can apply filters to narrow down the search results based on various criteria.
  3. View Recipe Details: users can view detailed information about a specific recipe, including ingredients and instructions.
  4. Save Recipes in Favorites: users can mark recipes as favorites and access them later from the favorites section.
  5. Recipe Step-by-step Checking: users can check off each step as they proceed through a recipe.
  6. Store done Recipes: done recipes are stored for future reference.

## Disclaimers

  - This project was developed by a group of 5 students, and its authorship is shared among us.
  - The Recipe App is designed as mobile-only