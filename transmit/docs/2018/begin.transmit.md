### In ten years humans will create 10 million new robots 

Maybe 100 million in the ten years after that. The default will be that ten people own them all, e.g. Jeff Bezos. This frustrates me. It’s unfair, short sighted and won’t end well. Bill Gates says we need a robot tax welfare. I don’t want to be on welfare. Neither does anyone I know.

Meanwhile in the world of not rich people, here’s an alternative idea: communal robots, owned by workers. For the last 18 months I've been working on this idea, but it’s been pointless to talk about because with robots there’s only show - not tell.

#### Well this week I can show - a little:

<iframe src="https://drive.google.com/file/d/1P8V7pKJnTlXcVzk1CoFVL1gV6yTmZFdZUg/preview" width="640" height="480"></iframe>

Welcome to the alternate reality where 10 million people will own those 10 million robots - a reality where “make it close, on-demand and cheaply bespoke” is an advantage for the working class. People like us!

So why did this bit of progress take me 18 months? Because like you, I have a day job. I work in the engine room at Autodesk. It's funny... Fusion360 and Eagle will play a key role for anyone who joins this worker-robot revolution.

#### What you see in the video is a couple of things 

*Thing 1:* a stepper motor as an Android USB type-C peripheral. It gets its data and 100W power from a standard USB cable. Btw, that’s Andy Rubin’s Essential PH-1 I bought used off of Amazon cheap. It’s unrooted, runs native OpenCV and has tons of sensors to support cool machine vision/learning applications. By this time next year people will literally be throwing away their 2018 Android models to get a 2019 model. Most of those old models have USB type-C. We can get them cheap and turn them into full-tilt controllers for boss robots!

*Thing 2:* a control program running at Google Compute. The motor’s behavior is not local - it’s coming from a container running 1000km away in Oregon. At some point I’ll support Amazon/AWS containers as well.

#### “So what?” you say...

The idea is that robot behaviors run entirely in the cloud. Doing this we can make them inherently communal so that others can remix and improve the best stuff, just like MIT's Scratch. I also plan to have an IDE cohabitate the container alongside the robot’s control app. This way you can dev/debug your robot live “en situ.” The container will spin up with everything it needs so you won’t have to install dev tools - ever. This makes it easier for normal people to build and test their own robot. Tho’ it will require me to bend Codenvy/Eclipse-CHE to my will. Which, btw, ***Codenvy***, this is something every cloud day-job person wants too. It’s silly that we dev/test on laptops and then shoehorn that into a cloud-based container. Idk, maybe Jetbrains gets there first and turns http://try.kotl.in/ into a real IDE that cohabitates a Kotlin app’s container. IntelliJ is great, but the world has changed entirely to cloud. There’s no value in sticking with misfit tooling leftover from a desktop dev era.

<img align="right" src="/images/cartbot.png">

####Next steps

I need to turn that tangle of wires into a single board that mounts to the back of the motor. Over the coming months I will use Autodesk EagleCAD to do that work, and I will share my progress. When it’s done, we should be able to get it off the bench and make something like a simple cartbot.

The whole thing is BSD-3 licensed - hardware and software. The goal is that motor makers will adopt, copy and improve my work. In a year or so, we should be able to click, click, click, and a box shows up that contains cheap parts to make our own industrial strength robots that implement behaviors shared from the work of others.

For the time being, these are toys - messy, hilarious, fun and frustrating.

https://blog.ycombinator.com/why-toys/ 

So… let’s play!

​	-- other real jeff
