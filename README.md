# Neura Flashcards

#### Video Demo: https://youtu.be/_cTz-RQ2wZ8

## Description

FlashLearn is a web-based flashcard application designed to help users study using active recall.
The application allows users to import flashcards from a JSON file, flip cards to reveal answers,
navigate between cards, and switch between light and dark themes.

This project was developed as the final project for HarvardX CS50's Introduction to Computer Science
and was built using HTML, CSS, and JavaScript, without external frameworks.

## Features

- Import flashcards from a JSON file
- Flip cards to reveal answers
- Navigate between flashcards (Next / Previous)
- Light and dark mode toggle
- Responsive design
- Runs locally without a server

## JSON File Format

The JSON file must follow this structure:

```json
[
  {
    "pergunta": "What is sociology?",
    "resposta": "The scientific study of society."
  }
]

