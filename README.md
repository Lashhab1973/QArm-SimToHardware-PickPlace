# QArm Sim-to-Hardware Pick-and-Place

Simulation-to-hardware validation of a model-based pick-and-place control pipeline for the Quanser QArm manipulator.

## Overview

This repository contains the implementation and validation assets for:

- Waypoint-based task sequencing
- Rest-to-rest cubic task-space trajectory generation
- Closed-form inverse kinematics
- Forward kinematic validation
- Simulation in Quanser QLabs
- Deployment via QUARC to physical QArm hardware

## Repository Structure

- `/simulation` — QLabs digital twin models
- `/hardware` — QUARC deployment models
- `/figures` — Figures used in the paper
- `/videos` — Experimental validation videos

## Associated Publication

F. Lashhab, "Simulation-to-Hardware Validation of a Model-Based Pick-and-Place Pipeline," 2026.

## Hardware Platform

Quanser QArm (4-DOF)  
Validated in both QLabs digital twin and physical AVRC Lab hardware.

## License

MIT License

## Citation

If you use this repository, please cite:

Lashhab, F., 2026. Simulation-to-Hardware Validation of a Model-Based Pick-and-Place Pipeline for a 4-DOF Robotic Manipulator Using Digital Twin and Physical QArm Hardware

## Experimental Media

A demonstration video of the physical QArm pick-and-place experiment is available at the following link:

[Hardware Demonstration Video (IMG_4622.mov)](https://howardu-my.sharepoint.com/personal/fadel_lashhab_howard_edu/_layouts/15/stream.aspx?id=%2Fpersonal%2Ffadel_lashhab_howard_edu%2FDocuments%2FAttachments%2FIMG_4622.mov&ct=1776307582383&or=OWA-NT-Mail&cid=f9effcf7-02c5-2868-c4e6-745720dfecf5&ga=1&LOF=1&startedResponseCatch=true&referrer=StreamWebApp.Web&referrerScenario=AddressBarCopied.view.1be5ce60-85c6-468a-9cc7-7cc1e386b39c)
