### Lesson 7 - Forward Kinematics, Inverse Kinematics and Walk Cycle

As it was previously explained in the last lesson, when you animate a character using the hierarchy method, you will be able to use two different styles of animation: Forward Kinematics (FK) and Inverse Kinematics (IK).

In Forward Kinematics, the **parent object** influences the **child object** in a hierarchical order. For example, the movement of the arm influences the movement of the forearm, which in turn influences the movement of the hand, as you can see in the animation below.

>FK img

This method is really good for putting your characters in very specific poses, but it can also be very cumbersome, since you have to manually rotate and position each section of the character separately.

Inverse Kinematics solves that issue by placing the control of the hierarchy on the last child object. In this case, instead of having to manually position and rotate each section of the arm separately, we only need to move the hand, and the rest of the arm will follow.

>IK img
 
This makes it much quicker to pose a character, especially if you are creating a walk cycle, or moving the characters hips.

>hip node movement