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

###Walk Cycle

Let's stop for a moment and think about how a person walks. What movements are involved in the simple act of walking? How does the body keep its balance? 

Walking is one of the most basic forms of locomotion, and for that reason it is something that most people do not think about very much. As animators though, we need to observe the world around us, and gather references from the simplest things. For an animator, the act of walking is an intricate collection of poses and nuanced details.

Walking is a naturally cyclic process. For this reason, one of the most important elements of a character's movement is what animators simply call a "walk cycle". The walk cycle is a looping animation of a character walking in place, and it not only serves to move the character around the scene, but it can also help define character traits and moods. A character might walk with confidence or run in fear, or it may drag its feet from tiredness or sadness. A walk cycle might show excitement or weariness, it may be purposeful or relaxed. 

Because of all the nuance a walk cycle can depict, it may seem like one of the hardest aspects of the character animation process. To simplify it, we can start by breaking down a walk cycle into a few simple poses.

