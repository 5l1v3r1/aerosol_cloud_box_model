# aerosol_cloud_box_model

A 0-D box model created for a joint Master's project between Cambridge and Birmingham.

The model works by calculating, at each time step, rates of change (tendencies) in variables of interest,
and passing these to an integrator.

The variables solved are aerosol number mixing ratio, cloud mass and number mixing ratio, rain mass mixing ratio.

At present, the model uses simple expressions for the activation fraction.  This can be expanded.

The model should also be updated to use Kappa Kohler theory to calculate the critical radius, and to then calculate the 
number activated by integrating over the aerosol size distribution.

The integrator updates the variables with their values at the new timestep.

Can add more here as required.
