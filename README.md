# linkedin-clean-url

Cleans the tracking stuff from LinkedIn URLs.

linkedin-clean-url is a user script.
It is run just before loading the document.
If it detects the `?trk=` in the URL on
[LinkedIn](https://www.linkedin.com/), it removes the tracking query string.


### Example

**Example 1**

```
https://www.linkedin.com/pulse/how-unique-your-web-browser-electronic-frontier-report-agnihotri?trk=pulse-det-nav_art
```
becomes:
```
https://www.linkedin.com/pulse/how-unique-your-web-browser-electronic-frontier-report-agnihotri
```

**Example 2**

```
https://www.linkedin.com/home?trk=nav_responsive_tab_home
```
becomes:
```
https://www.linkedin.com/home
```


### Security

This script does not increase the security, nor it provides privacy.
LinkedIn will still be able to track you.
However, if you bookmark or share the pages,
save pages to note taking and read it later services,
getting the tracking URLs removed might be useful.

## Requirements

### Mozilla Firefox

- [Greasemonkey](https://addons.mozilla.org/en-US/firefox/addon/greasemonkey/)
  or [Scriptish](https://addons.mozilla.org/en-US/firefox/addon/scriptish/) for
  [Mozilla Firefox](https://www.mozilla.org/en-US/firefox/new/).

### Google Chrome, Chromium

- Install [Tampermonkey](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo)
  for [Google Chrome](https://www.google.com/chrome/).


## License

[FreeBSD License](LICENSE.txt)


## User Scripts

You want to install other user scripts?
Check the following sites:

- [Greasy Fork](https://greasyfork.org/en)
- [OpenUserJS](https://openuserjs.org/)
- [Userscripts.org mirror](http://userscripts-mirror.org/)
