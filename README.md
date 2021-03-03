# incubed_amcl

Fork from https://github.com/ros-planning/navigation/tree/melodic-devel/amcl with some changes.

## Current changes

* Avoid that a negative covariance is stored to the parameter, to avoid not-a-number issues at map-updates
* Possibility to change the scan-topic dynamically
* Added possibility to ignore beams during calculating probability for the given pose
