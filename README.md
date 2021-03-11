# Project Diablo 2 Loot Filters
## Using Online / Auto-Updating Filters
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

## Using a Local Filter
To use your own local filter (useful if you customize an online one) place the filter in the **ProjectD2\filters\local** folder. Any *.filter* file in this folder will show up in the launcher under the **Local** option:
![05](https://user-images.githubusercontent.com/40577712/110862800-c7dbc300-828d-11eb-8971-083ca0b6550c.png)

## For Loot Filter Creators
To get your loot filter added to the launcher do a pull request to **filters.json**. The format is:
* **name:** the name for your filters; this is what will display beside the &#128712; in the launcher above your list of *.filter* files
* **url:** the URL to your GitHub repository which contains your *.filter* files
* **author:** your name; this is what will display on the left-side column in the launcher

An example JSON line using this repo would be:  
  
    {"name": "Elmegaard's Dope Filter's", "url": "https://api.github.com/Project-Diablo-2/LootFilters/contents", "author": "Elmegaard"}
