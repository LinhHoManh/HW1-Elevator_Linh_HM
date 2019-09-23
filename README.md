# HW1-Elevator_Linh_HM

# Elevator
 [Demo link]https://linhhomanh.github.io/HW1-Elevator_Linh_HM/Elevator.html

### Gif image of Elevator in Raider Park, TTU campus (Benchmark A)

- [x] Take photos of the control interface
<img src = "https://github.com/LinhHoManh/HW1-Elevator_Linh_HM/blob/master/RP2.jpeg">
<img src = "https://github.com/LinhHoManh/HW1-Elevator_Linh_HM/blob/master/RP1.jpeg">
<img src = "https://github.com/LinhHoManh/HW1-Elevator_Linh_HM/blob/master/RP3.jpeg">
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

## (Benchmark B)
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
## (Benchmark A)
- [x] Design and implement interactive features (see demo) link
  + Buttons assigned the floors are placed vertically
  + Feed back to elevator users by changing the color. Green for the floors,
  + The users can cancel their wrong options by double-clicking at the floor 3, floor 2, floor 1 and basement
- [x] Design and implement user feedback (see demo) link


## Reference 

 + Web editor: https://editor.p5js.org/ (P5 is developed in JavaScript environment, having the corresponding libraries to ControlP5 which is developed in Java and no longer support to have a render in html)
 

