# Coding Large Models (and components) from scratch

## What is this

This repo contains pyTorch code of different components of Large Models.

Currently, we roughly follow along the textbook: [Build a Large Language Model (From Scratch) -- Sebastian Raschka](https://www.amazon.com/Build-Large-Language-Model-Scratch/dp/1633437167), but will be implementing other papers in the future.

## Progress

- Build a Large Language Model (From Scratch) -- Sebastian Raschka (Current)
- Implemented [Simplifying Transformer Blocks -- He et al.](https://arxiv.org/abs/2311.01906) (14/2/25)
    - Removes skip connection
    - Removes Usage of Value projection matrix (after the first simplified block)
    - Removes outward projection layer (since they mostly resemble identity matrix)