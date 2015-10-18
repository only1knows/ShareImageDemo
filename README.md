## Image uploading extension for iOS demo

This is an iOS demo app that shows how to create an extension for uploading an image to a web server.

THe workflow form the user's point of view:

1. User shares an image from any app, it can be a Photos app, for example.
1. Our share extension is opened showing a previous of the image and a Post button.
1. The user can choose a destination folder for the image.
1. When user taps the Post button extension creates a background download task. The task sends a HTTP POST request with an image in its body.