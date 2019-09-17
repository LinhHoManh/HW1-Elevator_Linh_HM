# HW1-Elevator_Linh_HM

# Elevator

## To get a C, you need to:
### Gif image of Elevator in Raider Park, TTU campus
- [x] Find an elevator in the campus
<p align="center">
<img src="https://github.com/LinhHoManh/HW1-Elevator_Linh_HM/blob/master/Linh_Raider-Park.gif">
</p>

- [x] Show a gif image of the control interface in operation (above).
- [x] Find the issues with the current design.
    + Floor buttons aligned horizontally
    + Don't know when the door will be closing
    + No estimated time of arrival to the desire floor
- [x] Explain why it is bad
    + Floor buttons align horizontally => instead of horizontal direction, it should be vertical
    + No estimated time of arrival to the desire floor (optional). => if there is a feature displaying estimated time of arrival, there should be an electronic board

## To get a B, you need to:
- [x] Think about the common things that you use an elevator. List your most common uses and other more rare uses. Does the interface make doing those common things easier?
    + Common things: Elevator in TTU, for example in Computer Science building, Raider Park and other places, the increment of floor is always horizontal. 
    + Emergency buttons (Call operator, fire alarm): used in very rare case, and need to be marked better
- [x] Think about how the user interacts with the elevator. What is the common sequence of actions?
- [x] How does the elevator provide feedback to the user?
    + There should be some feedbacks showing how many times a button (floor) has been pressed
- [x] What are some common mistakes you can make with this current design?
    + There is no feedback to user when elevator arrives at a floor. Sometimes door opens and people just randomly walk out
- [x] Suggest the improvements to make on the control interface. Sketch your solution. And justify your design decisions.
    + The problem is feedback. I suggest to improve the feedback to users such as: notify users whether the door is closing or opening; notify users whether a desired floor is reached; time estimation for each floor

## Now, imagine that you can have a touch screen on the elevator. To get a A, you need to:
- [x] Come with your design for the touch screen? What is the screen size that you want?
   + Vertical touch screen (visual mapping with the building in terms of height) with screensize 30x50 cm (below)
    
//<p align="center">
//<img src="https://github.com/Alex-Nguyen/Elevator/blob/master/controlPanel.png" width="200px">
//</p>

- [x] Design and implement interactive features (see demo) link
  


## Implementation Design

- Framework for Virtual Reality using A-Frame (https://aframe.io/)
- Room model : https://jujunjun110.github.io/aframe-crawling-cursor/basic/
- Elevator model: Customize the room model with Blender3D software (https://www.blender.org/)
- User interface design: Microsoft Power Point
- Convert User Interface Design to A-Frame component
- Interaction: fuse and gaze
