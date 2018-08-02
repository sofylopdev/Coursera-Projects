# Coursera-Projects
Final Projects of Programming Mobile Applications for Android Handheld Systems, Part 1 and 2

Videos showing the apps: https://vimeo.com/user66732359

## Modern Art UI
### Objectives: 

Create an application from scratch with an interesting user interface.

### Project Description and Requirements:

 - This application's user interface is composed of geometric shapes arranged in a particular
order. Its layout inspired by the works of Modern Art masters such as Piet Mondrian and Ben Nicholson.
 - This application's user interface has one area containing multiple colored rectangles and another containing a SeekBar (sometimes called a Slider). When the user drags the SeekBar, all non‐white / non‐grey rectangles gradually change their color.
 - This application also contains an Options Menu. When the user clicks on the options menu an option labeled, "More Information" should appear. 
 - When the user clicks on the "More Information" option, a Dialog should appear displaying some text and displaying two buttons. If The user clicks on the "Not Now" button in the Dialog, the Dialog should be dismissed. 
- If the user clicks on the "Visit MOMA" Button, then the Web Browser should be opened to view a web page on the MoMA.org Web site.
For example, you might link to some object in the MoMA Collection that inspired their user interface design, to some cool page on MoMA.org,  or simply to the top level web page at www.moma.org.
- The user interface should:
   1.	Displays at least 5 separate colored rectangles, 
   2. At least one of these rectangles is "white" / "gray" in color, and 
   3. At least one of these rectangles is "non‐white" / "non‐gray" in color.


## DailySelfie

### Objectives:
Create an application from scratch that periodically reminds the user to take a selfie.
Over time the user will capture many selfies and thus will be able to see him or herself change over some period of time.

### Project Description and Requirements:

**Requirement #1:**

If the user clicks on the camera icon on the ActionBar, the app will open up a picture‐taking app already installed on the device.

**Requirement #2:**

If the user now snaps a picture and accepts it, the picture is returned to the DailySelfie app and then displayed in some way to
the user along with other selfies the user may have already taken.
The user should be able eventually see a small view for each selfie.

**Requirement #3:**

If the user clicks on the small view, then a large view will open up, showing the selfie in a larger format.
Hitting the back button in this case brings the user back to the ListView.
The behavior of your app may be different depending on how you organize it, but there must be a way to go from a small
view to a large view and then back to the original small view.

**Requirement #4:**

Whenever the user takes a selfie, the image data must be stored in some permanent way.
In particular, if the user exits the app and then reopens it, they should have access to all the selfies saved on
their device. 
You may optionally include some way for the user to delete some or all of their selfies.

**Requirement #5:**

Because the user wants to take selfies periodically over a long period of time, the app should create and 
set an Alarm that fires roughly once every two minutes, to make assessment easier.
In a real app, this would most likely be set to a longer period, such as once per day. 
When one of these alarms fires, a notification area notification should be placed in the notification area.
Pulling down on the notification drawer should expose a notification view.
Clicking on this notification view should bring the user back to the application.

