# CLRerNet: Improving Confidence of Lane Detection With LaneIoU

## Project Overview

This repository is dedicated to the research and development of a lane detection model called **CLRerNet**, which aims to improve the confidence of lane marker detection in autonomous driving systems. By introducing the novel **LaneIoU** method, the project seeks to achieve better alignment between the model’s predictions and real-world lane structures, especially by considering local lane angles.

Lane detection is a critical task in driver assistance systems and autonomous vehicles, where accurate prediction of lane positions can significantly enhance the safety and performance of these systems. **LaneIoU** takes into account the local angles of lanes, resulting in a more accurate assessment of the overlap between predicted lanes and ground truth lanes, compared to existing IoU-based methods.

## Key Features

- **LaneIoU**: A new IoU calculation method that improves upon standard IoU by incorporating lane angle information, enhancing accuracy in tilted and curved lane detection.
- **CLRerNet**: A lane detection model built upon anchor-based lane representations, optimized for generating high-confidence lane predictions using **LaneIoU**.
- Focus on improving lane detection benchmarks such as **CULane** and **CurveLanes**.

## Objectives

- Enhance the precision of lane detection models by improving confidence scores through the **LaneIoU** function.
- Develop a lane detection system that is reliable under various conditions such as curves and tilts.
- Contribute to state-of-the-art autonomous driving technologies by providing a robust lane detection framework.

## Demostration
https://youtu.be/77t6vMTwaGA
