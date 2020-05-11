# Enki (QT5)

a fast 2D robot simulator using the QT5 build system.

© 1999-2017 Stéphane Magnenat and others ([full list](AUTHORS))

© 2017 Bernd Porr <mail@berndporr.me.uk>


## License

[GPL 2.0](LICENSE).

# Build

first change into the enki folder

```
qmake
make
```
then go to examples and the ros directory
change to the catkin_ws
```
catkin_make
```
and hopefully all works :)

oh yeah, run with
```
rosrun enki_ros_pck robot
```
after sourcing the devel/setup.bash
