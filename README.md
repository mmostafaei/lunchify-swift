Lunchify (iOS)
===
This swift app shows a list of venues to have lunch at in Finland. Having a lunch buffet during lunch time in work-days is pretty common in Finland and many employees go to different venues during lunch.

## Supported Locations
- Helsinki City Centre
- Espoo (Keilaniemi, Leppävaara, ...)
- _More locations will be added gradually_

## Supported Languages
- English
- Suomi (Finnish)
- Svenska (Swedish, Menus are **not** available in Swedish)

## Data
Venue and meal data is provided by most of the corporate vendors (Amica, Sodexo, etc). In case there is no vendor, the data is scraped off the restaurants’ websites. Data is scraped using [Lunchify Scraper](https://github.com/sallar/lunchify-scraper) and hosted by [Lunchify API](https://github.com/sallar/lunchify-api) projects and both of them are open-sourced.

## Install
``` bash
$ git clone git@github.com:sallar/lunchify-swift.git
$ cd lunchify-swift
$ pod install
``` 
Then open the `.xcworkspace` file in XCode and run in simulator or on your device.

## Acknowledgements
- [Farzad Nazifi](https://github.com/euwars) for a great deal of help during development.
- [Arash Asghari](https://twitter.com/_arashsghari) for helping with the graphic design
- Some circular icons by [Freepik](http://www.freepik.com/)
- Illustrations by [Swifticons](http://swifticons.com/)

## Apple App Store
Please don’t submit direct copies of this project to App Store as it’s already there.

[![](https://lunchify.fi/static/badge.svg)](https://itunes.apple.com/us/app/lunchify/id1099214692?ls=1&mt=8)

## License
[MIT License](http://sallar.mit-license.org/)

