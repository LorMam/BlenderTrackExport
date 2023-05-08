# BlenderTrackExport
Blender Add-on for exporting the xy image coordinates of tracks made in Blender (Version >= 2.8).\
This guide is ment for Blender beginners, who just want to get some quick and easy video tracking done.
Very helpful for quick scientific video analyses and more handy than doing tracking in ImageJ.

## Installation

- Step 1: download the export_add_on.py file

Either via git clone,\
or go to the [raw file](https://raw.githubusercontent.com/LorMam/BlenderTrackExport/master/export_add_on.py), right click -> save as...


- Step 2: open Blender, navigate to Edit -> Preferences -> Add-ons

![plot](https://github.com/LorMam/BlenderTrackExport/blob/master/doc/1_open_preferences.png)

- Step 3: click "Install" in the top right corner and select the export_add_on.py

![plot](https://github.com/LorMam/BlenderTrackExport/blob/master/doc/2_preferences_window.png)

- Step 4: make sure the Add-on is activated

![plot](https://github.com/LorMam/BlenderTrackExport/blob/master/doc/3_activate_addon.png)

When the Add-on does not show up, check whether you downloaded the right file.\
Opened in the Editor, the file should look like [this](https://raw.githubusercontent.com/LorMam/BlenderTrackExport/master/export_add_on.py).

## Video Tracking in Blender

- Step 1: open Blender, select Video Editing

![plot](https://github.com/LorMam/BlenderTrackExport/blob/master/doc/4-blender%20splash%20screen.png)

- Step 2: select the Movie Clip Editor

![plot](https://github.com/LorMam/BlenderTrackExport/blob/master/doc/5-movie_clip_editor.png)

- Step 3: Drag and drop video

![plot](https://github.com/LorMam/BlenderTrackExport/blob/master/doc/6_drag_drop_video.png)

- Step 4: Add a tracking marker onto the Video, by clicking (1), then clicking the desired screen location. Track the marker by clicking one of the options (3).

![plot](https://github.com/LorMam/BlenderTrackExport/blob/master/doc/7_track_video.png)


## Add-on Usage

- Step 1: After tracking one or many markers throughout the video, select a folder to save the .csv file. Then either export all the tracks at once, or only the selected one by clicking respective button.

![plot](https://github.com/LorMam/BlenderTrackExport/blob/master/doc/8_export.png)

- Output: The saved files each contain three columns: frame, x, y. The origin (0,0) is the lower left corner of the video. The units are pixels.

![plot](https://github.com/LorMam/BlenderTrackExport/blob/master/doc/9_file.PNG)

## Tips for efficient tracking in Blender

How to use Pattern size, Search size, correlation and weights\
to be added.





## Future Ideas:
- Add options for custom coordinate origin, e.g. different corner/set one track to be the origin
- option to export all tracks into one file
