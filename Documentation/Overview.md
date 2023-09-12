## UI
* Floor plan for all floors, with visual elements


## Automation's
### Alerts
* Fire alarm
    * All lights on
    * All appliances off
        * Oven
        * Micro
        * Dishwasher
        * Washer/dryer

* Battery alerts 
    * All battery devices

* Door alert
    * Freezer
    * Refrigerator
    * Entrance doors

* Washer dryer
    * Alert done (interactive)
        * Disable the recurring alert        
    * Alert if not door opened after x
        * Ignore if dryer
    * Alert if arriving home and not emptied

* Oven and Micro alerts

* Dish washer
    * Alert
    * Led strip progress bar

* Robot vacuum
    * Room order to make give it the best chance to not get stuck 
        * Living room
        * Kitchen 
        * Dining
        * Hallway
        * Master 
        * Kids  

* Night mode
    * Checks all doors
        * Alert if needed
    * Checks battery state on phones and tables
        * Alert if needed

* Water leakage
    * Sink
    * Water heater
    * Water distribution cabinet


### Buttons
* All lights off
* TV
    * On
    * Off
    * TV mode 
        * TV on 
        * Kills all lights
        * Sofa light on lowest brightness
* Night mode
    * All lights off
    * Hallway and Bathroom 3% 

* Kitchen sink 4 button panel
    * Dining light on 
    * Kitchen light on (double click sets brightens 100%)
    * Vacuum Kitchen 
    * Turn off TV
* Dining light also turns on wine cabinet light
* Hallway button 
    * Double click kills all lights and appliances 
* If light on and on button is pressed light goes to max brightness


### Schedule
* Light schedule
    * All lights default brightness 
        * Depending on the time, lights will adjust by default to x% 
    * Different schedule for kids room
    * If night mode has been triggered all lights will default got to 5%
    * Outdoor lights follow sun rise and set 

* Vacuum starts when house is empty 
* Wake up lights synced to phone alarm 
* Waste alerts 
    * Metal
    * Cardboard
    * Waste

### Presences / Motion
* Checks if house Occupied or not
* Motion controlled lights for all rooms



### Power monitoring
* Appliances
* All lights
    * This uses power calc based on %
    * Custom power curve is created from testing each type 
* TV
* Servers
* Car Charger
* Floor heating
* Vacuum


### Power save
* Night and work temp control for heating 
    * Wil be overridden if someone is in the house or arriving


### Alarm 
Under development

* Motion, Doors, Vibration(not really doing anything)
    * Auto on/off based on presence 

### Plans 
* Smart door locks entrance 
* Visual alert for refrigerator/freezer door
* Power monitoring
    * Water heaters
    * Boiler plate
* Light switch off to disable motion sensing for that room 
* Bed presence
* MMWave for living room
* Door bell 