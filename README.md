# Triangle Type Checker

![HTML](https://img.shields.io/badge/HTML-5-orange)
![CSS](https://img.shields.io/badge/CSS-3-blue)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow)

A small web app that takes three angles and tells you what kind of triangle they form. Built to get more comfortable with conditional logic and form validation in vanilla JS.

![preview](assets/preview.PNG)

**🌐 Live Demo:** [Triangle Type Checker](https://playwithangle.netlify.app/)

## Features

- Takes three angles as input and checks if they can form a valid triangle (must add up to 180°)
- Classifies the triangle as Equilateral, Right, Obtuse, Isosceles, or Scalene
- Alerts on empty fields or invalid angle values
- Reset button to clear inputs and result

## Tech Stack

HTML5, CSS3, JavaScript (ES6)

## Project Structure

```
Triangle-Type-Checker/
├── index.html
├── style.css
├── script.js
├── assets/
└── README.md
```

## Running Locally

```bash
git clone https://github.com/chitrangna-dev/Triangle-Type-Checker.git
cd Triangle-Type-Checker
```

Open `index.html` in your preferred web browser.

## How It Works

1. User enters three angles
2. The app checks that none of the fields are empty and that the angles add up to exactly 180°
3. If valid, it goes through a set of conditions — equilateral first, then right angle, then obtuse, then isosceles, and scalene as the fallback
4. Result is shown on the page instantly, no reload

## What I Learned

While building this, I practiced:
- Validating form input before running any logic on it
- Using `if / else if` chains to classify data based on multiple overlapping conditions
- Working with the angle sum property of triangles as a validation rule
- Resetting form state and UI text with a single event listener

## Possible Improvements

- Add an Acute triangle case (currently a non-equilateral acute triangle just falls into Scalene/Isosceles without being labeled acute)
- Replace `alert()` with inline error messages for a smoother UX
- Add input restrictions so only positive numbers can be typed in the first place

## Connect

- GitHub: [chitrangna-dev](https://github.com/chitrangna-dev)
- LinkedIn: []
