# Calorie and Macronutrient Tracker

This Python script helps users track their daily food intake and visualize their progress towards calorie and macronutrient (protein, fat, carbs) goals. The program allows users to add new foods, then generates graphical representations of their calorie and macronutrient consumption for the day.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Requirements](#requirements)

## Overview

This project is a calorie and macronutrient tracker where users can:
- Log foods by inputting their names, calories, protein, fat, and carbohydrate contents.
- Visualize their daily progress with interactive charts.
- Track whether they're meeting their daily goals for calories and macronutrients.

## Features

- **Food Entry**: Manually enter the food name and its corresponding nutritional values (calories, protein, fat, carbs).
- **Progress Visualization**: Generate visual charts to see progress:
  - A pie chart for macronutrient distribution.
  - Bar chart comparing actual consumption with daily macronutrient goals.
  - Pie chart of calories consumed vs remaining calories.
  - A time-based plot showing cumulative calorie consumption over the day.
  
## Requirements

To run this script, you need the following Python libraries:

```bash
pip install numpy matplotlib
