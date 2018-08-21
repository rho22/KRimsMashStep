# KRimsMashStep

CraftBeerPi 3 plug-in extended from SwitchSensorMashStep that adds a second temperature for mash temp.

This plug-in takes the functionality from the SwitchSensorMashStep, and adds two different items:
   * Mode : Allows the user to configure the step to progress on a timer value, or wait for user input
   * Mash Temperature : The step starts the timer or messages the user when the mash temperature is hit

The SwitchSensorMashStep adds a second sensor which is used to trigger the timer.  The previous plug-in
uses one temperature to set the target for the heating element and for the secondary probe.

This plug-in was intended to be used with a k-rims setup.  A two vessel setup, of mash tun and boil kettle.
The kettle sensor is intended to be used for setting the target temperature. The mash temperature is intended
to probe in to the mash itself.  As there can be some temperature lost between the kettle and the mash, often
the kettle temperature needs to be a degree or two hotter than the target mash temperature for the mash
to high the required temperature.

By adding a mode parameter, the user can use the same step for initial mash-in or mash steps.

