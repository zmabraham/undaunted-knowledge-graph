# Undaunted Knowledge Graph

Interactive visualization of entities extracted from "Undaunted: How the Sixth Lubavitcher Rebbe Saved Russian Jewry, Reimagined American Judaism, and Ignited a Global Jewish Renaissance" by Rabbi David Eliezrie.

## Features

- **Interactive Graph Visualization**: Explore relationships between people, places, events, institutions, communities, concepts, and teachings
- **Filter by Entity Type**: Focus on specific types of entities
- **Search**: Quick search across all entities
- **Detailed Views**: Click any node to see complete information
- **Responsive Design**: Works on desktop and mobile

## Entity Types

- **PERSON**: 189 entities - People mentioned (Rebbeim, chassidim, rabbis, family members, government officials)
- **PLACE**: 78 entities - Geographic locations (cities, towns, neighborhoods, countries)
- **EVENT**: 78 entities - Dated occurrences (arrests, liberations, journeys, arrivals, etc.)
- **TEACHING**: 66 entities - Quotes, stories, anecdotes, discourses
- **CONCEPT**: 53 entities - Chassidic ideas that develop over time
- **INSTITUTION**: 36 entities - Organizations (yeshivos, publishing houses, committees)
- **COMMUNITY**: 4 entities - Groups of chassidim in specific locations

## Data Source

Extracted from the book using Claude API with the following specification:
- 504 total entities extracted from 543 pages
- Timeline-based with temporal anchoring
- Teaching attribution (who said it vs who recorded it)
- Compatible with Seforim Atlas database schema

## Usage

Open `index.html` in a web browser to explore the knowledge graph.

## Technology

- D3.js for force-directed graph visualization
- Vanilla JavaScript for interactivity
- CSS Grid for responsive layout
- Dark theme optimized for exploration

## License

Data extracted from published work. © 2025 David Eliezrie
