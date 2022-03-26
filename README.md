# Youtube CSS v2
Yet another css for Youtube 

## Installation
- Make sure that you are using latest version of the browser.
- [Recomended Method] - Install [User css](https://chrome.google.com/webstore/detail/user-css/okpjlejfhacmgjkmknjhadmkdbcldfcb).
Open [YouTube](https://www.youtube.com/).
Click on the *User css* icon from the extension.
Copy paste the code given below in the extension.
Customise accordingly. 
DONE.
- You can also use other extensions like [Stylus](https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne) or [Tampermonkey](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo) for the same.
```css
@import url(https://slogllykop.github.io/Youtube_v2/youtube.css);
* {
    /* Primary color of the theme */
    --bright: Aqua;

    /* Secondary color of the theme */
    --bright-2: #00bbff;

    /* Tertiary color of the theme (this color should be a darker version of primary) */
    --dark: #004545;

    /* Background image */
    --bg-img: url(https://slogllykop.github.io/Youtube_v2/img/bg.gif);

    /* "Youtube" name replacement */
    --yt-name: "Slogllykop";

    /* Video-player controls */
    --player-icon-color: invert(80%) sepia(100%) saturate(7500%) hue-rotate(180deg) brightness(160%) contrast(150%)
}
```
