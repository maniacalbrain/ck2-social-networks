# Deus Vult! Social Networks in Crusader Kings 2
These notebooks step through the process of extracting data from a Crusader Kings 2 save file and storing them in MonogoDB. The notebooks use pymongo and networkx to build 
networks from the data.  

To run these notebooks you will need to have a MongoDB instance running and in notebook 1 provide a path to an uncompressed save file and the 00_dynasties file. You can download a 
zip of the save file I used by clicking [here](http://www.anquantarbuile.com/static/files/ck2/ObserverModeSave.zip). This save file is from version 2.7.2, pre Jade Dragon, and running the first notebook on a newer version will bring across all dynasties and
characters though it may not pick up some of the new death traits and will not bring across the Chinese Imperial title as this is stored in a different part of the save file.

The article based on this networks can be found [here](http://anquantarbuile.com/social-networks-in-ck2) and a full list of all the networks created for this project can be found [here](https://maniacalbrain.github.io/linkurious/graphs/ck2/ck2-networks.html)

!["Royal Marriage Network colored by religion"](http://www.anquantarbuile.com/static/images/ck2/BattleNetworkReligion.png)