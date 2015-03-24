# City Nicknames
A collection of informal, unofficial, slang, and historical names for the largest cities worldwide (and a few countries, too!)  Implemented as a simple JSON mapping of nicknames to proper names.

Compiled from Wikipedia, Twitter, and personal experience.  Some nicknames are ambiguous, and have been used to refer to more than one city.  For example, "Pearl of the Orient" has been used to refer to Shanghai, Hong Kong, and the Phillipines.  In this case, we omit the nickname entirely from the list.  This is done to avoid the need for contextual disambiguation, for example in natural language processing tasks, etc.

## Types of nicknames

- Vernacular names, often used in casual conversation (e.g. "Philly", "B-Town", etc).
- Historical names (e.g. "Leningrad", "Constantinople", etc).
- Official slogans and nicknames - the type of nicknames that might be promoted in a publicity campaign, but no one actually uses (e.g. "Official Host City of the Turn of the Century" for Edmonton).

## Potential Applications

- Reverse geocoding based on textual location fields (Twitter, Facebook, etc)
- Analysis of historical documents
- Automated translation
- etc...