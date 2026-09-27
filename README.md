# GroupDNA — WhatsApp Group Chat Analyzer

A Python tool that parses a WhatsApp group chat export and generates a personality and 
activity analytics report: busiest hours, favourite words, response speed, silent streaks, 
and a personality archetype for every member.

# What it does:
- Parses raw WhatsApp `.txt` exports, handling system messages, media, and deleted messages
- Computes group statistics: message counts, busiest day/hour
- Builds an hour_by_person activity heatmap using NumPy
- Extracts the group's most-used words
- Calculates average response time and longest silent streaks per person
- Assigns each person a personality archetype (Insomniac, Narrator, Dramebaaz, Guardian 
  Angel, Chat Machine, Observer, and more) based on behavioural scoring rules

# Constraints
Built using only Python fundamentals and NumPy — no pandas, no matplotlib, no regex, no 
`collections.Counter`. All counting, sorting, and text processing done manually with loops, 
dictionaries, and string methods.

# How to run
1. Open the `.ipynb` notebook in Google Colab
2. Upload `hostel_bois.txt` to the Colab session (Files panel → upload)
3. Run all cells top to bottom


# About this project
This was my first-ever Python project, built as part of my internship at **Skillorbit**, 
through a project provided by **The Unlox Academy**, under the mentorship of **Mr. Girish 
Kumar**.

# Note on AI use
Claude was used as a learning aid to understand Python concepts and structure the code, since 
this was my first Python project. All code was typed and understood by me. # GroupDNA-WhatsApp-Analyzer