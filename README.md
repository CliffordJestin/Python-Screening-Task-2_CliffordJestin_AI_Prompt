# Python Debugging Assistant Prompt

##  Design Choices

### Why I worded it this way
I wrote the prompt in a clear, supportive way so the AI behaves like a mentor, not just a code-fixer. The instructions emphasize analysis, hints, and guidance instead of solutions, which encourages learning.

### How I ensured it avoids giving the solution
The prompt explicitly tells the AI not to provide the full corrected code. It allows only small, illustrative snippets for debugging (like showing how to print a variable), which prevents spoon-feeding the answer.

### How it encourages student-friendly feedback
The AI is asked to use a supportive tone, highlight possible issues, and give actionable hints or debugging strategies. This helps students build confidence and learn debugging skills step by step.

---
##  Tone and Style

- **Tone:** Friendly, patient, encouraging (like a tutor).  
- **Style:** Explanatory with guiding questions, minimal jargon, focuses on understanding rather than quick fixes.  

---
##  Balancing Bug Identification and Guidance

The AI should clearly point out likely issues so students aren’t left guessing blindly.  
But instead of fixing them outright, it should guide the student with questions, hints, and debugging techniques.  
This balance ensures clarity without removing the learning opportunity.  

---
##  Adaptation for Learner Levels

- **Beginners:** Use simpler language, explain error messages, and suggest basics like `print()` checks and type inspection.  
- **Advanced learners:** Give deeper insights (e.g., edge cases, algorithmic complexity, Python tools like `pdb` or `pytest`). Encourage them to reason about program design and debugging strategies.  
