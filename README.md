## Overview
This README is the specification of the coding assignment for Waffle Journal. You will implement React Native app (with Expo) and push entire project files on Github once you've finished. (Please use [Gitflow](https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow#:~:text=The%20overall%20flow%20of%20Gitflow,branch%20is%20created%20from%20develop&text=When%20a%20feature%20is%20complete%20it%20is%20merged%20into%20the,merged%20into%20develop%20and%20main), so that we can see the process)  
You can use any library if you need it.   
We care about the design, so it would be great if you make a pixel-perfect app.

## App
<img width="1230" alt="Screen Shot 2021-07-17 at 11 15 44 AM" src="https://user-images.githubusercontent.com/7218094/126022915-1b33ca45-ef0a-4336-b3f2-4ab96d92b08a.png">

The assignment app is called Gifra. It has basic functionalities as an animated gif browser which contains only two screens.

 * Search & search result
 * Gif detail screen

You can check out the design file for Gifra from [here](https://www.figma.com/file/TnAosap1nyLiACN9BdLcpa/Giphy?node-id=0%3A1).

### Main features
* Search Gifs by using [Gif search Api by Giphy](https://developers.giphy.com/docs/api/endpoint#search)
* Show loading spinner while loading search result
* Display results on a FlatList
* Use [RefreshControl](https://reactnative.dev/docs/refreshcontrol) to refresh the FlatList
* Display a gif image detail when the cell gets clicked (Use `React Navigation`. Detail screen should slide in from right to left.)


## Optional
 - Adding incremental search
 - Apply Masonry list to search result list instead of fixed height images of 2 column list
 - Add an **infinite scrolling function** to the FlatList
 - Display the search history list when cursor is focused on the TextInput

If you have any questions, feel free to ask Taishi. (taishi@wafflejournal.com)
