# A04: Deep Learning for an 11-Year-Old

## Entropy and Cross-Entropy: The Dragon Egg Cave

**Team Root Matrix:** Cesar Noriega, Mary Ann Mastri, Luiz Paludo, Nichelle Graf

🎮 **[Play The Dragon Egg Cave](https://strong-sorbet-129611.netlify.app/)**

This project was created for **ITAI 2376 – Deep Learning** as a group assignment focused on explaining a fundamental deep learning concept in a way that an 11-year-old could understand.

Our team selected **Entropy and Cross-Entropy** and created an interactive learning game called **The Dragon Egg Cave**.

The goal of the project is to turn abstract ideas such as uncertainty, probability, prediction confidence, and classification loss into a visual and interactive experience.

---

## Project Concept

The game places the learner inside a cave containing several dragon eggs. Only one egg contains a baby dragon.

At first, the eggs appear equally likely, creating high uncertainty. As the learner receives clues, such as differences in warmth, the probabilities change and uncertainty decreases.

The game then introduces **cross-entropy** by comparing a human guess with a probability-based prediction made by Dragon-Bot.

This helps demonstrate how deep learning models evaluate predictions using probabilities rather than only making simple right-or-wrong guesses.

---

## What the Game Teaches

### Entropy

Entropy represents uncertainty.

- If all choices seem equally likely, entropy is high.
- If one choice becomes much more likely than the others, entropy decreases.
- The game uses a visual confusion meter to show how uncertainty changes.

### Cross-Entropy

Cross-entropy evaluates how well predicted confidence matches the correct answer.

- High probability assigned to the correct answer results in a smaller loss.
- Low probability assigned to the correct answer results in a larger loss.
- Highly confident incorrect predictions receive a stronger penalty.

This reflects how classification models can be evaluated during deep learning training.

---

## Human vs. Dragon-Bot

The game compares two prediction styles.

The human player makes one completely confident choice, while Dragon-Bot can distribute confidence across several possible eggs.

After the correct egg is revealed, the game compares the outcomes and demonstrates how a neural network can represent uncertainty using probabilities rather than making only an all-or-nothing guess.

---

## Design Approach

The project was designed to make a difficult mathematical topic more accessible through:

- A dragon-themed story
- Interactive sliders
- Visual probability feedback
- Entropy and cross-entropy meters
- Immediate prediction results
- Minimal mathematical notation
- A comparison between human and AI-style predictions

The focus is on helping the learner understand the meaning of the concepts before introducing more complex mathematics.

---

## Deep Learning Connection

Cross-entropy is commonly used as a **loss function for classification problems**.

During training, a neural network:

1. Makes a prediction.
2. Assigns probabilities to possible classes.
3. Compares those probabilities with the correct answer.
4. Calculates the loss.
5. Adjusts its internal weights to reduce future error.

Over time, the model learns to assign higher probabilities to correct answers and lower probabilities to incorrect answers.

---

## Project Materials

This repository contains:

- **A04_RootMatrix_ITAI2376_Report.pdf** – Project report and explanation of the team's approach
- **A04_DragonEggCave_TechnicalDocumentation.pdf** – Program structure, mathematical logic, design choices, and technical implementation
- **Reflection Journal** – Individual reflections on the project and learning experience
- **Contribution Journal** – Documentation of each team member's contributions

### Live Interactive Project

🎮 **[Launch The Dragon Egg Cave](https://strong-sorbet-129611.netlify.app/)**

---

## Course Information

**Course:** ITAI 2376 – Deep Learning  
**Assignment:** A04 – Deep Learning for an 11-Year-Old  
**Topic:** Entropy and Cross-Entropy  
**Team:** Root Matrix  
**Project Type:** Group Project

---

## Reference

Brownlee, J. (2020, December 22). *Cross-entropy for machine learning*. Machine Learning Mastery.  
https://machinelearningmastery.com/cross-entropy-for-machine-learning/

---

## Course

**Course:** ITAI 2376 – Deep Learning  
**Assignment:** A04 – Deep Learning for an 11-Year-Old  
**Topic:** Entropy and Cross-Entropy  
**Project Type:** Group Project  

---

## Reference

Brownlee, J. (2020). *Cross-Entropy for Machine Learning*. Machine Learning Mastery.
https://machinelearningmastery.com/cross-entropy-for-machine-learning/

Google for Developers. (n.d.). Machine learning crash course. Google. https://developers.google.com/machine-learning/crash-course

Wikipedia contributors. (n.d.). Entropy (information theory). In Wikipedia. https://en.wikipedia.org/wiki/Entropy_(information_theory)
