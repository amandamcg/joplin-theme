## joplin theme
# dark mode
a dark mode theme for Joplin.

Joplin is an open source note taking app. Learn more about [Joplin](http://joplinapp.org).

It has been tested on Mac version Joplin 1.0.194 (prod, darwin). It was originally built for 1.0.195 and the scrollbars are very slightly different than the screenshots.

## Screenshots
Here it is at normal zoom.
![v0.5-updates.png](/screenshots/v0.5-updates.png)

You can see a larger zoomed out view if you open `/img/full-screen.png`

## 1. Install Font

This theme assumes you have IBM Plex Sans and IBM Plex Mono installed on your computer.

Install those from [https://github.com/IBM/plex](https://github.com/IBM/plex) or change the following lines in the `:root` section of  `userstyle.css` and `userchrome.css` to your favorite font:
```
--font-sans: "IBM Plex Sans";
--font-mono: "IBM Plex Mono";
```

## 2. Install Theme
- Open the Joplin app
- Navigate to  `Joplin > Preferences > Appearances`
- Click `Advanced Settings`
- Click `Custom stylesheet for rendered Markdown` and paste the content from `userstyle.css`
- Edit `Custom stylesheet for Joplin-wide app styles` and paste the content from `userchrome.css`


### Apply Changes
The css changes won't apply until you close and reopen the app.

HINT: If you are using Dev Tools to mess with CSS `Help > Toggle Developer tools`, you can hit `Command-R` (Mac) to Force Reload the app to apply the CSS without having to quit.

## 3. Check to see how it looks.
You can paste `css-sample.md` into a new Joplin note to see it in action.

- Make sure to select the "Dark" Theme in `Joplin > Preferences > Appearances`
- Editor font size is set to 14

![joplin-appearance-settings.png](/img/joplin-appearance-settings.png)

## 4. Tweak the variables
Lots of this theme is defined in the `:root` section of  `userstyle.css` and `userchrome.css`. You can update colors and sizing there.

![variable-definition.png](/img/variable-definition.png)

I prefer navigating to `~/.config/joplin-desktop` and editing the two files directly.


## Delete Theme
- Open the Joplin app
- Navigate to  `Joplin > Preferences > Appearances`
- Click `Advanced Settings`
- Click `Custom stylesheet for rendered Markdown` and delete all the CSS
- Edit `Custom stylesheet for Joplin-wide app styles` and delete all the CSS

## Want to see more themes and talk about Joplin CSS?
Visit https://discourse.joplinapp.org/t/share-your-css/1730/56

## Releases to this Theme
## v0.5.1
- cleaning up docs

## v0.5
- Adding a release log
- Updating screenshots to show code formatting
- Updated external notes to have a box, so that they would horizontally align with the Joplin notes URLs
