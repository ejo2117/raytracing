hobby project following the excellent [_Ray Tracing in One Weekend_](https://raytracing.github.io/books/RayTracingInOneWeekend.html)

edit `main.cc` to add/remove objects from the scene

then, you can build using clang:

```
clang++ -Wall -std=c++11 [path_to_main.cc] -o render
```

and view the scene in ppm format:

```
./render > scene.ppm
```

you should end up with an image that looks like this:

![scene](https://github.com/ejo2117/raytracing/assets/35907890/47279041-8656-48aa-8be7-1358458d3f34)
