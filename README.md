### Laser Maze
Lazer Maze is a clone of a game I played long time ago. 
In each level you must hit a target with a laser. You can move around, push objects. The Laser can interact with some objects. 
The main functionality is, that the laser always travels in straigt line. Mirrors can change its direction by 90°. 
The Mirrors are an example of objects that can interact with the laser. The can change its direction, but also the laser can rotate the mirror if hit from behind.

### Technical Notes
The game is writen in Rust. It uses ggez as a graphics engine and specs as a ECS.
The design in the background is similar to the one from https://sokoban.iolivia.me/