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

This repository includes code, supporting figures, and external media for simulation-to-hardware validation of the QArm pick-and-place pipeline.

### Videos
- [Physical QArm pick-and-place demonstration video 1](https://howardu-my.sharepoint.com/personal/fadel_lashhab_howard_edu/_layouts/15/stream.aspx?id=%2Fpersonal%2Ffadel_lashhab_howard_edu%2FDocuments%2FAttachments%2FIMG_4622.mov&ct=1776307582383&or=OWA-NT-Mail&cid=f9effcf7-02c5-2868-c4e6-745720dfecf5&ga=1&LOF=1&startedResponseCatch=true&referrer=StreamWebApp.Web&referrerScenario=AddressBarCopied.view.1be5ce60-85c6-468a-9cc7-7cc1e386b39c)
- [Physical QArm pick-and-place demonstration video 2](https://howardu-my.sharepoint.com/personal/fadel_lashhab_howard_edu/_layouts/15/stream.aspx?id=%2Fpersonal%2Ffadel%5Flashhab%5Fhoward%5Fedu%2FDocuments%2FAttachments%2FIMG%5F4594%2Emov&ct=1776307972195&or=OWA%2DNT%2DMail&cid=8bc11b83%2D8e1e%2D55e6%2D90b7%2Dcf3465e81c69&ga=1&referrer=StreamWebApp%2EWeb&referrerScenario=AddressBarCopied%2Eview%2E475a2684%2D7140%2D413b%2D95e9%2D61a4f376fd92)
- [Physical QArm pick-and-place demonstration video 3]([https://howardu-my.sharepoint.com/personal/fadel_lashhab_howard_edu/_layouts/15/stream.aspx?id=%2Fpersonal%2Ffadel%5Flashhab%5Fedu%2FDocuments%2FAttachments%2FIMG%5F4595%2Emov&ct=1776308065401&or=OWA%2DNT%2DMail&cid=6ac0a535%2D5a73%2D0ce4%2D68e4%2D874748ee6025&ga=1&referrer=StreamWebApp%2EWeb&referrerScenario=AddressBarCopied%2Eview%2Ee61f0a50%2Dd1fb%2D46d4%2D86bc%2Dffce1728e984](https://howardu-my.sharepoint.com/personal/fadel_lashhab_howard_edu/_layouts/15/stream.aspx?sw=bypass&bypassReason=abandoned&id=%2Fpersonal%2Ffadel_lashhab_howard_edu%2FDocuments%2FAttachments%2FIMG_4595%2Emov&ct=1776308270191&or=OWA-NT-Mail&cid=952ab4df-364f-a281-6ff5-f24387187a7b&ga=1&startedResponseCatch=true&referrer=StreamWebApp%2EWeb&referrerScenario=AddressBarCopied%2Eview%2E738d3b2d-d903-4c89-be49-930f88301fc9))
