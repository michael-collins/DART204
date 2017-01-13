#### 2. Ease in and Ease out

On the last section we saw that by adjusting the spacing of an animation we can create different types of movement, making the animation more interesting and realistic. A very simple way of adding interest to your animation is called **ease in and ease out**. This animation principle is based on the idea that everything that moves, be a character or an object, will have acceleration and deceleration. A moving object cannot come to a full stop instantly or go from completely still to really fast in a second. Here is the example we saw on the last section:

![](/assets/unit1/04_05_timing02_anim.gif)

The ball starts moving slowly, reaches full speed and then slows down again before coming to a stop at frame 24. This type of movement looks natural to us, so if you want to create a realistic animation, adding ease in and ease out is very important.

Let’s look at another example. If we animate a ball bouncing on the floor and going back up, our chart will look like this:

![](/assets/unit1/06_easeinout01.gif)

The ball starts falling slowly, then reaches full speed right before it hits the floor and then bounces back up, easing out before it stops briefly in mid air and starts falling again. If you look at this chart closely, you will notice that when we group our frames together, we will slow down the movement of the ball, and when the frames are more spaced out, the ball seems to move faster.

In computer animation you have the option to animate without dealing with each individual frame, and some programs like After Effects even create ease in and out automatically. Very convenient! To adjust how an object eases in and out in After Effects you will use a tool called **animation curve** (also known as graph editor). This is what the curve for this animation looks like:

![](/assets/unit1/07_AE_curve.png)

At first glance it can look very different from what we have seen so far, but do not fear! It is very simple to understand once you get the hang of it.

The bar at the top shows the time, and on the left we see the amount of pixels the object is moving on the screen. The green line in this case represents the “Y” position (vertical value) of the ball. It shows that the ball starts at 500 pixels, goes to roughly 1400 pixels, and then comes back to 500 pixels. The way the line curves defines how the ball will move, and here it shows that the ball will slowly start from its initial position, then accelerate until it hits the floor, and then decelerate on its way back up.

On the next section we will look into two different approaches to animation called straight ahead and pose to pose, the differences between them and how they can complement each other.
