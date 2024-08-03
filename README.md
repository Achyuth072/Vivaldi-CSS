# Vivaldi-CSS
A WIP mod collection for Vivaldi by a wannabe coder!

### Installation
1. Open Vivaldi browser settings
2. Navigate to Appearance > Custom UI Modifictions
3. Select a folder as your CSS mod folder and create/move CollapsingVerticalTabs.css to that folder
4. Restart Vivaldi

## Collapsing Vertical Tabs for Vivaldi
A CSS mod that allows you to have a auto collapsing vertical tabs in Vivaldi.

## Demo

## Features
- Automatically collapses/Expands vertical tabs on hover to save real estate.
- Floating tabs.
- Customizable widths for collapsed and expanded states; sort of.
- Snappier transitions; too snappy at times.

## Confuguration
Customizable variables in the CSS:
- '--closedDelay': Delay before tab bar closes after mouse leaves.
- '--openDelay': Delay before tab bar opens after mouse enters.
- '--expandedWidth': Width of tab bar when expanded.
- '--collapsedWidth': Width of tab bar when collapsed.
- '--transitionTiming': Speed and style of open/close animation.

  > Changing  '--expandedWidth' or '--collapsedWidth' will break the some parts of the mod, and you'd have to manually fix for each width value. Will fix this in future versions.

## Known Issues
- No proper way of reszing tabs without changing more code.
- Button-label of Workspace-Button is not displayed at times.
- Hovering over Workspace-Button while on tabs-subcontainer causes tabs-container.
- At times the previosly mention bug causes the tabs-contianer to not fully expand.
- Too snappy or jittery animations.

## Possible Future plans
- Optimize performace for smoother animations.
- A better implenmentaion of reszing the tabs.
- Add an optional auto hide feature for the entire tab bar.
- Add keyboard shortcuts for expanding/collapsing the tab bar.
- A possible JS version somewhere down the line?

## Credits
This CSS mod is based on the code shared on a Vivaldi Forum <a href="https://forum.vivaldi.net/topic/82900/collapsing-vertical-tabs-that-expand-on-hover-with-and-without-floating-tabs/79" target="_blank">thread</a>. I'm just making my own bug fixes and changes as I go.
> Contributions are welcome! Please feel free to submit a pull request!
