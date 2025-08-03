# readings
Things I've read

## July 11th, 2025 - Data Consolidation

Today I consolidated all my reading data from multiple sources into a single, unified CSV file:

### What I accomplished:
- **Merged philosophy papers**: Combined two CSV files containing 47 philosophy papers, removing duplicates and cleaning up inconsistencies
- **Added archived books**: Integrated 152 books from my historical archive (2008-2018) with ratings and reviews
- **Unified current readings**: Included my current reading list from readings.md (2023-2025)
- **Data cleaning**: Fixed formatting issues, standardized categories, corrected placeholder ratings
- **Created master file**: Final `readings.csv` contains 209 total entries with consistent structure

### File structure:
- `readings.csv` - **SOURCE OF TRUTH** - My reading history (books and papers)
- `philosophy_papers.csv` - Clean philosophy papers dataset
- `books archive.csv` - Historical book archive (cleaned)
- `readings.md` - Legacy markdown version (no longer maintained)

## Category System

The readings database uses a three-level hierarchical categorization system:

### Structure: Category → Subject → Topic

**Level 1: Categories (Primary)**
- `fiction` - Literary works, novels, stories
- `non-fiction` - All non-fiction content

**Level 2: Subjects (Secondary)**
- **Fiction:** `literary fiction`, `science fiction`
- **Non-fiction:** `philosophy`, `science`, `business & economics`, `biography & memoir`, `self-improvement`, `arts & humanities`, `health & wellness`, `education`

**Level 3: Topics (Tertiary - Optional)**
Specific focus areas within subjects:
- **Arts & Humanities:** `writing`, `photography`, `creativity`
- **Biography & Memoir:** `biography`, `autobiography`, `memoir`  
- **Business & Economics:** `finance`, `economics`
- **Self-Improvement:** `psychology`, `self-help`, `productivity`
- **Science:** `mathematics`, `computer science`
- **Health & Wellness:** `fitness`

### Usage Notes:
- Topics are optional - only ~24% of entries use them
- Philosophy (largest subject with 66 entries) rarely uses topics
- System accommodates both academic papers and popular books
- Classification becomes more specific at each level

### Notes:
There are quite a few more philosophy papers that I need to add to the list, but I can't currently find the old spreadsheet and I stopped tracking the papers in my vault a long time ago. I'll need to manually enter them to catch up on the missing entries.
