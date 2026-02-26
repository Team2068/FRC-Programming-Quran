# PID Controllers
PID controllers/Closed Loop Controllers help to get a motor to a specific setpoint (position, velocity, current, etc)

Here is documentation on tuning PID Loops: https://docs.yagsl.com/configuring-yagsl/how-to-tune-pidf

A lot of times these controllers should also make use of a Feed Forward (kV). For example, if you're trying to get a motor to a target RPM, you'll almost always need a feed forward for more precise and accurate control. If you're using a feed forward always tune the feed forward first then tune the PID.

For almost all of our controls we never tune the i constant.

## WPILIB Controllers
https://docs.wpilib.org/en/stable/docs/software/advanced-controls/controllers/pidcontroller.html

## REV Motor Controller PID Controllers (SparkMax)
https://docs.revrobotics.com/revlib/spark/closed-loop/closed-loop-control-getting-started

## Phoenix 6 Motor Controllers (TalonFX)
https://v6.docs.ctr-electronics.com/en/stable/docs/api-reference/device-specific/talonfx/basic-pid-control.html
