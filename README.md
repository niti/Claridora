# Claridora

----
## what is Claridora?

Claridora allows you to find a new way to discover music. Using Spotify and the Clarifai API, you Insert a link to an image online (that is public accessible) and you'll receive suggested tracks.

## How can I run Clairodora on my local machine?
This is a standalone javascript project, and the web application can be simply be run by opening the index.html file.

You will need to generate credentials for the Spotify API and Calrifai API.

# Credentials

1. Spotify API -- Visit  [developer.spotify.com] (https://developer.spotify.com) to generate a client id, secret id, and insert your callback url. In this project, we say http://localhost:8000/callback.html is our callback url.

2. Clarifai API --  Visit  [developer.clarifai.com] (https://developer.clarifai.com) to generate a client id, secret id, and access token.

Once all these credentials have been generated,  insert them into the appropriate fields in the app.js file of this project.

**TODO**: This project is underdevelopment.

1. Utilize local storage to generate access token with Clarifai

2. Export suggested songs to a user's playlist on Spoitfy




This project is an expansion from a project developed by [@possan] (https://github.com/possan/playlistcreator-example)
