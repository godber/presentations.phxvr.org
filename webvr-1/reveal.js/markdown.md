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


## Outline

* Foundation
* Tools
* Demo
* Other Examples


# Foundation


Two enabling browser APIs form the foundation of any immersive web experience:

* **WebXR** - enables browser access to XR Hardware
* **WebGL** - enables browser access to GPU Hardware


<img height=600px src="./webxr-stack-v1.png">


## WebXR Device API

> WebXR is an API for web content and apps to use to interface with mixed reality hardware such as VR headsets and glasses with integrated augmented reality features.

-- [MDN](https://developer.mozilla.org/en-US/docs/Web/API/WebXR_Device_API/Fundamentals#what_webxr_is_and_isnt)


* WebXR spec
    * https://www.w3.org/TR/webxr/
* MDN WebXR Docs
    * https://developer.mozilla.org/en-US/docs/Web/API/WebXR_Device_API


## WebGL/WebGL2 APIs

API supported by major browsers

* `v1` - 2011 ([link](https://www.khronos.org/registry/webgl/specs/latest/1.0/))
    * OpenGL ES 2.0 on HTML 5
* `v2` - 2017 ([link](https://www.khronos.org/registry/webgl/specs/latest/2.0/))
    * OpenGL ES 3.0 on HTML 5
    * **Extends** `v1`
* MDN WebGL Docs
    * https://developer.mozilla.org/en-US/docs/Web/API/WebGL_API


All sensible modern browsers support WebGL2 at this point.

You can test yours here:
https://get.webgl.org/webgl2/


iOS and MacOS Safari was a little behind the curve, but the latest versions do appear to
support it (Nov 2021).


You can write WebGL v1/v2 code directly, but you do so by writing in a low level
language understood by GPUs called GLSL.  Wrapped in Javascript.

I think most people use higher level options we'll discuss later.


Here are two great resources for exploring the WebGL route:

* https://webglfundamentals.org/
* https://webgl2fundamentals.org/



# Tools


Your options for building an immersive experience on the web include:

* Direct WebGL Implementation
* Javascript WebXR Framework
* Export WebGL from a Game Engine
    * Unity, Unreal?, Godot
    * Wavering support
* WebXR Engines?
    * https://wonderlandengine.com/


We're going to concentrate the Javascript/HTML Frameworks.



## Javascript WebXR Frameworks

* `three.js`
    * `A-Frame`
    * `react-three-fiber` (`r3f`)
* `babylonjs`
* `ar.js`


## Threejs

<?xml version="1.0" encoding="UTF-8"?>
<svg width=100 height=100 fill="none" stroke-linecap="square" stroke-miterlimit="10" version="1.1" viewBox="0 0 226.77 226.77" xmlns="http://www.w3.org/2000/svg">
 <g transform="translate(8.964 4.2527)" fill-rule="evenodd" stroke="#000" stroke-linecap="butt" stroke-linejoin="round" stroke-width="4">
  <path d="m63.02 200.61-43.213-174.94 173.23 49.874z"/>
  <path d="m106.39 50.612 21.591 87.496-86.567-24.945z"/>
  <path d="m84.91 125.03-10.724-43.465 43.008 12.346z"/>
  <path d="m63.458 38.153 10.724 43.465-43.008-12.346z"/>
  <path d="m149.47 62.93 10.724 43.465-43.008-12.346z"/>
  <path d="m84.915 125.06 10.724 43.465-43.008-12.346z"/>
 </g>
</svg>

* https://threejs.org
* [docs](https://threejs.org/docs/index.html#manual/en/introduction/Creating-a-scene)
* [examples](https://threejs.org/examples/#webgl_animation_keyframes)
* [fundamentals](https://threejs.org/manual/#en/fundamentals)
    * I'd start here.


### Threejs Fundamentals

Javascript framework for working with WebGL and WebXR ... scenegraph based:


<img src="./threejs-structure.svg">


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


