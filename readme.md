# OxIO Gazebo models database

## Context

This a repository containing different Gazebo models (under the SDF format) to enable simulation of robots in an indoor context (european appartment).


## Prerequesite
This model set has been tested with Gazebo 9.
Download or clone this repo in a location of your choice and then add this folder as a Gazebo model database path.

To do so, type the following command in the terminal before launching gazebo (or add this line to your ~/.bashrc).

```
export GAZEBO_MODEL_PATH=[...yourpath...]/oxio_gazebo_database:$GAZEBO_MODEL_PATH
```

## Content
This database contains :
        - small_appartment : a model of a typical small european 2 rooms apparment (inspired from mine :P )
        - couch : a couch in the middle of the living room that you can remove or not, depending if your robot has enough room to move
        - movee : a model for the movee robot 

## Test
To test, it, launch the file "ex_appart.world" from the repository:
``` gazebo ex_appart.world ```

## Enjoy ! :)


## More infos

I created this datase using blender, following those tutorial :

* [Import meshes](http://gazebosim.org/tutorials?tut=import_mesh&cat=build_robot) - How to import meshes on the sdf format
* [Make a model](http://gazebosim.org/tutorials?tut=build_model&cat=build_robot) - How to create a model
* [Archimesh](https://www.youtube.com/watch?v=Y1f0HhyaEnE) - Archimesh tutorial on blender
* [Meshlab](http://www.meshlab.net/) - For collada file optimzization
