# Class 11

## 🛠️ Debugging

* [p5js Debugging article](https://p5js.org/learn/debugging.html)
* ["Expert Software Developers' Approach to Error"](https://www.youtube.com/watch?v=UNMF5AS4SLg)
* What to do when [something doesn't work](../images/debugging.png)
  * Does your IDE point out any syntax problems?
  * Is there an error message in the console?
    * Is there a "[stack trace](https://en.wikipedia.org/wiki/Stack_trace)"?
  * Check your syntax
  * Can you make a more basic version of the code do something?
  * Double-check the documentation
  * Do some Googling - has someone else had this problem?
* General debugging
  * [Syntax errors](../images/roses-are-red.jpg)
  * Reference errors (is your code pointing to the right thing?)
  * `console.log()` / `println()`
  * Debuggers - [live demo](http://localhost/haxademic.js/demo/#three-scene)
* Graphical debugging
  * It's hard...
  * If something isn't displaying, can you make a simpler version?
  * Add a "debug view"
    * [#debugviewart](https://www.instagram.com/explore/tags/debugviewart/)

## 🛠️ Machine Learning & AI

### How to do ML/AI things

1. Use a friendly, commercially-available ML tool
2. (Beginner*) Find or download a tool/library/service that someone else has created, and use it
3. (Advanced) Download a tool that someone else has made, and train your own data set, then use that
4. (Expert) Write your own ML tool using existing ML frameworks like PyTorch or Tensorflow

__*__ Just using a ML tool that is "ready to use" can be an [expert-level](../images/carmack-pytorch.png) journey

### Find an ML tool

ML is really good at dealing with images, so many of the popular machine-learning tools are either image generators or analyzers. However, some other popular ML tools deal with text, audio, and other data types to do amazing, magical things. Some places to start, depending on your interests:

* Computer vision (image analysis)
  * [MediaPipe](https://mediapipe.dev/)
    * [MediaPipe multi-mode tracker in p5js](https://editor.p5js.org/orrkislev/sketches/wwLqrnVDt)
  * [YOLO](https://pjreddie.com/darknet/yolo/)
* Image creation
  * Diffusers like [Dall-E](https://openai.com/dall-e-3), [Midjourney](https://www.midjourney.com/), and [Stable Diffusion](https://github.com/CompVis/stable-diffusion)
  * [GAN](https://github.com/NVlabs/stylegan3)s
  * [FaceFusion](https://github.com/facefusion/facefusion)
* Image manipulation
  * [Super-resolution](https://deepai.org/machine-learning-model/torch-srgan) tools
  * [Frame interpolation](https://github.com/megvii-research/ECCV2022-RIFE) tools
  * [Style transfer](https://genekogan.com/works/style-transfer/), [pix2pix](https://phillipi.github.io/pix2pix/) and other image-based generators & effects
  * [Palette extraction](https://github.com/angristan/palette)
* Text (or code) generation
  * [ChatGPT](https://chat.openai.com/)
  * [LLaMA](https://cocktailpeanut.github.io/dalai/)
  * [GitHub Copilot](https://github.com/features/copilot)
* Audio manipulation
  - [OpenAI Jukebox](https://openai.com/blog/jukebox/)
  - [Spleeter](https://waxy.org/2019/11/fast-and-free-music-separation-with-deezers-machine-learning-library/)
  - [Open-Unmix](https://sigsep.github.io/open-unmix/js.html)
  - [Adobe Enhance Speech](https://podcast.adobe.com/enhance)
  
### Install an ML tool

How to install an ML tool:

* Some ML tools are fully hosted online and you don't need to install anything
  * [Stable Diffusion @ Stability.AI](https://huggingface.co/spaces/stabilityai/stable-diffusion)
  * [DreamStudio](https://beta.dreamstudio.ai/generate)
* Some will be pre-packaged into a nice UI in a desktop app. This is rare
  * [Runway](https://runwayml.com/)
  * [Stable Diffusion GUI](https://nmkd.itch.io/t2i-gui)
  * [Flowframes](https://nmkd.itch.io/flowframes)
  * [Waifu2x-Extension-GUI](https://github.com/AaronFeng753/Waifu2x-Extension-GUI)
* Some have online notebooks that are ready to use, usually in [Google Colab](https://github.com/dvschultz/stylegan2-ada-pytorch). This creates a virtual environment with a good GPU to use. You should be able to copy a notebook into your own acount and start using it. This will also usually cost money if you want a very good GPU.
* Some must be installed on your own computer. Sometimes a very fancy GPU is required (look for GPU RAM requirements). Often Linux and Windows are the target platforms
  * [This can be hard](../images/get-old-repo-to-run.png), [really](../images/get-old-repo-to-run-again.png)
  * Some projects are making it easier to install and run their tools
    * [Stable Diffusion WebUI](https://github.com/AUTOMATIC1111/stable-diffusion-webui)
* Many existing apps are now adding AI features
  * [Photoshop](https://twitter.com/AiBreakfast/status/1661217865205440512?lang=en)
  * [Windows Copilt](https://www.microsoft.com/en-us/windows/copilot-ai-features)
  * [VS Code + GitHub Copilot](https://github.com/features/copilot)

### Articles / videos

* [It’s Time to Pay Attention to A.I. (ChatGPT and Beyond)](https://www.youtube.com/watch?v=0uQqMxXoNVs)
* [Stable Diffusion, 1 month in](https://twitter.com/daniel_eckler/status/1572210382944538624)
* [Vox: The text-to-image revolution, explained](https://www.youtube.com/watch?v=SVcsDDABEkM)
* [Will Artificial Intelligence End Human Creativity?](https://www.youtube.com/watch?v=oqamdXxdfSA)
* [The Many Ways that Digital Minds Can Know](https://moultano.wordpress.com/2023/06/28/the-many-ways-that-digital-minds-can-know/)

### Courses / Tutorials

* Syllabus update: Find almost anything on YouTube!

### Interesting ML Tools

Lists of tools:

* https://pharmapsychotic.com/tools.html
* https://github.com/cacheflowe/creative-coding-notes#machine-learning
* https://twitter.com/golan/status/1496311115571212294

Beginner-friendly

* [ml5js](https://ml5js.org/) [demo from scratch](https://www.youtube.com/watch?v=8HEgeAbYphA)
* [Teachable Machine by Google](https://teachablemachine.withgoogle.com/) & [Shiffman tutorials](https://thecodingtrain.com/TeachableMachine/index.html)
* [Wekinator](http://www.wekinator.org/)
* [Artbreeder](https://www.artbreeder.com/)
* [Stable Diffusion GUI](https://nmkd.itch.io/t2i-gui)
* [Runway](https://runwayml.com/)

Computer vision

* [Mediapipe](https://google.github.io/mediapipe/)
* [Tensorflow](https://www.tensorflow.org/js/models)
  * [PoseNet](https://github.com/tensorflow/tfjs-models/tree/master/posenet)
  * [BodyPix](https://blog.tensorflow.org/2019/11/updated-bodypix-2.html)
* [YOLO](https://pjreddie.com/darknet/yolo/)
* Processing
  * [Creative Machine](https://github.com/jjeongin/creative-machine)
  * [Deep Vision Processing](https://github.com/cansik/deep-vision-processing)
  
More advanced

* [VQGAN + CLIP](https://alexasteinbruck.medium.com/vqgan-clip-how-does-it-work-210a5dca5e52)
* [StyleGAN3](https://github.com/NVlabs/stylegan3)
* [AWS ML tools](https://aws.amazon.com/machine-learning/)
* [Machine Learning for Artists](https://ml4a.net/)
* [Style Transfer](https://tenso.rs/demos/fast-neural-style/)
* [Spleeter](https://waxy.org/2019/11/fast-and-free-music-separation-with-deezers-machine-learning-library/)
* [Synopsis](https://special-circumstances.info/)
* [Descript](https://www.descript.com/)
* [Demucs](https://github.com/facebookresearch/demucs)
* [Depth-Aware video frame INterpolation (DAIN)](https://github.com/baowenbo/DAIN)
* [Consistent Video Depth Estimation](https://github.com/facebookresearch/consistent_depth)
* [Hotpot](https://hotpot.ai/tools)

### ML/AI Artists

* [List: mlart.co](https://mlart.co/)
* [Sougwen Chung](https://sougwen.com/)
* [Mario Klingemann](https://twitter.com/quasimondo/)
* [Ellie Pritts](https://www.instagram.com/elliepritts/)
* [Kyle McDonald](https://twitter.com/kcimc) - "[Discrete Figures](https://research.rhizomatiks.com/s/works/discrete_figures/en/)"
* [Helena Sarin](https://www.instagram.com/helena.sarin/)
* [Memo Akten](https://twitter.com/memotv)
* [Refik Anadol](http://refikanadol.com/)
* [Charlie Gerard](https://www.smashingmagazine.com/2019/09/machine-learning-front-end-developers-tensorflowjs/)
* [Derrick Schultz](https://artificial-images.com/)
* [Sofia Crespo](https://www.instagram.com/sofiacrespo/)

### Diversity in ML

* [WIRED: AI Is the Future - But Where Are the Women?](https://www.wired.com/story/artificial-intelligence-researchers-gender-imbalance/)
* [Women in Machine Learning](https://wimlworkshop.org/)
* [Women in Machine Learning & Data Science: Boulder](http://wimlds.org/about-the-boulder-team/)
* [Feminist.AI](https://www.feminist.ai/)
* [NPR: Lack of diversity in AI development causes serious real-life harm for people of color](https://www.npr.org/2022/02/13/1080464162/lack-of-diversity-in-ai-development-causes-serious-real-life-harm-for-people-of-)

### ML: The Good Things

* [Healthcare](https://blog.research.google/2019/12/developing-deep-learning-models-for.html)
* [Computer vision](https://www.youtube.com/watch?v=IXdDND9cVDg)
* [Self-driving cars](https://blogs.nvidia.com/blog/drive-labs-panoptic-segmentation/)
  * [But...](https://twitter.com/ISusmelj/status/1558912252119482368)
  * [And...](https://theintercept.com/2023/11/06/cruise-self-driving-cars-children/)
  * [And...](https://www.youtube.com/watch?v=E7ulhOcFfI0)
  * [And...](https://www.sfchronicle.com/projects/2023/self-driving-car-crashes/)
* [Helpful robots](https://youtu.be/tf7IEVTDjng?t=63) (or are they war machines?)
* [Natural Language Processing](https://www.youtube.com/watch?v=fOvTtapxa9c)
* [Enhancing old recordings](https://twitter.com/doodlewhale/status/1225796918128906243)
* [DrumBot - a digital bandmate](https://twitter.com/notwaldorf/status/1201599495244537858)

### ML: The Bad Things

* [Bias](https://twitter.com/lilyraynyc/status/1547361484144984065)
* [Bias in "creative tools"](https://techpolicy.press/researchers-find-stable-diffusion-amplifies-stereotypes/)
* [Bias in "generative AI"](https://www.bloomberg.com/graphics/2023-generative-ai-bias/)
* [Predictive policing algorithms are racist. They need to be dismantled.](https://www.technologyreview.com/2020/07/17/1005396/predictive-policing-algorithms-racist-dismantled-machine-learning-bias-criminal-justice/)
* [Healthcare bias](https://www.pcmag.com/opinions/healthcare-algorithms-are-biased-and-the-results-can-be-deadly)
* [Maybe it's not as good as we think](https://www.scientificamerican.com/article/ai-in-medicine-is-overhyped/)
* [Safety](https://www.businessinsider.com/hackers-trick-tesla-accelerating-85mph-using-tape-2020-2)
* [Privacy](https://twitter.com/kashhill/status/1218510902556811264)
* [Privacy, again](https://twitter.com/kmlefranc/status/1221869659139366912?s=20) [*](https://fama.io/product/)
* [Carbon footprint](https://www.technologyreview.com/s/613630/training-a-single-ai-model-can-emit-as-much-carbon-as-five-cars-in-their-lifetimes/) [:-(](https://www.technologyreview.com/2022/11/14/1063192/were-getting-a-better-idea-of-ais-true-carbon-footprint/)
* [Deepfakes](https://www.theguardian.com/technology/2020/jan/13/what-are-deepfakes-and-how-can-you-spot-them)
* [Job security](https://www.nytimes.com/2022/09/02/technology/ai-artificial-intelligence-artists.html)

### Biases in Software

Not necessarily specific to ML, but exacerbated by ML. Who is building the software that we use?

* [Bias against left-handed people](https://en.wikipedia.org/wiki/Bias_against_left-handed_people#Computer_input_devices)
* [Color film was built for white people. Here's what it did to dark skin.](https://www.youtube.com/watch?v=d16LNHIEJzs)
* [What my color-blindness taught me about design](https://uxdesign.cc/what-my-color-blindness-taught-me-about-design-d3009a93ff9c)
* [Women Work Better in Warmer Rooms, Study Says](https://time.com/5592353/office-temperature-study/)
* [Women suffer needless pain because almost everything is designed for men](https://www.vox.com/future-perfect/2019/4/17/18308466/invisible-women-pain-gender-data-gap-caroline-criado-perez)
* [Women suffer needless pain because almost everything is designed for men](https://www.vox.com/future-perfect/2019/4/17/18308466/invisible-women-pain-gender-data-gap-caroline-criado-perez)
* [Why Can't This Soap Dispenser Identify Dark Skin?](https://gizmodo.com/why-cant-this-soap-dispenser-identify-dark-skin-1797931773)
* [The racism of technology - and why driverless cars could be the most dangerous example yet](https://www.theguardian.com/technology/shortcuts/2019/mar/13/driverless-cars-racist)
* [What Domino's digital accessibility lawsuit means for compliance](https://www.ciodive.com/news/what-dominos-digital-accessibility-lawsuit-means-for-compliance/564737/)
* [Cost Cutting Algorithms Are Making Your Job Search a Living Hell](https://www.vice.com/en_us/article/pkekvb/cost-cutting-algorithms-are-making-your-job-search-a-living-hell)

## 📝 Homework:

* Read:
  * Some of the articles above
  * Investigate some ML tools
* Build something with a machine-learning tool
  * *Or* start work on your final project and present that next week

## 📋 Review code

* Present your web tech
