# project 1 Oba
The repository of the first project of the minor

LINK: http://rick712.github.io/project1-quick-hack-prototype/index.html

The goal of the project was to create a web app with a SPARQL database. Allthough the main focus of the project was ADAMNET, I chose to work with WikiData, simply because there is a lot more data, and I wanted to do something with sportspersons from Amsterdam. ADAMNET lacked data about sportspersons.

## The App
My idea was to give an overview of sportspersons and their accomplishments. A user should have been able to find a sportsperson based on the sport he or she practisised. Then you could search for a person. We had one week for this project, and the first two days I really struggled with SPARQL. Because of this, I didn't have enough time to finish my app. You can search for a sportsperson, but you can't see his or hers accomplishments.

## Wishlist
Of course, something I would have wanted to accomplish, is an overview of the accomplishments of the sportspersons, since this was the main goal of my web app. Unfortunately, I didn't have enough time, but this sure is something that I would like to add to the web app.
Then, if I had more time, I would like to change the visualisation of the dataset. Now it is really gray and boring. It doesn't represent something about sports or accomplishments at all.

## Opdracht 1.2 Browser Technologies

### Images
The web app does not have images, so this is no problem

### Custom fonts
The web app uses a custom font and a fallback font. The custom font can detect if there is a slow network.

### Disable Javascript
The web app depends on Javascript to load the content, so it won't work when you disable it. I could show a message to the user when Javascript is disabled, to enable it to use the web app.

### Colour
The styling of the web app only has black, white and gray colours, so a person with colourblindness shouldn't have a problem with using the website.

### High speed internet
At slow 3G, the app itself loads within 9 seconds, which is not that bad. The SPARQL query call loads within 18 seconds. I don't really can change the fact that the query call takes 18 seconds.

### Cookies
The website doesn't use cookies.

### Local storage
The website doesn't use local storage, but it could be really usefull to store the results of the query call in the local storage. When the user has a slow network, the user doesn't need to wait several seconds.

### Mouse / trackpad
The website is accessible with tabs
