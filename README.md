# mouse-profile-indicator
Indicator for Ubuntu with Unity desktop, which allows saving mouse speed profiles

[![Sample Screenshot](http://i.imgur.com/tvltqna.png)](http://i.imgur.com/tvltqna.png)

### Overview

The purpose of this indicator is to allow users to easily switch between user-defined mouse speeds. This is useful for those who use laptops with wireless mouse on different surfaces, for users who switch between mousepads and table surface, or share same account with two or more users who may prefer different mouse speeds. This is also useful for users who alternate between multiple mouses that may need to have different sensitivity settings.

### Usage
When current value of mouse speed does not equal to any of the set profiles, the indicator label is set to "N/A". Under such condition, users can click "Store current" or middle-click on the indicator icon, and popup window asking user to name this new profile will appear. Note, that profile names and values should be unique, i.e. you cannot have two profiles named "Profile 1", and cannot have two profiles with value -0.5

Once profile is stored, the menu of the indicator will be re-build to include that profile. Clicking on the profile menuentry will activate that profile.

Effects of the profile switching can be tested via observing the scales in System Settings -> Mouse & Touchpad menu change as you click on your stored profile
