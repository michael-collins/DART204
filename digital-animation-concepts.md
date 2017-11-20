##Digital Animation Concepts

###Compositions

Compositions (or comps) are containers of elements inside of After Effects. Comps have their own independent timelines and layer hierarchy. Based on the complexity of your animation you can have one comp, or hundreds of them. It all depends on the number of elements that needs to be animated.

Comps can have many different roles in you project. Since comps can be **nested**, they are essential to organize your animation and create a **hierarchy** inside After Effects. As an example, you can have an animated bouncing ball element in one comp, and a background environment animation in another. You can group and edit these two animations inside a third comp, that in this case will be a scene. If you have multiple scenes, you can then group and edit them all together in a bigger comp, which could contain your entire animation.

The first thing you do when starting a new project in After Effects is create a new composition, and assets from Photoshop and Illustrator are imported in After Effects as compositions, giving you access to their separate layers and timelines.

###Layers

Much like in Photoshop and Illustrator, layers in After Effects are used to define an element in a scene, and if that element will be in front or behind another element. Each layer can be animated separately and has its own set of animation properties.


### Animation Properties

Every element in After Effects has a few base properties that will define its animation. The most important properties are **position, scale, rotation and opacity**.

Here is a quick example of these properties in After Effects:

![](/assets/unit2/anim_properties.gif)

- **Position** defines where the element is on screen over time.
- **Scale** defines the size of the element over time.
- **Rotation** defines the degree of rotation of the element over time.
- **Opacity** defines the transparency of the element over time.

These properties cover pretty much all of the animations we will create, and when coupled with masks, they consist of the core of digital animation and motion design.

> video how to access properties in after effects

A **mask** is not an animation property, but masks are very important and are used extensively in digital animation. They are a little bit different because they need two elements to work: the animation element (in the example above, the cube) and the mask itself (the rectangle that animates over the cube).

>video how to use masks

### Keyframes

In traditional animation, we generally think in terms of frames and how they are defined by importance (keyframes, extremes and inbetweens). These concepts are also important in digital animation, but there is a shift in the way you work and understand them. For example, once you create keyframes for an element in After Effects, the software will automatically fill in the gaps with inbetweens. Most of the time, it is not necessary to worry about extremes and inbetweens at all because a lot of the work is done on the keyframes themselves, through speed and easing options.

In After Effects, when you create a keyframe, that keyframe is automatically set as a **linear keyframe**.   

This is what linear keyframes look like:

![](/assets/unit2/linear_keys.jpg)

When you have two linear keyframes like that, it means that the **timing and spacing** between those keyframes is constant and that animation doesn’t have any kind of easing.

To apply easing to your keyframes all you have to do is select the keyframes, click with the right mouse button, then select **Keyframe Assistant > Easy Ease**. Your keyframes now will look like this:

![](/assets/unit2/ease_keys.jpg)

This will create an effect as if the inbetweens are grouped closer to the keyframes, creating smoother acceleration and deceleration. The great thing about easing keyframes in After Effects is that it can be applied to any animation property: position, scale, rotation and even opacity.

### Rendering
