# Uputstvo
1. `git clone https://github.com/gkatarina/grafika-projekat.git`
2. CLion -> Open -> path/to/my/project_base
3. Main se nalazi u src/main.cpp
4. Cpp fajlovi idu u src folder
5. Zaglavlja (h i hpp) fajlovi idu u include
6. Šejderi idu u folder shaders. `Vertex shader` ima ekstenziju `.vs`, `fragment shader` ima ekstenziju `.fs`
7. ALT+SHIFT+F10 -> project_base -> run

# grafika

Computer graphics project  
Day and night mode  
Includes everything from 1 - 9 week from the computer graphics course + face culling (on the models), advanced lighting (applied in shaders whenever any kind of lighting is included) and blending (mode discard used - on the grass texture).  
Group A - cubemaps (enviroment)  
Group B - hdr & bloom (moon/sun glow)  

No code outside of LearnOpenGL repository was used.  

W, A, S, D for moving around. Use SHIFT to toggle fast movement on or off.  
F1 to toggle ImGui on/off. ImGui gives mouse imput + controls.  
M to switch between night and day mode.  
F to toggle flashlight on/off. Flashlight can be used only in night mode.  
SPACE to toggle Bloom on/off

_Models_
Dam object: https://www.turbosquid.com/FullPreview/1868860  

_Textures_   
Wood texture used on cubes: https://www.flickr.com/photos/photoshoproadmap/8640003215  
Moon texture used for the sphere:  https://svs.gsfc.nasa.gov/cgi-bin/details.cgi?aid=4720  
Grass texture png: https://www.freeiconspng.com/img/44175  

_Cubemaps_  

Clouds: https://opengameart.org/content/cloudy-skyboxes  
Nightsky: //// (?)

Demo of the project can be found here: https://www.youtube.com/watch?v=F5k-6ctT110 
