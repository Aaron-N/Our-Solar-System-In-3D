# Our-Solar-System-In-3D
An interactive 3D model of our Solar System created with OpenGL.  

I created this model with the following adjustments for ease of use:
• Tweaked the planet diameters and orbital radii so they could be easily visible
• Kept everything to scale, except for the Sun, which I adjusted to a diameter that 
looked the best
• Followed Kepler’s Third Law of planetary motion
• Scaled the orbital periods of the planets and kept them proportional so the outer 
planets movement can be seen
• Used NASA textures for the textures of the Sun and all the planets, applied to 
instances of spheres
• Displayed the orbit path lines of each planet
• Created a point light at the sun that illuminates the planets, and also added some 
ambient light overall
• Put a starfield image in the distance behind the solar system when looking at it 
from the viewing position I select, just to give it a slightly more realistic look

To run, download all files and open Sample.sln with Visual Studio, run Clean Solution,
then Build Sample, and then start the program by selecting Start Without Debugging.

Screenshots are also available in this repository to view without running.
