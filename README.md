[![DUB Package](https://img.shields.io/dub/v/dray.svg)](https://code.dlang.org/packages/dray)

# dray

dlang bindings to [raylib](https://github.com/xdrie/raylib) **v3.5.0** (based on the official upstream [3.5.0 release](https://github.com/raysan5/raylib/releases/tag/3.5.0)).

some minor changes are included:
+ `raygui` included
+ HIDPI enabled

## usage

all you need to do is add this package as a dependency and it should automatically build the Raylib C library and link it in.
if for some reason you want to use a custom build, just place your own `libraylib.a` in the package root (usually something like `~/.dub/packages/dray_xxx`.

note that `raylib` has some of its own dependencies such as OpenGL.

## example

see [example](example/), which demonstrates a simple application using these Raylib bindings.
