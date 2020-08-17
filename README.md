# rusafe

## Inspiration
As Rutgers-New Brunswick students, we are constantly reminded of all of the crime that is occurring on the streets beside us via police reports to our emails and our phones. We wanted to create a platform on which students like us can visualize where these crimes are occurring so we can understand which streets to avoid.

## What it does
RU Safe is a website that has an interactive Google Map of New Brunswick, New Jersey. It will read local police reports through Nixle and plot them on the RU Safe map so that Rutgers students can see exactly where the crimes that they are constantly alerted of took place.

## How we built it
First, we used java to read pages of Nixle alerts and to extract the locations where crimes in New Brunswick occurred. Then, those locations are automatically organized into a text file then plotted on the interactive map on our website. We created and designed our RU Safe website using html, javascript, and css. For the interactive map, we used the Google Maps API.

## Challenges we ran into
In reading the locations that were in the Nixle alerts, we had trouble originally creating a regular expression to find all of the street names. We also had trouble getting information from a url for the first time. Lastly, we had been working on RU Safe as two separate parts, and thus we struggled initially when trying to create a smooth transition between the frontend and the backend.

## Accomplishments that we're proud of
This is some of our first hackathons, and we're generally proud of our entire process and working together to make something. We each tackled something new this weekend and we all learned a lot. We're proud of ourselves for sticking through when we wanted to give up and for trying to make something to the best of our abilities.

## What we learned
We got to practice using html and javascript, which we were originally not too familiar with. We learned how to use the Google Maps JavaScript API. We also got to read more into website design and Google Cloud products. Also, to read from pages and pages of Nixle alerts, we learned how to create a regular expression to find the street names.

## What's next for RU Safe
While RU Safe can already read crime alerts and plot the location of the crimes on the map, we want for RU Safe to also detail the crimes that occurred with markers on the map in the future. Furthermore, RU Safe would like to expand beyond the streets of College Ave and New Brunswick to the other Rutgers campuses and beyond.
