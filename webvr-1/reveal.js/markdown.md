# WebXR

Austin Godber

@godber

phxvr.org/webvr.dev


## Why the Web?

* Low friction
  * Immersive with 2D fallback
  * Distribution is easier
  * Source easily shared and copied
* The web eats everything
* Lots of cases where it's a bad choice


...


I already bought the domain.


## WebGL/WebGL2

Javascript API supported by major browsers

* `v1` - 2011 ([link](https://www.khronos.org/registry/webgl/specs/latest/1.0/))
    * OpenGL ES 2.0 on HTML 5
* `v2` - 2017 ([link](https://www.khronos.org/registry/webgl/specs/latest/2.0/))
    * OpenGL ES 3.0 on HTML 5
    * **Extends** `v1`


All sensible modern browsers support WebGL2 at this point.

You can test yours here:
https://get.webgl.org/webgl2/


iOS and MacOS Safari was a little behind the curve, but the latest versions do appear to
support it (Nov 2021).


You can write WebGL v1/v2 code directly, but you do so by writing in a low level
language understood by GPUs called GLSL.

I think most people use higher level options we'll discuss later.


Here are two great resources for exploring the WebGL route:

* https://webglfundamentals.org/
* https://webgl2fundamentals.org/


## How to do it?

Your options for building an immersive experience on the web include:

* Direct WebGL Implementation
* Javascript WebXR Framework
* Export WebGL from a Game Engine
    * Unity, Unreal, Godot
    * Wavering support
* WebXR Engines
    * https://wonderlandengine.com/
    * Are there more?


We're going to concentrate the Javascript/HTML Frameworks and demo some options.



## WebXR Frameworks

* [threejs](https://threejs.org/)
    * aframe
    * [r3f](https://docs.pmnd.rs/react-three-fiber/getting-started/introduction)
* babylonjs
* [ar.js](https://ar-js-org.github.io/AR.js-Docs/)


## Threejs

```js
const foo = 'bar';
```



## Aframe

threejs wrapper



## r3f - React 3 Fiber

threejs wrapper

https://docs.pmnd.rs/react-three-fiber/getting-started/introduction



## babylon.js



## PWA on Oculus

https://timmykokke.com/blog/2021-11-05-webxr-pwa-apk/

## Physics

* `ammo.js`
* `canon.js`??


