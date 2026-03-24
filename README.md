# Roller Animated Page — CSS Animation Study

A responsive front-end study project built to explore and practice **CSS animations, motion design, and modern styling architecture** using only HTML and CSS.

---

## Description

This project focuses on implementing **animation-driven UI patterns**, simulating interactions and motion commonly found in modern landing pages.

The goal is to understand how to structure, control, and optimize animations using native CSS features.

---

## CSS Concepts Studied

This project demonstrates the following CSS concepts and best practices:

- **CSS Custom Properties (Variables)**  
  Used to centralize design tokens such as colors, typography, spacing, and layout constraints (desktop/mobile containers).

- **CSS Reset & Base Styles**  
  Applied consistent resets (box-sizing, margin/padding) to ensure predictable rendering across browsers.

- **Responsive Design**  
  Mobile-first base with desktop overrides using:
  ```css
  @media (width >= 80em)

Adapting layout, spacing, and animation behavior.

* **Modern Layout Techniques**

  * **Flexbox** for alignment and distribution
  * **CSS Grid** for structured layouts

* **Utility Classes**
  Reusable classes for spacing, alignment, and layout patterns to reduce repetition and improve scalability.

* **Modular CSS Architecture**
  Styles split into multiple files (tokens, utilities, components, sections) and composed via a central entry file.

* **CSS Animations (Keyframes)**
  Custom `@keyframes` used for:

  * Entrance animations
  * Sequential motion
  * Looping effects

* **CSS Transitions**
  Smooth state changes for hover and interaction feedback.

* **Transform-Based Animations**
  Heavy usage of:

  * `translate`
  * `scale`
  * `rotate`

  Optimized for performance (GPU-accelerated, no layout reflow).

* **Timing Functions (Easing)**
  Use of `ease`, `ease-in-out`, and `cubic-bezier()` to simulate natural motion and bounce effects.

* **Animation Composition**
  Combining:

  * `opacity + transform`
  * delays (`animation-delay`)
  * multiple elements sequencing

* **Hover & Microinteractions**
  Interactive feedback using transitions and transforms.

---

## Project Structure

* `index.html`: Semantic HTML structure used as animation base.
* `styles/`: Modular CSS organization:

  * `global.css`: Tokens (variables), resets, base styles
  * `utils.css`: Utility classes (spacing, layout helpers)
  * `animations.css`: Keyframes and animation definitions
  * `components/`: Reusable UI parts (buttons, cards, etc.)
  * `sections/`: Section-specific styles
  * `index.css`: Main file importing all styles
* `assets/`: Images and visual resources

---

## Technologies Used

* HTML5
* CSS3

  * Custom Properties
  * Flexbox
  * Grid
  * Keyframes Animations
  * Transitions
  * Media Queries

---

## How to View

[Link do projeto](https://erikmatheussilva.github.io/roller-animated-page/)
---

## Learning Outcomes

This project was used to practice:

* Structuring a scalable CSS architecture
* Building animation systems using only CSS
* Creating smooth, performant UI motion
* Managing responsive layouts with animation
* Using design tokens for consistency
* Separating concerns (tokens, utilities, animations, components)

