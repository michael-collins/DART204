### Lesson 5: Character Design and Rigging

When we design a character to be animated in After Effects, we first need to think about how this character will move, and what actions it is going to perform. We then break up this character in elements and prepare them to be animated. This will help us define what kind of **rigging** we will use for this character.

Rigging is the process of parenting or linking parts of a character to create a hierarchy. For example, we can parent the hand to the forearm, so when we move the forearm, the hand will follow. If we we do that again between the forearm and the arm, we will create a hierarchy. This process makes animating a character much more efficient and intuitive.

In this lesson we will study two different rigging styles, each with its advantages and disadvantages.

Let's start with a simple character design:

>character image or quick overview video

This character was created in Adobe Illustrator, and its source file is available for download from the course page. When you open the .AI file, you'll notice that each part of the character's body is in a separate layer. Just as we did previously for the logo animation, we need to have each part that will be animated in its own layer, so the importing process in After Effects will be much more streamlined.

One of the first steps we need to perform after we have the character elements in separate layers and imported into After Effects is to position the **anchor point** of each piece properly.

The anchor point is what defines your layer's center of rotation. As an example, the center of rotation of an arm is the shoulder, while the center of rotation of the forearm is the elbow. For this reason it is very important to place the anchor points of your layers properly **before you start rigging**.

To move the anchor point of a layer, select the layer or object, click the **Pan behind** tool, then click the anchor point and move it to the desired position.

![](/assets/unit3/anchor_point.gif)

With the anchor points properly placed, we can start **parenting** the layers to each other.

To parent one object to another in After Effects, all you need to do is click the pick whip icon and drag from the **child** layer, to the **parent** layer. The dropdown next to the pick whip will then show the name of the parent layer:

![](/assets/unit3/parent_layers.gif)

Once that is done, whenever you rotate or move the **parent layer**, the **child layer** will follow.


