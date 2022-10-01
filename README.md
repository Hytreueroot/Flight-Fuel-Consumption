# Flight-Fuel-Consumption

In this project, a fuel consumption model was developed by working on real flight data. The goal is to develop a regression model that calculates how much fuel the plane consumes per unit time, using the right attributes.

Two datasets are available: **DataSet1_Q:** Samples from one aircraft. **DataSet2_Q:** Samples from 10 different planes. The model created with **DataSet1_Q** has been tested for **DataSet2_Q**.

* Target parameter is sum of **FF1 (lb/hr)** and **FF2 (lb/hr)**.

* In the first step, train the model using all the data.

* In the second step, a different models are trained for each flight phase: climb, cruise (fixed altitude) and descent. By looking at the Altitude and Altitude Dot parameters, the climb, descent or cruise phases are separated.

## Explanation of Data:

**Altitude (ft)**: The altitude of the aircraft.\
**Heading (deg)**: Compass direction of the aircraft.\
**CAS (kt)**: Flight speed regulated by altitude.\
**Ground speed (kt)**: The speed of the aircraft relative to the ground.\
**Mach**: The ratio of the speed of the aircraft to the speed of sound.\
**Temp (C)**: Outdoor temperature.\
**APU Fuel**: A system used when the plane is on the ground.\
**Mass**: Mass of aircraft.\
**FF1 (lb/hr)**: Instantaneous fuel consumption of the first engine (lbs per hour).\
**FF2 (lb/hr)**: Instantaneous fuel consumption of the second engine (lbs per hour).\
**Throttle 1/2**: Throttle levels of engines.\
**Course (deg)**: Another expression of the compass direction of the airplane.\
**Wind Direction (deg)**: Wind direction.\
**Wind Speed (kt)**: Wind speed.\
**Flap (deg)**: The extent to which the parts that provide extra wing surface, used only for takeoff and landing, are opened.\
**Landing Gear**: Whether the landing gear is on or off.\
**Speed break**: Air brake.\
**Zero Fuel Weight (lbs)**: The weight of the aircraft without fuel.\
**Fuel Onboard (kg)**: The remaining amount of fuel.\
**Air pressure (mb)**: Atmospheric pressure at the location.\
**Ground Speed Dot (kt/s2)**: Acceleration of the aircraft.\
**Altitude Dot (ft/s)**: The amount of rise/fall per unit time.\
**Heading Dot (deg/s)**: Change of direction per unit time.\
**True Airspeed (m/s)**: The relative speed of the aircraft relative to the air.\
**True Airspeed Dot (m/s2)**: Acceleration.\
**Gamma (rad)**: Climb or descent angle.\
**Drag (N)**: Air resistance.\
**Thrust (N)**: The total thrust produced by the engines.\
