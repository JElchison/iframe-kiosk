# iframe-kiosk
iframe-based kiosk that uses JavaScript to continuously rotate through a list of webpages.  Includes jQuery countdown timer until next webpage.

## Example
To see a running example, check out https://jelchison.github.io/iframe-kiosk/

## Webpages
Your own custom webpages can be used, instead of the Cincinnati-centril webpages provided.  Be sure to keep `delaySec` in sync with `urls`.

### Mixed Content
Beware the standard pitfall:  Browsers may reject mixed content.  If you're serving index.html via HTTPS, browsers may not want to load HTTP webpages in the iframe.

### iframe Detection
Some websites detect iframes and break out of them.  There's no easy way around it, except to avoid using those websites in your rotation.

## Countdown Timer
A minified version of http://keith-wood.name/countdown.html is included (MIT license).
