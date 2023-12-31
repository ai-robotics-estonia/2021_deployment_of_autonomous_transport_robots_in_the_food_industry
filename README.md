# Deployment of Autonomous Transport Robots in the Food Industry

## Summary
| Company Name | [Kulinaaria OÜ](https://www.kulinaariatoit.ee/en/) |
| :--- | :--- |
| Development Team Lead Name | [Tõnis Raamets](https://www.etis.ee/CV/T%C3%B5nis_Raamets/eng/) |
| Development Team Lead E-mail | [tonis.raamets@taltech.ee](mailto:tonis.raamets@taltech.ee) |
| Objectives of the Demonstration Project | Validate transport robots feasability in a classical logistics workflow. |
| Final Report | [Mobiilsete robotite spetsiifiliste nõuete analüüs_KULINAARIA_2022_30_06_FINAL.pdf](https://github.com/ai-robotics-estonia/deployment_of_autonomous_transport_robots_in_the_food_industry/files/13800672/Mobiilsete.robotite.spetsiifiliste.nouete.analuus_KULINAARIA_2022_30_06_FINAL.pdf); [Demoproject_report_#1_AV_AI.docx.pdf](https://github.com/ai-robotics-estonia/deployment_of_autonomous_transport_robots_in_the_food_industry/files/13800671/Demoproject_report_.1_AV_AI.docx.pdf); [Demonstration-Project_Report_#2.pdf](https://github.com/ai-robotics-estonia/deployment_of_autonomous_transport_robots_in_the_food_industry/files/13800670/Demonstration-Project_Report_.2.pdf); [Demonstration_Project_Summary - Template.pdf](https://github.com/ai-robotics-estonia/deployment_of_autonomous_transport_robots_in_the_food_industry/files/13800669/Demonstration_Project_Summary.-.Template.pdf); [ANNEX1_Mobiilsete robotite spetsiifiliste nõuete analüüs_KULINAARIA_2022.pdf](https://github.com/ai-robotics-estonia/deployment_of_autonomous_transport_robots_in_the_food_industry/files/13800668/ANNEX1_Mobiilsete.robotite.spetsiifiliste.nouete.analuus_KULINAARIA_2022.pdf) |

# Description
## Objectives of the Demonstration Project
*Please describe your project objectives in detail.*

The purpose of the demo project is to automate the movement of goods in the packing area of the factory in order to increase the logistical speed and production capacity of the factory. The logistics of the packing area of the Kulinaaria OÜ factory will soon be automated and transport robots will be integrated with the company's ERP system. This makes it possible to manage the movement of materials and goods remotely using a digital twin warehouse. The system created during the project is universal and does not depend too much on the goods being moved, but it is mainly aimed at warehouses and more spacious areas where the paths of people and robots rarely cross.

The main goal of the demo project is to analyze whether and how Kulinaaria OÜ can to use mobile robots for delivery and whether it is possible to interface a control system for mobile robots with artificial intelligence functionality and with the company's existing resource planning system so that their optimize the movement trajectories of mobile robots and transport tasks.

## Activities and Results of the Demonstration Project
### Challenge
*Please describe challenge addressed (i.e, whether and how the initial challenge was changed during the project, for which investment the demonstration project was provided).*

The design and engineering of AMR systems also includes the design of the flow path and the necessary. minimising the number of vehicles required. The design of the flow path shall take into account the physical layout of the flow paths and the need for a number of vehicles in the shift when examining the need for a number of vehicles shall be assessed and this in turn will provide the basis for determining the required AMR- number of AMRs required.
Significant implications for the overall system installation cost, travel time and operational costs are estimated in terms of the design of loading and unloading locations and road layout. This will depend directly on the the number of AMRs to be used for the specified capacity. An important component in the selection of AMR systems is also the unit cost. load. A large unit requires fewer AMRs, but requires more complex handling, and lifting equipment. Lower unit loads require more AMRe but also reduce the need for cost of AMRs. Preference should be given to one-way closed segment flow paths and one type of AMR.
which is much easier to manage and creates less congestion, fewer opportunities for collisions and fewer crossings of different traffic paths. In addition, the proportion of idling should be reduced to achieve an optimal flow path. An important part of automating material handling in the enterprise is the use of automatic detection and communication technology, which gives us near-flawless data collection at the point of use.

An automatic materials and components identification system gives us the ability to identify in real time to track the location, quantity, origin, destination, material and product specific parameters (e.g. temperature, humidity, etc.) and movement schedule of materials and components. The automated communication system also enables paperless data transmission. Various identification and recognition technologies such as machine vision, laser scanners are used, radio-frequency identification solutions and various magnetic stripe solutions.

For details, check the [final report](#summary).

### Data Sources
*Please describe which data was used for the technological solution.*  

For details, check the [final report](#summary).

### Technologies
*Please describe and justify the use of selected technologies.*
- Autonomous Mobile Robots (AMR)
- Visual Components 3D simulation software
- Siemens Technomatix Plant Simulation 3D simulation software
- Matlab - Dijkstra's algorithm
- Dimusa - MES software
- Axapta - ERP system
- IoT sensor systems

For details, check the [final report](#summary).

### Technological Results
*Please describe the results of testing and validating the technological solution.*

The analysis of key technical indicators and the mapping of workplaces for the development of an AI-based system are described; AMR digital twin simulation data has been validated in a production environment with real-world testing of AMR systems.

A cyberphysical environment has been developed and described for the production of Kulinaaria OÜ, which enables the use of artificial intelligence (AI) functionality to perform the movement trajectories and transport tasks of mobile robots. An object-oriented approach to AI algorithms (decision tree and shortest path algorithms) is used to create the execution orders and movement trajectories of the mobile robot. For a more detailed and pictorial overview, a description of the node class is provided.

The project is unique in a number of ways:
- the project created a virtual factory concept, where the feasibility of using a mobile robot was analysed using a 3D virtual factory in Kulinarie, which was created on a 2D plan of the physical factory. The input to the virtual factory was real production data. This approach is a fast and less time-consuming process for solving a specific problem in a manufacturing plant, and the results obtained are concrete and easy to interpret;
- The project created a prototype cyber-physical environment that interfaced with the enterprise resource planning (ERP) system, the mobile robot control system, the virtual factory with workstations, and the artificial intelligence functionality to solve the robot's planning tasks. This approach allows us to test the suitability of the different solutions in advance on the basis of a virtual factory, and to identify which solution is the most suitable for the use of AI. and the most cost-effective for the company.

For details, check the [final report](#summary).

### Technical Architecture
*Please describe the technical architecture (e.g, presented graphically, where the technical solution integration with the existing system can also be seen).*

Autonomous mobile robots (AMRs) are one of the most flexible robots in the types of material handling systems. These vehicles are capable of autonomously moving very large objects. of different weights and shapes using modern guidance and routing systems. AMR are linked through a centralised computer system to a linked production and service environment in order to coordinate their movements with other material handling equipment and the AMR. This provides the possibility to plan very precisely the movement of materials in the production and to obtain the movements and feedback on movements and operations in real time. AMR systems are becoming an important part of the small and medium sized manufacturing enterprise, both in the warehouse and in the manufacturing plant and in-plant logistics. AMRs are battery-powered and unmanned central computer-controlled and precisely addressable vehicles that use either wired guides or magnetic and optical guidance solutions to move. The main advantages over today's known forklifts, trolleys and fixed material handling equipment such as conveyors are high flexibility, space utilisation, safety and overall lower operating costs. AMR systems are very flexible, especially when it is necessary to change the flow path of materials or, for example, can be dynamically redirected to respond to changes in system priorities. To make AMR selections, we use the selection criteria in the theory and the transport and freight specifications in the specifications.

In addition to the above conditions, the selection of an AMR system should also take into account the floor friction coefficient, the steps on the floor surface, the maximum permissible floor slope, the room temperature and humidity, electromagnetic disturbances, the availability of Wifi in the premises, the location of the charging point and the required power. AMR choices must take into account the possibility of integrating the AMR control system with the company's ERP system to ensure consistency of materials and tasks and compatibility with the building's electronic equipment (automatic doors, lifts, storage shelves).
The technical description and specifications of the mobile robots used in this project are as follows are given below.

<img width="642" alt="Screenshot 2023-12-31 at 10 57 14" src="https://github.com/ai-robotics-estonia/deployment_of_autonomous_transport_robots_in_the_food_industry/assets/15941300/19c046c7-914a-40bd-957e-ebe2d625f59b">
<img width="645" alt="Screenshot 2023-12-31 at 10 57 07" src="https://github.com/ai-robotics-estonia/deployment_of_autonomous_transport_robots_in_the_food_industry/assets/15941300/eae5b926-30a8-43a6-945b-8fa37690191a">

For details, check the [final report](#summary).

### User Interface 
*Please describe the details about the user interface(i.e, how does the client 'see' the technical result, whether a separate user interface was developed, command line script was developed, was it validated as an experiment, can the results be seen in ERP or are they integrated into work process)*

For details, check the [final report](#summary).

### Future Potential of the Technical Solution
*Please describe the potential areas for future use of the technical solution.*

The company has or wants to acquire AMR systems for automated production logistics in the near future. The company wants to use the artificial intelligence (AI) functionality in the automated production logistics solution to plan the transport commands and routes of the AMR system.

Various manufacturing companies that want to adopt or already have autonomous mobile (AMR) systems and want to automate their production processes using artificial intelligence functionality. For example, manufacturing companies from different sectors:
- chemical industry sector;
- wood processing sector;
- metalworking sector.

Potential client(s)
- Chemi Pharm
- Halver Mööbel
- Inission Eesti

For details, check the [final report](#summary).

### Lessons Learned
*Please describe the lessons learned (i.e. assessment whether the technological solution actually solved the initial challenge).*

By using the virtual factory concept and 3D simulation software, it is possible to quickly solve the company's specific problems and requires fewer resources. The obtained results are specific and easy to interpret and give the company the opportunity to determine the amount of investments.During the demo project, we gained experience how to connect autonomous mobile robot (AMR) systems with different software and hardware systems and connect them with artificial intelligence functionality

For details, check the [final report](#summary).
