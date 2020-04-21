## An interesting approach
This approach serves as an example of using external/unusual data sources...
### Problem Statement
Better align wine style marketing to target segments
- Text mined 24K internal tasting notes for key palate and nose descriptors against winemaker, varietal, wine style, vintage, appellation etc and created a consumer focused scoring hierarchy for each
- Web-scraped an additional 50K tasting notes of the same products to add a “control” for winemaker bias
- Initially used a thesaurus based scorer (frequency of terms and term pairs – after irrelevant parts of speech were removed)
- Switched palate to an ordinal system thereby complicating everything
- Brought in 550K transactions with A/S/L demographic data and built a classifier, affinity model and demographic clusterer
- Text-processing
- Data mining for clustering/classifying
- Sources such as sharepoint, oracle databases, salesforce, direct to consumer data
### End Result
Ability to classify wines based on nose, palate profiles and link those to consumer preferences based on individual demographic data - wealth, physical location, age, education
Used for NPD and targeted marketing, consumer communication (language styles and preferences)...Yes women in age group xx DO care about appellation, they care slightly more than other women and a lot more than men