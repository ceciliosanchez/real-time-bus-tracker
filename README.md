# Project for MIT xPro Full Stack Developer course

## Name

A real-time bus tracker via APIs that displays the movement of buses in Boston.

## Description

A real-time webpage using data from Boston's MBTA bus company and Google Maps API, which shows the real time movements of public busses on the map.

## How to run   

1. Clone the repository to your computer from: https://github.com/ceciliosanchez/real-time-bus-tracker/tree/main
2. Obtain your own Google Cloud Maps Platform API access token by signing up at Google Cloud.
3. In the index.html file, replace YOUR_GOGLE_MAPS_KEY at line 9.
4. Sign up also at https://api-v3.mbta.com Boston Bus Public Company and generate your own API Key.
5. In the mapanimation.js file, replace your Key at line 42.
6. Then index.html will refresh with markers representing the real positions of the bus: [route]=47
7. If you want to change the bus line, you can do so on line 42, and enter any valid line number after [route]=

The bus markers will move in real-time as the API updates their positions.
Note: An internet connection is necessary to fecth data from the APIs.

## Support

Reach out at http://ceciliosanchez.com/contact/

## License information

MIT License

