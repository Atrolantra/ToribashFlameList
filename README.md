# ToribashFlameList
Going to make a nice js app for people to search a list of all of the flames in the game.
- [ ] Get all flames saved into a datasource.
  - [ ] Find suitable data source.
  - [ ] Make script to scrape data from most known flames [here](http://forum.toribash.com/showthread.php?t=556523) and add to data source.
  - [ ] Find a good way to check for new flames created and add these to data source.
    - [ ] No direct flame API for this so it will have to use the API to simply check every item id from the last one checked last time and add data for any that are flames. (Not sure how much of the actual flame data desired can be gotten even from the shop/item API so may need to scrape actual item id pages still.)
  - [ ] Investigate the js library and get it to read and display the data from our data source instead of hard coded html.
- [ ] Tinker with any design/layout improvements as well as settings and other modifications to get best functionality.
- [ ] Consider setting up an API to allow people to query the flame data here.
- [ ] Consider making a stats page to show interesting aspects of flames.
- [ ] Find a way to access the flame's data string and spec parameters and have them available too. 
  - [ ] I believe these are available in Toribash/data/flames.dat but I'm unsure if all are there or just ones seen ingame. Also not sure of ordering if any etc. Needs investigation.
- [ ] Better way to display the date.
- [ ] Flame names link to their itemid page.
- [ ] Consider how doable it'd be to list current owner too.
  - [ ] API could be used.
    - [ ] Find out how to call it efficiently.
    - [ ] Find out how to call it while keeping login details etc safe if it is to be done dynamically from here somehow.
    - [ ] Otherwise (and especially if datasource is external somewhere) consider making a script to run at a certain interval and update this information.
