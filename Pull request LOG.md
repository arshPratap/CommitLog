# Pull request LOG

This file consists of a detailed log of my Pull requests that I have made to ardupilot community.This would help in the following areas :
- I can have a detailed and customised log of the PRs 
- Help me prioritise my PRs so as to focus my attention to more important ones 
- Help other developers get a detailed log of my contribution to Ardupilot 

## [_Ardupilot_](https://github.com/ArduPilot/ardupilot)
These are the following PRs that I have made to the ardupilot codebase
- Copter:PreArm Battery low voltage message repeated two times fix
	 - https://github.com/ArduPilot/ardupilot/pull/16530
	 - Detail:Fixed the issue that a low voltage pre arm message was being printed twice
	 - Status:Merged
- Copter: AP_Arming: Added check for EKF origin altitude 
	 - https://github.com/ArduPilot/ardupilot/pull/16101
	 - Detail:Added an additional check for EKF orign to make sure its not too far from home altitude
	 - Status:Merged
- AP_HAL:examples:Printf: Improvements in the Printf example
	 - https://github.com/ArduPilot/ardupilot/pull/16260
	 - Detail:Added proper documentation for the Printf example after testing it with Pixhawk board, as suggested [here](https://ardupilot.org/dev/docs/learning-ardupilot-the-example-sketches.html#rough-example-code)
	 - Status:Merged
	 - Note:Documentation was little bit too lengthy( comments for every line )
- AP_HAL:examples:AnalogIn: Added comments in the AnalogIn example 
	 - https://github.com/ArduPilot/ardupilot/pull/16229
	 - Detail:Added proper documentation for the Printf example after testing it with Pixhawk board, as suggested [here](https://ardupilot.org/dev/docs/learning-ardupilot-the-example-sketches.html#rough-example-code)
	 - Status:Merged
- Copter: EKF3: pre-arm check GPS failure fix 
	 - https://github.com/ArduPilot/ardupilot/pull/16132
	 - Detail:Configuring the pre-arm failure for GPS_TYPE=0 so that users flying indoors with GPS disabled could fly their drone accordingly 
	 - Status:Closed in favor of the [PR]()
- Morse:Made changes to add vehicle following camera 
	 - https://github.com/ArduPilot/ardupilot/pull/16762
	 - Detail:Added the vehicle following camera functionality for Morse simulations. 
	 - Status:Closed in favor of the [PR](),as this implementation was rough around the edges and had some loopholes
- Morse:Added Vehicle Follow Support 
	 - https://github.com/ArduPilot/ardupilot/pull/16779
	 - Detail:Added the vehicle following camera functionality for Morse simulations.Upgrade of the above PR.
	 - Status:Needs Review
- Copter:Implement LOITER_TURNS in Guided Mode
	 - https://github.com/ArduPilot/ardupilot/pull/16473
	 - Detail:Added a loiter_turns sub mode for the guided drive mode in accordance with what asked for [here]()
	 - Status:Needs work as some functions have caused duplication in the code base.
- Rover/EKF: fix for vehicle moving when GPS_TYPE=0
	 - https://github.com/ArduPilot/ardupilot/pull/16562
	 - Detail:Provided a fix for rover still moving when GPS_TYPE=0
	 - Status:Needs Rework
- Copter: Add pre-arm check for velocity innovation less than 1m/s
	 - https://github.com/ArduPilot/ardupilot/pull/16617
	 - Detail:Added a Pre-arm check for velocity innvoation less than 1m/s
	 - Status:Needs Review
## [_Ardupilot Wiki_](https://github.com/ArduPilot/ardupilot_wiki)
These are the following PRs that I have made to the ardupilot documentation
- starting.rst: Fix alignment issue 
	 - https://github.com/ArduPilot/ardupilot_wiki/pull/3300
	 - Detail:Fixed some alignment issue where text was present in for comma seperated list of values
	 - Status:Merged
- building-setup-windows10.rst: Updated the documentation 
	 - https://github.com/ArduPilot/ardupilot_wiki/pull/3299
	 - Detail:Updated the documentation for building and configuring up the WSL so as to run the ardupilot codebase
	 - Status:Merged
- Wiki:Dev:Fixed some typos 
	 - https://github.com/ArduPilot/ardupilot_wiki/pull/3265
	 - Detail:Fixed some basic typos
	 - Status:Merged
