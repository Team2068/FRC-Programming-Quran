This is just info that's especially important for leads to know, and also useful for all of programming to know.

Note: Programming Lead has to read everything by the time their season starts and has to have experience with all the tools we use

# Sensors:
- Read the docs for all sensors, and look into their API, especially for the configuration aspect.
- When programming mechanisms and their sensors a good thing to think about is CAN utilisation, and looking into configuration settings for the status frame period, would help you gain insight into reducing CAN utilisation and avoiding buying devices that are unnecessary.
- Since we'll probably be using REV motors for a while, [here](https://docs.revrobotics.com/brushless/spark-max/control-interfaces) is the page for the status frame periods on the SparkMaxes.
- When choosing sensors, evaluate them on a strengths & vulnerability basis. For every sensor you rely on is another point of failure, so you have to think about how to secure them, strategies for if/when they fail, and how to avoid using a sensor while still sustaining accuracy and holding redundancy in-case that sensor breaks.


# Chassis:
- Learn about Odometry, Path-Planning, Motion Planning, Swerve Modules (and tankdrive), and simming the Robot.
- Get good at logging robot data / state and tracing when and where faults occured and then find out why (normally if it isn't obvious then it's likely linked to some sort of dependency which you fail to acknowledge or something you assume to work correctly (like a library or the field) didn't actually perform as expected)

# Scouting
- Learn how to log and model data from the bot
- Learn the different stastics models used in FRC (EPA & OPR) and understand their application and meanings
- Learn and gather tools that help to better understand and estimate how matches will go
- Understand the value of driver training and the data gathered from it and use the trends to give insight into where adjustments can be made and be creative with developing excercise to hammerout the deficiets in our drivers

# Programming Lead:
- Most of the time look for ways to improve the development process and getting through testing and debugging quicker while still retaining functionality
- The big goal is to have enough time to polish things like your chassis' controls & mechanisms movement
- Research into tools that would prove useful in the future and test them out before and during the season
