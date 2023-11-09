Forked from https://curseforge.com/wow/addons/libuidropdownmenu, based on v4.21.10010550587 (2023/07/29)

List of changes (to comply with GNU GPL-2.0):

09-11-2023:
- Changed all globals to use L_NUMY_ or L_Numy as prefixes, instead of L_ for compatibility with the original lib
- Fixed clicking on the mouseOverIcon, by editing `local function icon_OnClick`
- Fixed the display mode not being properly set when hovering over the expand arrow (syncing the code to blizzard's code)

I expect this fork will be removed or killed once the original is updated. I do not suggest anyone other than me to use this fork, I will not keep it maintained.
