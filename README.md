# minor-project
group dna whatsappchat
## Project Overview

GroupDNA is a simple WhatsApp chat analysis project. It reads an exported WhatsApp group chat and uses Python to find useful information about the group's communication patterns.

The project analyzes messages, participants, active days and hours, common words, response time, silent periods, and basic personality types.

## Dataset

The project uses:

`hostel_bois.txt`

The file contains an exported WhatsApp group chat.

## Technologies Used

- Python
- NumPy
- datetime
- collections.Counter

## Main Features

### 1. Chat Parsing
The WhatsApp chat is read line by line and divided into:
- Date and time
- Sender
- Message text

Special entries such as media messages, deleted messages, and system messages are handled separately.

### 2. Group Overview
The program calculates:
- Total number of messages
- Number of participants
- Messages sent by each participant

### 3. Activity Analysis
The program finds:
- Busiest day
- Busiest hour
- Most active participant

### 4. Activity Heatmap
A NumPy matrix is created using participants and hours of the day. This helps show when each participant is most active.

### 5. Top Words
The program counts frequently used words and removes common words so that more useful words can be identified.

### 6. Response Speed and Silent Streaks
Message timestamps are compared to find reply gaps and periods when the group stayed silent.

### 7. Personality Archetypes
Each participant is assigned one simple personality archetype based on their message behaviour.

The archetypes used are:
- The Spammer
- The Group Mom
- The Night Owl
- The Storyteller
- The Drama Queen
- The Ghost
- The Comedian
- The Question Master

### 8. Final Report
The notebook combines the main results into a final GroupDNA report.

## Project Files

```text
GroupDNA_WhatsApp_Chat_Analyzer_Veeralakshmi_90percent_with_comments.ipynb
hostel_bois.txt
README.md
```

## How to Run

1. Keep `hostel_bois.txt` in the same folder as the notebook.
2. Open the `.ipynb` file in Jupyter Notebook, JupyterLab, Google Colab, or VS Code.
3. Run the cells from top to bottom.
4. Check the output of each analysis section.
5. The final cell displays the GroupDNA report.

## Important Notes

- The project uses NumPy for numerical analysis.
- Pandas and Matplotlib are not required.
- The analysis is based only on the messages available in the supplied dataset.
- Some WhatsApp special messages are excluded from normal message statistics.

## Expected Output

The notebook produces results such as:

- Group message count
- Participant count
- Individual message counts
- Busiest day and hour
- Participant activity matrix
- Top words
- Response-time information
- Silent streak information
- Individual personality archetypes
- Final GroupDNA summary

  it look like this:
  
  <img width="620" height="448" alt="Screenshot 2026-09-20 170100" src="https://github.com/user-attachments/assets/980affff-9e40-42d5-9e30-1452e621cc85" />
  <img width="847" height="252" alt="Screenshot 2026-09-20 170039" src="https://github.com/user-attachments/assets/02d09629-8539-4241-bf0e-87dd63f6da77" />


## Author

**Navyashree S**

**Project:** GroupDNA - WhatsApp Chat Analyzer

