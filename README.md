# Blender-2-G'MIC

**Update (5-3-16):**

Alpha2 version is now available. This latest version features a set of six new "Sequence" filters that allow you to enhance still images by animating filter effects over time. The results are saved as an image sequence. Examples in the video below show a range of filter possibilities as applied to lettering/logos and images (see also Dragon image at bottom of this page). The script has also been updated. 

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/omGe6VF5WBs/0.jpg)](https://www.youtube.com/watch?v=omGe6VF5WBs)


B2G is a Python script that allows you to access a selected range of G'MIC's image processing features from within the Blender Video Sequence Editor (VSE). With the script, you can creatively filter single images, image sequences, and movie files.

This is experimental Alpha release software likely to contain bugs that might cause Blender and/or G'MIC to encounter difficulties. It is provided without a warranty of any kind (see GPL software license included with the script).

The code should recognize whether it's being used on Linux or Windows; however, if you start using the blend file on one system, it's best to keep it there rather than trying to treat it as totally portable. File paths, image formats and codec issues all come into play. Issues that may be problematic are pathname symbols and spaces in file/folder names (best not to have spaces). At times, Blender can employ an internal "Relative Path" notation that will prevent B2G from working well. Relative paths can be turned off permanently in the Users Preferences window, or, more simply, you can select "External Data/Make All Paths Absolute" from the File Menu to ensure images are referenced so that G'MIC can find them.

**PREREQUISITES**

To use Blender-2-G'MIC on Linux or Windows you will need:

*  At least Blender 2.76b (works with 2.77, but not fully tested)

   **_If B2G UI does not appear, make sure to select "Load UI"  in the User Preferences Window._**

      https://www.blender.org/download/
      
*  The G'MIC software installed and added to your System path, or alternatively, the standalone version.       

      http://gmic.eu/download.shtml







**It is recommended that you check out the script development history and range of script features at YouTube:**

**1. Creative Imagery with Blender-2-G'MIC**

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/4Q78OPmbn3o/0.jpg)](https://www.youtube.com/watch?v=4Q78OPmbn3o)


**2. Blender-2-G'MIC Feature Update**

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/p1twxAsLb6o/0.jpg)](https://www.youtube.com/watch?v=p1twxAsLb6o)



**Important info on enabling the link between Blender/G'MIC and further usage is given in the following video.**

**3. Initial Settings & Use - Alpha Release**

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/TSzoEXAV1zs/0.jpg)](https://www.youtube.com/watch?v=TSzoEXAV1zs)


**CURRENT FILTER AVAILABILITY**

The G'MIC image processing system currently offers over 460 different filters, with more being added on a regular basis. B2G's filter offerings are currently limited to a selection of about 20 fully-featured filters with slider adjustments (filters can be added/removed with a small amount of extra work via panel and menu definitions).

Basic access to the many other filters is still possible through the use of VSE Command Strips. These allow you to save to the VSE Timeline "favorite" filter settings that you may encounter while reviewing other G'MIC users work, or that you generate yourself using the G'MIC Gimp Plugin. This library of presets can then be applied directly to image assets with just a few clicks. A selection of such strips are provided as examples in the alpha release blend file.  


**TWIRLING DRAGON - Created with Blender-2-G'MIC's "Twirl Animated" filter**

[![Alt Text Here](https://github.com/Starfall-Robles/Blender-2-G-MIC/raw/master/DragonTwirl.gif)

