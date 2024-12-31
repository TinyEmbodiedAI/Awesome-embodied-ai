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
- [Pfeifer, Rolf, and Fumiya Iida. "Embodied artificial intelligence: Trends and challenges." Lecture notes in computer science (2004): 1-26.](https://people.csail.mit.edu/iida/papers/PfeiferIidaEAIDags.pdf) - Description (2004)  
- [马伟霞](www.baidu.com) - Description (Year)  

### Foundational Papers  
- [Title](link) - Description (Year)  
- [Title](link) - Description (Year)  

### Recent Advances  
- [Title](link) - Description (Year)  
- [Title](link) - Description (Year)  

## Software & Tools  

### Simulation Platforms  
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
- [Framework Name](link) - Description  
- [Framework Name](link) - Description  

### Libraries  
- [Library Name](link) - Description  
- [Library Name](link) - Description  

## Datasets  

### Benchmark Datasets  
- [EmbodiedCity](https://www.selectdataset.com/dataset/3cb617b98d918ddab4192d889095eb78) - 发布时间：2024-10-13 数据集内容：EmbodiedCity是由清华大学构建的一个用于评估具身智能在真实城市环境中表现的基准平台。该数据集基于北京市的一个商业区，构建了高度逼真的3D模拟环境，包含真实的街道、建筑、城市元素、行人和交通流量。数据集结合了历史收集的真实世界交通数据和模拟算法，模拟了行人和车辆的流动。数据集创建过程中，详细构建了城市建筑的3D模型，并提供了完整的输入输出接口，使具身智能代理能够轻松获取任务需求和环境观察，并进行决策和性能评估。该数据集主要应用于具身智能的评估和训练，旨在解决具身智能在开放户外城市环境中的感知、规划和行动能力问题。
- [MARPLE](https://www.selectdataset.com/dataset/ae5229d69754093549512461afe33160) - 发布时间：2024-10-03 数据集内容：MARPLE是由斯坦福大学开发的一个用于评估长时推理能力的基准数据集。该数据集通过模拟家庭环境中的智能体交互，支持视觉、语言和听觉等多模态证据，旨在测试模型在日常家庭场景中解决“whodunit”类型问题的能力。数据集内容包括多模态观察数据和智能体行为轨迹，通过Mini-BEHAVIOR模拟器生成。创建过程涉及多层次的规划和模拟，以生成多样化的环境和智能体行为。MARPLE主要应用于机器学习和认知科学领域，旨在解决复杂场景中的长时多模态推理问题。
- [CAN-DO](https://www.selectdataset.com/dataset/0a534c344b8d334004a32ea0172a8bd5) - 发布时间：2024-09-22 数据集内容：CAN-DO数据集由新加坡科技设计大学和阿里巴巴达摩院联合创建，旨在评估大型多模态模型在复杂环境中的具身规划能力。该数据集包含400个多模态样本，每个样本包括自然语言用户指令、环境图像、状态变化和相应的行动计划。数据集涵盖常识知识、物理理解和安全意识等多个方面。创建过程中，研究团队结合真实场景图像和合成图像，确保数据多样性和复杂性。CAN-DO数据集主要应用于具身规划领域，旨在解决现有模型在视觉感知、理解和推理能力上的瓶颈问题。
- [MMDL&MMQADL](https://www.selectdataset.com/dataset/757213dc9b23b2314ddf5705b38eab04) - 发布时间：2024-08-21 数据集内容：MMDL和MMQADL是由日本国立先进工业科学技术研究所创建的多模态数据集，旨在支持具身AI的发展。MMDL包含3,530个模拟视频，每个视频展示约30秒至1分钟的家庭日常活动，通过3D模拟器生成并详细标注。MMQADL则是一个问答数据集，用于评估机器人对日常生活的理解能力，包含多种类型的问题和答案。这些数据集通过标准化的注释和详细的描述，为具身AI在理解人类行为和家庭环境方面提供了重要的资源。
- [ARIO](https://www.selectdataset.com/dataset/68e066b815bbb802c1f587885fd12a34) - 发布时间：2024-08-20 数据集内容：ARIO数据集由南方科技大学、中山大学和鹏城实验室联合创建，旨在为多用途、通用型具身智能代理提供标准化的数据格式。该数据集包含约300万条记录，涵盖258个系列和321,064个任务，结合了真实世界和模拟数据。创建过程中，数据集通过多平台收集、模拟生成和开源数据转换等方式构建。ARIO数据集的应用领域广泛，主要用于提高具身智能代理的鲁棒性和适应性，解决数据格式不统一、多样性不足和数据量不足等问题。
- [MFE-ETP](https://www.selectdataset.com/dataset/f87c1a88da43c4cb9e8d487f66fa8c56) - 发布时间：2024-07-06 数据集内容：MFE-ETP数据集由天津大学智能与计算学部创建，是一个针对具身任务规划的多模态基础模型综合评估基准。该数据集包含1184个高质量测试案例，覆盖100个具身任务，涉及对象理解、时空感知、任务理解和具身推理等多个能力维度。数据集的创建过程结合了从BEHAVIOR-100和VirtualHome平台收集的典型家庭任务数据，并通过人工标注和设计任务指令进行精细化处理。MFE-ETP数据集主要应用于提升多模态基础模型在具身人工智能领域的任务规划能力，旨在解决模型在复杂任务场景中的性能瓶颈问题。
- [RoomTour3D](https://www.selectdataset.com/dataset/108f249504b0df9611312f43fb8ac591) - 发布时间：2024-06-27 数据集内容：RoomTour3D是一个几何感知视频指令数据集，用于具身导航。该数据集包含1847个房间游览场景的几何感知视频指令数据，以及使用COLMAP进行的三维场景重建、相对深度估计、开放世界对象标签和定位等中间产品。数据集的组织结构包括colmap_reconstruction、ram_grounding_p1、relative_depth_estimation和trajectories等部分，每个部分都有详细的文件结构和内容描述。此外，数据集还提供了视频下载链接和版权声明，确保用户在使用时的合规性。
- [EmbSpatial-Bench](https://www.selectdataset.com/dataset/12271ef1d372b6fd9b146548895a82e6) - 发布时间：2024-06-23 数据集内容：EmbSpatial-Bench 是一个用于评估语言视觉模型（LVLM）在具身场景中空间理解能力的基准测试，包含3640个问答对，涵盖294个物体类别和6种空间关系。EmbSpatial-SFT 是一个指令调优数据集，提供用于空间关系识别和物体定位的两个任务的问答数据，基于 MP3D 的训练场景构建。


### Research Datasets  
- [Dataset Name](link) - Description  
- [Dataset Name](link) - Description  

## Courses & Tutorials  

### Online Courses  
- [Course Name](link) - Institution, Instructor  
- [Course Name](link) - Institution, Instructor  

### Video Tutorials  
- [Tutorial Series](link) - Description  
- [Tutorial Series](link) - Description  

### Books & Reading Materials  
- [Book Title](link) - Author(s), Year  
- [Book Title](link) - Author(s), Year  

## Projects  

### Open Source Projects  
- [Project Name](link) - Description  
- [Project Name](link) - Description  

### Research Projects  
- [Project Name](link) - Institution, Description  
- [Project Name](link) - Institution, Description  

### Demo Applications  
- [Application Name](link) - Description  
- [Application Name](link) - Description  

## Conferences & Workshops  

### Major Conferences  
- [Conference Name](link) - Date, Location  
- [Conference Name](link) - Date, Location  

### Workshops & Symposiums  
- [Workshop Name](link) - Associated Conference, Date  
- [Workshop Name](link) - Associated Conference, Date  

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
