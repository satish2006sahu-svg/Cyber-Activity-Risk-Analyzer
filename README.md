# Cyber-Activity-Risk-Analyzer

## Description
A Python program that analyzes login activity scores, categorizes them into risk levels, and applies personalized filtering based on the register number. It generates a final security report with valid, ignored, and removed entries.

## Validation Rules
- Activity score less than 0 is treated as invalid data and ignored.
- Scores between 0–30 are categorized as Low Risk.
- Scores between 31–60 are categorized as Medium Risk.
- Scores between 61–99 are categorized as High Risk.
- Scores 100 and above are categorized as Critical Risk.
- Personalized filtering is applied based on the last digit (D) of the register number:
  - If D is even → All Low Risk scores are removed.
  - If D is odd → All Critical Risk scores are removed.

## Constraints Followed
- Must use list
- Must use for loop
- Must use conditional statements
- No list comprehension
- No dictionaries
- No filter()
- No built-in sum/max/min
- No hard-coded values
## Language Used
Python
