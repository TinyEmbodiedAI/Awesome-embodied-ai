# Awesome Embodied AI  

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)  
[![GitHub stars](https://img.shields.io/github/stars/TinyEmbodiedAI/awesome-embodied-ai.svg)](https://github.com/TinyEmbodiedAI/awesome-embodied-ai/stargazers)  
[![GitHub forks](https://img.shields.io/github/forks/TinyEmbodiedAI/awesome-embodied-ai.svg)](https://github.com/TinyEmbodiedAI/awesome-embodied-ai/network)  
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)  
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)  

A curated list of awesome Embodied AI resources, frameworks, libraries, papers, and projects. Embodied AI focuses on developing intelligent systems that learn through physical or virtual interaction with their environment.  

## Contents  

- [Introduction](#introduction)  
- [Getting Started](#getting-started)  
- [Papers](#papers)  
- [Software & Tools](#software--tools)  
- [Datasets](#datasets)  
- [Courses & Tutorials](#courses--tutorials)  
- [Projects](#projects)  
- [Conferences & Workshops](#conferences--workshops)  
- [Research Groups](#research-groups)  
- [Companies & Organizations](#companies--organizations)  
- [Contributing](#contributing)  

## Introduction  

Embodied AI represents a paradigm shift in artificial intelligence research, emphasizing the importance of physical or virtual embodiment in developing intelligent systems. This list aims to provide a comprehensive collection of resources for researchers, developers, and enthusiasts in the field.  

### What is Embodied AI?  
- The integration of perception, action, and learning in physical or simulated environments  
- Focus on interactive and experiential learning  
- Emphasis on real-world or realistic virtual environment interaction  

## Getting Started  

### Essential Concepts  
- Sensorimotor Learning  
- Active Perception  
- Environmental Interaction  
- Embodied Learning  
- Cognitive Development  

### Key Resources for Beginners  
- [Introduction to Embodied AI](link) - A comprehensive overview  
- [Embodied AI Tutorial](link) - Step-by-step guide  
- [Basic Concepts and Principles](link) - Fundamental theories

## Papers  

### Survey Papers  
- [Title](link) - Description (Year)
- [Pfeifer, Rolf, and Fumiya Iida. "Embodied artificial intelligence: Trends and challenges." Lecture notes in computer science (2004): 1-26.](https://people.csail.mit.edu/iida/papers/PfeiferIidaEAIDags.pdf) - 在上世纪80年代，人工智能研究出现了一个重大的范式转变，即转向具身化。尽管具身化人工智能仍然多样化、不断变化，且远未达到“理论稳定”的状态，但关于重要问题和方法的共识已经达成或正在迅速形成。这篇论文简要地描述了这个领域，总结了它的成就，并确定了未来研究的重要问题。一个长期未解决的基本问题是，思考是如何从具身系统中产生的。换句话说，一个核心问题可以被概括为：“行走是如何与思考联系在一起的？” (2004)  
- [Duan, Jiafei, et al. "A survey of embodied ai: From simulators to research tasks." IEEE Transactions on Emerging Topics in Computational Intelligence 6.2 (2022): 230-244.](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9687596) - 在“具身AI”时代，AI智能体通过与环境的交互，类似于人类的自我感知，来进行学习。因此，对能够支持各种具身AI研究任务的具身AI模拟器的需求显著增长。然而，目前还没有一份关于该领域的全面综述。本文旨在对具身AI领域进行全面的调研，从模拟器到研究内容。通过对九种现有的具身AI模拟器进行评估，本文旨在了解这些模拟器在具身AI研究中的适用性和局限性。最后，本文对具身AI中的三大研究任务——视觉探索、视觉导航和具身问答进行了调研，涵盖了最先进的方法、评价指标和数据集。通过对该领域进行调研所获得的新见解，本文将为模拟器选择和未来研究方向提供建议。 (2022) 
- [Liu, Yang, et al. "Aligning cyber space with physical world: A comprehensive survey on embodied ai." arXiv preprint arXiv:2407.06886 (2024).](https://arxiv.org/pdf/2407.06886) - 目前还没有关于具身AI在MLMs时代全面而深入的综述。本综述对具身AI的最新进展进行了全面探索。我们首先对具身机器人和模拟器的代表性工作进行了深入分析，以全面了解研究的重点及其局限性。然后，我们分析了四个主要研究目标：1）具身感知，2）具身交互，3）具身智能体和4）仿真到真实世界的适应，涵盖了最先进的方法、基本范式和全面的数据集。此外，我们还探讨了MLMs在虚拟和真实具身智能体中的复杂性，强调了它们在促进动态数字和物理环境中交互的重要性。最后，我们总结了具身AI的挑战和局限性，并讨论了其潜在的未来发展方向。 (2024)
- [Moulin-Frier, Clément, et al. "Embodied artificial intelligence through distributed adaptive control: An integrated framework." 2017 Joint IEEE International Conference on Development and Learning and Epigenetic Robotics (ICDL-EpiRob). IEEE, 2017.](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8329825) - 人工智能研究的未来在于两个关键词：整合与具身。通过分析最近的进展来支持这一观点。在整合方面，最近最有影响力的贡献是通过将深度学习等现代机器学习方法与蒙特卡洛树搜索、目标发散探索或可寻址内存系统等传统方法相结合而实现的。在具身方面，传统的基准任务（如视觉分类或棋盘游戏）正在过时，因为最先进的学习算法在其中大多数任务上已经接近或超越了人类的表现，这促进了第一人称3D游戏平台的发展，这些平台具有真实的物理环境。基于这一分析，我们首先提出了一种具身认知架构，将人工智能的异构子领域整合到一个统一的框架中。我们通过展示如何在这个框架中表达该领域的主要贡献来证明我们方法的实用性。然后，我们主张基准环境需要重现生态有效的条件，以通过具身智能体之间的认知军备竞赛的概念来引导越来越复杂认知技能的获取。 (2017)
- [Durante, Zane, et al. "Agent ai: Surveying the horizons of multimodal interaction." arXiv preprint arXiv:2401.03568 (2024).](https://arxiv.org/pdf/2401.03568)- 多模态AI系统很可能会成为我们日常生活中无处不在的一部分。将这些系统具象化为在物理和虚拟环境中活动的智能体，是提高它们交互性的一个有前途的方法。目前，系统利用现有的基础模型作为构建具身智能体的基本模块。将智能体嵌入到这样的环境中，有助于模型处理和解释视觉及上下文数据，这对创建更复杂、更具上下文感知的AI系统至关重要。 (2024)  
- [Xi, Zhiheng, et al. "The rise and potential of large language model based agents: A survey." arXiv preprint arXiv:2309.07864 (2023).](https://arxiv.org/pdf/2309.07864) - 由于大型语言模型（LLMs）展现出多功能的能力，因此被视为实现通用人工智能（AGI）的潜在火花，为构建通用AI智能体带来了希望。许多研究人员利用LLMs作为基础来构建AI智能体，并取得了显著进展。本文对基于LLMs的智能体进行了全面综述。首先追溯了智能体概念从哲学起源到在AI中的发展历程，并解释了为什么LLMs是构建智能体的合适基础。在此基础上，我们提出了一种基于LLMs的智能体的通用框架，该框架包含三个主要组件：大脑、感知和行动，并且可以针对不同的应用进行定制。随后，我们从单智能体场景、多智能体场景和人机合作三个方面探讨了基于LLMs的智能体的广泛应用。在此基础上，我们深入研究了智能体社会，探索了基于LLMs的智能体的行为和个性、从智能体社会中涌现出的社会现象以及它们为人类社会提供的见解。 (2023)
- [Dong, Xiaofei, et al. "A Survey of LLM-based Agents: Theories, Technologies, Applications and Suggestions." 2024 3rd International Conference on Artificial Intelligence, Internet of Things and Cloud Computing Technology (AIoTC). IEEE, 2024.](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10748304) - 本文回顾了人工智能领域的理论基础，包括大型语言模型、思维链、对齐、检索增强生成和具身AI等。在此基础上，我们介绍了基于LLMs的代理的关键技术，包括感知、规划、记忆和行动四个核心组件。 (2024)

### Foundational Papers  
- [Paolo, Giuseppe, Jonas Gonzalez-Billandon, and Balázs Kégl. "A call for embodied AI." arXiv preprint arXiv:2402.03824 (2024).](https://arxiv.org/pdf/2402.03824) - 具身人工智能（Embodied AI，简称E-AI）作为实现通用人工智能（AGI）的下一个关键步骤，将其与当前的人工智能发展，特别是大型语言模型（LLMs），进行了对比。我们追溯了具身概念在哲学、心理学、神经科学和机器人学等多个领域的演变，强调了E-AI如何区别于传统的静态学习范式。通过扩展E-AI的范围，引入了一个基于认知架构的理论框架，强调感知、行动、记忆和学习是具身智能体的重要组成部分。这个框架与弗里森的主动推理原则一致，为E-AI的发展提供了一个全面的方法。尽管人工智能领域取得了进展，但仍存在重大挑战，例如制定新的AI学习理论和开发先进硬件。我们的讨论为未来的E-AI研究奠定了基础。我们强调了创建能够与人类和其他智能实体在真实世界环境中无缝沟通、协作和共存的E-AI智能体的重要性。 (2024)
- [Majumdar, Arjun, et al. "Openeqa: Embodied question answering in the era of foundation models." Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition. 2024.](https://openaccess.thecvf.com/content/CVPR2024/papers/Majumdar_OpenEQA_Embodied_Question_Answering_in_the_Era_of_Foundation_Models_CVPR_2024_paper.pdf) - 本文提出了一种现代的具身问答（Embodied Question Answering，EQA）的定义：即理解环境以能够用自然语言回答关于环境的问题。智能体可以通过两种方式实现：一是利用情景记忆，例如智能眼镜上的智能体；二是通过主动探索环境，例如移动机器人。 (2024)
- [Tao, Stone, et al. "Maniskill3: Gpu parallelized robotics simulation and rendering for generalizable embodied ai." arXiv preprint arXiv:2410.00425 (2024).](https://arxiv.org/pdf/2410.00425) - 模拟技术使得机器人学习的计算可扩展性达到了前所未有的高度。然而，许多现有的模拟框架通常只支持有限的场景和任务，缺乏扩展通用机器人技术和模拟到真实世界转换的关键特性。本文引入并开源了ManiSkill3，这是一种最快、支持接触丰富物理特性、且面向通用可泛化操作的机器人模拟器。ManiSkill3支持GPU并行化，包括模拟、渲染、异构模拟、点云/体素视觉输入等多个方面。与其他平台相比，ManiSkill3的模拟和渲染速度快了10-1000倍，GPU内存使用量减少了2-3倍，在基准环境中可达到高达30,000帧/秒的帧率。这得益于系统中极低的Python/PyTorch开销、基于GPU的模拟、SAPIEN并行渲染系统的使用等因素。以前需要数小时训练的任务现在只需几分钟。我们还提供了最全面的GPU并行环境和任务，涵盖了12个不同的领域，包括但不限于移动操作（如绘画）、人形机器人以及由艺术家设计或来自真实世界数字孪生的逼真场景中的灵巧操作。此外，我们提供了数百万个来自运动规划、强化学习和遥操作的演示帧。ManiSkill3还提供了一套全面的基准，涵盖了流行的强化学习和从示范中学习算法。 (2024)

### Recent Advances  
- [Duan, Jiafei, et al. "A survey of embodied ai: From simulators to research tasks." IEEE Transactions on Emerging Topics in Computational Intelligence 6.2 (2022): 230-244.](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9687596) - 人工智能领域正在经历一场从“互联网AI”向“具身AI”的范式转变。在“互联网AI”时代，AI算法和智能体从互联网上收集的图像、视频或文本数据集进行学习。而在“具身AI”时代，AI智能体通过与环境的交互，类似于人类的自我感知，来进行学习。因此，对能够支持各种具身AI研究任务的具身AI模拟器的需求显著增长。这种对具身AI的日益浓厚的兴趣有助于推动人工智能通用智能（AGI）的发展。然而，目前还没有一份关于该领域的全面综述。本文旨在对具身AI领域进行全面的调研，从模拟器到研究内容。通过对九种现有的具身AI模拟器进行评估，本文旨在了解这些模拟器在具身AI研究中的适用性和局限性。最后，本文对具身AI中的三大研究任务——视觉探索、视觉导航和具身问答进行了调研，涵盖了最先进的方法、评价指标和数据集。通过对该领域进行调研所获得的新见解，本文将为模拟器选择和未来研究方向提供建议。 (2022)  
- [Xu, Zhiyuan, et al. "A survey on robotics with foundation models: toward embodied ai." arXiv preprint arXiv:2402.02385 (2024).](https://arxiv.org/pdf/2402.02385) - 尽管对具身人工智能（Embodied AI）的研究已经持续了数十年，但赋予智能体人类水平的智能仍然是一个持久的挑战。这种智能包括感知、学习、推理、决策制定、控制和泛化能力，使得它们能够在开放、非结构化和动态的环境中执行通用任务。最近，计算机视觉、自然语言处理和多模态学习领域的进展表明，基础模型在特定任务上已经具备了超越人类的能力。它们不仅为将基础模块集成到具身AI系统中提供了坚实的基础，而且为如何从方法论的角度扩展机器人学习提供了新的思路。本综述旨在对机器人领域的基础模型进行全面而最新的概述，重点关注自主操作，涵盖高层规划和低层控制。此外，我们展示了它们常用的数据集、模拟器和基准。重要的是，我们强调了该领域固有的关键挑战，并勾勒出了未来研究的潜在途径，为推动学术和工业界的前沿发展做出贡献。 (2024)
- [Title](link) - Description (Year)  
- [Title](link) - Description (Year)
  
## Software & Tools  

### Simulation Platforms  
- [Savva, Manolis, et al. "Habitat: A platform for embodied ai research." Proceedings of the IEEE/CVF international conference on computer vision. 2019.](https://openaccess.thecvf.com/content_ICCV_2019/papers/Savva_Habitat_A_Platform_for_Embodied_AI_Research_ICCV_2019_paper.pdf) - Description  
- [Deitke, Matt, et al. "Robothor: An open simulation-to-real embodied ai platform." Proceedings of the IEEE/CVF conference on computer vision and pattern recognition. 2020.](https://openaccess.thecvf.com/content_CVPR_2020/papers/Deitke_RoboTHOR_An_Open_Simulation-to-Real_Embodied_AI_Platform_CVPR_2020_paper.pdf) - Description
- [Fu, Haoyuan, et al. "RFUniverse: A Multiphysics Simulation Platform for Embodied AI." arXiv preprint arXiv:2202.00199 (2022).](https://arxiv.org/pdf/2202.00199) - Description 

### Development Frameworks  
- [Weihs, Luca, et al. "Allenact: A framework for embodied ai research." arXiv preprint arXiv:2008.12760 (2020).](https://arxiv.org/pdf/2008.12760) - Description  
- [Liu, Guocai, et al. "EAI-SIM: An Open-Source Embodied AI Simulation Framework with Large Language Models." 2024 IEEE 18th International Conference on Control & Automation (ICCA). IEEE, 2024.](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10591865) - Description  

### Libraries  
- [Library Name](link) - Description  
- [Library Name](link) - Description  

- [Isaac Sim](https://developer.nvidia.com/isaac/sim) - NVIDIA Isaac Sim是一款参考应用程序，它使开发人员能够在基于物理的虚拟环境中设计、模拟、测试和训练基于人工智能的机器人和自主机器。Isaac Sim 建立在 NVIDIA Omniverse 的基础上，具有完全的可扩展性，使开发人员能够构建基于通用场景描述（OpenUSD）的自定义模拟器，或者将 Isaac Sim 的核心技术集成到他们现有的测试和验证流程中。
- [AirSim](https://github.com/microsoft/AirSim) - 2017年，微软研究院创建了AirSim，作为一个用于人工智能研究和实验的模拟平台。AirSim 是一款基于 Unreal Engine的无人机、汽车等多种设备的模拟器。它是开源的、跨平台的，并支持与流行的飞行控制器（如 PX4 和 ArduPilot）进行软件在环（Software-in-the-Loop, SIL）模拟，以及与 PX4 进行硬件在环（Hardware-in-the-Loop, HIL）模拟，以实现物理和视觉上逼真的模拟。AirSim 被开发为一个 Unreal 插件，可以简单地插入到任何 Unreal 环境中。同样也为 Unity 插件提供了一个实验性版本。AirSim 作为一个 AI 研究平台，主要用于实验深度学习、计算机视觉和强化学习算法在自动驾驶车辆中的应用。为此，AirSim 还提供了 API，以便以平台无关的方式检索数据和控制车辆。
- [V-REP](https://www.coppeliarobotics.com/) -V-REP（Virtual Robot Experimentation Platform，现已更名为CoppeliaSim）是一款功能强大的机器人仿真软件，为开发者提供了一个集成的3D开发环境，用于快速原型验证、远程监控、快速算法开发、机器人相关教育和工厂自动化系统仿真。这款软件因其全面的功能和用户友好的界面，在机器人研究和教育领域广受好评。
- [Unity](https://github.com/Unity-Technologies/ml-agents) -Unity机器学习agent工具包（ML-Agents）是一个开源项目，它使游戏和模拟能够作为训练智能agent的环境。我们提供了基于PyTorch的***算法的实现，使游戏开发者和爱好者能够轻松地为2D、3D以及VR/AR游戏训练智能agent。研究人员还可以使用提供的易于使用的Python API，通过强化学习、模仿学习、神经进化或任何其他方法来训练agent。这些训练好的agent可用于多种目的，包括控制NPC行为（在各种设置中，如多agent和对抗性）、游戏构建的自动化测试以及在发布前评估不同的游戏设计决策。ML-Agents工具包对游戏开发者和AI研究人员来说是互惠互利的，因为它提供了一个中心平台，可以在Unity的丰富环境中评估AI的进步，然后将这些进步提供给更广泛的研究和游戏开发者社区。
- [Pybullet](https://github.com/bulletphysics/bullet3) -PyBullet 是一个用于机器人学、游戏开发和图形研究的开源物理仿真库。它是基于 Bullet Physics SDK，这是一个成熟的、广泛使用的开源物理引擎。PyBullet 提供了 Python 接口，使得开发者能够利用 Bullet 强大的物理仿真能力，同时享受 Python 的易用性。主要优势：多体动力学仿真: PyBullet 能够精确模拟多体系统的动态行为，包括刚体和软体动力学。机器人学支持: 它支持加载 URDF（统一机器人描述格式）文件，这是一种在机器人学中广泛使用的标准格式。逆向动力学和运动规划: PyBullet 提供了逆向动力学求解器和运动规划算法，这对于机器人的路径规划至关重要。渲染和可视化: 它包括一个简单的直接渲染器，也可以通过 VR 接口进行更高级的渲染。强化学习环境: PyBullet 与 OpenAI Gym 兼容，为强化学习提供了标准化的环境和接口。跨平台: 它可以在 Windows、Linux 和 macOS 上运行。
- [PhyScene](https://physcene.github.io/) -PhyScene是一种新颖的方法，用于生成具有真实布局、可移动目标和丰富物理交互性的交互式3D场景，这些特性专为具身agent量身定制。基于条件扩散模型来捕获场景布局，并设计了新颖的基于物理和交互性的引导函数，这些函数包含了来自物体碰撞、房间布局以及agent交互性的约束。
- [RoboGen](https://robogen-ai.github.io/) -RoboGen，这是一种生成式机器人agent，它通过生成式模拟自动学习多样化的机器人技能。RoboGen利用了基础和生成模型领域的最新进展，并没有直接使用或调整这些模型来生成策略或低级动作，而是倡导一种生成式方案，该方案利用这些模型自动生成多样化的任务、场景和训练监督，从而在最小人为监督的情况下扩大机器人技能学习的规模。RoboGen方法使机器人agent具备了自我引导的“提出-生成-学习”循环：agent首先提出有趣的任务和技能来开发，然后通过填充相关目标和资产以适当的空间配置来生成相应的模拟环境。之后，agent将提出的高级任务分解为子任务，选择**学习方法（强化学习、运动规划或轨迹优化），生成所需的训练监督，然后学习策略以获得所提出的技能。这项工作试图提取大规模模型中嵌入的广泛且多功能的知识，并将其转移到机器人领域。我们的完全生成式流程可以反复查询，产生与各种任务和环境相关的无穷无尽的技能演示。
- [ThreeDWorld](https://www.threedworld.org/) -ThreeDWorld（TDW）是一个用于交互式多模态物理模拟的平台。TDW能够在丰富的3D环境中模拟移动agent与物体之间的高保真感官数据和物理交互。其独特属性包括：实时接近照片级真实的图像渲染；目标和环境的库，以及用于自定义它们的例程；用于高效构建新环境类别的生成程序；高保真音频渲染；包括布料、液体和可变形物体在内的多种材料类型的真实物理交互；体现AIagent的可定制agent；以及对人类与VR设备交互的支持。TDW的API允许多个agent在模拟中交互，并返回一系列代表世界状态的传感器和物理数据。
- [iGibson 1.0](https://svl.stanford.edu/igibson/) -iGibson是一个基于Bullet的快速视觉渲染和物理模拟环境。iGibson配备了十五个完全可交互的高质量场景，数百个从真实家庭和办公室重建的大型3D场景，并且与CubiCasa5K和3D-Front等数据集兼容，提供了12000多个额外的可交互场景。iGibson的一些特点包括领域随机化、与运动规划器的集成以及易于使用的工具来收集人类演示。通过这些场景和功能，iGibson允许研究人员训练和评估使用视觉信号来解决导航和操纵任务的机器人agent，如开门、拿起和放置物体或在柜子里搜索。
- [SAPIEN](https://sapien.ucsd.edu/) -SAPIEN模拟器为机器人、刚体和铰接物体提供物理模拟。它通过纯Python接口支持强化学习和机器人技术。此外，它还提供了多种渲染模式，包括深度图、法线图、光流、活动光和光线追踪。
- [Habitat](https://github.com/facebookresearch/habitat-sim) -Habitat是一个用于研究具身人工智能（AI）的平台。Habitat能够在高度逼真的3D模拟环境中训练具身agent（虚拟机器人）。具体来说，Habitat由以下部分组成：
（i）Habitat-Sim：一个灵活、高性能的3D模拟器，具有可配置的agent、传感器和通用的3D数据集处理能力。Habitat-Sim运行速度快—在渲染Matterport3D场景时，它能够在单线程下达到数千帧每秒（fps）的速度，而在单个GPU上进行多进程处理时，速度可超过10,000 fps。
（ii）Habitat-API：一个模块化的高级库，用于具身AI算法的端到端开发——定义任务（如导航、指令跟随、问题回答）、配置、训练和评估具身agent。
- [Dynamic Animation and Robotics Toolkit (DART)](http://wiki.ros.org/stage) -用于二维环境（无z轴高度信息）的仿真器。最早1999年由USC Robotics Research Lab开发，常用于路径规划或多机器人 (multi-agents) 仿真。
- [GAZEBO](gazebosim.org/) -Gazebo是目前最广泛使用的仿真环境，最早在2004年由USC Robotics Research Lab (南加州大学机器人实验室) 开发。依托于ROS的发展，Gazebo具有很强的仿真能力，同时也在机器人研究和开发中得到了广泛应用。Gazebo的功能包括：动力学仿真、传感器仿真、三维环境仿真，同时支持多种机器人模型：包括PR2、Turtlebot、AR.Drone等。

### Development Frameworks  
- [Embodied Multi-Modal Agent trained by an LLM from a Parallel TextWorld](https://arxiv.org/pdf/2311.16714) - 南科大史玉回团队提出新的具身智能体训练框架  
- [具身大模型框架ViLa+CoPa](https://zhuanlan.zhihu.com/p/691623973) - Description
- [o1-preview评估框架](https://www.showapi.com/news/article/6736a9a14ddd79f11a14afa4)
- [端到端AI控制系统](https://blog.csdn.net/weixin_48649532/article/details/144049952)
- [自主无人系统的具身认知智能框架](http://www.ral.neu.edu.cn/_upload/article/files/80/b8/9564432f44129cca25bc957f6c55/86e6a726-b988-4893-967f-2bf1b71a89e1.pdf)
- [Psi R0-端到端具身模型](https://ai-bot.cn/psi-r0/)
- [ARTNR：具身多智能体任务中规划与推理的基准测试框架](https://www.51cto.com/article/801682.html),[Paper](https://scontent-hkg1-2.xx.fbcdn.net/v/t39.2365-6/464851531_1221845409090666_2252263696901529721_n.pdf?_nc_cat=103&ccb=1-7&_nc_sid=3c67a6&_nc_ohc=57t4MekU5d8Q7kNvgGHZLDc&_nc_zt=14&_nc_ht=scontent-hkg1-2.xx&_nc_gid=AP84iiMP4yT2dx7Jh70Nn1B&oh=00_AYCJYRFwktQj-PkAyejTL3iLCYkkmeeSDEVzOobWNlX7MQ&oe=677BDD0B)
- [Savva, Manolis, et al. "Habitat: A platform for embodied ai research." Proceedings of the IEEE/CVF international conference on computer vision. 2019.](https://openaccess.thecvf.com/content_ICCV_2019/papers/Savva_Habitat_A_Platform_for_Embodied_AI_Research_ICCV_2019_paper.pdf)- Description  
- [Deitke, Matt, et al. "Robothor: An open simulation-to-real embodied ai platform." Proceedings of the IEEE/CVF conference on computer vision and pattern recognition. 2020.](https://openaccess.thecvf.com/content_CVPR_2020/papers/Deitke_RoboTHOR_An_Open_Simulation-to-Real_Embodied_AI_Platform_CVPR_2020_paper.pdf) - Description
- [Fu, Haoyuan, et al. "RFUniverse: A Multiphysics Simulation Platform for Embodied AI." arXiv preprint arXiv:2202.00199 (2022).](https://arxiv.org/pdf/2202.00199) - Description 
- [Weihs, Luca, et al. "Allenact: A framework for embodied ai research." arXiv preprint arXiv:2008.12760 (2020).](https://arxiv.org/pdf/2008.12760) - Description  
- [Liu, Guocai, et al. "EAI-SIM: An Open-Source Embodied AI Simulation Framework with Large Language Models." 2024 IEEE 18th International Conference on Control & Automation (ICCA). IEEE, 2024.](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10591865) - Description  


### Benchmark Datasets  
- [EmbodiedCity](https://www.selectdataset.com/dataset/3cb617b98d918ddab4192d889095eb78) - 发布时间：2024-10-13 数据集内容：EmbodiedCity是由清华大学构建的一个用于评估具身智能在真实城市环境中表现的基准平台。该数据集基于北京市的一个商业区，构建了高度逼真的3D模拟环境，包含真实的街道、建筑、城市元素、行人和交通流量。数据集结合了历史收集的真实世界交通数据和模拟算法，模拟了行人和车辆的流动。数据集创建过程中，详细构建了城市建筑的3D模型，并提供了完整的输入输出接口，使具身智能代理能够轻松获取任务需求和环境观察，并进行决策和性能评估。该数据集主要应用于具身智能的评估和训练，旨在解决具身智能在开放户外城市环境中的感知、规划和行动能力问题。
- [MARPLE](https://www.selectdataset.com/dataset/ae5229d69754093549512461afe33160) - 发布时间：2024-10-03 数据集内容：MARPLE是由斯坦福大学开发的一个用于评估长时推理能力的基准数据集。该数据集通过模拟家庭环境中的智能体交互，支持视觉、语言和听觉等多模态证据，旨在测试模型在日常家庭场景中解决“whodunit”类型问题的能力。数据集内容包括多模态观察数据和智能体行为轨迹，通过Mini-BEHAVIOR模拟器生成。创建过程涉及多层次的规划和模拟，以生成多样化的环境和智能体行为。MARPLE主要应用于机器学习和认知科学领域，旨在解决复杂场景中的长时多模态推理问题。
- [CAN-DO](https://www.selectdataset.com/dataset/0a534c344b8d334004a32ea0172a8bd5) - 发布时间：2024-09-22 数据集内容：CAN-DO数据集由新加坡科技设计大学和阿里巴巴达摩院联合创建，旨在评估大型多模态模型在复杂环境中的具身规划能力。该数据集包含400个多模态样本，每个样本包括自然语言用户指令、环境图像、状态变化和相应的行动计划。数据集涵盖常识知识、物理理解和安全意识等多个方面。创建过程中，研究团队结合真实场景图像和合成图像，确保数据多样性和复杂性。CAN-DO数据集主要应用于具身规划领域，旨在解决现有模型在视觉感知、理解和推理能力上的瓶颈问题。
- [MMDL&MMQADL](https://www.selectdataset.com/dataset/757213dc9b23b2314ddf5705b38eab04) - 发布时间：2024-08-21 数据集内容：MMDL和MMQADL是由日本国立先进工业科学技术研究所创建的多模态数据集，旨在支持具身AI的发展。MMDL包含3,530个模拟视频，每个视频展示约30秒至1分钟的家庭日常活动，通过3D模拟器生成并详细标注。MMQADL则是一个问答数据集，用于评估机器人对日常生活的理解能力，包含多种类型的问题和答案。这些数据集通过标准化的注释和详细的描述，为具身AI在理解人类行为和家庭环境方面提供了重要的资源。
- [ARIO](https://www.selectdataset.com/dataset/68e066b815bbb802c1f587885fd12a34) - 发布时间：2024-08-20 数据集内容：ARIO数据集由南方科技大学、中山大学和鹏城实验室联合创建，旨在为多用途、通用型具身智能代理提供标准化的数据格式。该数据集包含约300万条记录，涵盖258个系列和321,064个任务，结合了真实世界和模拟数据。创建过程中，数据集通过多平台收集、模拟生成和开源数据转换等方式构建。ARIO数据集的应用领域广泛，主要用于提高具身智能代理的鲁棒性和适应性，解决数据格式不统一、多样性不足和数据量不足等问题。
- [MFE-ETP](https://www.selectdataset.com/dataset/f87c1a88da43c4cb9e8d487f66fa8c56) - 发布时间：2024-07-06 数据集内容：MFE-ETP数据集由天津大学智能与计算学部创建，是一个针对具身任务规划的多模态基础模型综合评估基准。该数据集包含1184个高质量测试案例，覆盖100个具身任务，涉及对象理解、时空感知、任务理解和具身推理等多个能力维度。数据集的创建过程结合了从BEHAVIOR-100和VirtualHome平台收集的典型家庭任务数据，并通过人工标注和设计任务指令进行精细化处理。MFE-ETP数据集主要应用于提升多模态基础模型在具身人工智能领域的任务规划能力，旨在解决模型在复杂任务场景中的性能瓶颈问题。
- [RoomTour3D](https://www.selectdataset.com/dataset/108f249504b0df9611312f43fb8ac591) - 发布时间：2024-06-27 数据集内容：RoomTour3D是一个几何感知视频指令数据集，用于具身导航。该数据集包含1847个房间游览场景的几何感知视频指令数据，以及使用COLMAP进行的三维场景重建、相对深度估计、开放世界对象标签和定位等中间产品。数据集的组织结构包括colmap_reconstruction、ram_grounding_p1、relative_depth_estimation和trajectories等部分，每个部分都有详细的文件结构和内容描述。此外，数据集还提供了视频下载链接和版权声明，确保用户在使用时的合规性。
- [EmbSpatial-Bench](https://www.selectdataset.com/dataset/12271ef1d372b6fd9b146548895a82e6) - 发布时间：2024-06-23 数据集内容：EmbSpatial-Bench 是一个用于评估语言视觉模型（LVLM）在具身场景中空间理解能力的基准测试，包含3640个问答对，涵盖294个物体类别和6种空间关系。EmbSpatial-SFT 是一个指令调优数据集，提供用于空间关系识别和物体定位的两个任务的问答数据，基于 MP3D 的训练场景构建。
- [Roboturk](https://opendatalab.org.cn/OpenDataLab/Roboturk/tree/main) - RoboTurk 真实机器人数据集收集了有关三个不同现实世界任务的大型数据集：洗衣房布局、塔楼创建和对象搜索。 所有三个数据集都是使用 RoboTurk 平台收集的，由众包工作人员远程收集。 我们的数据集包含来自 54 个不同用户的 2144 个不同演示。 我们提供用于训练的完整数据集和用于探索的数据集的较小子样本。
- [Mini-BEHAVIOR](https://github.com/StanfordVL/mini_behavior) - Mini-BEHAVIOR是一个专为具身AI设计的基准数据集，由斯坦福大学创建。该数据集包含20个模拟家庭任务，旨在评估和训练AI代理在复杂环境中的决策和规划能力。数据集通过程序生成技术创建了无限的任务变体，支持开放式学习。Mini-BEHAVIOR简化了原始BEHAVIOR基准的复杂性，同时保留了任务层面的决策挑战，适用于快速原型设计和训练，是具身AI领域研究和开发的重要工具。
- [BridgeData V2](https://rail-berkeley.github.io/bridgedata/) - BridgeData V2是由加州大学伯克利分校和斯坦福大学等机构合作创建的大型机器人操作行为数据集，包含60,096个轨迹，覆盖24个环境。数据集设计用于支持大规模机器人学习研究，涵盖广泛的技能和环境变量，支持通过目标图像或自然语言指令进行任务调节。创建过程中，数据集通过人工操作和自主收集相结合的方式，确保了数据的多源性和多样性。该数据集适用于多种机器人学习方法，旨在解决机器人技能在不同环境和任务中的泛化问题，推动机器人学习领域的研究进展。\
- [G1数据集-人形机器人操作](https://github.com/unitreerobotics/avp_teleoperate) - 宇树科技公布了开源 G1 人形机器人操作数据集，用以训练人形机器人，适配多种开源方案。宇树 G1 人形机器人操作数据集具有以下特点：（1）多样化的操作能力展示：通过演示视频可以看到，G1 人形机器人能够完成拧瓶盖倒水、叠三色积木、将摄像头放入包装盒、收集物品并存储、双臂抓取红色木块并将其放入黑色长方形容器中等复杂操作，显示出高度的灵活性和实用性。（2）数据采集方式创新：使用苹果的 Vision Pro 对 G1 进行遥操作控制。（3）丰富的数据维度：数据集中的图像分辨率为 640×480，每个手臂和灵巧手的状态及动作维度为 7。目前包含拧瓶盖倒水、叠三色积木、包装摄像头、存储物品、双臂抓取和放置等五大类操作的数据集。
- [TACO-RL-长时域操作](https://www.kaggle.com/datasets/oiermees/taco-robot) - TACO - RL 使用的数据集是通过在模拟和真实环境中对机器人进行远程操作收集的，包含机器人与环境交互的状态 - 动作序列，用于训练分层策略以解决长时域机器人控制任务，支持机器人从无结构的游戏数据中学习通用技能并实现复杂任务的执行。收集的数据为无结构的游戏数据，未针对特定任务进行标记，包含多种机器人操作行为，如推动、抓取、放置物体，操作抽屉、滑动门和与 LED 按钮交互等，具有丰富的多样性和复杂性。数据集用于训练低层级策略，通过对无结构数据进行自动编码，学习从潜在计划到动作的映射，提取一系列基本行为原语。高层级策略通过离线强化学习（RL）利用后见之明重标记技术进行训练。
- [CLVR-遥控](https://github.com/clvrai/clvr_jaco_play_dataset) - CLVR Jaco Play Dataset 是一个专注于遥控机器人领域的数据集，共 14.87 GB，由南加州大学和 KAIST 的研究团队发布，它提供了 1,085 个遥控机器人 Jaco2的片段，并配有相应的语言注释。
- [FurnitureBench-长时域操作](https://clvrai.github.io/furniture-bench/docs/tutorials/dataset.html) - FurnitureBench是一个用于测试真实机器人复杂长时域操作任务的数据集。数据集聚焦于家具组装这一复杂长时域操作任务，其任务层次结构长，涉及家具部件的选择、抓取、移动、对齐和连接等步骤，平均任务时长在 60 - 230 秒（600 - 2300 低层级步骤）。任务要求机器人具备多种复杂技能，如精确抓取（不同家具部件抓取姿态各异）、部件重定向（通过拾取放置或推动实现）、路径规划（避免碰撞已组装部件）、插入和拧紧（精确对齐并重复操作）等。
- [Cable Routing-多阶段电缆布线](https://sites.google.com/view/cablerouting/data) - 该数据集是为训练机器人的电缆布线策略而收集的，用于支持分层模仿学习系统，使机器人能够学习执行多阶段电缆布线任务，应对复杂的电缆操作挑战。数据集中包含了多种电缆形状、夹取位置和方向的变化，以及不同数量夹子（一夹、两夹、三夹）的布线任务数据，有助于训练出具有泛化能力的策略。
- [RoboTurk-模仿学习](https://roboturk.stanford.edu/dataset_real.html) - ROBOTURK 数据集是通过众包平台收集的用于机器人学习任务的大规模数据集，旨在解决机器人模仿学习中数据收集困难的问题，使机器人能够从大量的人类演示中学习操作技能，应对复杂的操作任务。数据涵盖了不同用户在多种任务和操作条件下的演示，包括不同物体的操作（如 lifting 任务中的立方体、picking 任务中的各种物品、assembly 任务中的螺母等）以及不同的操作场景，有助于训练出具有泛化能力的机器人策略。
- [Wang, Zhiqiang, et al. "All robots in one: A new standard and unified dataset for versatile, general-purpose embodied agents." arXiv preprint arXiv:2408.10899 (2024).](https://arxiv.org/pdf/2408.10899) - Description (2024)   
- [Dataset Name](link) - Description  


### Research Datasets  
- [Ramakrishnan, Santhosh K., et al. "Habitat-matterport 3d dataset (hm3d): 1000 large-scale 3d environments for embodied ai." arXiv preprint arXiv:2109.08238 (2021).](https://arxiv.org/pdf/2109.08238) - Description  
- [Zhao, Qianfan, et al. "A real 3d embodied dataset for robotic active visual learning." IEEE Robotics and Automation Letters 7.3 (2022): 6646-6652.](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9729641&tag=1) - Description  

## Courses & Tutorials  

### Online Courses  
- [Building and Working in Environments for Embodied AI](https://ai-workshops.github.io/building-and-working-in-environments-for-embodied-ai-cvpr-2022/) - Simon Fraser University, Angel Xuan Chang

### Video Tutorials  
- [CS539 - Embodied AI](https://web.engr.oregonstate.edu/~leestef/courses/2019/fall/cs539.html) - We will read and analyze the strengths and weaknesses of recent research papers on a variety of topics in embodied AI and identify open research questions. 

### Books & Reading Materials  
- [Multimodal Large Models: The New Paradigm of Artificial General Intelligence](https://hcplab-sysu.github.io/Book-of-MLM/) - Yang Liu, Liang Lin, 2024

## Projects  

### Open Source Projects  
- [CogAgent: Visual Expert for Pretrained Language Models](https://github.com/THUDM/CogVLM?tab=readme-ov-file) - CogAgent is an open-source visual language model improved based on CogVLM.
- [All Robots in One: A New Standard and Unified Dataset for Versatile, General-Purpose Embodied Agents](https://imaei.github.io/project_pages/ario/) - we introduce ARIO (All Robots In One), a new data standard that enhances existing datasets by offering a unified data format, comprehensive sensory modalities, and a combination of real-world and simulated data.
- [Language Guided Generation of 3D Embodied AI Environments](https://github.com/allenai/Holodeck) - Description

### Research Projects  
- [ProAgent: From Robotic Process Automation to Agentic Process Automation](https://github.com/OpenBMB/ProAgent) - Tsinghua University, this paper introduces (APA), a groundbreaking automation paradigm using LLM-based agents for advanced automation by offloading the human labor to agents associated with construction and execution.

### Demo Applications  
- [Application Name](link) - Description  
- [Application Name](link) - Description  

## Conferences & Workshops  

### Major Conferences  
- [The Fifth Annual Embodied AI Workshop](https://embodied-ai.org/) - Tuesday, June 18 from 8:50am to 5:30pm Pacific, 2024, Seattle Convention Center
- [RoboTHOR: An Open Simulation-to-Real Embodied AI Platform](https://openaccess.thecvf.com/content_CVPR_2020/papers/Deitke_RoboTHOR_An_Open_Simulation-to-Real_Embodied_AI_Platform_CVPR_2020_paper.pdf) - 2020
- [Habitat: A Platform for Embodied AI Research](https://openaccess.thecvf.com/content_ICCV_2019/html/Savva_Habitat_A_Platform_for_Embodied_AI_Research_ICCV_2019_paper.html) - 2019

### Workshops & Symposiums  
- [Retrospectives on the Embodied AI Workshop](https://arxiv.org/pdf/2210.06849) - Associated Conference, 13 Oct 2022
- [Workshop on Embodied Intelligence with Large Language Models In Open City Environment](https://openreview.net/pdf?id=zIybgEio8Y) - Associated Conference,  03 Dec 2024

## Research Groups  

### Academic Research Groups  
- [Group Name](link) - Institution, Focus Areas  
- [Group Name](link) - Institution, Focus Areas  

### Industry Research Labs  
- [Lab Name](link) - Company, Focus Areas  
- [Lab Name](link) - Company, Focus Areas  

## Companies & Organizations  

### Companies Working on Embodied AI  
- [Company Name](link) - Focus Areas  
- [Company Name](link) - Focus Areas  

### Organizations & Foundations  
- [Organization Name](link) - Mission  
- [Organization Name](link) - Mission  

## Contributing  

### How to Contribute  
1. Fork the repository  
2. Create a new branch: `git checkout -b add-new-resource`  
3. Add your changes following the formatting guidelines  
4. Submit a pull request  

### Contribution Guidelines  
- Ensure the resource is relevant to Embodied AI  
- Provide a clear description  
- Include necessary links and references  
- Follow the existing format  
- Verify links are working  
- Add new resources to the appropriate section  

### Quality Standards  
- Resources should be actively maintained  
- Content must be high quality and informative  
- Commercial resources should be clearly marked  
- Avoid duplicates  

## License  

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.  

## Acknowledgments  

Special thanks to all contributors who have helped to build and maintain this awesome list!  

---  

## Star History  

[![Star History Chart](https://api.star-history.com/svg?repos=tinyEmbodiedAI/awesome-embodied-ai&type=Date)](https://star-history.com/#tinyEmbodiedAI/awesome-embodied-ai&Date)  

## Contact  

For questions, suggestions, or issues, please:  
- Open an issue  
- Submit a pull request  
- Contact maintainers: [maintainer@email.com](mailto:jqwang16@icloud.com)  

---  

If you find this resource helpful, please consider giving it a ⭐️ to help others discover it!
