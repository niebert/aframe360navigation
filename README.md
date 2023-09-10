# Aframe360Navigation
This repository applies link traversal concept on 360 degree images in [AFrame](https://aframe.io).

* **[360 Degree Tour at River Rhine near Rodenkirchen/Cologne in Germany](https://niebert.github.io/aframe360navigation)**

## 360 Degree Images
As 360 degree images 4 images of the river Rhine close to Cologne/Rodenkirchen in Germany were used:
* [**Rheinauen - Cologne 1**](https://niebert.github.io/HuginSample/rhein1_rodenkirchen.html) - [Equirectangular Image](https://niebert.github.io/HuginSample/img/rhein1_rodenkirchen.jpg) - image is licensed under the [Creative Commons](https://en.wikipedia.org/wiki/en:Creative_Commons) [Attribution-Share Alike 4.0 International license](https://creativecommons.org/licenses/by-sa/4.0/deed.en).
* [**Rheinauen - Cologne 2**](https://niebert.github.io/HuginSample/rhein2_rodenkirchen.html) - [Equirectangular Image](https://niebert.github.io/HuginSample/img/rhein1_rodenkirchen.jpg) - image is licensed under the [Creative Commons](https://en.wikipedia.org/wiki/en:Creative_Commons) [Attribution-Share Alike 4.0 International license](https://creativecommons.org/licenses/by-sa/4.0/deed.en).
* [**Rheinauen - Cologne 3**](https://niebert.github.io/HuginSample/rhein3_rodenkirchen.html) - [Equirectangular Image](https://niebert.github.io/HuginSample/img/rhein1_rodenkirchen.jpg) - image is licensed under the [Creative Commons](https://en.wikipedia.org/wiki/en:Creative_Commons) [Attribution-Share Alike 4.0 International license](https://creativecommons.org/licenses/by-sa/4.0/deed.en).
* [**Rheinauen - Cologne 4**](https://niebert.github.io/HuginSample/rhein4_rodenkirchen.html) - [Equirectangular Image](https://niebert.github.io/HuginSample/img/rhein1_rodenkirchen.jpg) - image is licensed under the [Creative Commons](https://en.wikipedia.org/wiki/en:Creative_Commons) [Attribution-Share Alike 4.0 International license](https://creativecommons.org/licenses/by-sa/4.0/deed.en).

With the [link-traversal](https://aframe.io/aframe/examples/showcase/link-traversal/index.html) approach users are able to navigate from one location to another location. Every single 360 degree images is used for a single location. The implementation of navigation in this example uses the Aframe tag `a-link` and the "sky" is generated with the equirectangular images, that are projected on a sphere. The objective of this repository is to provide a basic example for [Wikiversity learning resource for 3D modelling](https://en.wikiversity.org/wiki/3D_Modelling) and web-based exploratory Aframe environment for [Real World Labs](https://en.wikiversity.org/wiki/Real_World_Labs). The link traversal approach runs offline in a browser. For creating your 360 degree image you can use Hugin or e.g. specific dual fish eye cameras. See repository HuginSample, Wikiversity Learning Resource about 3D modelling and Aframe.

## Link Traversal
This example is based on the [`link-traversal` example of Aframe](https://aframe.io/aframe/examples/showcase/link-traversal/index.html) - see https://aframe.io/aframe/examples/showcase/link-traversal/index.html

You can also explore the basic concept of using [`AFrame`](https://aframe.io) models and [`AR.js`](https://ar-js-org.github.io/AR.js-Docs/) for location based an marker based [Augmented Reality](https://en.wikiveristy.org/wiki/3D_Modelling)

## JSON3D4Aframe
For adding 3D object on markers and generating basic 3D scenes on Markers you can use [JSON3D4Aframe](https://niebert.github.io/JSON3D4Aframe). Geometric element can be placed in a scene with 360 degree images. The learning objective focuses on a mathematical coordinate system an basic mathematical operations like rotation and moving of geometric primitives in a 3D scene.

See example https://niebert.github.io/JSON3D4Aframe/mods3d/water_molecule_sky_aframe.html

## Links
* [Aframe](https://aframe.io)
* [`JSON3D4Aframe`](https://niebert.github.io/JSON3D4Aframe)
* [`AR.js`](https://ar-js-org.github.io/AR.js-Docs/)
