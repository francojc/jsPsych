# jsPsych Project Guidelines

## Running Experiments
- Open HTML files directly in browser to run experiments
- For local development, use a local server: `python -m http.server` or `npx serve`

## Project Structure
- HTML files in root directory contain complete experiments
- Images and media in `/img` directory
- Follow existing patterns for new experiments

## Code Style
- Use 2-space indentation in HTML and JavaScript
- Include descriptive comments for experiment logic
- Organize jsPsych timeline elements logically
- Use camelCase for variable names
- Prefer descriptive variable names over abbreviations
- Include comments for complex stimuli or conditional logic

## jsPsych Conventions
- Load jsPsych from CDN (currently using v8.2.1)
- Group related stimuli in timeline variables
- Initialize plugins explicitly before use
- Handle data saving appropriately for your environment
- Use preload functions for media files