<h1 align="center">
    <img src="/assets/rs_logo_bw.png" height="113" />
    <br>Raccoon Stats
</h1>

> System for statistics of games with a card reader, API and UI. **WIP**
## Project
The project consists of three different parts:

### API
[API](https://github.com/tuommii/rs-api) is made with *Go* + *GraphQL* + *PostgreSQL* and it uses GitHub as OAuth-provider.
For monitoring I'm using *Prometheus* and *Grafana*.

### Widget
[Widget](https://github.com/tuommii/rs-device) is made with *Arduino MKR1000* + *RC522* + *LCD 16x2* and coded with C/C++. You can check [source code](https://github.com/tuommii/rs-device/blob/master/device.ino) easily, basically one file.

## UI
[UI](https://github.com/tuommii/rs-ui) is made with Vue (**Source code is private before i clean it up**)

## Video
Click the image below to see the widget and app in action

[![Video](https://img.youtube.com/vi/EkBzWn7Ymk0/0.jpg)](https://www.youtube.com/watch?v=EkBzWn7Ymk0)

## Screenshot
<img src="/assets/screenshot.png" height="500" />
