# FRC Programming Quran
A repository storing the accumulated knowledge gained from the programming buckets. On this page we'll link resources to learn more about the topics, and in the folders, we'll give our explanations and experiences with the topics to give more tricks.

[If we ever fall of this hard](https://docs.wpilib.org/en/stable/docs/zero-to-robot/introduction.html)

And keep this in mind just in case electrical falls off (it will be your problem): https://docs.wpilib.org/en/stable/docs/hardware/hardware-basics/wiring-best-practices.html

## Table of Contents (In no particular order)

- [Tools](README.md#Tools)
- [Control Systems](README.md#Control-Systems)
- [Motion Profiles](README.md#Motion-Profiles)
- [PID Controllers](README.md#PID-Controllers)
- [Phoenix Control Systems Docs](README.md#CTRE-Control-Systems-Docs)
- [Swerve](README.md#Swerve)
- [Sensors & Data Processing](README.md#Sensors)
- [Development Manual for REV SPARK MAX](https://www.revrobotics.com/development-spark-max-users-manual/)
- [State Space Modeling](https://docs.wpilib.org/en/stable/docs/software/advanced-controls/state-space/index.html)
- [Tank Drive / WestCoast Drive](https://docs.wpilib.org/en/stable/docs/software/hardware-apis/motors/wpi-drive-classes.html)

# Tools
- [Advantage Scope](https://github.com/Mechanical-Advantage/AdvantageScope) -> Useful for analysing data, troubleshooting issues, replaying matches, and tuning PIDs
- [Advantage Kit](https://github.com/Mechanical-Advantage/AdvantageKit)
- [Path Planner](https://github.com/Mechanical-Advantage/AdvantageScope) (Use the microsoft store's) -> Path planning
- [Choreo](https://sleipnirgroup.github.io/Choreo/usage/editing-paths/#obstacles) -> Better Path Planning
- [WPILib Datalogger](https://docs.wpilib.org/en/stable/docs/software/telemetry/datalog.html) -> Logging data that will be analysed by other tools
- [Shuffleboard](https://docs.wpilib.org/en/stable/docs/software/dashboards/shuffleboard/index.html) -> Good for creating an interface for the drive coach to work with and useable for debugging
- [WPILib Simulation](https://docs.wpilib.org/en/stable/docs/software/wpilib-tools/robot-simulation/physics-sim.html). I recommend siming only the mechanism if we aren't physically prototyping it, so we can tune values safely (and not break the robot like I did).
- [SysID / Robot Characterisation](https://docs.wpilib.org/en/stable/docs/software/advanced-controls/system-identification/index.html)

# Control Systems
- [Control Systems Bible](https://github.com/calcmogul/controls-engineering-in-frc) -> A comprehensive overview of Control Systems Theory used in FRC
- [WPILIB Intro to Control Systems](https://docs.wpilib.org/en/stable/docs/software/advanced-controls/introduction/control-system-basics.html) -> A good introduction into control systems theory and how it's used in FRC
- [Control Systems Glossary](https://docs.wpilib.org/en/stable/docs/software/advanced-controls/controls-glossary.html)
- [WPILIB Controllers](https://docs.wpilib.org/en/stable/docs/software/advanced-controls/controllers/index.html)

# Motion Profiles
- [Motion Profiling](https://frc3603-docs.readthedocs.io/en/latest/motion-profiling.html)
- [254's paper on Motion Profiling](https://www.chiefdelphi.com/uploads/default/original/3X/a/b/ab808bbf5f212c6deba8565dac83852bbd9b4394.pdf)
- [Trapezoidal Profiles WPILIB](https://docs.wpilib.org/en/stable/docs/software/advanced-controls/controllers/trapezoidal-profiles.html)
- (Haven't read, but may be good?) https://www.chiefdelphi.com/t/motion-magic-vs-motion-profiling/365813

# PID Controllers
- [How to Tune PID](https://pidexplained.com/how-to-tune-a-pid-controller)
- [WPILib PID Controllers](https://docs.wpilib.org/en/stable/docs/software/advanced-controls/controllers/pidcontroller.html#pid-control-in-wpilib)
- [PID Comamnds & Subsystems](https://docs.wpilib.org/en/stable/docs/software/commandbased/pid-subsystems-commands.html)
- [Profiles + PID](https://docs.wpilib.org/en/stable/docs/software/commandbased/profilepid-subsystems-commands.html)
- [REV PID Controllers](https://docs.revrobotics.com/sparkmax/operating-modes/closed-loop-control)
- [Phoenix PID Controllers](https://pro.docs.ctr-electronics.com/en/latest/docs/api-reference/device-specific/talonfx/basic-pid-control.html)

# CTRE Control Systems Docs
- [Phoenix Control Systems Intro](https://pro.docs.ctr-electronics.com/en/latest/docs/api-reference/device-specific/talonfx/talonfx-control-intro.html)
- [Closed Loop Control Introduction](https://pro.docs.ctr-electronics.com/en/latest/docs/api-reference/device-specific/talonfx/closed-loop-requests.html)
- [Open Loop Control Introduction](https://pro.docs.ctr-electronics.com/en/latest/docs/api-reference/device-specific/talonfx/open-loop-requests.html)

# Swerve
- [Swerve Drive Overview](https://yagsl.gitbook.io/yagsl/fundamentals/swerve-drive)
- [Swerve Module Overview](https://yagsl.gitbook.io/yagsl/fundamentals/swerve-modules)
- [Things to Keep in Mind](https://yagsl.gitbook.io/yagsl/bringing-up-swerve/preface) -> Read through this section of the documentation

# Sensors
- [Encoders Overview](https://docs.revrobotics.com/duo-control/sensors/encoders)
- [Hall Effect Sensors Review At All Levels](https://www.mdpi.com/1424-8220/20/15/4163) -> You don't need to know everything in this paper
- [Hall Effect Sensors outside of FRC](https://www.mdpi.com/1424-8220/21/21/7072)
- [Motor FOC](https://www.mathworks.com/videos/motor-control-part-4-understanding-field-oriented-control-1587967749983.html)
- [Filters](https://docs.wpilib.org/en/stable/docs/software/advanced-controls/filters/index.html)
