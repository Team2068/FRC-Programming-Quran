This is just info that's especially important for leads to know, and also useful for all of programming to know.

Note: Programming Lead has to read everything by the time their season starts and has to have experience with all the tools we use

# Sensors:
- Read the docs for all sensors, and look into their API, especially for the configuration aspect.
- When programming mechanisms and their sensors a good thing to think about is CAN utilisation, and looking into configuration settings for the status frame period, would help you gain insight into reducing CAN utilisation and avoiding buying devices that are unnecessary.
- Since we'll probably be using REV motors for a while, [here](https://docs.revrobotics.com/sparkmax/operating-modes/control-interfaces) is the page for the status frame periods on the SparkMaxes.
- When choosing sensors, evaluate them on a strengths & vulnerability basis. For every sensor you rely on is another point of failure, so you have to think about how to secure them, strategies for if/when they fail, and how to avoid using a sensor while still sustaining accuracy and holding redundancy in-case that sensor breaks.


// TODO: Everything under here is speculation for now, will need to revise once we've tried all of this

# Chassis:
- Learn about Odometry, Path-Planning, Motion Planning, Swerve Modules (and tankdrive), and simming the Robot.
- When simming the robot, especially at the start of the season, simming the game-specific mechanism is the most important part as once mechanical has choosen a design, writing the code and testing it on a simulated version of the intake can be very useful.

# Programming Lead:
- Most of the time look for ways to improve the development process and getting through testing and debugging quicker while still retaining functionality
- The big goal is to have enough time to polish things like your chassis' controls & mechanisms movement
- Research into tools that would prove useful in the future and test them out before and during the season
