# joplin-theme

This repo houses my Joplin theme. Joplin is an open source note taking app.
Learn more about [Joplin](http://joplinapp.org).

## Screenshots
Here it is at normal zoom.
- ![normal-zoom.png](normal-zoom.png)

Here's a wide view.
- ![full-screen.png](full-screen.png)

## To use
1. From the Joplin app, navigate to Joplin > Preferences > Appearances

1. Under advanced settings:
- Upload userstyles.css to `Custom stylesheet for rendered Markdown`
- Upload userchrome.css to `Custom stylesheet for Joplin-wide app styles`

1. Install fonts on your computer
This theme assumes you have IBM Plex Sans and Mono installed on your machine. Install those from https://github.com/IBM/plex or change the following lines in both css files to your favorite font:
`--font-sans: "IBM Plex Sans";`
`--font-mono: "IBM Plex Mono";`

1. Things looking weird?
- Make sure to select the "Dark" Theme in Joplin > Preferences > Appearances
- Editor font size is set to 14

## Want to tweak?
At the top of both files you can see that many things are defined as css variables. That might be a good place to start to see how the theme is built.

## Want to get rid of this?
Delete everything from the 2 css files and you will be back to normal.
