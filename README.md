# three-js-raykim1996
Ray Dongho Kim

Project Name: Ray Dongho Kim_Three.js Project

https://pennvr.github.io/three-js-raykim1996/

In this project, I used Perlin Noise function, in order to generate randomness in terms of the plane's height and slope to give more "mountain"-like visual. I also used vertex coloring, making the g value of each vertex to depend on its height, creating some depth to the terrain visually. The firework particles are just created below the plane with random x and z position with random y-direction velocity with random amount of life-time. As their life-time ends, they trigger blast function, which creates group of smaller particles with random x, y, z velocity, in the next position where the original firework particle would be. The firework particle and the blasted particles have averaged value between random color and white, so the particles look like they emit light.

Just click the index.html file to run the code.

I did not feel any particular motion sickness. I think the fact that the camera is stationary and only can rotate in set position worked well in terms of not causing motion sickness. Also the terrain and particles are not too complicated visually, just consist of simple planes, made it easier for the users to perceive it.

The hardest part of this assignment was to implement appropriate randomness in gradiant vector part of Perlin Noise function and vertex-coloring.

If I have an opportunity to do this project again, I would try to implement fade/smoothing funstion to make the terrain less pointy/unnatural. Also I want to work more on the Perlin Noise function to improve it and make the adjacent vertices' heights to be more depending on surrounding ones, so even though I divide the whole plane into heigher divisions, increasing vertices, it can still generate smooth mountain-like terrain and less pointy.

It would be cooler / let the students' work to be cooler, if we went over how to apply shader thoroughly. Some TAs and other people in SigLab were saying using shader would make it cooler, so I initially wanted to try that. But it was had to apply shader, which I gave up and did the vertex-coloring instead to the terrain, to give better visuals than just plain colored terrain.

