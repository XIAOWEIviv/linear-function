# Fit the Line

A small game about least squares. Each level shows a scatter of noisy points. Drag the line to fit them, then see how close you got to the ordinary least squares (OLS) solution, the best possible fit.

[![Play Now](https://img.shields.io/badge/Play%20Now-f6b94c?style=for-the-badge)](https://xiaoweiviv.github.io/linear-function/)

## How it works

- 3 levels: warm-up, negative slope, heavy noise, small sample, outliers
- Drag the handles to tilt the line, grab the line to slide it, or use the sliders
- Score per level = 100 × MSE(OLS) ÷ MSE(yours), total out of 300
- After each level, the OLS line and the noise-free true trend are revealed
- Toggle residuals as lines or as literal squares to see what "least squares" minimizes
- From level 3 on, the MSE meter and residual view are hidden until you lock in

Full rules are in the "How it works" panel in the game.

## Tech

Single `index.html`: vanilla JavaScript and Canvas, no dependencies. Hosted on GitHub Pages.
