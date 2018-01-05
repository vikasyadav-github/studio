# [m28.studio](https://m28.studio)

## What is this?

A simple catalogue of browser MMO games with a lot of focus on being well curated and simple. The list of games is randomized every time the page is loaded to give all games a fair chance of getting discovered.

## How can I get my game added?

Please submit a pull request with a data file (see the "data/" directory for examples) and a 1200x800 png image.

Remember that the vetting process is pretty rigorous, it's essentially done by [me](https://github.com/Matheus28/) alone, and I prefer games that I find fun, unique and/or interesting.

## What does the pull request need to look like?

You need a 1200x800 png image (goes in /static/images/), plus a data file (goes in /data/).

The contents of the data file need to be the following (don't include the comments):

    {
    	"name": "Game name",
    	"href": "Game URL (starting with http:// or https://, prefer https if your game supports it)",
    	"image": "images/<your image file>.png",
    	"caption": "Enter your caption here, short and in a neutral tone. See other games for examples",
      
      // Only include if you are linking back to m28.studio (optional).
      // If you change your mind please submit a pull request changing this
    	"hasLinkBack": true
    }
    
If you'd like to update any data or images related to your game please submit a pull request.

## Do I need to link back to m28.studio?

Not at all. We provide a small visibility advantage to games that do, making it more likely that they'll be closer to the top of the list. But you're not required to link to the list to be listed.

If you do link back to m28.studio, please prefer naming the link "More games", as the term ".io games" is incredibly non-descriptive.
