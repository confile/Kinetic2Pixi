Kinetic2Pixi
============

[![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/confile/Kinetic2Pixi?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

The project describes the migration of a KineticJs application to PixiJs


Stage
-----

Kinetic
```
var stage = new Kinetic.Stage();
```
Pixi
```
var stage = new PIXI.Stage(0x66FF99);
```


Join the project
================

- If you want to join this project you can contact me at mail@michaelgorski.de or file an issue.
- Gitter Chat: https://gitter.im/confile/Kinetic2Pixi

ToDo Kinetic which should be migrated
=============================================

- Zoom
- Kinetic.Layer is handled using stage.addChild method with the index parameter
- Kinetic.Rect to PIXI.Graphics
- Kinetic.Image to PIXI.ImageLoader
- Kinetic.Group to PIXI.DisplayObjectContainer
- Event listeners are handled through PIXI.DisplayObject (abstract class, all object extend this and thus have listeners)

