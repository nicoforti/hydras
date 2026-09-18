# HYDRAS
## Hydrodynamic-aware Distributed Robots for Marine Source-Seeking

HYDRAS is a research project at the University of Florence combining
autonomous multi-robot sensing, reinforcement learning, and hydrodynamic
modeling for pollutant source localization in coastal and port environments.

## Motivation

Currents, tides, wind-driven mixing, and turbulence shape pollutant
transport in marine environments. The resulting concentration fields
are dynamic and difficult to interpret from sparse, local measurements.

HYDRAS aims to enable scalable and reliable source localization by
connecting cooperative robotic sensing with realistic models of
marine transport.

## Research objectives

The project aims to develop autonomous source-seeking methods for
networks of sensing robots, combining:

- Distributed multi-agent reinforcement learning for cooperative
  source seeking.
- Decentralized control and event-triggered communication.
- Physics-based hydrodynamic simulations for training and evaluation.
- Oceanographic data from Copernicus Marine and EMODnet.

The approach combines model-informed offline training with model-free
online execution: robots learn from simulated marine environments
and select actions from available measurements without requiring
an explicit environment model during operation.

## OCEANS 2026 contribution

**Hydrodynamic-Aware Reinforcement Learning for Autonomous Marine
Source Seeking**

Nicola Forti, Mattia Manneschi, Irene Simonetti, Giorgio Battistelli  
University of Florence, Italy

This initial study investigates centralized source seeking using
a single reinforcement-learning policy and three sensing configurations:
central-agent-only, single ring, and double ring.

The policy is trained using MIKE 21 simulations of coastal hydrodynamics
and pollutant transport near Cecina, Italy. Ring measurements represent
ideal co-moving sensing locations.

At a maximum speed of 1.2 m/s, ring-based PPO achieves 98.4–98.7%
success, compared with 56.4% for the field-climbing baseline.

### Materials

The paper, poster, presentation slides, and demonstration videos
will be added here as they become available.

## Opportunities

We welcome expressions of interest in thesis projects and research
opportunities related to:

- Multi-agent systems and cooperative robotics.
- Distributed control and estimation.
- Reinforcement learning for marine environmental monitoring.

Please contact the project team for current opportunities.

## Project contacts

**Nicola Forti**  
Assistant Professor  
Department of Information Engineering (DINFO)  
University of Florence, Italy  
[nicola.forti@unifi.it](mailto:nicola.forti@unifi.it)

**Irene Simonetti**  
Assistant Professor  
Department of Civil and Environmental Engineering (DICEA)  
University of Florence, Italy  
[irene.simonetti@unifi.it](mailto:irene.simonetti@unifi.it)

## Funding

Supported by the University of Florence through the HYDRAS project
(CUP B13C25004820001).
