##Problem Statement & Applications

**Problem Statement:**

This case study tackles Named Entity Recognition (NER) on Twitter data — a sequence labelling task where each token in a sentence is assigned a label indicating whether it is part of a named entity and, if so, what type (Person, Location, Company, Product, etc.) or not an entity at all (O).

Twitter NER is harder than standard NER because:

- Tweets are short, noisy, and use informal language, slang, and abbreviations
- Entity boundaries are ambiguous ("Apple" = company or fruit?)
- No guarantee of grammatical sentences

**Where this is used:**

| Application | How NER is applied |
|---|---|
| Social media monitoring | Extract brand/product mentions from tweets in real time |
| News aggregation | Identify people, organisations, and locations in articles |
| Customer support | Extract product names and issues from tickets |
| Healthcare | Extract drug names, diseases, and symptoms from clinical notes |
| Finance | Extract company names and financial instruments from reports |
| Search engines | Tag entities in documents to improve retrieval |

**Modifications and extensions:**

- **Relation Extraction**: After identifying entities, find relationships between them (e.g. "Elon Musk *founded* Tesla")
- **Entity Linking**: Map extracted entities to a knowledge base (e.g. link "Apple" to Wikidata entry Q312)
- **Event Detection**: Identify events and their participants from text
- **Slot Filling**: In dialogue systems, extract intent slots (date, location, person) from user utterances
