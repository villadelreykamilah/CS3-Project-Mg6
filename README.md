# CS3SY26-Mg-ProjectProposal_6

<h2>
Name of the Application	: Tamagotchi Pet Simulator<br>
Section			   	    : Magnesium<br>
Group Members			: Mayen Elise F. Ilagan, Sophia E. Ramirez, Kamilah R. Villadelrey<br>		
Date (Proposal Date)	: November 5, 2026<br>
</h2>

## Project Description:
This program is a calculator that can return a needed value based on other physics quantities given by the user. For example, it can find an object’s initial velocity when a user gives the object’s final velocity, acceleration, and time in motion. It uses the kinematic equations and derives from Newton’s second law of motion, depending on the user’s needs. Target demographics of this project include physics students, physics teachers, and physicists, as it can help with tedious calculations.<br>
The program has a main class, <b>Physics</b>, which has the attribute topic, which stores either kinematic or force, to specify what kind of calculation the program needs. Physics class also has 2 subclasses, <b>Kinematics</b>, and <b>Forces</b>. Kinematics has attributes initial_velocity, final_velocity, horizontal_velocity, acceleration, time, vertical_displacement, and horizontal_displacement, and has methods kinematic_equation_1(), all the way until kinematic_equation_5(), representing each kinematic equation. The Forces class has attributes y_net_force, x_net_force, mass, y_acceleration, x_acceleration, normal_force, gravity, and weight, and has methods calculate_weight(), calculate_normal_force(), calculate_x_net_force(), and calculate_y_net_force()

[Class Diagram](classdiagram.png)