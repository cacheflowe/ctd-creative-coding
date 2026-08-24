# Class 8

## 🛠️ Shaders

Platforms & tools

* [The Book of Shaders](http://thebookofshaders.com/) (+ [Editor](http://editor.thebookofshaders.com/))
  * A comprehensive guide to shaders, highly recommended
  * [Github contributions](https://github.com/patriciogonzalezvivo/thebookofshaders)
* [ISF (Interactive Shader Format)](https://isf.video/)
  * [ISF Editor](https://editor.isf.video/)
  * [Intro to ISF](https://www.youtube.com/playlist?list=PLUz4GJjPWsS0iqMFrCOiNBQ2R0yD7Wtfe)
  * [ISF files for VJ apps](https://www.interactiveshaderformat.com/)
* [glslsandbox.com](http://glslsandbox.com/)
  * Livecodeable intro to shaders
* [Shadertoy](https://www.shadertoy.com/)
  * The motherlode of shaders. Both awesome and educational
  * [Getting started](https://www.youtube.com/watch?v=u5HAYVHsasc)
* [Vertex Shader Art](https://www.vertexshaderart.com/)
* [shaderpark.com](https://shaderpark.com/)
* [Shader Doodle](https://github.com/halvves/shader-doodle)
  * [Examples](https://shader-doodle.com/gallery)
* [cables.gl](https://cables.gl/) ([intro](https://www.youtube.com/watch?v=oY4mdasGExA))
  * A comprehensive (and free!) tool for building WebGL experiences with a node-based interface, similar to TouchDesigner
* [TouchDesigner](https://derivative.ca/)
  * Integrates GLSL shaders in a node-based environment (requires Desktop app)
* [vvvv](https://vvvv.org/)
* [KodeLife](https://hexler.net/kodelife)
* [F3 App](https://www.f3.cool/)
  * Fragment shader live coding app
* [GraphToy](https://graphtoy.com/)
  * Amazing tool by Inigo Quilez, the master of shaders

Using GLSL shaders in p5js

* Built-in p5js shader support
  * [p5js Shaders](https://p5js.org/learn/getting-started-in-webgl-shaders.html)
  * [createShader()](https://p5js.org/reference/p5/createShader/)
  * [createFilterShader()](https://p5js.org/reference/p5/createFilterShader/)
  * [shader()](https://p5js.org/reference/p5/shader/)
    * [Example: applying a shader to a shape](https://editor.p5js.org/p5/sketches/3D:_shader)
  * [filter()](https://p5js.org/reference/p5/filter/)
* [p5.buildGeometry()](https://p5js.org/reference/p5/buildGeometry/)
  * [Buffer geometry basic example](https://editor.p5js.org/dave@daveisadork.com/sketches/0NbZbRLiw)
  * Cache your WEBGL drawing calls to be (sometimes drastically) more efficient
* [p5.framebuffer()](https://p5js.org/reference/p5/createFramebuffer/)
  * [Example: feedback effect](https://editor.p5js.org/davepagurek/sketches/EULMkpgZz)
  * Offscreen rendering for compositing effects

Educational resources

* [The Little Grasshopper (Tutorial series)](http://www.pixelshaders.com/proposal/)
* [Three.js & Shaders](https://blog.maximeheckel.com/posts/the-study-of-shaders-with-react-three-fiber/)
* [thndl: WebGL from Scratch - Interactive Intro to Graphics Programming](https://www.thndl.com/)
* [WebGL2 Fundamentals](https://webgl2fundamentals.org/)
* [WebGL + Shaders tutorials](http://www.webglacademy.com/)
* [Learning shaders in three.js](https://blog.maximeheckel.com/posts/the-study-of-shaders-with-react-three-fiber/)
* [Paul Malin - Shadertoy demos & tutorials](https://shadertoyunofficial.wordpress.com/author/movax64/)
* [GPU Optimization for GameDev](https://gist.github.com/silvesthu/505cf0cbf284bb4b971f6834b8fec93d)
* [WebGL Fluid Simulation](https://github.com/PavelDoGreat/WebGL-Fluid-Simulation)
  * [Single-file WebGL 2 rewrite](https://haxiomic.github.io/GPU-Fluid-Experiments/html5/)
* [Codrops: Fun with WebGL2.0](https://tympanus.net/codrops/2023/03/28/modern-webgl-techniques-for-interactive-experiences/)
* [Shaderific - iOS Shader Editor](http://www.shaderific.com/glsl.html)
* [Learning Modern 3D Graphics Programming](https://paroj.github.io/gltut/)

Advanced shader resources

* [Raymarching Toolkit for Unity](https://github.com/neitri/Unity-RaymarchingToolkit)
* [Inigo Quilez Classics](https://www.iquilezles.org/www/index.htm)
* [Learn OpenGL](https://learnopengl.com/Introduction)
* [Real-Time Rendering Resources](http://www.realtimerendering.com/)
* [3D Game Shaders For Beginners](https://github.com/lettier/3d-game-shaders-for-beginners)

Demoscene

* [Pouet](http://www.pouet.net/)
  * [Fermi paradox](http://www.pouet.net/prod.php?which=68375) - 64KB, by Mercury
* [Demoscene - The Art of the Algorithms](https://www.youtube.com/watch?v=5MexnBunH_g)
* [Memories of Fractal Landscapes](https://www.playablefashion.com/writing/fractallandscapes/)


## 📝 Homework:

Read:

* [What is a particle system?](http://natureofcode.com/book/chapter-4-particle-systems/)
* [Signed Distance Field Resources](https://github.com/CedricGuillemet/SDF)
* [A trip through the Graphics Pipeline](https://fgiesen.wordpress.com/2011/07/09/a-trip-through-the-graphics-pipeline-2011-index/)
* [Casual Introduction to Low-Level Graphics Programming](http://stephaniehurlburt.com/blog/2016/10/28/casual-introduction-to-low-level-graphics-programming)
* [Computational complexity of GPGPU](https://thume.ca/2023/01/02/one-machine-twitter/)

Watch:

* [Shader Coding Introduction](https://www.youtube.com/watch?v=3mfvZ-mdtZQ&list=PLGmrMu-IwbguU_nY2egTFmlg691DN7uE5&index=1)
* [An introduction to Shader Art Coding](https://www.youtube.com/watch?v=f4s1h2YETNY)
* [Shaders and Textures with p5.js and WebGL](https://www.youtube.com/playlist?list=PLRqwX-V7Uu6bPhi8sS1hHJ77n3zRO9FR_)
* [Edan Kwan - Building Engaging WebGL Experiences](https://www.youtube.com/watch?v=lg8vukwgpo8)

**Build something with shaders**

* Recommended starter project:
  * Recreate [this animated gradient](https://cacheflowe.com/code/lab/webcam-shader-gradient) from Justin's 2020-10-12 lecture
    * [Video recording - see 1:02:00 mark](https://www.youtube.com/watch?v=P-03e3DkJnU&t=4141s)
* Other ideas
  * Build an interactive or animated shader to use as a background for one of your previous sketches
  * Use the webcam as a texture and create an effect with the ISF Editor
  * Use ilter() or createFilterShader() in p5js to make post-processing effects
  * Build your own particle system
  * Remix a shader that you find interesting on Shadertoy

## 📋 Review code

* Present your audio sketches
