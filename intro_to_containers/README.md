Introduction
Modern software development requires environments that are predictable, reproducible, and easy to share. As applications become more complex, configuring systems manually leads to inconsistencies, hidden dependencies, and difficult-to-reproduce errors.

Containers address these problems by packaging an application together with its runtime environment in a lightweight, isolated unit. Instead of depending on how a machine is configured, containers provide a consistent execution context that behaves the same way across different systems.

This project introduces the foundational concepts of containerization using Docker. The emphasis is on understanding how containers work, what problems they solve, and how their behavior differs from traditional execution environments.

Context
Containers define a specific way of running software:

Applications execute inside isolated environments.
Filesystems are composed of immutable layers with a temporary writable layer.
Processes have a defined lifecycle that starts and ends explicitly.
Data persistence must be configured intentionally.
This project explores these characteristics through observation and reasoning. By interacting directly with containers, inspecting their structure, and modifying their behavior, you will develop a mental model of how containerized systems operate and why they are widely used in modern development workflows.

Learning Objectives
By completing this project, you will be able to:

Explain the differences between physical machines, virtual machines, and containers.
Describe the problems containers are designed to solve.
Install Docker and verify that the container runtime is functioning.
Pull images from a container registry and run basic containers.
Inspect containers and images to understand configuration, metadata, and runtime information.
Understand the purpose and structure of a Dockerfile.
Build custom images and reason about image layers.
Explain how Docker reuses or rebuilds layers during image builds.
Describe how containers move through different lifecycle states.
Distinguish between ephemeral container storage and persistent volumes.
Manage disk usage by removing unused Docker resources.
These objectives focus on understanding behavior, causality, and system design rather than memorizing commands.

Resources
The following resources are recommended for research and reference:

Official Documentation
Docker Overview: https://docs.docker.com/get-started/overview/
Docker Installation Guide: https://docs.docker.com/get-docker/
Docker Command-Line Reference: https://docs.docker.com/engine/reference/commandline/docker/
Dockerfile Reference: https://docs.docker.com/engine/reference/builder/
Storage and Persistence
Docker Storage Overview: https://docs.docker.com/storage/
Docker Volumes Documentation: https://docs.docker.com/storage/volumes/
Images and Layers
Images, Containers, and Storage Drivers: https://docs.docker.com/storage/storagedriver/
Supplementary Reading
Containers vs. Virtual Machines (conceptual comparison): https://www.redhat.com/en/topics/containers/containers-vs-vms
You are expected to use these resources to investigate, verify, and reason about container behavior rather than relying on surface-level explanations.