1. My project is plane fight with a BOSS. I did not work with anyone but I 
do make use of the bubble from previous assignment and modify it as bullets in this assignment. 

2. I have used three texture to map with my BOSS, plane and bullets. 

3. I modify the shader in the main.html. I change the value of diffuse and specular x by using 
floor funtion. Both of them will affect fcolor variable,which will change the shadow of the object.
The shader comments are in the main.html.

4. I make changes to make the eye position moving around the object. I am not sure this is what 
assignment ask for, but you can see 360 degree moving around the camera. 

5. My project is connecting to the real-time and I use TIME variable to control the bullet and 
When boss is getting beated. A part of BOSS's body will disappear, which controled by time(Beated
by our plane)

6. I think I have covered everything.

If the textures do not work, check the console for an error message related to “Cross-origin image”.  To use textures in WebGL we have to bypass a security issue that is present with most browsers.

Firefox
Go to:  about:config
Find: security.fileuri.strict_origin_policy parameter
Set it to false
Chrome
Close all running chrome instances first. Then start Chrome executable with a command line flag (strongly suggest making this a desktop icon for easy reuse):

chrome --allow-file-access-from-files

For more details and other methods see:

https://github.com/mrdoob/three.js/wiki/How-to-run-things-locally

 

 
