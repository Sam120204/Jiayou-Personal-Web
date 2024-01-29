---
date: '2'
title: 'FlappyBird with NEAT'
cover: 'bird.png'
github: 'https://github.com/Sam120204/FlappyBird---Python-with-NEAT'
tech:
  - Python
  - NEAT modeule
  - PyGame
  - Makefile
showInProjects: true
---

- Utilized the Python-NEAT module to enable AI to control the bird that can navigate obstacles and achieve endless gameplay autonomously.

- _How it works?_

  - NEAT stands for NeuroEvolution of Augmenting Topologies, which is a genetic algorithm designed to efficiently evolve artificial neural network topologies.

- _How NEAT applies to Flappy Bird?_

  - Note that all individuals belong to the same species because we found a solution before any topological innovation occurred.

  - From generation 0 to generation 4, all birds almost immediately hit the ground or the upper limit.

  - From generation 5, NEAT started to know how to keep the bird flying, but it still didn’t figure out how to get through the pipes. At generation 9, a huge breakthrough happened: a bird learned how to pass the pipes and became the skilled player
