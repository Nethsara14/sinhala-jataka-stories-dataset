# Sinhala Jataka Stories Dataset (JSON)

A structured dataset of **548 Sinhala Jataka stories** formatted as individual JSON files, complete with titles, story texts, topics, categorization tags, and life-lesson summaries.

![Stories](https://img.shields.io/badge/Stories-548-b45309?style=for-the-badge)
![Format](https://img.shields.io/badge/Format-JSON-15803d?style=for-the-badge)
![License: MIT](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)

## Web Application

Looking for the mobile-first Progressive Web App built using this dataset?
- **App Repository:** [Nethsara14/sinhala-jataka-stories](https://github.com/Nethsara14/sinhala-jataka-stories)
- **Live Demo:** [https://nethsara14.github.io/sinhala-jataka-stories/](https://nethsara14.github.io/sinhala-jataka-stories/)

## Dataset Structure

```text
Data/
├── 1.json
├── 2.json
├── ...
├── 550.json
└── index.json
```

### Individual Story Schema (`Data/<number>.json`)

Each JSON file contains the following fields:

```json
{
  "title": "Story Title in Sinhala",
  "text": "Full story text in Sinhala...",
  "topic": "Core theme or subject",
  "life_lesson_summary": "Key moral or life lesson in Sinhala",
  "tags": ["Tag1", "Tag2"]
}
```

## Author

**Sasindu Nethsara Karanayaka** · [devnethsara.com](https://devnethsara.com/)

CodeGen N3xt Solutions · © 2026

## Content Attribution & License

### Story Content Source
The original Sinhala Jataka story texts were sourced from the **University of Sri Jayewardenepura (ශ්‍රී ජයවර්ධනපුර විශ්වවිද්‍යාල වෙබ් අඩවිය)**:
- Source URL: [https://www.sjp.ac.lk/buddhism/download-buddhist-555-jathaka-katha-free-pdf/](https://www.sjp.ac.lk/buddhism/download-buddhist-555-jathaka-katha-free-pdf/)

All JSON structuring, metadata extraction, categorization tags, topics, and life-lesson summaries were engineered and curated by **Sasindu Nethsara Karanayaka** (CodeGen N3xt Solutions).

### License
The dataset structure, JSON formatting, and curated metadata are licensed under the **MIT License**.
