---
layout: post
title: Droid Diaries 01 - Lunar Landing! 
---

The droids have successfully landed on the Lunar surface! Woooot woooott!! :fireworks: :tada: :confetti_ball: :tada: :fireworks: 

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">The droids have landed! Processing plant in sight...Team <a href="https://twitter.com/hashtag/jjunkyard?src=hash&amp;ref_src=twsrc%5Etfw">#jjunkyard</a> working on verifying telemetry data. <a href="https://twitter.com/hashtag/nasa?src=hash&amp;ref_src=twsrc%5Etfw">#nasa</a> <a href="https://twitter.com/hashtag/SpaceRobotics?src=hash&amp;ref_src=twsrc%5Etfw">#SpaceRobotics</a> <a href="https://twitter.com/hashtag/CentennialChallenge?src=hash&amp;ref_src=twsrc%5Etfw">#CentennialChallenge</a> <a href="https://t.co/G6TpDL0UKe">pic.twitter.com/G6TpDL0UKe</a></p>&mdash; Jjunkyard (@JawaJunkyard) <a href="https://twitter.com/JawaJunkyard/status/1246874400365744128?ref_src=twsrc%5Etfw">April 5, 2020</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script> 

Our team has been working hard trying to verify the telemetry from the robots. So far all sensors have been reporting as expected. We also have some initial imagery of the lunar surface from the droid's stereo cameras. :satellite:

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">Telemetry data from the droid looks A-OK. Here is some data from the stereo cameras on the droid! <a href="https://twitter.com/hashtag/jjunkyard?src=hash&amp;ref_src=twsrc%5Etfw">#jjunkyard</a> <a href="https://twitter.com/hashtag/nasa?src=hash&amp;ref_src=twsrc%5Etfw">#nasa</a> <a href="https://twitter.com/hashtag/space?src=hash&amp;ref_src=twsrc%5Etfw">#space</a> <a href="https://twitter.com/hashtag/robotics?src=hash&amp;ref_src=twsrc%5Etfw">#robotics</a> <a href="https://t.co/2tcCesjOqy">pic.twitter.com/2tcCesjOqy</a></p>&mdash; Jjunkyard (@JawaJunkyard) <a href="https://twitter.com/JawaJunkyard/status/1246876425195413505?ref_src=twsrc%5Etfw">April 5, 2020</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script> 

Droid wheels are responding as expected, remote tele-op sequence was executed flawlessly. Here is some recording from the sequence! :video_game:

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">Tele-op sequence initialized! Target is the perimeter of the processing plant! <a href="https://twitter.com/hashtag/jjunkyard?src=hash&amp;ref_src=twsrc%5Etfw">#jjunkyard</a> <a href="https://twitter.com/hashtag/nasa?src=hash&amp;ref_src=twsrc%5Etfw">#nasa</a> <a href="https://twitter.com/hashtag/centennialChallenge?src=hash&amp;ref_src=twsrc%5Etfw">#centennialChallenge</a> <a href="https://twitter.com/hashtag/space?src=hash&amp;ref_src=twsrc%5Etfw">#space</a> <a href="https://twitter.com/hashtag/Robots?src=hash&amp;ref_src=twsrc%5Etfw">#Robots</a> <a href="https://t.co/QgAhTjuF6h">pic.twitter.com/QgAhTjuF6h</a></p>&mdash; Jjunkyard (@JawaJunkyard) <a href="https://twitter.com/JawaJunkyard/status/1246885304486621185?ref_src=twsrc%5Etfw">April 5, 2020</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script> 

We also took the robot out for a spin around the lunar surface. Here is a footage from the waltz! :dancers:

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">Camera feed from the droid&#39;s space waltz! <a href="https://twitter.com/hashtag/jjunkyard?src=hash&amp;ref_src=twsrc%5Etfw">#jjunkyard</a> <a href="https://twitter.com/hashtag/Robotics?src=hash&amp;ref_src=twsrc%5Etfw">#Robotics</a> <a href="https://twitter.com/hashtag/NASA?src=hash&amp;ref_src=twsrc%5Etfw">#NASA</a> <a href="https://t.co/Ps9lJChbKU">pic.twitter.com/Ps9lJChbKU</a></p>&mdash; Jjunkyard (@JawaJunkyard) <a href="https://twitter.com/JawaJunkyard/status/1246885793697681408?ref_src=twsrc%5Etfw">April 5, 2020</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script> 

Our team is currently busy implementing some odometry plugins for the processing of the telemetry data from the four wheels so that we can have a better grasp on the positioning of the droid relative to other objects on the lunar surface. This will help us localize and autonomously navigate the droid without a human operator present. Bye bye tele-op sequences...

So far it has been a non-trivial problem since the droid has four independently driven wheel which all are steerable as well, and each can also move relative to each other since the mounting steering arms have certain degrees of freedom. Since the droid is being driven in a skid-steering configuration, all four wheels need to be taken into account when solving for the forward kinematics to estimate the pose of the robot. Stay tuned for updates on this. 

If you have any suggestions or useful pointers please feel free to comment below...also don't forget to follow us on Twitter for future updates from our team!
