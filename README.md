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