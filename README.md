# Auto-Sticker Node (V1.0):

## Node Overview:
    Glossy Paper Amount:  Controls how much paper is glossy (0 = node; 1 = all)
    Paper Roughness:      Roughness of the paper shader
    Warble Scale:         Scale of the warble-texture
    Warble Strengh:       Intensity of the warbles
    Wear Scale:           Scale of the rip-texture
    Wear Roughness:       Detail Amount of the rip-texture
    Wear Falloff:         Changes the amount of the half-torn paper
    Wear Fac:             Intensity of the rips
    Seed:                 Just a random seed input
    ColorMap / Random:    Allows to use the Color Map in Cycles for getting the same randomness values between both render engines (Maybe good for Material Preview)
    Random Color Map:      Input your "Random-Color-Per-Face"-Map here!


You can add object duplicates, linked duplicates or just add more faces in Edit-Mode. Note that each "Sticker-Square" takes up the entire uv grid!

Also, there is no "Random per Island" node in Eevee, so if you want that feature you'll have to run the script shown on the right, with the sticker object selected in the viewport. This assigns a random color to each face, but must be "rebaked" if new faces are added in the mesh.  

If you want to add custom image clusers head into the other node group next to the main one. In it are two framed nodes which you'll have to change. One for the Image-Texture and the other one selects the number of lines and rows the image cluser has. (Yes it's 3-Axis, but that's just because blender doesn't have 2d-Vectors!)

The "Object-Info"-node gets its random value from the object-name, so seeds are going to change when renaming objects. Just a heads up!

If you have any further questions, feel free to contact me via Discord.


Alright, have fun with it and stay awesome! :D


## The Credit-Section 
    
    Original Sticker-Image provided to the public domain by Blender Bender
        Discord: Blender Bender#2640

    HDRI from HDRI/Poly-Haven
        https://polyhaven.com/hdris


    All of the node stuff made by me, David Buehler
        Discord: daveiator#0922
 
Also shoutout to that one guy in a forum, who shared the "randomFaces"-script! I can't seem to find the post anymore but it has prooven super useful in many projects! Thanks for that!


22. July 2021