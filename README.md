## joplin theme
# dark mode
a dark mode theme for Joplin.

Joplin is an open source note taking app. Learn more about [Joplin](http://joplinapp.org).

It has been tested on Mac version Joplin 1.0.194 (prod, darwin). It was originally built for 1.0.195 and the scrollbars are very slightly different than the screenshots.

## Screenshots
Here it is at normal zoom.
![v0.5.5-updates.png](/screenshots/v0.5.5-updates.png)

You can see an (older) larger view that shows the whole interface if you open `/img/full-screen.png`

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

- HINT: I often have to force quit and restart the app after applying CSS changes and switching notes, not sure why.

## 4. Tweak the variables
Lots of this theme is defined in the `:root` section of  `userstyle.css` and `userchrome.css`. You can update colors and sizing there. Make sure to update the variables in both files!

```
:root {
    --white: #FBFCFB;
    --dark-white: #EEF0EA;
    --light-grey: #A3A79F;
    --grey: #575856;
    --dark-grey: #292A28;
    --darker-grey: #1D2024;
    --black: #040404;
    --primary: #0097DB;
    --secondary: #005378;
    --base-size-1: 1px;
    --base-size-4: 4px;
    --base-size-13: 13px;
    --base-size-18: 18px;
    --base-size-24: 24px;
    --base-size-32: 32px;
    --base-size-40: 40px;
    --base-size-272: 272px;
    --font-sans: "IBM Plex Sans";
    --font-mono: "IBM Plex Mono";
    --font-weight-light: 200;
    --font-weight-base: 300;
    --font-weight-bold: 500;
    --font-line-height: 1.1em;
}
```

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
## 0.5.5
- made external link color brighter
- changed external link color variable to "secondary" to be more clear

## 0.5.4
- cleaning up docs

## 0.5.3
- fixed the resource icon size
- updated the css

## 0.5.2
- removed the hack that added an icon next to every link, looked bad for inline links, weird alignment issues. reduced the size of the Joplin J for internal links.
- fix the checkbox alignment issue seen in v1.0.194
- update h4 to match h3

## v0.5.1
- cleaning up docs

## v0.5
- Adding a release log
- Updating screenshots to show code formatting
- Updated external notes to have a box, so that they would horizontally align with the Joplin notes URLs
