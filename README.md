# AnkiSpanishScraper
Builds an Anki pack from the top 5000 most common Spanish words

The 5000 words are sourced from [A Frequency Dictionary of Spanish: Core Vocabulary for Learners](https://www.amazon.com/Frequency-Dictionary-Spanish-Vocabulary-Dictionaries/dp/0415334292).

This project uses [AnkiSharp](https://github.com/AnkiTools/AnkiSharp), a library to assist with creating the .apkg file containing the Anki information. Because the library is no longer actively maintained, it required some additional configuration to run on a MacOS, namely that the IDE has to use .net x64 for it's CLI executable.

Currently, it is a proof-of-concept project, so the CSS and other customization for the pack is rudimentary.
