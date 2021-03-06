# VR development frameworks
#### February 14, 2019

Creating VR desktop applications is significantly different to Web applications due to the fact that developing in HTML5 brings specific practices into play and by that we need to consider the challenges and trade-offs that might occur. 

### Main 3D development practices. Moving from 3D web to WebVR
The main API for creating 3D in a web browser is WebGL. WebGL is compatible throughout all browsers and makes the most of the GPU capabilities that computers have to offer. In order to rapidly build 3D scenes in web pages we can use Three.js( https://threejs.org/ ): an intuitive, easy-to-use library that provides a set of commonly used 3D objects. Since it is open source and hosted on GitHub, the provided material can be further replicated or modified by the developer’s own intent. Three.JS has, in fact, been the most popular JavaScript 3D engine for Web applications. 


### A-Frame is your saviour.

Besides Mozilla’s VR team achievements with Oculus VR in 2014, they also contributed to the Three.JS project, by adding a set of objects for extending this library with VR capability. This became another major milestone in Mozilla’s strong contribution to WebVR development. On a stronger note, in December 2015 A-Frame was released. A-Frame, by Mozilla, is a framework for building VR experiences, based on top of HTML. It is an entity-component based framework, where the user can code re-usable components that can have their own schema, events and structure based on the Three.JS library.


### Why A-Frame?

Since A-Frame supports most VR Headsets, and can also be incorporated with other popular Web Development frameworks, such as ReactJS and Vue.JS, it can be considered as an organic choice for a web developer to choose this technology on 360° content making and also making the most use of positional tracking and controllers. 


### Further considerations

I have looked at React.JS A-Frame library released <a href="https://github.com/supermedium/aframe-react" target="_blank">here</a>. After a couple of tries in converting my project in A-Frame and vanilla JavaScript to a React-Aframe project I have decided to keep things simple and go with the original idea. React-Aframe can bring some compatibility issues in the future. Also, since I am using an Oculus Go and need to override the trackpad axis in order to be able to move in the scene - I think that if I went with React-Aframe it would cause another decrease in the performance speed. 


### What I have got so far

Default Scene - sound source (sphere). User can change the materials/properties of the room they're in. 