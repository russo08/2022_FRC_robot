# 2022 FRC robot

This is the firmware I, along with 4 high school students, developed to be used on our team’s custom robot for the 2022 season of the FIRST Robotics Competition. 
This project was intended to help introduce high school students to the C++ language and help them build and develop their skills as programmers. Our objective was to create a robot that could perform various autonomous routines that would help us score as many points as possible during the autonomous portion of every match. We also wanted to create a simple and intuitive user interface between the robot and our drive team during the tele-operated portion of the match where they had to pick up and shoot cargo to score points for our team alliance. 
Our firmware featured 3 separate autonomous modes to be used during the autonomous period of every match, all of which were state machines with varying states, depending on what our alliance team’s strategy was for that particular match. One mode simply moved the robot backward. The second mode would shoot a single cargo into the bottom goal and then move backward. Out last autonomous mode would allow the robot to shoot cargo in the top goal, move to pick up an additional cargo, do a 180 turn, drive up to the lower goal, shoot the cargo, and then move backward. 
Our end result was a robot that was consistent and reliable. Out team and robot were also within the top 40% of teams in the state. We were able to make it to the state championship, despite it being many student’s first year in the program. This was also my first year as a mentor in the program. 

Our component list was as follows:
- 4 brushless motors with relative encoders for the drive train
- 4 motor controllers to control our drivetrain motors
- 3 pneumatic solenoids, 2 for our arm and 1 to pull our pin 
- 1 DC motor for our ball intake/shooter
- 1 Pneumatic control module to control all 3 solenoids
- 1 Power distribution panel to distribute power to the various components
- 1 Open-Mesh OM5P-AC radio to communicate wirelessly between our 	computer and our robot
