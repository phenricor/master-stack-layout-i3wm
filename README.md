This is a little project based on i3a by Michael Góral (https://git.goral.net.pl/i3a.git).
Basically, I wanted to implement some of the "master stack" layout from dwm to i3wm and swaywm, but every solution on the internet had problems that impacted the workflow I wanted, such as containers breaking the layout after switching from workspaces, and etc.

Based on that, I wrote some python scripts to include in the config file, some directly inspired on i3a, like cycle_focus.py and resize-compass.py.
# What you'll need
* swaywm or i3wm
* i3ipc (https://pypi.org/project/i3ipc/), it can be downloaded with pipx.
# Config
I included a `config` file with my personal suggestion on keybindings to use the layout scripts, similar to how dwm typically works. Insert into your configs as you want.
# Scripts
1. master-layout.py: Forces the master-stack layout, and reestablish it when something breaks.
2. cycle-focus.py: Focus windows in clockwise direction
3. cycle-move.py: Moves windows in clockwise direction
4. resize-compass.py: Shrinks and grows the focused window (i3 default shrinking/growing is alternated according to the side the window is)
5. swap: Swaps current focused stack window with master
# To do
* Monocle view
