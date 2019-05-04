%% Object-tracking-using-MATLAB
%%%%%%%%%%%%%%%--------OBJECTIVE----------%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%the objective of this program is to track an activity of a moving red
%object from the camera input. The features can be analysed more clearly
%using bounding box and centroid of the red object.

%%%%%%%%%%%%%%%-------HOW to DO THIS?-----%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%This can be done by displaying the red component of the rgb image from
%the actual rgb video frames and then converting it into binary. The red
%component is displayed as white colour, rest everything else should be black.
%After this display a bounding box around the region of interest and also
%mark its centroid to track the movement of its geometric centre.
