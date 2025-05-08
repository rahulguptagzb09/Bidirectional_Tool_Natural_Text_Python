# Project: Development of a Bidirectional Mapping Tool for Natural Text and Python Code

## **Scope**

- Build an interactive Google Colab notebook to convert natural language into Python code.
- Natural language input is immediately translated into clear and consistent **structured text**.
- The structured text acts as unambiguous pseudocode and is always mapped 1:1 to the Python code.
- This mapping should be based on predefined examples and rules — used both when converting natural language to structured text and structured text to code.
    
    👉 [Example](Example.md)
    
- Users can write logic in natural language, which is automatically **transformed into structured text, then into code.**
- If the user edits the code directly, it only updates the structured text — not the original natural language.

## **Deliverables**

1. **Google Colab Notebook** with two text areas and a "convert" button (using e.g. `ipywidgets`):
    - **Text 1: Natural Language Input** ➝ Automatically rewritten as clear, unambiguous structured logic.
    - **Text 2: Python Code** ➝ Automatically generated from structured text.
2. **Mapping Logic**:
    - Natural Language ➝ Structured Text (overwrites Text 1)
    - Structured Text ➝ Python Code (updates Text 2)
    - Python Code ➝ Structured Text (updates Text 1)
3. **ChatGPT API Integration**:
    - Used to handle all translation steps, following prompt rules and mapping examples.
4. **Improved Mapping Examples**:
    - Optionally refine and expand the provided example list.
        
        👉 [Example](Example.md)
        

[Example](Example.md)