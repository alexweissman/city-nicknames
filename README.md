# City Nicknames
A collection of informal, unofficial, slang, and historical names for the largest cities worldwide (and a few countries, too!)  Implemented as a simple JSON mapping of nicknames to proper names.

Compiled from Wikipedia, Twitter, and personal experience.

## Scope

Some nicknames are ambiguous, and have been used to refer to more than one major city.  For example, "Pearl of the Orient" has been used to refer to Shanghai, Hong Kong, and the Phillipines.  In this case, we omit the nickname entirely from the list.  This is done to avoid the need for contextual disambiguation, for example in natural language processing tasks, etc.

We acknowledge that there are many cities that share an official name as well (e.g. "Boston, Massachusetts" and "Boston, Indiana").  Proper names will always be assumed to refer the city of that name with the largest population.  So, `"Beantown" : "Boston"` is referring to Boston, Massachusetts, US.

## Types of nicknames

- Vernacular names, often used in casual conversation (e.g. "Philly", "B-Town", etc).
- Historical names (e.g. "Leningrad", "Constantinople", etc).
- Official slogans and nicknames - the type of nicknames that might be promoted in a publicity campaign, but no one actually uses (e.g. "Official Host City of the Turn of the Century" for Edmonton).

## Potential applications

- Reverse geocoding based on textual location fields (Twitter, Facebook, etc)
- Analysis of historical documents
- Automated translation
- etc...

## Future work

It may be useful to map nicknames to more structured data.  For example, we could include some structured data in the proper names, including state/province and country, and name type (vernacular, historical, or official).  Also we could consider building a probabilistic model, in cases where nicknames can refer to more than one place.

It would be good to include some of the historical names from https://en.wikipedia.org/wiki/List_of_city_name_changes.  This would require a manual review, because some historical names may now be used to refer to current places.

## Submitting nicknames

If you know of an **unambiguous** nickname that we don't have listed, please open an issue for review and submission.  Or, simply submit a pull request with the changes.