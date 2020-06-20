# Coaches-API
 A simple API about the coaches of CodeNext.

# Documentation

### URL

The API URL is: https://mikestonecolumbia.github.io/Coaches-API/CoachesInfo.json.
__No API key required.__ Simply click the link and you will be redirected to the JSON data.

### Response Format

Data will be retrieved in the form of JSON. The results will include a single JSON array called __CoachInfo__.
Within __CoachInfo__ there are 7 properties that you can extract. _name, college, association, quality, favorite_food, hobby, and quotes_. All of these values __except__ for quotes will be returned as Strings. Quotes will be returned as a __String array__

### Accepted Methods

This API only supports the __GET__ method. Other methods like __PUT__ and __POST__ are not supported.
