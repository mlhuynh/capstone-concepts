# Capstone Concept - Linh Huỳnh

## Team members (Leave blank for none)

## Problem Statement #1: Plant Sounds

Ever curious if a plant could produce sound? PlantSounds, a piece of hardware that enables humans to listen to any plant.

## MVP Feature Set

1. Base Device:
    - Hardwire an Arduino as the primary unit that will convert electric pulses released by plants into audible sound waves (via a synthesizer).
2. "Under the hood" hardware program:
    - Sonify or convert data into sound in a semi-musical way that can be enjoyed by our auditory sensory system.
4.  Web or Mobile App where users can:
    - Log on to add their plant
    - Save recordings of their plant

### Potential Additional Features

1. See visualizaitons of their plant sonification.
2. Like or bookmark button for recordings 
3. Add animated plant avatars


## Draft Technology Choices

- Hardware: Arduino
- Backend: Arduino development environment (C++)
- Front End: Javascript, CSS/HTML, Chart.js or Plotly.js, React
- Deployment: Heroku or Github Pages

## Problem Statement #2: Parking Finder

Ever visited a friend, attended an event, or headed to a unfamiliar destination and have problems finding a parking spot? ParkingFinder can be your best friend (aka web application) to find any open or available on-street and off-sreet parking.

## MVP Feature Set

1. Capability to enter in current location
2. Based on current location, the web application should be able to show where you are on a map, relative to surrounding open parking spots or garages.
3. Selecting the icon on each open parking spot should provide a navigatable address with directions.

### Potential Additional Features

1. Create or login to account.
2. Use GPS to automatically identify current location.

## Draft Technology Choices

- Backend: Not quite sure yet
- APIs: [Inrix IQ](https://docs.inrix.com/) or Google Place API
- Front End: Javascript, CSS/HTML, React, Mapbox Studio
- Deployment: Heroku or Github Pages

## Problem Statement #3: Recylcing Finder

Have you ever had an item that you wanted to properly dispose of but don't know where or how? RecyclingFinder can aid in locating loacal, nearby businesses that accepts certain types of recycling. The goal of this web application is to help reduce the amount of recyclable items that would otherwise accumulate in our waste streams or landfills. (Limited to Washington State only or King County)

## MVP Feature Set

1. Built-in drop-down menu or capablity to query type of item to generate map of nearby recycling centers or businesses that accepts proper disposal of entered item. 
2. Capability to enter in current location
3. Based on current location, the web application should be able to show where you are on a map, relative to surrounding recycling centers or businesses.
4. Selecting the icon on each open parking spot should provide the name of the facility or business, hours or operation, a navigatable address with directions, etc.

### Potential Additional Features

1. Create or login to account.
2. Use GPS to automatically identify current location.

## Draft Technology Choices

- Backend: Not quite sure yet
- APIs: King County API, powered by Socrata
- Front End: Javascript, CSS/HTML, React, Mapbox Studio
- Deployment: Heroku or Github Pages

## Problem Statement #4: Air Quality Monitor

It's that time of the year again when pollen flies rampant in the air. With climate change unfortunately on the rise, there's also an increased frequency in wildfires over the summer that can make it particularly harder for those with asthma or allergies. With the AirCheck web or mobile application, you can easily and quickly check air quality details (including pollen count, UV, and wind direction) in a pinch.

## MVP Feature Set

1. Capability to enter in city or current location.
2. List current air quality, UV index, and pollen count.
3. Display or generate map of surrounding wildfires and reatime wind direction (to see visualization of the smoke coverage trajectory).

### Potential Additional Features

1. Create or login to account.
2. Use GPS to automatically identify current location.

## Draft Technology Choices

- Backend: Not quite sure yet
- APIs: IQAir
- Front End: Javascript, CSS/HTML, React, Mapbox Studio
- Deployment: Heroku or Github Pages

## Problem Statement #5: Plant Watering System

Are you a plant lover but life keeps throwing curveballs and you become an unintentional plant serial-killer? Well, you're in luck because PlantSaver is a hardware/software pairing that can monitor the soil status of your plant and water it whenever necessary.

## MVP Feature Set

1. Base Device:
    - Hardwire an Arduino as the primary unit that will hooked up to sensors and a water source for automated plant watering.
2. "Under the hood" hardware program:
    - Convert and transfer soil data to frontend software.
4.  Web or Mobile App where users can:
    - Display soil stats.
    - Save record (date/time) in which plant was automatically watered.
    - Indicate when water meter/source is empty and needs to be refilled.

### Potential Additional Features

1. See visualizaitons of plant in the form or graph or chart.
3. Add animated plant avatars to display happiness level of plant (sad and wilting for underwatered plant, happy and dancing for well-watered plant).


## Draft Technology Choices

- Hardware: Arduino
- Backend: Arduino development environment (C++)
- Front End: Javascript, CSS/HTML, Chart.js or Plotly.js, React
- Deployment: Heroku or Github Pages
