# draw-and-mouse-tracking
*New JsPsych plugin for draw in canvas and cursor position tracking*

🧠 You can see it an [working example](https://nrz7zmmo5m.cognition.run/) running on Cognition.run: 

![draw and mouse tracking jsPsych plugin example gif](https://github.com/GEJ1/draw-and-mouse-tracking/blob/main/new_plugin.gif)


**Parameters:**
* Images to present
* canvas_background_color 
* content_wrapper_color
* Draw line color
* Line width
* Canvas size



**Data Generated:**
* pos_tracking: The X and Y position of the cursor in the canvas while you are drawing.
* cursor_time : The time relative to the start of the trial for every (X,Y) position. (This can be useful to calculate velocity)
* X_click: The position of the click in X coordinate.
* Y_Click: The position of the click in Y coordinate.
* rt: trial_duration
