# Project Diablo 2 Loot Filters

# Table of Contents
1. [Using Online / Auto-Updating Filters](https://github.com/Project-Diablo-2/LootFilters#using-online--auto-updating-filters)
2. [Using a Local / Customized Filter](https://github.com/Project-Diablo-2/LootFilters#using-a-local--customized-filter)
3. [For Loot Filter Creators](https://github.com/Project-Diablo-2/LootFilters#for-loot-filter-creators)

# Using Online / Auto-Updating Filters
Using this option will allow you to select which filter you want without worrying about missing updates. The launcher will automatically grab the newest version of your selected filter whenever you press **Play**!

1. In the Project Diablo 2 launcher, click the **Item Filter Profiles** button:  
![PD2LootFilter01](https://github.com/user-attachments/assets/52bc9569-1e88-464c-b15a-a10841fa863e)
2. On the left-side column (1), select the loot filter creator whose filter you wish to use.
3. On the right-side column (2), select the filter you wish to use from that creator:  
![PD2LootFilter02](https://github.com/user-attachments/assets/da84c47e-11cf-4ba8-a2d3-edc76afc0631)
4. Once you select a filter from the right side, click **Save Filter** to apply it and close the filter window:  
![PD2LootFilter03](https://github.com/user-attachments/assets/b89dace1-2cec-484a-92f5-787d2fefab9f)
5. You're now ready to play!

You can also use the other buttons for extra information:
1. **Authors Page:** this will take you to the others GitHub page where there may be additional information about their filter
2. **Preview Filter:** allows you to see how the item **may** look in-game (please note it's not 100% accurate)
3. **Copy to Local:** copies the current version to a local version; this means you will not receive any further updates and will have to manually update every time the author does (not recommended)
4. **Help:** the button at the top will bring you back to this page!

# Using a Local / Customized Filter
**NOTE:** When you use a local filter this means you do not get the automatic updates from the creator. You will have to manually edit in the changes from the creator when they make them.  
To use your own local filter (useful if you customize an online one) use the **Copy to Local** button and then edit the filter in the `..\ProjectD2\filters\local\` folder. In the launcher you can now use the **Local Filter** option to use your modified version:
<img width="710" height="530" alt="PD2LootFilter04" src="https://github.com/user-attachments/assets/0642f53c-fedd-46e0-91b1-cf1307cb5e0a" />

# For Loot Filter Creators
To get your loot filter added to the launcher do a pull request to **filters.json**. The format is:
* **name:** the name for your filters; this is what will display beside the &#128712; in the launcher above your list of *.filter* files
* **url:** the URL to your GitHub repository which contains your *.filter* files (example and explanation below)
* **author:** your name; this is what will display on the left-side column in the launcher

**NOTE:** these fields cannot contain special characters (such as `&` etc) or it will break the launcher
Your repo should also contain a `README.md` file, even if it's just the header in it.

When submitting a pull request please check your edit to the JSON is valid using https://jsonlint.com/

An example JSON line using this repo would be:  
  
    {"name": "Elmegaard's Dope Filter's", "url": "https://api.github.com/repos/Project-Diablo-2/LootFilters/contents", "author": "Elmegaard"}
**Please note** this is the URL of your base GitHub page with the added `api.` at the beginning, `repos/` after `.com`, and `/contents` at the end of the URL. 
Format your line properly or your pull request will be denied.
