# Full Stack Assesment
## Introducation
You will be implementing an Android application that will call the national weather api and populate the forecast on a screen.

All reasources and architecture has been provided to you. It will be your job to implement these resources into a functioning weather forecast app.

## The UI
The following are the two screens we would like to see implmented.
<p align=center>
  <img src="https://user-images.githubusercontent.com/82067568/206309377-a61e7589-857d-4a77-8371-3547c471d228.png" height = "500">
</p>

Screen #1 should be implmented as closely as possible to the provided screen. Margins, text size, and shades of colors don't have to be precise.

Screen #2 should consist of a textview on top and a recyclerview on the remainder of the screen. Every forecast should have a corresponding:
- icon
- time of day
- temperature

## Function 

When Screen #1's forecast button is pressed the application should initialize the forecast activity, which will call the national weather api for the forecast of a given location.

Calling the weather api is a two step process.

- The first step is to send a location request. The response will be two grid cooordinates. 

- The second step will be to send a forescast request with the previously given grid coordinates. The response will be the finale forecast for the next couple of days.

Please reference the following link: https://weather-gov.github.io/api/general-faqs
