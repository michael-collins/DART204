### Lesson 7 - Character Rigging, Forward and Inverse Kinematics

When we design a character to be animated in After Effects, we need to think about how this character will move, and what actions it is going to perform. This will help us define what kind of **rigging** we will use for this character.

Rigging is the process of preparing a character to be animated, and it's like creating a character's bone structure. In this lesson we will study two different rigging methods, Forward Kinematics and Inverse Kinematics, each with its advantages and disadvantages.

Both methods consist of parenting, or linking parts of a character to create a hierarchy. For example, we can parent the hand to the forearm, so when we move the forearm, the hand will follow. If we do that again between the forearm and the arm, we will create a hierarchy. This process makes animating a character much more efficient and intuitive.

One of the first steps we need to perform after we have the character elements in separate layers and imported into After Effects is to position the **anchor point** of each piece properly.

The anchor point is what defines your layer's center of rotation. As an example, the center of rotation of an arm is the shoulder, while the center of rotation of the forearm is the elbow. For this reason it is very important to place the anchor points of your layers properly **before you start rigging**.

To move the anchor point of a layer, select the layer or object, click the **Pan behind** tool, then click the anchor point and move it to the desired position.

![](/assets/unit3/anchor_point.gif)

With the anchor points properly placed, we can start **parenting** the layers to each other.

#### Forward Kinematics (FK)

To parent one object to another in After Effects, all you need to do is click the pick whip icon and drag from the **child** layer, to the **parent** layer. The dropdown next to the pick whip will then show the name of the parent layer:

![](/assets/unit3/parent_layers.gif)

Once that is done, whenever you rotate or move the **parent layer**, the **child layer** will follow. That is what animators call **Forward Kinematics**

In Forward Kinematics, the **parent object** influences the **child object** in a hierarchical order. For example, the movement of the arm influences the movement of the forearm, which in turn influences the movement of the hand, as you can see in the animation below.

![](/assets/unit3/FK.gif)

This method is really good for putting your characters in very specific poses, but it can also be very cumbersome, since you have to manually rotate and position each section of the character separately.

####Inverse Kinematics (IK)

**Inverse Kinematics** is faster to animate because it puts the the control of the hierarchy on the last child object. In this case, instead of having to manually position and rotate each section of the arm separately, we only need to move the hand, and the rest of the arm will follow.

![](/assets/unit3/IK.gif)
 
This makes it much quicker to pose a character, especially if you are creating a walk cycle, or moving the character's hips. On the image below, the character on the left is rigged using FK, and the one on the right is using IK. Both are being moved by their respective parent nodes (in this case, the hip node).

![](/assets/unit3/char_compare.gif)

From this simple comparison we can already see that the character on the right will be much easier to animate.

The downside of using IK is that it can be difficult to pose your character exactly as you want, since you lose control of each individual joint.

To setup a character using IK, we will use a plugin called DUIK. This plugin is free, and it is one of the best animation plugins available for After effects. You can download the plugin from this link: https://rainboxprod.coop/en/tools/duik/duik-download/

Here is a step by step of the setup process:

> IK character setup video

