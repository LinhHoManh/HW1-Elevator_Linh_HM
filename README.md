# HW1-Elevator_Linh_HM

# Elevator

## To get a C, you need to:
### Elevator showcase from Electrical Engineering Center
- [x] Find an elevator in the apartment/campus/hotel. Only one example for each student (below)
<p align="center">
<img src="https://github.com/LinhHoManh/HW1-Elevator_Linh_HM/blob/master/Linh_Raider-Park.gif">
</p>

- [x] Take photos of the control interface (above)
- [x] Show a gif image of the control interface in operation (above).
- [x] Find the issues with the current design.
    + Door automatically closes without warning users
    + Floor buttons align horizontally
    + No spatial relationship between floor number and the actual floor
    + No indicator to show the current floor we are in
    + Don't know when the door will be closing
    + No estimated time of arrival to the desire floor
- [x] Explain why it is bad
    + Door automatically closes without warning users => unaware users may face problem (e.g., dropping coffee)
    + Floor buttons align horizontally => not follow the design convention
    + No spatial relationship between floor number and the actual floor => not follow the design convention
    + No indicator to show the current floor we are in => want to floor 4, elevator is still in floor 3, door opens, I think I'm in 4th floor
    + Don't know when the door will be closing => this happens a lot, hit the close button and wait for 3 minutes, door not closes due to internal problem.
    + No estimated time of arrival to the desire floor (optional). => it's better to know how much time we reach the destination so we can better plan our moving time.

## To get a B, you need to:
- [x] Think about the common things that you use an elevator. List your most common uses and other more rare uses. Does the interface make doing those common things easier?
    + Common things: Hit the desired floor button many times (to make sure that the button is pressed); Press the close door many time with expect that the door will close faster
    + Rare uses: Emergency buttons (Call operator, fire alarm)
- [x] Think about how the user interacts with the elevator. What is the common sequence of actions?
    + Hit the desired floor/door close many times. Nothing change in terms of operation
- [x] How does the elevator support the user figure out how to make it work?
    + with signifiers (floor numbers for each floor, star indicates ground or 1st floor, rounded or rectangle buttons for pressing)
- [x] How does the elevator provide feedback to the user?
    + Light on the button indicates that the corresponding floor is pressed
    + Sound is played once the elevator reached a floor (only to notify users)
- [x] What are some common mistakes you can make with this current design?
    + Get out of the elevator before/after my desired destination. When the elevator is moving I usually talk to people or use my phone.
- [x] Suggest the improvements to make on the control interface. Sketch your solution. And justify your design decisions.
    + The problem is feedback. I suggest to improve the feedback to users such as: notify users whether the door is closing or opening; notify users whether a desired floor is reached; time estimation for each floor

## Now, imagine that you can have a touch screen on the elevator. To get a A, you need to:
- [x] Come with your design for the touch screen? What is the screen size that you want?
   + Vertical touch screen (visual mapping with the building in terms of height) with screensize 30x50 cm (below)
    
<p align="center">
<img src="https://github.com/Alex-Nguyen/Elevator/blob/master/controlPanel.png" width="200px">
</p>

- [x] Design and implement interactive features (see demo) link
  + Avatar (human) shows that users are at the 2nd floor
  + Three buttons (bottom)  supports emergency and disability person
  + Help button assist users find out the departments
  + Home button returns to the main screen
  + Once a desired floor is pressed, yellow background confirms that action. Press again to clear
  + Audio feedback allows users to know when the door is closing/openning, which floor is reached
  + Text on top of the screen allows users to see the feedback visually (or for hearing impaired people)
- [x] Design and implement user feedback (see demo) link
- [x] You can use any tools you want including Processing, javascript, or even power point => Virtual Reality using A-Frame


## Implementation Design

- Framework for Virtual Reality using A-Frame (https://aframe.io/)
- Room model : https://jujunjun110.github.io/aframe-crawling-cursor/basic/
- Elevator model: Customize the room model with Blender3D software (https://www.blender.org/)
- User interface design: Microsoft Power Point
- Convert User Interface Design to A-Frame component
- Interaction: fuse and gaze
