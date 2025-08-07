# Word-grouping-logic
This project processes a column of words from an Excel file and groups them based on character-index similarity. Words are grouped if they share at least three matching character-index pairs (including spaces). The goal is to identify structurally similar words and analyze their frequency.

## 🔧 Features
- Reads data from Excel using `pandas`
- Cleans and filters unique, non-null entries
- Groups words with structural similarity using custom logic
- Merges overlapping groups
- Annotates each word with its group name
- Provides frequency analysis of grouped words

## 📂 Example Usage
- Excel file: `Data_for_if_statement.xlsx`
- Column name: `column`

## 📊 Output
- DataFrame with `group` column
- Frequency counts of each group
- Identification of groups with at least two members
