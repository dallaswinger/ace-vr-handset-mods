# Handset mods for the ACE VR (staccato) handset

These are parts for a 3D printed VIRTUAL REALITY controller.

## The issue
After having found that the index on the staccato handset was not perfectly 1:1 in game vs reality, I attempted at the suggestion of other community members to correct this by shimming the controller in the FCU. This was an improvement but was inconsistent for me personally.

## The workaround
Ace has said they are now looking into this as there may be a number of variables (like meta quest controller calibration from factory) that could cause this; but I wanted a temporary work around until a real solution is provided.

The solution I came to was raising the rear of the FCU within the handset itself. This is fairly easy and straightforward. Find a slightly smaller diameter front pin (even something like a QTIP cut down will work), then, instead of inserting the rear pin _into_ the stock rear FCU hole, lift the entire rear of the FCU and place the pin _below_ the FCU; there is enough tension within the system that this is solid. 

_because the root cause of the index/calibration issue has not yet been identified, it is NOT certain that other people experiencing this issue have the EXACT same problem (and thus, solution)_ -- this solution worked for me but I cannot guarantee it will be exactly the same for everyone. That being said, this is exactly why I'm providing replacement parts, rather than recommending modification to stock ones. With no permanent modification to the system, this is entirely reversible once there is a software fix.

### Downside
So if the workaround is good, why does this repo exist? 

With the FCU canted to offset the index/calibration issue, the trigger shoe is now raised within the trigger guard (this didn't bother me much if I'm being honest), and the magazine release doesn't work as the bar now does not reach. 

## Solution 
This repo has files to replace those two parts.

# Disclaimer
Experimental. Use at your own risk. Your mileage may vary. Use common sense. While I've provided these assets in an attempt to prevent others from having to make permanent modifications to their handset I still would advise only doing so if you feel comfortable.

# Credits
The trigger is a modified version of [NeverGM's](https://github.com/NeverGM/ACE-VR-Handsets) `trigger_short_pretravel_.stl`
Clearanced to fit the ACE VR staccato handset, and the face moved to adjust the LOP to be more similar to stock. This part may need to be _slightly_ sanded to fit and spin freely within the FCU depending on the finish your printer leaves.

