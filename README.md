# Project Diablo 2 Loot Filters

# Table of Contents
1. [Using Online / Auto-Updating Filters](https://github.com/Project-Diablo-2/LootFilters#using-online--auto-updating-filters)
2. [Using a Local / Customized Filter](https://github.com/Project-Diablo-2/LootFilters#using-a-local--customized-filter)
3. [For Loot Filter Creators](https://github.com/Project-Diablo-2/LootFilters#for-loot-filter-creators)

# Using Online / Auto-Updating Filters
Using this option will allow you to select which filter you want and not have to worry about missing an update. The launcher will automatically grab the newest version of your selected filter whenever you press Play!
1. In the Project Diablo 2 launcher click the "Item Filter Profiles" button:
![01](https://user-images.githubusercontent.com/40577712/110861246-e0e37480-828b-11eb-99c9-1000149c7c43.jpg)
1. On the left-side column (1) select the loot filter creator whose filter you wish to use.
1. On the right-side column (2) select the filter you wish to use from that creator:
![02](https://user-images.githubusercontent.com/40577712/110861437-20aa5c00-828c-11eb-9e8d-bd04e3e01399.png)
1. Once you select a filter from the right side you will see text saying "Config Saved", which means you are good to go!
![03](https://user-images.githubusercontent.com/40577712/110861656-72eb7d00-828c-11eb-80f0-2d586bb2773c.png)
1. Click the **X** button in the top-right corner and you're ready to play!

You can also click on the &#128712; above the right-side column to go to that creators GitHub page:
![04](https://user-images.githubusercontent.com/40577712/110861945-daa1c800-828c-11eb-95fa-7bc8714fd885.png)

# Using a Local / Customized Filter
**NOTE:** When you use a local filter this means you do not get the automatic updates from the creator. You will have to manually edit in the changes from the creator when they make them.  
To use your own local filter (useful if you customize an online one) place `default.filter` in the `ProjectD2\filters\local` folder. Now in the launcher select the **Local** option to use this filter:
![05](https://user-images.githubusercontent.com/40577712/111204358-6c1a7e00-859c-11eb-9124-66289c2a4d48.png)

# For Loot Filter Creators
To get your loot filter added to the launcher do a pull request to **filters.json**. The format is:
* **name:** the name for your filters; this is what will display beside the &#128712; in the launcher above your list of *.filter* files
* **url:** the URL to your GitHub repository which contains your *.filter* files (example and explanation below)
* **author:** your name; this is what will display on the left-side column in the launcher

An example JSON line using this repo would be:  
  
    {"name": "Elmegaard's Dope Filter's", "url": "https://api.github.com/repos/Project-Diablo-2/LootFilters/contents", "author": "Elmegaard"}
**Please note** this is the URL of your base GitHub page with the added `api.` at the beginning, `repos/` after `.com`, and `/contents` at the end of the URL. 
Format your line properly or your pull request will be denied.
