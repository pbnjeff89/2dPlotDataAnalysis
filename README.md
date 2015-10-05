# Necessary modules

* pandas
* os
* matplotlib

# Functions

#### correctZeros
Intended for cleaning up anomalous things in the data that usually are from noise or whatever in lab equipment, but it hasn't really come up so I haven't implemented this yet.

#### splitBy
Used for data files that are not already split. Implementation for data files that are already split can be made in the future (though it'll probably make splitting a lot more cumbersome than it should be).

#### plotStability
Generate 2D plots, usually differential conductance or resistance as a function of both gate voltage and current/voltage bias.

#### plotWaterfall
Generate 1D plots, for example of differential conductance as a function of bias, but for multiple gate voltages.
