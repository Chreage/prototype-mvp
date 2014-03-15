* recode arch with the node location independant of the scenegraph
* all node attached to the scene root


architecture
============
* generation of x,z of all node from lsystem
  * store the generation in the node itself
* display these nodes with THREE.Sprite
  * set the scale from the generation
* render a perlin terrain
  * set the y of each node to the terrain height
* use threex.domEvent on each node
  * if hover then display a DomElement cartouche with the name of the site
  * if click, open the url