# Citizenship App Data

This repository contains the questions data for the Citizenship App, storing U.S. citizenship test questions and categories.

## Data Structure

### questions.json
Contains:
- `citizenshipQuestions`: Array of 100 official U.S. citizenship test questions
- `categories`: Array of question categories with associated colors

### Question Format
```json
{
  "id": number,
  "question": "string",
  "answer": "string" | ["array", "of", "strings"],
  "category": "string"
}
```

### Categories
- Principles of American Democracy
- System of Government  
- Rule of Law
- Colonial Period and Independence
- 1800s
- 1900s and Recent History
- Geography
- Symbols
- Holidays

## Usage
This data is consumed by the CitizenshipApp mobile application via raw GitHub URLs for dynamic content updates.

## Data Source
Questions sourced from official USCIS civics test study materials.