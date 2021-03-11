# LootFilters
## Using filters
To select a loot filter, simply select the author of the loot filter in the list of authors and then select one of the loot filters listed under that author then close the loot filter settings and hit play.  
You can press the &#128712; above the loot filter list to get more information about the filter from the author.

## Local filters
To access your own local filters put them in "Diablo II/ProjectD2/filters/local" and select them in the loot filter list, this will create a symlink to the filter you have selected when you press play, so any changes you make to the filter in that folder will get updated in game when you refresh the filter.

## Loot Filter Developers
To get your loot filter added to the launcher, either do a pull request or send the line you want added to filters.json to the mods on discord. There will be a link to your git repository for the players to get more information about your loot filter.

##### Name
The name of your list of loot filters, will be displayed in the launcher above your list of loot filters
##### Url
The url to your git repository holding a list of .filter files in the root directory
##### Author
Who made the repository, this will be listed in the launcher and all your loot filters will be listed under your name
