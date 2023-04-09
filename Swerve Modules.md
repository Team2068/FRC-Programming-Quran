Here's a basic overview of Swerve Modules:
They contain 2 motors, 1 for steering and 1 for drive, and an absolute encoder for having a concrete referrence for our module's position.
For programming them, it's as simple as configuring your motors and absolute encoder (in absolute mode, you'd think it would be like that by default, but not always), then creating functions for setting the angle on the motors and drive velocity (speed & direction). That's really it. For a proper example look at [Muhkeighnzeigh](https://github.com/Team2068/Muhkeighnzeigh/blob/345a8f8b88193f8298563a383025ff4ce6a35e86/src/main/java/frc/robot/SwerveModule.java)

I learnt about how swerve modules work by using the SDS library(the library in the com folder of the same commit) and through my many attempts at rewriting it for simplicity, I learnt how simple it was under the hood and how the layers of abstraction (likely there for teh same of easily adding support for new types of motors and encoders). I tried recreating it without the factory-builder pattern, but due to trying to sustain the same layers of abstractin of the sake of other team who might look at the code and use it. What I learnt from trying to work on it was

~Ayidana A.
