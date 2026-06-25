This repository contains the Unity project and related materials for the paper "Aligning Movement and Modality: The Interplay of Locomotion and Sensory Cues in Non-Visual Virtual Reality"

Abstract:
Virtual reality (VR) heavily relies on visual feedback, creating spatial navigation barriers for blind and low vision (BLV) users. We present a 3x3 within-subjects experiment (N=18) evaluating three ubiquitous locomotion techniques (sliding joystick, teleportation, arm-swinging) paired with non-visual directional guidance from off-the-shelf hardware (audio-only, vibrotactile-only, combined). A mixed-methods analysis reveals that BLV users can independently navigate in VR with a high overall success rate (88%). However, efficiency heavily depends on mechanical alignment: continuous movement benefited from ecologically grounded audio, whereas discrete teleportation relied on vibrotactile cues to avoid wandering, despite unimodal vibration inducing high cognitive load. Participants also demonstrated a strategic speed-accuracy trade-off, prioritising navigational momentum over rigid path adherence as they adapted to multimodal redundancy. We conclude that accessible non-visual VR requires aligning locomotion continuity with matching sensory feedback and offering customisable options, rather than relying on a singular optimal technique.

Project Overview:
This Unity project contains the Unity virtual reality environments and experimental setup described in the paper. It was created to investigate how blind and visually impaired users use 3 locmotion methods (sliding joystick, teleportation, arm-swinging) with 3 types of non-visual feedback (audio-only, vibration-only, combined). Vibrations require a bHaptics vest.

The main scene includes the complete experimental procedure, 3 virtual routes, and data logging components.
The training scene contains the complete training procedure and training environment.

System Requirements:
Unity Version: 6000.3.3f1

Target Platform: Meta Quest with Link Cable

Hardware:
VR Headset: Meta Quest 2, Pro, 3

PC: Windows 11

Dependencies & Plugins
This project relies on the following packages and plugins. Please ensure they are installed correctly.

Unity Packages:
Meta XR All-in-One SDK
bHaptics Haptic Plugin

How to Run the Experience
Connect Your VR Headset: Ensure your headset is connected to your computer and recognised (e.g., via Link cable).

Ensure bHaptics vest is connected to PC - use bHaptics Player to complete setup.

Select the configurations for training/test.

Enter Play Mode: Press the "Play" button at the top of the Unity Editor.

Press the trigger to begin opening voice instructions.

Press the trigger button to start training/testing procedure. This will generate the first free training or first target.

Follow audio, vibration, or combined audio-vibration to reach current target (2 min limit default). Once all 3 targets reached, point to the starting position and press the grip button.

Once ready to move on to the next route, press grip + trigger button at the same time.

Once all routes are complete (9 routes), the program will automatically exit and the logs file will open on your connected computer.

Controls:

[Controller Right Analogue Stick]: Move in tilted direction (sliding joystick)

[Controller Trigger Button]: Start training/testing phase. Teleport

[Controller Grip Button]: Select starting location

[Controller Grip + Trigger Button]: Move on to next route (only after current route finished)
