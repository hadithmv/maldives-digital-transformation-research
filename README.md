# Maldives Digital Transformation: Social Media Discourse Analysis

## Research Project for Social Media and Web Science Module
**Author:** Mohamed Ashraaf Ibrahim

---

## Overview

This repository contains the data, analysis, and documentation for research examining how digital transformation in the Maldives is portrayed on X (formerly Twitter) under the Maldives 2.0 national initiative.

**Research Question:** How is digital transformation in the Maldives portrayed on X, and what socio-technical factors influence public discourse?

---

## Repository Structure

```
maldives-digital-transformation-research/
├── data/
│   ├── raw_data.csv           # 100 posts with engagement metrics
│   ├── coded_data.csv         # Thematically coded posts with sentiment
│   └── word_frequency.csv     # Word frequency for visualisation
├── analysis/
│   ├── thematic_analysis.md   # Coding methodology and theme definitions
│   └── sentiment_summary.md   # Sentiment distribution analysis
├── visualizations/
│   ├── chart_data.csv         # Data for Excel chart generation
│   └── visualization_guide.md # Step-by-step chart creation guide
├── poster/
│   └── poster_content_final.md # Complete poster text and layout
├── presentation/
│   └── presentation_script.md  # 20-minute presentation script
└── README.md
```

---

## Dataset Description

### raw_data.csv
| Column | Description |
|--------|-------------|
| Post_ID | Unique identifier (Post_001 to Post_100) |
| Date | Publication date (GMT) |
| Source_Type | Government, NGO, Business, Individual, Media, International_Org |
| Anonymized_Username | Coded username (User_001 format) |
| Post_Text | Full text content (URLs removed/placeholder) |
| Likes | Number of likes at collection time |
| Reposts | Number of reposts at collection time |
| Replies | Number of replies at collection time |

### coded_data.csv
Additional columns:
| Column | Description |
|--------|-------------|
| Sentiment | Positive, Neutral, or Negative |
| Theme_Primary | Main theme code |
| Theme_Secondary | Secondary theme code |
| Keywords | Key terms extracted from post |

---

## Key Findings

- **Sentiment:** 75% positive, 15% neutral, 10% negative
- **Top Sources:** Government (25%), NGO (25%), Business (18%), Individual (18%)
- **Peak Activity:** November 2025 (Google Dhivaru announcement)
- **Top Themes:** E-Governance (22%), Women/Youth Empowerment (18%), Infrastructure (15%)

---

## Methodology

1. **Data Collection:** Keyword/hashtag search on X (Sep 2024 - Dec 2025)
2. **Sampling:** Purposive sampling of diverse source types
3. **Analysis:** Mixed methods (quantitative metrics + qualitative thematic coding)
4. **Tools:** Microsoft Excel, Voyant Tools
5. **Ethics:** Public data only, all usernames anonymised

---

## Ethical Statement

- All data is from publicly available X posts
- No private or protected content was accessed
- Usernames have been anonymised to protect privacy
- Research conducted for academic purposes only

*Last updated: December 2025*
