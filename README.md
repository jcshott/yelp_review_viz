## Michelin WordViz ##

The Michelin WordViz is a service for foodies to see visualizations of the most common words found in Yelp reviews of 3 star Michelin restaurants.

## File Structure: ##

```
Michelin-WordViz/
│   README.md
│   runserver.py (server)
│    [all .py files]
│
└──────static
    │   │
    │   │───css/
    │   │    style files
    │   │
    │   │───js/
    │   │    javascript files
    │   │    
    │   │───img/
    │   │    image files
    │
    └───templates/
    │   *.html files
│
│───beautiful_soup/ [seed data]  
```


**To run the server**

From the main project directory:

```sh
$ python runserver.py
```
All routes should be written to <kbd>runsever.py</kbd> file.

All python files should be saved in the parent directory.
