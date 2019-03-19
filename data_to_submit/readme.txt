Data to submit:

# OCEAN FLOW
Enclosed are our three (lat, lon) predictions for the corresponding additional three trajectories, along with some measure of error (our confidence in the estimates).

# INCOMPRESSIBLE SIMULATION
the incompressible data we submitted corresponds to our estimates for the x and y
velocities after 9998, 9997, 9996 time steps prediction lead time respectively
(data format: 9x9 numpy arrays).

Unfortunately, we could not come up with an uncertainty estimate; the submitted lead
time forecasts are simply an average of the first 9998 time steps, noting that there
are clear long time scale patterns (negative y flow along y boundaries, upwards y flow
through the domains y centre axis)

# WEATHER STATION
weather_forecast.txt - forecast for the 6 variables described in the description of the task, weather_variance.txt - variance for each variable