---
ID_PAGE: 25306
PG_TITLE: SpriteManager
PG_VERSION: 2.1
TAGS:
    - Sprite
---
##Description

class [SpriteManager](/classes/2.2/SpriteManager)



##Constructor

##new [SpriteManager](/classes/2.2/SpriteManager)(name, imgUrl, capacity, cellSize, scene, epsilon, samplingMode)

Create a new [SpriteManager](/classes/2.2/SpriteManager)
A tutorial about sprites can be found here

####Parameters
 | Name | Type | Description
---|---|---|---
 | name | string |  Name of the sprite manager
 | imgUrl | string |  Link of the image
 | capacity | number |  The capacity of the sprite manager
 | cellSize | number |  Size of cells
 | scene | [Scene](/classes/2.2/Scene) |  [Scene](/classes/2.2/Scene) which contain the sprite Manager
optional | epsilon | number |  Epsilon
##Members

###name : string

Name of the sprite manager

###cellSize : number

Size of cells

###sprites : [Sprite](/classes/2.2/Sprite)[]

Sprites contains in the manager

###renderingGroupId : number

The rendering group ID

###layerMask : number



###onDispose : () =&gt; void

Called on dispose

###fogEnabled : boolean



##Methods

###render() &rarr; void

Render this sprite manager
###dispose() &rarr; void


