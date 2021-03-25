# Are Colour Experiences The Same Across The Visual Field?  
## Panoworks Version  
  
  
Project in progress. Run 'main.iqx' to run the experiment.  

Main parameters are controlled in 'main.iqx' in the \<values\> object.

 * 'radius_central' sets the radius at which central stimuli are presented in degrees of visual angle (DVA)
 * 'radius_peripheral' sets the radius at which peripheral stimuli are presented in DVA
 * 'stimulus_size' sets the radius of the central stimulus circle  
  
 * 'magnify' determines whether peripheral scaling is applied or not. Set to 'true' or 'false'
 * 'peripheral_scaling_factor' sets the magnification factor for peripherally presented stimuli relative to centrally presented stimuli  
  This is a function of eccentricity. For example, a stimulus at 10DVA with a scaling factor of 0.45 will be 4.5 times larger than the
  central stimulus  

More values that may need to be changed to make this work are on 'calibration_main.iqx' and should be self-explanatory.
