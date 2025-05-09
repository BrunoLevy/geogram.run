# geogram.run
[geogram](https://github.com/BrunoLevy/geogram) utilities and demos usable in a browser (transpiled with emscripten)

_Note that transpiled Geogram programs are
between 5x and 10x slower than their native versions. If you
want the best experience with Geogram, I highly recommend using
a version compiled for your processor/OS (but these transpiled
versions can be used to occasionaly repair/remesh small meshes)_

Applications
------------
- [GeoBox](https://brunolevy.github.io/geogram.run/geobox.html) _(geometry processing in your browser)_
- [GeoCod](https://brunolevy.github.io/geogram.run/geocod.html) _(teaching how to code, for kids)_
- [GeoShade](https://brunolevy.github.io/geogram.run/geoshade.html) _(teaching GLSL, with examples from ShaderToy)_

_Note_: you can load your own files in the application. For that, use
the _add file:_ `Browse...` button (top right). We cannot use an
in-app menu to open a file load dialog box (browser's security rules
forbids that). The output can be saved by the _File/Save as..._ menu
in the application (and then will be available from the browser as if
it was downloaded from the web).

Basic demos
-----------
- [Delaunay2d](https://brunolevy.github.io/geogram.run/geogram_demo_Delaunay2d.html)
- [Delaunay3d](https://brunolevy.github.io/geogram.run/geogram_demo_Delaunay3d.html)
- [Sphere eversion](https://brunolevy.github.io/geogram.run/geogram_demo_Evert.html)
- [Ray tracing](https://brunolevy.github.io/geogram.run/geogram_demo_Raytrace.html)
