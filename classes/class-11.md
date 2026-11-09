# Class 11

## 🛠️ Machine Learning & AI

See [Learning With AI](../docs/learning-with-ai.md#articles-and-resources) for some hot takes and articles

🎤 **Case study**: New TD tools:

- https://github.com/cacheflowe/td-http-api
- https://github.com/cacheflowe/td-native-inference

## ML Models

  - Models
    - A machine learning model is a mathematical representation of patterns learned from data, used to make predictions or generate outputs. There are neural network models, decision trees, support vector machines, and many other types of models, each suited for different tasks and data types.
    - [But What Is a Neural Network?](https://www.youtube.com/watch?v=aircAruvnKk) - 3Blue1Brown
  - [Embeddings](https://editor.p5js.org/cacheflowe/sketches/W1R_BODeG)
    - > Embeddings are mathematical data representations of abstract concepts that translate between human mediums—like words, images, and sounds—and a shared coordinate system where machine learning models have been trained to calculate how those concepts relate.
  - Training vs inference
    - During **training**, the neural network analyzes billions of examples to calculate the patterns between concepts, automatically adjusting the numbers in its lookup table so that related ideas land closer together in mathematical space.
    - During **inference**, the model uses the learned patterns to make predictions or generate outputs based on new, unseen data.
  - Types of training
    - Supervised Learning (Learning with a Teacher): The model is trained on labeled data, learning to map inputs to known outputs.
    - Unsupervised Learning (Learning by Discovery): The model finds patterns and structures in unlabeled data.
    - Reinforcement Learning (Learning by Trial and Error): The model learns by interacting with an environment and receiving feedback in the form of rewards or penalties.
    - Self-Supervised Learning (The Modern LLM Method): The model generates its own labels from the input data and learns to predict them, often used for pretraining on large datasets.
  - Types of models
    - **Convolutional Neural Networks (CNNs):** Slide filters across an image to detect local pixel patterns and textures.
      - _GANs (Generative Adversarial Networks):_ Two networks (a generator and a discriminator) compete to produce realistic images.
      - _Autoencoders:_ Compress input data into a small embedding, then reconstruct it.
      - _Examples:_ StyleGAN, VGG-16, Stable Diffusion, Midjourney.
    - **Recurrent & State Space Models (RNNs & SSMs):** Process sequential data step-by-step using feedback loops or linear state tracking.
      - _Examples:_ LSTMs (early Google Translate), Mamba / Mamba-2.
    - **Transformers:** Use "self-attention" to weigh relationships between all parts of the input (text tokens or image patches) at once.
      - _Autoregressive:_ Predicts the next token in a sequence (e.g., GPT).
      - _Bidirectional:_ Reads context in both directions to understand meaning (e.g., BERT).
      - _Mixture of Experts (MoE):_ Routes each input through a small subset of specialized sub-networks for efficiency.
      - _Diffusion Transformers (DiTs):_ Applies transformers to grids of image patches for better layout and text rendering.
      - _Examples:_ GPT-4o, Gemini, Claude, BERT, Flux, Stable Diffusion 3.
    - **Multimodal Models:** Combine encoders for different media (text, images, audio) into a shared embedding space—so the phrase _"a golden retriever puppy"_ and a photo of one map to the same region.
      - _Examples:_ ChatGPT, Gemini, Claude, Nano Banana.
- LLMs 
  - The latest & greatest are multimodal models
  - Self-hosting ([llama.cpp](https://github.com/ggml-org/llama.cpp), [ollama](https://ollama.com/), [LMStudio](https://lmstudio.ai/))
    - [apfel](https://apfel.franzai.com/)
    - VRAM discussion
      - Applies to LLMs and any model that you run locally
  - Concepts
    - Tokens: The basic units of text that LLMs process.
    - Context window: The maximum number of tokens the model can consider at once.
    - Temperature/sampling: Controls randomness in generated outputs.
- Agent Harnesses
  - Coding Assistants
    - Claude
    - Copilot
    - Codex
    - Open-source options
      - pi / omp
  - [Skills](https://platform.claude.com/docs/en/agents-and-tools/agent-skills/overview)
  - Tool-calling
    - Run local shell commands and scripts
    - File system access & search
    - Web fetches
    - Network requests
    - [MCP servers](https://modelcontextprotocol.io/)
      - More and more integrations are being added to existing tools and platforms
      - [Blender](https://www.blender.org/lab/mcp-server/), [Unity](https://docs.unity3d.com/Packages/com.unity.ai.assistant@2.0/manual/unity-mcp-overview.html), [TouchDesigner](https://derivative.ca/community-post/derivative-tdmcp-mcp-server-touchdesigner-beta/75406), etc
      - Introspection and execution
    - "Thinking" agents that can plan and reason over multiple steps

## Creative ML Tools

- General frameworks for creative ML tools
  - [ComfyUI](https://comfy.org/)
  - [RunwayML](https://runway.com/)
  - [Flora](https://flora.ai/)
- Images
  - [Upscalers](https://github.com/xinntao/real-esrgan)
  - Style transfer
  - Inpainting
  - Cleanup & editing
  - Computer Vision - real-time and offline tools
    - [MediaPipe](https://developers.google.com/edge/mediapipe/solutions) & [Yolo](https://docs.ultralytics.com/tasks)
      - Face/Hand/Pose estimation (landmarks)
      - [Segmentation](https://www.aidemos.meta.com/segment-anything)
      - Object detection
    - Monocular [depth estimation](https://roboflow.com/blog/depth-estimation-models)
      - [DepthAnything](https://depth-anything.github.io/) v2/v3
      - Apple's Depth Pro
      - Microsoft's [DAViD](https://microsoft.github.io/DAViD/)
    - Optical flow
  - Photogrammetry (3d reconstruction from images)
    - [Gaussian splatting](https://superspl.at/)
    - Point clouds
    - Mesh reconstruction
  - Specific Generative image tools
    - Nano Banana, ChatGPT Images
    - Useful for concepting visual ideas
    - Useful for image editing 
    - Don't be surprised if people get mad at you for [generating a flier](https://www.liendesign.com/blog/how-to-spot-ai-flyer-design-packaging-mistakes)
- Video
  - Generative video slop :(
  - Scene-detection [splitting](https://www.scenedetect.com/)
  - Upscaling & Frame interpolation ([RIFE](https://github.com/hzwer/ECCV2022-RIFE))
  - Motion graphics ([Remotion](https://www.remotion.dev/))
  - Video editing 
- Audio
  - Speech recognition (Whisper)
  - Speech generation
    - Voice-cloning (deepfakes)
  - Music generation (Suno)
  - Sound classification
  - [Track-splitting](https://www.lalal.ai/)
  - [Adobe Enhance Speech](https://podcast.adobe.com/enhance)
- Text
  - Text generation
  - Text classification (BERT)
  - Sentiment analysis
- Friendly frameworks for developers to integrate machine learning into their projects
  - [ml5](https://ml5js.org/)
  - [Teachable Machine](https://teachablemachine.withgoogle.com/)
  - [MediaPipe](https://developers.google.com/edge/mediapipe/solutions)
  - [transformers.js](https://huggingface.co/docs/transformers.js/en/index)
  
## Finding models

- [HuggingFace](https://huggingface.co/) (the GitHub of ML models)
  - Great place to look for open-weight models
  - Look at [HF Spaces](https://huggingface.co/spaces/) for demos of models
- [Qualcomm AI Hub](https://aihub.qualcomm.com/models)

## Popular frameworks & model formats

- [PyTorch](https://pytorch.org/) (Python w/ GPU support)
- [TensorFlow](https://www.tensorflow.org/) (Python & JavaScript)
  - TFLite (TensorFlow Lite for mobile & embedded devices)
- [ONNX](https://onnx.ai/) (small & cross-platform)
  - [WebGPU](https://onnxruntime.ai/docs/tutorials/web/ep-webgpu.html) (for running ONNX & other models in the browser)
- [CoreML](https://developer.apple.com/documentation/coreml) (Apple's ML model format for native iOS/macOS apps)

### ML/AI Artists (as of 2022)

Justin needs to update this list :) 

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
* ~~[Women in Machine Learning & Data Science: Boulder](http://wimlds.org/about-the-boulder-team/)~~
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




## 📝 Homework

Read:

* Some of the articles above
* Investigate some ML tools

**Build something with a machine-learning tool or work on your final projects**


## 📋 Review code

* Present your ML/Final project progress
