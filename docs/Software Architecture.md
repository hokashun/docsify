## Software Architecture

The software architecture is meticulously crafted to provide precise control and efficient management of robotic systems via a network-based communication framework. This system ensures smooth interaction with the robot and empowers operators to issue commands while receiving real-time feedback. The supported communication protocols are `HTTP `and `WebSocket`. Any client, whether it's implemented in `Node.js `, `TypeScript `or `Python`, can be utilized as long as it supports these two protocols to establish communication with the three system layers. Furthermore, a joystick terminal can also be employed for this purpose.

![1698819486264](image/README/1698819486264.png)

* **Bottom Layer - Motion Library**

  * The Motion Library, at the bottom layer, handles core functions related to motion control and operational control.
  * It encompasses motor control, motion algorithms, and operational control, ensuring precise and coordinated robot movements.
* **Middle Layer - Body**

  * The middle layer, known as the Body, represents the physical embodiment of the robot and is responsible for various aspects of its operation.
  * Components for head interaction, joint control, upper limb dexterity, hand environmental awareness, and proprioception contribute to the robot's physical capabilities and sensory perception.
* **Upper Layer**

  * The uppermost layer is versatile and dynamic, incorporating advanced functionalities such as graphical programming, cluster control, avatar control, and embodied intelligence.
  * This layer enables higher-level tasks, including human-robot interaction, decision-making, and intelligent behaviors.

Software architecture enables the functionality of the robot by providing a structured and organized framework that effectively manages the various aspects of the robot's operation. Here's how each layer of the architecture contributes to the robot's functionality:

## Bottom Layer - Motion Library

### Core Motion Control

- This layer ensures that the robot's fundamental motion control, including motor control and low-level operational control, is handled accurately. This is crucial for controlling the robot's movement, which is fundamental to its operation.

### Motion Algorithms

- The use of motion algorithms within this layer ensures that the robot can execute precise and coordinated movements. These algorithms help the robot navigate its environment and interact with objects or humans effectively.

### Operational Control

- Operational control functions ensure that the robot's basic operational aspects are managed efficiently, such as power management, self-calibration, and diagnostics. This is essential for the robot's overall reliability and performance.

## Middle Layer - Body

### Physical Representation

- The Body layer represents the physical embodiment of the robot, encompassing its structural components. It is responsible for various physical aspects, such as head interaction, joint control, upper limb dexterity, hand environmental awareness, and proprioception.

### Head Interaction

- This component provides sensory perception, allowing the robot to interact with its environment through vision, hearing, or other sensory modalities.

### Joint Control

- Joint control contributes to the robot's mobility and flexibility, enabling it to perform various physical tasks and movements.

### Upper Limb Dexterity

- This aspect enhances the robot's ability to manipulate objects and interact with the environment in a precise and controlled manner.

### Hand Environmental Awareness

- Environmental awareness in the hand ensures that the robot can interact with objects safely and adapt to its surroundings.

### Proprioception

- Proprioception enables the robot to have self-awareness of its body and movements, which is vital for executing tasks effectively and avoiding collisions.

## Upper Layer

### Advanced Functionalities

- The Upper Layer provides a dynamic and versatile framework that includes advanced functionalities, such as graphical programming, cluster control, avatar control, and embodied intelligence.

### Graphical Programming

- Graphical programming tools simplify customization and programming, making it easier for developers and users to define robot behaviors and tasks.

### Cluster Control

- The ability to control multiple robots as a cluster enhances the robot's capabilities for collaborative and coordinated tasks.

### Avatar Control

- This feature can allow remote operation by a human user, enabling teleoperation or remote supervision.

### Embodied Intelligence

- Embodied intelligence empowers the robot to exhibit intelligent behaviors and adapt to changing situations, enhancing its autonomy and problem-solving abilities.

Overall, this three-layered architecture is designed to create a balanced system. The Bottom Layer handles fundamental control, the Middle Layer provides the physical capabilities and sensory perception, and the Upper Layer adds advanced functionality and intelligence. This architecture enables the robot to perform tasks, interact with humans, and adapt to a wide range of applications and environments, making it a versatile and functional robotic system.

### Introduction

- Provide an introduction that briefly explains the software architecture's role in enabling your robot's functionality.
- Mention that the architecture consists of three primary layers: Bottom Layer, Middle Layer, and Upper Layer.

### Bottom Layer - Motion Library

#### 1.1 Core Motion Control

- Describe how the Motion Library handles fundamental motion control, including motor control and low-level operational control.

#### 1.2 Motion Algorithms

- Explain the algorithms used in the Motion Library for precise and coordinated robot movements.

#### 1.3 Operational Control

- Detail the operational control functions within the Motion Library, highlighting their role in the robot's operation.

### Middle Layer - Body

#### 2.1 Physical Representation

- Describe the Body as the physical embodiment of the robot and its role in the architecture.

#### 2.2 Head Interaction

- Explain how the architecture facilitates head interaction, which may include vision and auditory capabilities.

#### 2.3 Joint Control

- Discuss how joint control is handled within the Body layer, contributing to the robot's mobility and flexibility.

#### 2.4 Upper Limb Dexterity

- Detail the robot's upper limb dexterity, which enables precise manipulation and interaction with objects and the environment.

#### 2.5 Hand Environmental Awareness

- Explain how the robot's hand environmental awareness contributes to safe and effective interactions with the surroundings.

#### 2.6 Proprioception

- Describe how proprioception, the robot's self-awareness of its body and movements, enhances its overall capabilities.

### Upper Layer

#### 3.1 Advanced Functionalities

- Introduce the uppermost layer, emphasizing its dynamic nature and advanced functionalities.

#### 3.2 Graphical Programming

- Explain how graphical programming tools are integrated into the architecture for ease of use and customization.

#### 3.3 Cluster Control

- Discuss the concept of cluster control, where multiple robots can be coordinated and managed as a group.

#### 3.4 Avatar Control

- Describe how the architecture enables avatar control, potentially for teleoperation or remote operation by a human user.

#### 3.5 Embodied Intelligence

- Explain the concept of embodied intelligence within the upper layer, which allows the robot to exhibit intelligent behaviors and adapt to various situations.

### Conclusion

- Summarize the significance of the three-layer architecture in achieving a balance between core motion control, physical capabilities, and advanced functionalities.
- Emphasize how this architecture enables the robot to perform tasks, interact with humans, and exhibit intelligent behaviors.

### References

- Include references to any specific software libraries, frameworks, or technologies used within each layer of the architecture.

## How the Architecture Enables Robot Functionality

The described software architecture enables the functionality of the robot by providing a structured and organized framework that effectively manages the various aspects of the robot's operation. Here's how each layer of the architecture contributes to the robot's functionality:

**1. Bottom Layer - Motion Library:**

- **Core Motion Control:** This layer ensures that the robot's fundamental motion control, including motor control and low-level operational control, is handled accurately. This is crucial for controlling the robot's movement, which is fundamental to its operation.
- **Motion Algorithms:** The use of motion algorithms within this layer ensures that the robot can execute precise and coordinated movements. These algorithms help the robot navigate its environment and interact with objects or humans effectively.
- **Operational Control:** Operational control functions ensure that the robot's basic operational aspects are managed efficiently, such as power management, self-calibration, and diagnostics. This is essential for the robot's overall reliability and performance.

**2. Middle Layer - Body:**

- **Physical Representation:** The Body layer represents the physical embodiment of the robot, encompassing its structural components. It is responsible for various physical aspects, such as head interaction, joint control, upper limb dexterity, hand environmental awareness, and proprioception.
- **Head Interaction:** This component provides sensory perception, allowing the robot to interact with its environment through vision, hearing, or other sensory modalities.
- **Joint Control:** Joint control contributes to the robot's mobility and flexibility, enabling it to perform various physical tasks and movements.
- **Upper Limb Dexterity:** This aspect enhances the robot's ability to manipulate objects and interact with the environment in a precise and controlled manner.
- **Hand Environmental Awareness:** Environmental awareness in the hand ensures that the robot can interact with objects safely and adapt to its surroundings.
- **Proprioception:** Proprioception enables the robot to have self-awareness of its body and movements, which is vital for executing tasks effectively and avoiding collisions.

**3. Upper Layer:**

- **Advanced Functionalities:** The Upper Layer provides a dynamic and versatile framework that includes advanced functionalities, such as graphical programming, cluster control, avatar control, and embodied intelligence.
- **Graphical Programming:** Graphical programming tools simplify customization and programming, making it easier for developers and users to define robot behaviors and tasks.
- **Cluster Control:** The ability to control multiple robots as a cluster enhances the robot's capabilities for collaborative and coordinated tasks.
- **Avatar Control:** This feature can allow remote operation by a human user, enabling teleoperation or remote supervision.
- **Embodied Intelligence:** Embodied intelligence empowers the robot to exhibit intelligent behaviors and adapt to changing situations, enhancing its autonomy and problem-solving abilities.

Overall, this three-layered architecture is designed to create a balanced system. The Bottom Layer handles fundamental control,
