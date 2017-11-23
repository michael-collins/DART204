###Character Rigging

When we design a character to be animated in After Effects, we need to think about how this character will move, and what actions it is going to perform. This will help us define what kind of **rigging** we will use for this character.

Rigging is the process of preparing a character to be animated, and it's like creating a character's bone structure. In this lesson we will study two different rigging methods, Forward Kinematics and Inverse Kinematics, each with its advantages and disadvantages.

Both methods consist of parenting, or linking parts of a character to create a hierarchy. For example, we can parent the hand to the forearm, so when we move the forearm, the hand will follow. If we do that again between the forearm and the arm, we will create a hierarchy. This process makes animating a character much more efficient and intuitive.

One of the first steps we need to perform after we have the character elements in separate layers and imported into After Effects is to position the **anchor point** of each piece properly.

The anchor point is what defines your layer's center of rotation. As an example, the center of rotation of an arm is the shoulder, while the center of rotation of the forearm is the elbow. For this reason it is very important to place the anchor points of your layers properly **before you start rigging**.

To move the anchor point of a layer, select the layer or object, click the **Pan behind** tool, then click the anchor point and move it to the desired position.

![](/assets/unit3/anchor_point.gif)

With the anchor points properly placed, we can start **parenting** the layers to each other.

