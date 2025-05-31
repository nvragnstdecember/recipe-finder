# 🧑‍🍳 Recipe Finder - ADP Mini Project

## 📄 Abstract

The **Recipe Finder** is a Python-based mini project designed to help users discover recipes they can cook with the ingredients they already have. By leveraging Python’s data structures such as sets and dictionaries, the application performs efficient ingredient comparisons to suggest matching recipes from a predefined database. This tool encourages smarter meal planning, minimizes food waste, and demonstrates the power of simple algorithms in solving real-life problems.

---

## 🔍 Introduction

Planning meals can be challenging, especially when limited by available ingredients. Often, people either waste food or struggle to decide what to cook. The Recipe Finder simplifies this by allowing users to input their ingredients and receive matching recipe suggestions from a preset collection.

---

## 🧩 Problem Definition

Users frequently face the problem of:

- Wasting ingredients due to lack of recipe ideas
- Spending unnecessary time deciding what to cook
- Lack of technical tools to automate meal planning
- Not knowing which dishes are possible with what’s available

This project addresses these issues with a Python tool that offers relevant recipe suggestions based on available ingredients.

---

## 🔧 Proposed Methodology

The application uses a dictionary to store recipes and their required ingredients as sets. The user inputs their available ingredients, and the application matches this set with the recipe database using Python’s `issubset()` method.

### 1. 📥 User Input

- Ingredients are entered as a comma-separated list (e.g., `egg, cheese, tomato`)
- Inputs are cleaned and normalized to lowercase

### 2. 🧮 Recipe Matching Algorithm

- Each recipe is checked to see if all required ingredients are a subset of the user's available ingredients
- Matching recipes are stored and displayed

### 3. 🔁 Scalability

- New recipes can be easily added to the dictionary
- The same logic will automatically include them in search results

---

## 💻 Implementation

### 4.1 Technologies Used

| Technology   | Purpose                             |
|-------------|-------------------------------------|
| Python 3.x   | Core programming language           |
| set()        | Ingredient comparison and logic     |
| dict()       | Storage of recipe data              |
| input/output | User interaction                    |

---

## 📊 Results and Discussion

The Recipe Finder program performed effectively during testing. Key observations:

- ✅ Correctly matched available ingredients to valid recipes
- ⚡ Delivered fast results using efficient set-based comparisons
- ♻️ Helped users reduce waste and plan meals more efficiently
- 🔄 Easily extensible by adding new recipes to the dictionary

---

## ⚠️ Limitation
The current implementation requires exact matches of ingredient names. For future improvements, support for:

- Partial matching (e.g., "cheddar" as "cheese")
- Suggestions with missing ingredients
- Integration with voice assistants or web apps

---

## ✅ Conclusion
The Recipe Finder demonstrates how simple Python logic can address common daily issues like meal planning. With an intuitive interface, modular structure, and real-world applicability, it serves both as a functional tool and a solid introduction to core Python concepts such as dictionaries, sets, and input handling. Future enhancements could turn it into a full-featured smart meal assistant.

---

## 👨‍💻 Developed for
ADP Lab (Application Development using Python Laboratory)
