---
title: Software Proposal
---

## Introduction
To showcase our our subsystems will communicate and function together, we created the following software diagram, using the UML format. Below in **Figure 1**, each of our subsystems' pseudo-code is laid out to give an understanding of the process each system will complete, and how they will communicate with each other. A brief summary is that both the light and moisture sensors will take their readings, and send outputs when needed to then control the motor and speaker subsystems, to water the plant and alert the user, respectively.

## Software Diagram

Our software diagram in draw.io can be found ["here"]()


<img width="891" height="681" alt="EGR304 Software Design drawio" src="https://github.com/user-attachments/assets/ba607a58-4dff-4b08-8721-0c8017a5672e" />

![Software Proposal](../image/EGR304 Software Design.drawio.svg)

**Figure 1:** Software Diagram


## Conclusions and Future Work
There are many prospective issues with this proposal that we wish to address. Since this is a project for the EGR 304 class, we need to maintain the class project requirements and build our system so that it can be demonstrated in a lab setting. However, for an actual product, we would ideally make several changes. First, the light sensor would not alert the second it receives low light, but instead measure the readings over a day's time and report its findings to the user the next day, so they could consider moving their plant to receive more sunlight. Then, the speaker subsystem would most likely be replaced with a connection to an app, where, instead of audio alerts, the app would send push notifications to the user so they know the status of their plant without being annoyed by constant sounds coming from the device.





