##Digital Animation Process

### From traditional to digital

So far we've been looking at how animation was done traditionally, with hand-drawn illustrations done frame by frame, and the principles that guide this process to create the illusion of movement.

While some people may see traditional and digital animation as two different kinds of animation, the truth is that one is simply an evolution of the other. Both are based on the exact same principles, but digital animation uses computer programs to simplify some of its processes.

Some of these programs still try to replicate the hand-drawn, frame by frame experience, but most modern animation programs use a different approach that greatly speeds-up the animation process. One of these programs is Adobe After Effects, and this is what we will be using in this course.

2D animation is just one of the many capabilities of After Effects. For this reason the program can be a little bit overwhelming at first. Please watch [this introductory video](https://helpx.adobe.com/after-effects/how-to/aftereffects-workflow-terminology.html) to have a better sense of the software's interface and and general functionality before we can continue to our next exercises.

###Asset creation

Asset creation is the process of drawing your characters, props and environments. In traditional animation, different assets would be drawn in separate cels to be superimposed later. In digital animation, this process is done in drawing software such as Photoshop, Illustrator and even in After Effects itself. You can start with an illustration that contains a complete scene, with characters, environment and props, but having each of these parts in a separate file makes it much more manageable later on.

Another very important part of the asset creation process is **separating each element in its own layer**. For example with a character, you'll need to have separate layers for the head, the torso, for different parts of each arm, for different parts of each leg, for each hand and each foot, and depending on the character, also for facial features that will be animated separately like the mouth and eyes. If this is not done properly you'll end up with a flat image that can't be animated.

>img or video separate layers in photoshop and illustrator


###Importing Assets in After Effects

When you finished preparing your assets in Photoshop or Illustrator, you can start importing them in After Effects. Always check if your layers were properly imported so you don't have any problems in the future.

>video importing assets to after effects

##Digital Animation Concepts

###Compositions

Compositions are groups of elements inside of After Effects. An entire scene can be a composition, or even an entire animation. It all depends on the complexity of the animation and the number of elements that needs to be animated.

The first thing you do when starting a new project in After Effects is create a new composition. 

compositions, layers


### Animation Properties

Every element in After Effects has a few base properties that will define its animation. The most important properties are **position, scale, rotation and opacity**.

Here is a quick example of these properties in After Effects:

![](/assets/unit2/anim_properties.gif)

- **Position** defines where the element is on screen over time.
- **Scale** defines the size of the element over time.
- **Rotation** defines the degree of rotation of the element over time.
- **Opacity** defines the transparency of the element over time.

A **mask** is not an animation property, but masks are very important and are used extensively in motion design. They are a little bit different because they need two elements to work: the animation element (in the example above, the cube) and the mask itself (the rectangle that animates over the cube).

These properties cover pretty much all of the animations we will create, and when coupled with masks, they consist of the core of digital animation and motion design.

> video how to access properties in after effects

### Keyframes

In traditional animation, we generally think in terms of frames and how they are defined by importance (keyframes, extremes and inbetweens). These concepts are also important in digital animation, but there is a shift in the way you work and understand them. For example, once you create keyframes for an element in After Effects, the software will automatically fill in the gaps with inbetweens. Most of the time, it is not necessary to worry about extremes and inbetweens at all because a lot of the work is done on the keyframes themselves, through speed and easing options.

In After Effects, when you create a keyframe, that keyframe is automatically set as a **linear keyframe**.   

This is what linear keyframes look like:

![](/assets/unit2/linear_keys.jpg)

When you have two linear keyframes like that, it means that the **timing and spacing** between those keyframes is constant and that animation doesn’t have any kind of easing.

To apply easing to your keyframes all you have to do is select the keyframes, click with the right mouse button, then select **Keyframe Assistant > Easy Ease**. Your keyframes now will look like this:

![](/assets/unit2/ease_keys.jpg)

This will create an effect as if the inbetweens are grouped closer to the keyframes, creating smoother acceleration and deceleration. The great thing about easing keyframes in After Effects is that it can be applied to any animation property: position, scale, rotation and even opacity.

>render and composition settings


