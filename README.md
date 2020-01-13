# hack-a-thing-1-bryanshin

## What did I do?
I am very interested in incorporating an AR/VR component into my CS98 project, so I decided to use this opportunity to learn about AR. I followed a well-written tutorial that outlined the developement of an Android application that can paint lines either on a detected flat surface or in 3D space, and then visualize that in AR. The tutorial I followed can be found using the link at the bottom of this readme.

## Who did what?
I worked by myself on this.

## What did you learn?
I have done some small, brief projects in Unity, but this tutorial taught me alot of fundamentals that I had never learned before, such as proper project structuring, prefab creation, materials creation, and general C# scripting. I also learned about the different ways that Unity implements AR developement. I found that Unity includes a variety of different packages that allow for AR programming, such as AR Foundation, AR Kit, and Vuforia. For this project, AR Foundation was used. I learned how to set up a Unity scene to include the foundation objects for AR. Finally, I learned a little bit about raycasting, and how Unity handles it using AR Foundation (conveniently). This was great, as it seems like an effective way to implement user interaction with the scene.

## What didn't work?
One thing that I found very difficult was testing the code. Because AR by nature requires camera input, it was nearly impossible to test my application using the Unity editor. There was no way to mimic camera input. One solution I tried to implement was feeding in my webcam's video input, but this was super difficult because in order to do that, I would have to constantly change build platforms from Mac to Android (and vice-versa). The only way I found to test my code was to simply build the application and run in on my phone, which took around 2-3 minutes. This doesn't seem to bad, but since I was inexperienced in the AR making process and had to debug super often, this build time ate up a large chunk of time.
I was also unable to implement different colors of paint. There seems to be an issue with using the Trail Renderer component in Unity, as changing the color of the material and the Trail Renderer both still result in a black line drawn. I tried researching the issue, and it seems that it is comes from a conflict between the new versions of Unity not supporting the outdated Trail Renderer very well.

## URL to the tutorial I used:
https://vrgamedevelopment.pro/make-an-ar-drawing-app-part-3/

## Notes:
* The completed Android application is in the Builds folder.
* Download the .apk file to your Android device, open it, and install the application.
