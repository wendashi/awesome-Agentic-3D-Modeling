# awesome Agentic 3D Modeling 🤖🔧

> Let's build agentic framework to create 3D assets! 👀🤖🔧
>
> Curated list of high-quality open-source projects and resources for AI-powered 3D modeling, design, and content generation using agentic approaches.

![Overview of agentic 3D generation](./img/overview.png)

---

- [Research & Academic Projects](#research-academic-projects)
  - [Agentic 3D Scene Generation](#agentic-3d-scene-generation)
  - [Agentic 3D Object Generation](#agentic-3d-object-generation)
  - [Agentic 3D Material / Shader Generation](#agentic-3d-material-shader-generation)
  - [Agentic 3D Simulation](#agentic-3d-simulation)
  - [Executable World Models & Physical Reasoning](#executable-world-models-physical-reasoning)
  - [Agentic (3D) Game Generation/Development](#agentic-3d-game-generation-development)
  - [Agentic 3D Benchmarks](#agentic-3d-benchmarks)
  - [Agentic 3D Generation For 2D Creation](#agentic-3d-generation-for-2d-creation)
  - [MLLM-based 3D Generation and Understanding](#mllm-based-3d-generation-and-understanding)
- [3D Agents & Modeling Frameworks](#agents-modeling-frameworks)
  - [Vision & CAD Integration](#vision-cad-integration)
  - [CAD & Engineering Design](#cad-engineering-design)
  - [Game Development Framework](#game-development-framework)
  - [Unreal Engine Integration](#unreal-engine-integration)
- [Design & Simulation Tools](#design-simulation-tools)
  - [3D Agent Environments & Simulation Platforms](#agent-environments-simulation-platforms)
  - [Autonomous Vehicle & Robotics Simulation](#autonomous-vehicle-robotics-simulation)
- [Contributing](#contributing)
- [License](#license)

<a id="research-academic-projects"></a>
## 🔬 Research & Academic Projects

<a id="agentic-3d-scene-generation"></a>
### Agentic 3D Scene Generation

1. [DesignAgent3D: Interactive 3D Scene Editing via Designer-like Multimodal Reasoning](https://arxiv.org/abs/2608.21438) - **arXiv 2026** | Plan-Perceive-Act agent, interactive intent clarification, persistent multi-view editing

2. [StateFlow: Building, Evolving, and Accessing 3D World States for Previsualization](https://yuyangyin.github.io/StateFlow/) - **arXiv 2026** | Persistent editable 3D world state, structured scene evolution, render-feedback camera planning

3. [iARCS: Iterative Agentic RL for Controllable 3D Scene Generation](https://arxiv.org/abs/2608.06161) - **arXiv 2026** | LLM-generated reward programs, iterative feedback, task-constrained scene generation

4. [Code-as-Room: Generating 3D Rooms from Top-Down View Images via Agentic Code Synthesis](https://code-as-room.github.io/) - **arXiv 2026** | Multi-stage MLLM agents, Blender code, cross-stage memory <a href="https://github.com/YxuanAr/Code-as-Room" title="GitHub Repo"><img src="https://img.shields.io/github/stars/YxuanAr/Code-as-Room.svg?style=social" alt="Stars"></a>

5. [VIGA: Vision-as-Inverse-Graphics Agent via Interleaved Multimodal Reasoning](https://fugtemypt123.github.io/VIGA-website/) - **arXiv 2026** | Analysis-by-synthesis code agent, interleaved generator-verifier loop, Blender scene reconstruction, editing, and dynamic scene synthesis <a href="https://github.com/Fugtemypt123/VIGA" title="GitHub Repo"><img src="https://img.shields.io/github/stars/Fugtemypt123/VIGA.svg?style=social" alt="Stars"></a>

6. [SimWorlds: A Multi-Agent System for Dynamic 3D Scene Creation](https://arxiv.org/abs/2607.01766) - **arXiv 2026** | Dynamic 4D scenes, Blender agents, deterministic verification

7. [EmbodiedGen V2: An Agentic, Simulation-Ready 3D World Engine for Embodied AI](https://horizonrobotics.github.io/EmbodiedGen/) - **arXiv 2026** | Simulation-ready worlds, physics-validated editing, cross-simulator export <a href="https://github.com/HorizonRobotics/EmbodiedGen" title="GitHub Repo"><img src="https://img.shields.io/github/stars/HorizonRobotics/EmbodiedGen.svg?style=social" alt="Stars"></a>

8. [MANSION: Multi-floor lANguage-to-3D Scene generatIOn for loNg-horizon tasks](https://github.com/AgibotGeneral/MANSION) - **CVPR 2026** | LLM-driven procedural multi-floor building generation. Given a natural-language description (e.g., "2-story office building with conference rooms"), generates complete building layouts including room segmentation, walls, doors, windows, furniture placement, lighting, and top-down rendered images.

9. [MUSE: Agentic 3D Scene Authoring via Memory-Grounded Incremental Requirement Satisfaction](https://arxiv.org/abs/2606.14168) - **arXiv 2026** | Multi-agent scene construction and editing, memory, verification

10. [SceneConductor: 3D Scene Generation from Single Image with Multi-Agent Orchestration](https://arxiv.org/abs/2606.08402) - **arXiv 2026** | Multi-agent scene construction, planner-guided refinement

11. [PhysAgent: Automating Physics-Based 4D Synthesis via Trajectory-Grounded Multi-Agent Feedback](https://arxiv.org/abs/2606.08688) - **arXiv 2026** | Simulator-in-the-loop agents, force-field generation, trajectory feedback

12. [SceneSmith: Agentic Generation of Simulation-Ready Indoor Scenes](https://github.com/nepfaff/scenesmith) - **ICML 2026 Spotlight** | Scene generation, interactive environments <a href="https://github.com/nepfaff/scenesmith" title="GitHub Repo"><img src="https://img.shields.io/github/stars/nepfaff/scenesmith.svg?style=social" alt="Stars"></a>

13. [SAGE: Scalable Agentic for 3D Generation and Editing](https://github.com/NVlabs/sage) - **CVPR 2026** | Scene generation, interactive environments <a href="https://github.com/NVlabs/sage" title="GitHub Repo"><img src="https://img.shields.io/github/stars/NVlabs/sage.svg?style=social" alt="Stars"></a>

14. [Agentic World Modeling](https://github.com/matrix-agent/awesome-agentic-world-modeling) - Agentic world modeling, multimodal agents, and world-modeling resources <a href="https://github.com/matrix-agent/awesome-agentic-world-modeling" title="GitHub Repo"><img src="https://img.shields.io/github/stars/matrix-agent/awesome-agentic-world-modeling.svg?style=social" alt="Stars"></a>

15. [Scene-Weaver: Multi-Scene Choreography for Interactable Virtual Worlds](https://github.com/Scene-Weaver/SceneWeaver) - **NeurIPS 2025** | Scene generation, interactive environments <a href="https://github.com/Scene-Weaver/SceneWeaver" title="GitHub Repo"><img src="https://img.shields.io/github/stars/Scene-Weaver/SceneWeaver.svg?style=social" alt="Stars"></a>

16. [IDesign: Product Intelligent Design System Powered by Generative AI and Designers](https://github.com/atcelen/IDesign/) - **ECCV 2024** | Generative design, human-AI collaboration <a href="https://github.com/atcelen/IDesign/" title="GitHub Repo"><img src="https://img.shields.io/github/stars/atcelen/IDesign.svg?style=social" alt="Stars"></a>

17. [SceneTeller: Language-to-3D Scene Generation](https://github.com/sceneteller/SceneTeller) - **ECCV 2024** | Language-to-3D scene, spatial reasoning <a href="https://github.com/sceneteller/SceneTeller" title="GitHub Repo"><img src="https://img.shields.io/github/stars/sceneteller/SceneTeller.svg?style=social" alt="Stars"></a>

18. [Holodeck: Language-Driven Scene Construction in Virtual Environments](https://github.com/allenai/Holodeck) - **CVPR 2024** | Language-to-3D scene, spatial reasoning <a href="https://github.com/allenai/Holodeck" title="GitHub Repo"><img src="https://img.shields.io/github/stars/allenai/Holodeck.svg?style=social" alt="Stars"></a>

19. [LayoutGPT: Analytical Layout Generation by Coupling LLMs with Geometric Optimizers](https://github.com/weixi-feng/LayoutGPT) - **NeurIPS 2023** | Layout reasoning <a href="https://github.com/weixi-feng/LayoutGPT" title="GitHub Repo"><img src="https://img.shields.io/github/stars/weixi-feng/LayoutGPT.svg?style=social" alt="Stars"></a>

20. [LEGO-Anything: Coding Agents for 3D Scene Reconstruction](https://lego-anything.com) - **arXiv 2026** | Image-to-editable Blender scene reconstruction through coding agents, iterative rendering and validation, plus LEGO-Bench evaluation

21. [NeoWorld-Pro: Programming Interactive Scenes from Monocular Images for Embodied Simulation](https://neoworldproject.github.io/neoworld-pro-website/) - **arXiv 2026** | MLLM-generated executable scene programs from monocular images, physics-in-the-loop refinement, articulated objects, and simulation-ready interactive scenes

22. [3DCodeVerse: Exploring 3D Worlds as Code](https://3dcodeverse.com/) - **2026** | Code-based 3D world generation and exploration <a href="https://github.com/gaoypeng/3dcodeverse" title="GitHub Repo"><img src="https://img.shields.io/github/stars/gaoypeng/3dcodeverse.svg?style=social" alt="Stars"></a>

23. [SceneCraft: An LLM Agent for Synthesizing 3D Scenes as Blender Code](https://proceedings.mlr.press/v235/hu24g.html) - **ICML 2024** | LLM agent for generating and refining executable Blender scene programs

24. [BlenderLLM: Training Large Language Models for Computer-Aided Design with Self-improvement](https://github.com/FreedomIntelligence/BlenderLLM) - **2024** | BlendNet dataset and self-improving LLM training for Blender code generation <a href="https://github.com/FreedomIntelligence/BlenderLLM" title="GitHub Repo"><img src="https://img.shields.io/github/stars/FreedomIntelligence/BlenderLLM.svg?style=social" alt="Stars"></a>

25. [WorldAgents: Can Foundation Image Models be Agents for 3D World Models?](https://arxiv.org/abs/2603.19708) - **ECCV 2026** | Multi-agent 3D world synthesis with a VLM director, image generator, and two-stage 2D/3D verifier

26. [NaLA: A 3D Native LLM Layout Agent for High-quality 3D Scene Generation](https://adamcwan.github.io/NaLA/) - **ECCV 2026** | Native 3D scene and asset tokens, collision/support reasoning, coarse-to-fine object placement <a href="https://github.com/adamcwan/NaLA-code" title="GitHub Repo"><img src="https://img.shields.io/github/stars/adamcwan/NaLA-code.svg?style=social" alt="Stars"></a>

27. [SceneOrchestra: Efficient Agentic 3D Scene Synthesis via Full Tool-Call Trajectory Generation](https://arxiv.org/abs/2604.19907) - **ECCV 2026** | Trainable tool orchestrator, discriminator-selected execution trajectories, efficient 3D scene synthesis <a href="https://github.com/yunhe24/sceneorchestra" title="GitHub Repo"><img src="https://img.shields.io/github/stars/yunhe24/sceneorchestra.svg?style=social" alt="Stars"></a>

28. [SceneSpinner: Taming LLMs for Codematic Indoor Scene Generation](https://jfzhang95.github.io/) - **ECCV 2026** | Language-planned generation of editable indoor scenes as structured code

29. [HoloCode: A Code-Centric Multi-Agent Framework for Image-to-3D Scene Generation](https://neurips.cc/virtual/2026/poster/152551) - **NeurIPS 2026** | Code-centric multi-agent image-to-3D scene generation

<a id="agentic-3d-object-generation"></a>
### Agentic 3D Object Generation

1. [DiagGen: Agentic Generation of Deformable Assets with Sim-based Diagnostics for Robotic Simulation](https://arxiv.org/abs/2609.23103) - **arXiv 2026** | Single-image-to-simulation-ready deformable assets, part-wise geometry and material inference, simulator-based diagnostics and repair <a href="https://github.com/diaggen/diaggen" title="GitHub Repo"><img src="https://img.shields.io/github/stars/diaggen/diaggen.svg?style=social" alt="Stars"></a>

2. [Procedura: Agentic 3D Modeling with Procedural Control](https://spatiaos.github.io/projects/procedura/) - **arXiv 2026** | Editable part-structured programs, deterministic assembly checks, simulator-validated articulation <a href="https://github.com/SpatiaOS/Procedura" title="GitHub Repo"><img src="https://img.shields.io/github/stars/SpatiaOS/Procedura.svg?style=social" alt="Stars"></a>

3. [ViSculpt: Visual-Centric Agentic Geometry Editing](https://arxiv.org/abs/2608.24169) - **arXiv 2026** | Multi-agent Blender GUI control, localized mesh editing, visual feedback <a href="https://github.com/sig-pku/ViSculpt" title="GitHub Repo"><img src="https://img.shields.io/github/stars/sig-pku/ViSculpt.svg?style=social" alt="Stars"></a>

4. [USDCraft: Geometrically Grounded Programmatic Modeling of Articulated 3D Assets for Simulation](https://xingyoujun.github.io/usdcraft/#application) - **arXiv 2026** | Text/image-to-programmatic articulated assets, geometry-grounded modeling, physical parameters, and Isaac Sim-ready USD export

5. [SIMART: Decomposing Monolithic Meshes into Sim-ready Articulated Assets via MLLM](https://github.com/ByteDance-Seed/SimArt) - **SIGGRAPH 2026** | MLLM-based part decomposition and kinematic prediction, sparse 3D VQ-VAE, and URDF generation for physics-based simulation

6. [Artisan: Towards Physically Grounded Articulated 3D Assets](https://github.com/physicalvision/Artisan) - **arXiv 2026** | Multi-agent design, coding, and review pipeline for articulated asset generation with procedural modeling, physical simulation feedback, and benchmark evaluation

7. [EditHero: A Benchmark for Long-Horizon Part-Level 3D Editing and Vibe Modeling](https://arxiv.org/abs/2610.02298) - **arXiv 2026** | Long-horizon part-level 3D editing benchmark, multi-turn object state chains, part assembly and retexturing <a href="https://github.com/AlayaLab/EditHero" title="GitHub Repo"><img src="https://img.shields.io/github/stars/AlayaLab/EditHero.svg?style=social" alt="Stars"></a>

8. [CoGen3D: An Agentic Human-AI Co-Design Pipeline for 3D Asset Generation for Virtual Reality](https://arxiv.org/abs/2607.03731) - **arXiv 2026** | Conversational co-design, image-to-3D, immersive deployment

9. [PhysForge: Agentic Physics-Based 3D Object Generation and Simulation](https://github.com/HKU-MMLab/PhysForge) - **ICML 2026** | Physics-driven generation, agentic workflow <a href="https://github.com/HKU-MMLab/PhysForge" title="GitHub Repo"><img src="https://img.shields.io/github/stars/HKU-MMLab/PhysForge.svg?style=social" alt="Stars"></a>

10. [PhysX-Anything: Simulation-Ready Physical 3D Assets from Single Image](https://github.com/ziangcao0312/PhysX-Anything) - **CVPR 2026** | Image-to-3D, physical modeling, simulation-ready assets <a href="https://github.com/ziangcao0312/PhysX-Anything" title="GitHub Repo"><img src="https://img.shields.io/github/stars/ziangcao0312/PhysX-Anything.svg?style=social" alt="Stars"></a>

11. [PhysX-Omni: Unified Simulation-Ready Physical 3D Generation](https://github.com/physx-omni/PhysX-Omni) | Physical 3D generation, rigid/deformable/articulated objects <a href="https://github.com/physx-omni/PhysX-Omni" title="GitHub Repo"><img src="https://img.shields.io/github/stars/physx-omni/PhysX-Omni.svg?style=social" alt="Stars"></a>

12. [MeshLLM: Empowering Large Language Models to Progressively Understand and Generate 3D Mesh](https://github.com/Fangkang515/MeshLLM) - **ICCV 2025** | Multimodal LLM <a href="https://github.com/Fangkang515/MeshLLM" title="GitHub Repo"><img src="https://img.shields.io/github/stars/Fangkang515/MeshLLM.svg?style=social" alt="Stars"></a>

13. [Idea23D: Collaborative LMM Agents for 3D Model Generation from Interleaved Multimodal Inputs](https://github.com/yisuanwang/Idea23D) - **COLING 2025** | Collaborative agents, multimodal input <a href="https://github.com/yisuanwang/Idea23D" title="GitHub Repo"><img src="https://img.shields.io/github/stars/yisuanwang/Idea23D.svg?style=social" alt="Stars"></a>

14. [Articraft: An Agentic System for Scalable Articulated 3D Asset Generation](https://articraft3d.github.io/) - **2026** | Agentic generation of scalable, articulated 3D assets <a href="https://github.com/articraftresearch/Articraft" title="GitHub Repo"><img src="https://img.shields.io/github/stars/articraftresearch/Articraft.svg?style=social" alt="Stars"></a>

15. [LAM: Language Articulated Object Modelers](https://gaoypeng.github.io/LAM/) - **CVPR 2026** | Language-guided modeling of articulated 3D objects <a href="https://github.com/gaoypeng/LAM" title="GitHub Repo"><img src="https://img.shields.io/github/stars/gaoypeng/LAM.svg?style=social" alt="Stars"></a>

16. [LL3M: Large Language 3D Modelers](https://threedle.github.io/ll3m/) - **2025** | Large-language-model-driven 3D modeling <a href="https://github.com/threedle/ll3m" title="GitHub Repo"><img src="https://img.shields.io/github/stars/threedle/ll3m.svg?style=social" alt="Stars"></a>

17. [Articulate-Anything: Automatic Modeling of Articulated Objects via a Vision-Language Foundation Model](https://articulate-anything.github.io/) - **ICLR 2025** | Vision-language-based automatic modeling of articulated objects <a href="https://github.com/vlongle/articulate-anything" title="GitHub Repo"><img src="https://img.shields.io/github/stars/vlongle/articulate-anything.svg?style=social" alt="Stars"></a>

<a id="agentic-3d-material-shader-generation"></a>
### Agentic 3D Material / Shader Generation
1. [ShaderAgent: Self-Evolving Agentic Procedural Material Generation](https://github.com/VAST-AI-Research/ShaderAgent) - **SIGGRAPH Asia 2026** | Reference-image-to-editable Blender procedural materials, shader DSL, reason-act-critic optimization

2. [VLMaterial: Procedural Material Generation with Large Vision-Language Models](https://github.com/mit-gfx/VLMaterial) - **ICLR 2025 Spotlight** | Open-source procedural material dataset and propose to perform program-level augmentation by prompting another pre-trained LLM

3. [Shaders21k: Procedural Image Programs for Representation Learning](https://github.com/mbaradad/shaders21k) - **NeurIPS 2022** | Large-scale dataset of procedural shader programs for representation learning <a href="https://github.com/mbaradad/shaders21k" title="GitHub Repo"><img src="https://img.shields.io/github/stars/mbaradad/shaders21k.svg?style=social" alt="Stars"></a>

<a id="agentic-3d-simulation"></a>
### Agentic 3D Simulation
1. [Eureka: Human-Level Reward Design via Coding Large Language Models](https://eureka-research.github.io/) - **arXiv 2023** | LLM-generated reward code, reinforcement learning, robot simulation and policy optimization <a href="https://github.com/eureka-research/Eureka" title="GitHub Repo"><img src="https://img.shields.io/github/stars/eureka-research/Eureka.svg?style=social" alt="Stars"></a>

<a id="executable-world-models-physical-reasoning"></a>
### Executable World Models & Physical Reasoning

1. [Code World Model: Coding Agent as World Brain](https://github.com/buaacyw/code-world-model) - **arXiv 2026** | Coding agent, executable persistent world state, spatiotemporal proxy compilation, video-based world realization <a href="https://github.com/buaacyw/code-world-model" title="GitHub Repo"><img src="https://img.shields.io/github/stars/buaacyw/code-world-model.svg?style=social" alt="Stars"></a>

2. [Code-as-World: Agentic Discovery of Executable World Representations for Physical Reasoning](https://github.com/mirros-lab/code-as-world) - **Technical Report 2026** | Agentic simulation and verification, executable physical representations, counterfactual rollouts <a href="https://github.com/mirros-lab/code-as-world" title="GitHub Repo"><img src="https://img.shields.io/github/stars/mirros-lab/code-as-world.svg?style=social" alt="Stars"></a>

<a id="agentic-3d-game-generation-development"></a>
### Agentic (3D) Game Generation/Development

1. [GameDevBench: Evaluating Agentic Capabilities Through Game Development](https://github.com/waynchi/gamedevbench) - **ICML2026** | Multimodal LLM, Game Development, Game Engine <a href="https://github.com/waynchi/gamedevbench" title="GitHub Repo"><img src="https://img.shields.io/github/stars/waynchi/gamedevbench.svg?style=social" alt="Stars"></a>

2. [OpenGame: Open Agentic Coding for Games](https://github.com/leigest519/OpenGame) | Multimodal LLM, Game Development <a href="https://github.com/leigest519/OpenGame" title="GitHub Repo"><img src="https://img.shields.io/github/stars/leigest519/OpenGame.svg?style=social" alt="Stars"></a>

<a id="agentic-3d-benchmarks"></a>
### Agentic 3D Benchmarks

1. [3DCodeBench: Benchmarking Agentic Procedural 3D Modeling Via Code](https://www.3dcodebench.com/) - **arXiv 2026** | VLM coding agents, Blender execution feedback, procedural 3D evaluation <a href="https://github.com/gaoypeng/3dcodebench" title="GitHub Repo"><img src="https://img.shields.io/github/stars/gaoypeng/3dcodebench.svg?style=social" alt="Stars"></a>

2. [WorldCoder-Bench: Benchmarking Physically Grounded 3D World Synthesis](https://github.com/shuolucs/WorldCoder-Bench) - **2026** | Benchmark for physically grounded 3D world synthesis <a href="https://github.com/shuolucs/WorldCoder-Bench" title="GitHub Repo"><img src="https://img.shields.io/github/stars/shuolucs/WorldCoder-Bench.svg?style=social" alt="Stars"></a>

3. [SceneActBench: Can Agents Act on the 3D Scenes They See?](https://feinaldo2.github.io/sceneactbench-project-page/) - **2026** | Benchmark for evaluating whether agents can perceive and act in 3D scenes <a href="https://github.com/Feinaldo2/SceneActBench" title="GitHub Repo"><img src="https://img.shields.io/github/stars/Feinaldo2/SceneActBench.svg?style=social" alt="Stars"></a>

4. [3DHarnessBench: Probing Agentic 3D-to-Code Capabilities of Frontier Vision-Language Models](https://llada60.github.io/3DHarnessBench/) - **2026** | Benchmark for agentic 3D-to-code capabilities of frontier VLMs <a href="https://github.com/llada60/3DHarnessBench" title="GitHub Repo"><img src="https://img.shields.io/github/stars/llada60/3DHarnessBench.svg?style=social" alt="Stars"></a>

5. [BenchCAD: A Comprehensive, Industry-Standard Benchmark for Programmatic CAD](https://github.com/BenchCAD/BenchCAD-main) - **2026** | Execution-grounded programmatic CAD benchmark, 17,900 CadQuery programs, vision-to-code, code editing, and QA tasks <a href="https://github.com/BenchCAD/BenchCAD-main" title="GitHub Repo"><img src="https://img.shields.io/github/stars/BenchCAD/BenchCAD-main.svg?style=social" alt="Stars"></a>

6. [BenchCAD 2.0](https://github.com/BenchCAD-org/benchcad-2) - **2026** | Community-grounded parametric CAD benchmark data pipeline, auditable part families, multi-turn refinement, and successor repository to BenchCAD <a href="https://github.com/BenchCAD-org/benchcad-2" title="GitHub Repo"><img src="https://img.shields.io/github/stars/BenchCAD-org/benchcad-2.svg?style=social" alt="Stars"></a>

7. [BlenderWorld](https://github.com/QwenLM/BlenderWorld) - Benchmark for visual agents creating editable Blender scenes from real-world references, with rubric-based structural and visual evaluation <a href="https://github.com/QwenLM/BlenderWorld" title="GitHub Repo"><img src="https://img.shields.io/github/stars/QwenLM/BlenderWorld.svg?style=social" alt="Stars"></a>

8. [BlenderGym: Benchmarking Foundational Model Systems for Graphics Editing](https://blendergym.github.io/) - **CVPR 2025** | Benchmark for foundational-model systems performing graphics editing in Blender <a href="https://github.com/richard-guyunqi/BlenderGym-Open" title="GitHub Repo"><img src="https://img.shields.io/github/stars/richard-guyunqi/BlenderGym-Open.svg?style=social" alt="Stars"></a>

9. [BlenderFORGE: Framework for Optimizing Reactive 3D-Graphics Editing Ability of MLLMs](https://neurips.cc/virtual/2026/poster/151100) - **NeurIPS 2026** | Framework for training and evaluating reactive MLLM-based 3D graphics editing

<a id="agentic-3d-generation-for-2d-creation"></a>
### Agentic 3D Generation For 2D Creation

1. [BlenderFusion: 3D-Grounded Visual Editing and Generative Compositing](https://blenderfusion.github.io/) - **arXiv 2025** | 3D-grounded visual compositing, Blender-based editing, object/camera/background control, and 2D image creation via layering-editing-compositing

<a id="mllm-based-3d-generation-and-understanding"></a>
### MLLM-based 3D Generation and Understanding

1. [CG-MLLM: Captioning and Generating 3D Content via Multi-modal Large Language Models](https://arxiv.org/abs/2601.21798) - **ICML 2026** | Unified MLLM for 3D captioning, image-to-3D generation, and 3D understanding with fine-grained geometry <a href="https://github.com/dreaming-huang/CG-MLLM" title="GitHub Repo"><img src="https://img.shields.io/github/stars/dreaming-huang/CG-MLLM.svg?style=social" alt="Stars"></a>

2. [ShapeLLM-Omni: A Native Multimodal LLM for 3D Generation and Understanding](https://arxiv.org/abs/2506.01853) - **NeurIPS 2025 Spotlight** | Native multimodal LLM for 3D generation, understanding, and interactive editing <a href="https://github.com/JAMESYJL/ShapeLLM-Omni" title="GitHub Repo"><img src="https://img.shields.io/github/stars/JAMESYJL/ShapeLLM-Omni.svg?style=social" alt="Stars"></a>

3. [SAR3D: Autoregressive 3D Object Generation and Understanding via Multi-scale 3D VQVAE](https://arxiv.org/abs/2411.16856) - **CVPR 2025** | Autoregressive 3D generation and understanding, text/image-conditioned object synthesis, multi-scale 3D VQVAE <a href="https://github.com/cyw-3d/SAR3D" title="GitHub Repo"><img src="https://img.shields.io/github/stars/cyw-3d/SAR3D.svg?style=social" alt="Stars"></a>


<a id="agents-modeling-frameworks"></a>
## 🎯 3D Agents & Modeling Frameworks

<a id="vision-cad-integration"></a>
### Vision & CAD Integration

1. [NVIDIA-Omniverse/content-agents](https://github.com/NVIDIA-Omniverse/content-agents) - AI-powered agents for automating 3D content workflows using VLMs. Analyzes 3D assets and automates workfl <a href="https://github.com/NVIDIA-Omniverse/content-agents" title="GitHub Repo"><img src="https://img.shields.io/github/stars/NVIDIA-Omniverse/content-agents.svg?style=social" alt="Stars"></a>

2. [jingcheng-chen/rhinomcp](https://github.com/jingcheng-chen/rhinomcp) - RhinoMCP - Connects Rhino 3D to AI Agent through Model Context Protocol (MCP). Enables agents to control CAD workflows. <a href="https://github.com/jingcheng-chen/rhinomcp" title="GitHub Repo"><img src="https://img.shields.io/github/stars/jingcheng-chen/rhinomcp.svg?style=social" alt="Stars"></a>

3. [Elianio/Bynce](https://github.com/Elianio/Bynce) - 3D design agent framework for generative design tasks. <a href="https://github.com/Elianio/Bynce" title="GitHub Repo"><img src="https://img.shields.io/github/stars/Elianio/Bynce.svg?style=social" alt="Stars"></a>

4. [huggingface/meshgen](https://github.com/huggingface/meshgen) - MeshGen - Use AI Agents to control Blender with natural language. Supports multiple LLM backends with optional LLaMA-Mesh and Hyper3D integration. <a href="https://github.com/huggingface/meshgen" title="GitHub Repo"><img src="https://img.shields.io/github/stars/huggingface/meshgen.svg?style=social" alt="Stars"></a>

5. [meshy-dev/meshy-3d-agent](https://github.com/meshy-dev/meshy-3d-agent) - Agent skills for Meshy workflows including text/image-to-3D, retexturing, remeshing, rigging, animation, and printability preparation. <a href="https://github.com/meshy-dev/meshy-3d-agent" title="GitHub Repo"><img src="https://img.shields.io/github/stars/meshy-dev/meshy-3d-agent.svg?style=social" alt="Stars"></a>

<a id="cad-engineering-design"></a>
### CAD & Engineering Design

1. [AgentsCAD: Automated Design for Manufacturing of FDM Parts via Multi-Agent LLM Reasoning and Geometric Feature Recognition](https://arxiv.org/abs/2607.02448) - **arXiv 2026** | Multi-agent DFAM, B-Rep feature reasoning, VLM geometry verification

2. [Embodied CAD: Solver-Grounded LLM Agents for Parametric B-Rep Assembly Modeling](https://arxiv.org/abs/2606.31252) - **arXiv 2026** | Parametric assemblies, exact-kernel feedback, solver-grounded planning and repair

3. [CAD-Assistant: Tool-Augmented VLLMs as Generic CAD Task Solvers](https://cadassistant.github.io/) - **ICCV 2025** | Tool-augmented vision-language models for generic CAD tasks <a href="https://github.com/dimitrismallis/CAD-Assistant" title="GitHub Repo"><img src="https://img.shields.io/github/stars/dimitrismallis/CAD-Assistant.svg?style=social" alt="Stars"></a>

4. [CAD-Recode: Reverse Engineering CAD Code from Point Clouds](https://github.com/filaPro/cad-recode) - **ICCV 2025** | Reverse engineering executable CAD code from point clouds <a href="https://github.com/filaPro/cad-recode" title="GitHub Repo"><img src="https://img.shields.io/github/stars/filaPro/cad-recode.svg?style=social" alt="Stars"></a>

5. [MeshCoder: LLM-Powered Structured Mesh Code Generation from Point Clouds](https://daibingquan.github.io/MeshCoder/) - **NeurIPS 2025** (listed as 2026 in the cited reference) | Structured mesh-code generation from point clouds <a href="https://github.com/InternRobotics/MeshCoder" title="GitHub Repo"><img src="https://img.shields.io/github/stars/InternRobotics/MeshCoder.svg?style=social" alt="Stars"></a>

6. [Generating CAD Code with Vision-Language Models for 3D Designs](https://github.com/Kamel773/CAD_Code_Generation) - **ICLR 2025** | CADCodeVerify framework for generating and verifying CAD code with vision-language models <a href="https://github.com/Kamel773/CAD_Code_Generation" title="GitHub Repo"><img src="https://img.shields.io/github/stars/Kamel773/CAD_Code_Generation.svg?style=social" alt="Stars"></a>

7. [Shpigford/nurb](https://github.com/Shpigford/nurb) - Agentic CAD for 3D printing using parametric B-rep solids, exact-geometry printability checks, slicer estimates, stress analysis, and print-ready 3MF export. <a href="https://github.com/Shpigford/nurb" title="GitHub Repo"><img src="https://img.shields.io/github/stars/Shpigford/nurb.svg?style=social" alt="Stars"></a>

8. [datadrivenconstruction/cad2data-Revit-IFC-DWG-DGN](https://github.com/datadrivenconstruction/cad2data-Revit-IFC-DWG-DGN) - AI Agent-enabled workflow for automated conversion of CAD files <a href="https://github.com/datadrivenconstruction/cad2data-Revit-IFC-DWG-DGN" title="GitHub Repo"><img src="https://img.shields.io/github/stars/datadrivenconstruction/cad2data-Revit-IFC-DWG-DGN.svg?style=social" alt="Stars"></a>

9. [datadrivenconstruction/OpenConstructionEstimate-DDC-CWICR](https://github.com/datadrivenconstruction/OpenConstructionEstimate-DDC-CWICR) - Open multilingual construction cost database <a href="https://github.com/datadrivenconstruction/OpenConstructionEstimate-DDC-CWICR" title="GitHub Repo"><img src="https://img.shields.io/github/stars/datadrivenconstruction/OpenConstructionEstimate-DDC-CWICR.svg?style=social" alt="Stars"></a>

10. [atopile/atopile](https://github.com/atopile/atopile) - Design circuit boards with code! Get software-like design reuse, validation, version control and collaboration in hardware. <a href="https://github.com/atopile/atopile" title="GitHub Repo"><img src="https://img.shields.io/github/stars/atopile/atopile.svg?style=social" alt="Stars"></a>

11. [assalas/pcb-designer-ai-agent](https://github.com/assalas/pcb-designer-ai-agent) - Intelligent AI-powered PCB design automation tool using ML for component placement and routing optimization. <a href="https://github.com/assalas/pcb-designer-ai-agent" title="GitHub Repo"><img src="https://img.shields.io/github/stars/assalas/pcb-designer-ai-agent.svg?style=social" alt="Stars"></a>

12. [jangtrinh/design-os-3d-blender](https://github.com/jangtrinh/design-os-3d-blender) - Free, source-available (PolyForm Shield) MCP server and agent skill for headless Blender (`bpy`) that generates parametric mechanical parts such as gears, enclosures, drone frames and exploded assemblies from plain-English specs or JSON, with glTF/STL export and a Three.js viewer. <a href="https://github.com/jangtrinh/design-os-3d-blender" title="GitHub Repo"><img src="https://img.shields.io/github/stars/jangtrinh/design-os-3d-blender.svg?style=social" alt="Stars"></a>


<a id="game-development-framework"></a>
### Game Development Framework

10. [Yuan-ManX/ai-game-devtools](https://github.com/Yuan-ManX/ai-game-devtools) - Your AI Game Dev Hub - Ultimate resource hub for AI-powered game development tools and frameworks. <a href="https://github.com/Yuan-ManX/ai-game-devtools" title="GitHub Repo"><img src="https://img.shields.io/github/stars/Yuan-ManX/ai-game-devtools.svg?style=social" alt="Stars"></a>

<a id="unreal-engine-integration"></a>
### Unreal Engine Integration

11. [prajwalshettydev/UnrealGenAISupport](https://github.com/prajwalshettydev/UnrealGenAISupport) - Unreal Engine plugin for LLM/GenAI models & MCP UE5 server. Supports OpenAI, Deepseek, Claude <a href="https://github.com/prajwalshettydev/UnrealGenAISupport" title="GitHub Repo"><img src="https://img.shields.io/github/stars/prajwalshettydev/UnrealGenAISupport.svg?style=social" alt="Stars"></a>

---

<a id="design-simulation-tools"></a>
## 🛠️ Design & Simulation Tools

<a id="agent-environments-simulation-platforms"></a>
### 3D Agent Environments & Simulation Platforms

1. [google-deepmind/lab](https://github.com/google-deepmind/lab) - DeepMind Lab, a customizable Quake III-based 3D environment with navigation and puzzle tasks for training and evaluating learning agents. <a href="https://github.com/google-deepmind/lab" title="GitHub Repo"><img src="https://img.shields.io/github/stars/google-deepmind/lab.svg?style=social" alt="Stars"></a>

<a id="autonomous-vehicle-robotics-simulation"></a>
### Autonomous Vehicle & Robotics Simulation

12. [truevisionai/designer](https://github.com/truevisionai/designer) - Truevision Designer - 3D tool to design roads, intersections and environments for testing autonomous vehicles. <a href="https://github.com/truevisionai/designer" title="GitHub Repo"><img src="https://img.shields.io/github/stars/truevisionai/designer.svg?style=social" alt="Stars"></a>

13. [rovr-network/ROVR-Open-Dataset](https://github.com/rovr-network/ROVR-Open-Dataset) - Large-scale open 3D dataset designed for autonomous driving, robotics, and 4D perception tasks. <a href="https://github.com/rovr-network/ROVR-Open-Dataset" title="GitHub Repo"><img src="https://img.shields.io/github/stars/rovr-network/ROVR-Open-Dataset.svg?style=social" alt="Stars"></a>

14. [Moonlake's 3D Agent: Computer Use Capabilities For World Modeling](https://moonlakeai.com/blog/3d-agent) 

<a id="contributing"></a>
## 💡 Contributing

Have found a new awesome agentic 3D modeling project? Feel free to submit a PR!

**Guidelines for contributions:**
- Include project name, GitHub link, and dynamic star badge
- Add brief description (1-2 sentences)
- Include conference/venue for research papers
- Categorize appropriately
- Include key technologies used

**Format for new entries:**
```markdown
N. [Project Name](link) - Brief description
   <a href="link" title="GitHub Repo">
     <img src="https://img.shields.io/github/stars/owner/repo.svg?style=social" alt="Stars">
   </a>
```

---

<a id="license"></a>
## 📝 License

This list is licensed under [CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/).
