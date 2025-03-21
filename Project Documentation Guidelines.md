1.  ![A logo of a globe with a graduation cap AI-generated content may
    be incorrect.](media/image1.png){width="1.2333333333333334in"
    height="1.1333333333333333in"}**Project Planning & Management**

    - **Project Proposal**

**Overview:** This project aims to design and configure a network
infrastructure using Cisco devices. The goal is to implement internal
and external networks using Cisco routers and switches. The project
involves configuring 10 routers, 2 switches, and integrating multiple
routing protocols (OSPF, EIGRP, BGP) for inter-router communication. The
primary objective is to set up a network that uses multiple routing
protocols and secure configurations.

**Objectives:**

- Design a network using Cisco routers and switches (10 routers, 2
  switches).

- Configure and implement OSPF, EIGRP, and BGP to establish
  communication between routers.

- Implement secure network practices such as password encryption and
  configuration security.

- Ensure communication between routers using different protocols via
  BGP.

**Scope:**

- Installation and configuration of network devices using Cisco Packet
  Tracer or GNS3.

- Configuration of routers with OSPF and EIGRP protocols.

- Integration of BGP for inter-protocol communication.

- Final report and presentation to demonstrate the project\'s outcome.

<!-- -->

- **Project Plan**

**Timeline:**

![A diagram of a network AI-generated content may be
incorrect.](media/image2.png){width="7.646113298337708in"
height="2.972916666666667in"}

**Resource Allocation**:

- **Tools**: GNS3.

- **Hardware/Software Requirements**: 10 Cisco routers, 2 switches, and
  a computer with the ability to run simulation tools.

<!-- -->

- **Task Assignment & Roles**

1.  **Saif ElDeen Samir (Network Architect)**

    - **Week 1**: Design the network topology, ensure the installation
      of internal and external networks (10 routers, 2 switches).

    - **Week 4**: Design and oversee the configuration of BGP for
      inter-protocol communication.

    - **Collaborates**: Works with other members to ensure the network
      design flows smoothly.

    - **Deliverables**: Network design document, BGP configuration
      overview.

2.  **Ibrahim Zayed (Router Configuration Specialist)**

    - **Week 2**: Configure OSPF on the first 5 routers (3 areas:
      stubby, totally stubby, backbone).

    - **Week 3**: Configure EIGRP on the remaining 5 routers.

    - **Deliverables**: OSPF configuration, EIGRP configuration, router
      configuration scripts.

3.  **Abdelrahman Sobhy (Security & Configuration Lead)**

    - **Week 2** and **Week 3**: Configure secure settings such as
      password encryption, enabling VTY access passwords, and ensuring
      secure communication between routers.

    - **Collaborates**: Works with all members to ensure security is
      integrated into configurations.

    - **Deliverables**: Configurations for enabling secret and VTY
      passwords, password encryption, secure access policies.

4.  **Hanna Mostafa (Protocol Integration Specialist)**

    - **Week 4**: Configure BGP and ensure inter-protocol communication
      (OSPF/EIGRP) using ISP.

    - **Collaborates**: Works with the Network Architect to ensure BGP
      is properly configured and integrated with existing protocols.

    - **Deliverables**: BGP configuration, troubleshooting report,
      integration plan for OSPF/EIGRP communication via BGP.

5.  **Salma Amin (Testing & Documentation Lead)**

    - **Throughout the Project**: Perform testing and validation on each
      configuration (OSPF, EIGRP, BGP).

    - **Final Week**: Work on the final **project report** and
      **presentation**. Document each stage of the project, including
      designs, configurations, and testing results.

    - **Collaborates**: Works with all members to test configurations
      and ensure the network is functioning correctly.

    - **Deliverables**: Testing reports, final project report,
      presentation slides.

- **Risk Assessment & Mitigation Plan**

| **Risk**                                        | **Mitigation**                                              |
|-------------------------------------------------|-------------------------------------------------------------|
| Configuration errors leading to downtime        | Frequent testing and validation after each configuration.   |
| Incompatibility between protocols (OSPF, EIGRP) | Use a detailed configuration guide to ensure compatibility. |
| Network misconfigurations in ISP section        | Run simulations first, document every configuration change. |
| Time overruns in configuration setup            | Keep buffer times in the schedule for troubleshooting.      |

- **KPIs**

<!-- -->

- **Response Time**: Time for each router to respond to a ping request.

- **System Uptime**: Percentage of time the network operates without
  failure.

- **User Adoption Rate**: Number of successful configurations
  implemented by each team member.

**2. Literature Review**

- **Feedback & Evaluation -- Lecturer's Assessment of the Project**

Seek feedback throughout the project phases, especially after
configuring each protocol (OSPF, EIGRP, BGP). This feedback will guide
adjustments to the configuration or design as needed.

- **Suggested Improvements -- Areas Where the Project Can Be Enhanced**

<!-- -->

- Explore more advanced network security configurations (e.g., ACLs or
  VPNs).

- Implement Quality of Service (QoS) policies for traffic management.

- Utilize more complex routing protocols (e.g., OSPF with Route
  Summarization or EIGRP with route redistribution).

<!-- -->

- **Final Grading Criteria**

<!-- -->

- **Documentation (40%)**: Detailed configuration, design, and testing
  report.

- **Implementation (30%)**: Successful configuration of OSPF, EIGRP, and
  BGP.

- **Testing (20%)**: Proper testing and verification of network
  connectivity.

- **Presentation (10%)**: Clear and concise final presentation.

**3. Requirements Gathering**

- **Stakeholder Analysis -- Identifying Key Stakeholders and Their
  Needs**

<!-- -->

- **Internal Team**: Needs to collaborate on configurations and testing.

- **Lecturer**: Requires progress reports, final report, and clear
  presentation.

- **End Users**: Require secure and reliable network communication
  between protocols.

<!-- -->

- **User Stories & Use Cases -- Scenarios Illustrating How Users
  Interact with the System**

<!-- -->

- **User Story 1**: As a network administrator, I need to configure OSPF
  on routers to ensure efficient routing.

- **User Story 2**: As a network engineer, I need to integrate BGP
  between two different routing protocols to ensure inter-network
  communication.

<!-- -->

- **Functional Requirements**

<!-- -->

- OSPF configuration for 3 areas (stubby, totally stubby, and backbone).

- EIGRP configuration with Autonomous System 1.

- BGP configuration to allow communication between OSPF and EIGRP.

- Secure configuration practices (password encryption, VTY, and enable
  secret).

<!-- -->

- **Non-functional Requirements**

<!-- -->

- **Performance**: Ensure routing protocols handle high volumes of
  traffic.

- **Security**: Encrypt passwords and secure VTY access.

- **Reliability**: Ensure routers and switches remain operational 99.9%
  of the time.

**4. System Analysis & Design**

- **Problem Statement & Objectives**

The problem being solved is how to configure multiple routing protocols
across a network with different requirements (OSPF, EIGRP, and BGP). The
goal is to enable secure, reliable, and efficient communication between
devices.

- **Use Case Diagram & Descriptions**

Create use cases for configuring and managing each protocol (OSPF,
EIGRP, BGP) and interactions between routers and switches.

- **Software Architecture**

Use **Hybrid Architecture** (Combining OSPF, EIGRP, and BGP), where
routers connect with different routing protocols using BGP for
inter-protocol communication.

- **Deployment System & Integration**

**Technology Stack**

- **Router Configuration**: Cisco devices (configured with OSPF, EIGRP,
  BGP).

- **Tools**: Cisco Packet Tracer, GNS3.

- **Security**: Password encryption, access control lists (ACLs), and
  secure management.

**Deployment Diagram**

Show how routers are distributed across different subnets and where BGP
acts as an intermediary for protocol communication.

- **Additional Deliverables**

**Testing & Validation**

- **Unit Tests**: Check individual configurations for OSPF, EIGRP, BGP.

- **Integration Tests**: Ensure all routers communicate effectively
  between the two protocols.

- **User Acceptance Testing**: Test end-to-end communication after
  protocol configuration.

**Deployment Strategy**

The network will be deployed using Cisco Packet Tracer or GNS3 for
simulation, with potential future deployment on actual hardware.
