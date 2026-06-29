# GroupDNA-WhatsApp-Analyzer
WhatsApp Chat Analyzer built using python and NumPy without pandas, Matplotlib or Regex. 
# GroupDNA - WhatsApp Chat Analyzer

## Project Description

GroupDNA is a WhatsApp Chat Analyzer developed using Python and NumPy. It reads an exported WhatsApp chat file and generates a detailed text-based report about group activity, messaging patterns, and participant behaviour.

This project is built using only Python fundamentals and NumPy without using Pandas, Matplotlib, or Regular Expressions.

---

## Features

### Feature 1 – Chat Parser
- Reads the WhatsApp chat file.
- Separates date, time, sender and message.
- Counts system messages, media messages and deleted messages.

### Feature 2 – Group Overview
- Total messages
- Total participants
- Chat period
- Messages sent by each participant

### Feature 3 – Most Active Day and Hour
- Finds the busiest day.
- Finds the busiest hour in the chat.

### Feature 4 – Activity Heatmap
- Displays participant activity by hour using a text-based heatmap.

### Feature 5 – Favourite Words
- Finds the most frequently used words after removing common stop words.

### Feature 6 – Response Patterns
- Finds the fastest and slowest replier.
- Calculates average response time.

### Feature 7 – Longest Silent Streak & Personality Archetypes
- Calculates consecutive silent days.
- Classifies users into personality archetypes such as:
  - The Spammer
  - The Storyteller
  - The Night Owl
  - The Group Mom
  - The Drama Queen
  - The Ghost

### Feature 8 – Conversation Starter Detection
- Detects who starts the most conversations after long inactive periods.

### Final Report
- Generates a complete GroupDNA report containing all analysis in a clean text format.

---

## Technologies Used

- Python 3
- NumPy
- Google Colab

---

## Constraints Followed

- No Pandas
- No Matplotlib
- No Regular Expressions (Regex)
- No external visualization libraries

---

## Files

- GroupDNA_Suhasini_<RollNumber>.ipynb
- hostel_bois.txt
- README.md

---

## How to Run

1. Open the notebook in Google Colab.
2. Upload the `hostel_bois.txt` file.
3. Run all notebook cells from top to bottom.
4. The final GroupDNA report will be displayed.

---

## Output

The notebook generates a report containing:

- Group Overview
- Messages Per Person
- Activity Heatmap
- Favourite Words
- Response Patterns
- Longest Silent Streaks
- Personality Archetypes
- Conversation Starter Detection
- Final GroupDNA Report

---

## Author

**Suhasini Mallick**

# Notebook Link
https://colab.research.google.com/drive/1eWm9I34O51tlcO6UkDVW6Y3VqYM6f_I6?usp=sharing

# sample output 

<img width="291" height="155" alt="Screenshot 2026-06-29 133528" src="https://github.com/user-attachments/assets/85353a26-8734-4554-9d30-2a783b0eac31" />
<img width="411" height="531" alt="Screenshot 2026-06-29 133453" src="https://github.com/user-attachments/assets/20cb376c-9be3-40e0-924c-5fc38c839883" />
<img width="317" height="523" alt="Screenshot 2026-06-29 133436" src="https://github.com/user-attachments/assets/2d3dac81-0739-440c-83d2-9c761b4d365a" />
<img width="258" height="221" alt="Screenshot 2026-06-29 133546" src="https://github.com/user-attachments/assets/389fe1a8-4264-4bcd-af5d-09a6d58cb3ed" />


