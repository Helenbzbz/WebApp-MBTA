# Website Application Project

## 🎯 Project Overview
* 🎖 Take an input of a location name
* 🎬 Return the name of the nearest MTBA station and whether this station is wheelchair accessible

## 🎟 Implementation
* 🏵 I write the mbta_helper function to automatically turn a place name into longtitude and latitude and then use these information to obtain the station and whealchair information. 
* 🎼 Three html templates are used to take the input and return the output. The first html page requires the user to enter a location name through form and request. After clicking the button 'Check Nearest MBTA', it directs user to the second html page to print the name of the station and whether it's wheel chair accessible, a button can direct people back to start a new search. If the result is an error, it direct user to the third html page to tell the uer there is an index error and provide a button to redirect user back to the first html.

## 🎰 Project Refelction
* 🧩 The overall assignment goes smoothly and I was able to utilize what I learnt in class to write the mbta_helper function and design an interactive web structure. There are 2 things that could be improved in the future. 
* 🎮 First, sometimes the get_lat_long function returns data difference from what I found via Google. After I change space into %20, some research results become correct but there are still certain search results go wrong. If I have time in the future, I would try to understand what cuases such mnistakes and fix the issues. 
* 🚝 Seocnd, because sometimes the search results are not accurate, the website return an error instead of the result page. Therefore I adjust the page slightly to show the 'indexerror'page and provide a button to direct back to the orginal page. In the future, a more detailed error result might be return.
