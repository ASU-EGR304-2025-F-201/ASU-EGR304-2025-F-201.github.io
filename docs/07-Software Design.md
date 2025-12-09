---
title: Team Software Design
---

## Introduction
To showcase our our subsystems will communicate and function together, we created the following software diagram, using the UML format. Below in **Figure 1**, each of our subsystems' pseudo-code is laid out to give an understanding of the process each system will complete, and how they will communicate with each other. A brief summary is that both the light and moisture sensors will take their readings, and send outputs when needed to then control the motor and buzzer subsystems, to water the plant and alert the user, respectively.

## Team Software Diagram

Our software diagram in draw.io can be found ["here"](https://viewer.diagrams.net/?tags=%7B%7D&lightbox=1&highlight=0000ff&edit=_blank&layers=1&nav=1&title=EGR304%20Software%20Design.drawio&dark=auto#R%3Cmxfile%3E%3Cdiagram%20name%3D%22Page-1%22%20id%3D%22XCvLQIIv3M2afVEnnrfr%22%3E7V1bd6I6FP41rnXOg13cL4%2FW3madzpqesZ3OPFJNMVMkFrDa8%2BtPkIsSI0JIQKd9KoQk4M7%2B9t75spP21OFsdR048%2BlXNAFeT5Emq5560VMURdZV%2FCcueU9KZFO3kxI3gJO0bFMwgv%2BBtFBKSxdwAsJCxQghL4LzYuEY%2BT4YR4UyJwjQsljtGXnFt84dF%2BwUjMaOt1v6CCfRNCm1dGlTfgOgO83eLEvpk5mTVU4LwqkzQcutIvWypw4DhKLkarYaAi%2BWXiaXpN3Vnqf5hwXAj6o0%2BNey%2FH%2FG6BUF3t3E8c7vbHPap%2FSSFoXReyaDAC38CYi7kXrq%2BXIKIzCaO%2BP46RIPOy6bRjMP38n4Mmn95niLtHVaAIIIrLbekH7kNUAzEAXvuMp0S45GJrXlRui5JFNd0tJbJx1iN%2B9qIwV8kQqihlCUUxTKqmUhaScsJE3jLyQoQffGRfDpYSWtrv4Nw9v%2Bj35mxcBkx8rsig0tgjEo62xHvHG3o%2FQWBdEUuch3vMtN6XlxADZ1bhGap2L%2FDaLoPTW8ziJCxUEBKxj9jJuf6endr60nF6u05%2FXNe3bjY9ltNYpvf20%2F2zRb32XtUvPuBC6ISuSg0ZUgAJ4TwbeinPmPaD21lxnUfgT8EAW47DsIsSBYQKDuYsAm7IRVhICsi8KAzQYB8%2B5qsDR%2BoAfX1YcDxzOmb%2FPMMn94COxRgcoQSJveIYhHINcJVdGLOiEROpGMT9qKUIv8MxpgS%2BZoLbVPVVnLQe%2FSWtYMElis5X3gjF9w0XAaSwJf3MMZYDKaWm2jmccV%2FN2MwhEK%2BicU1nIwuoSCLh4KwymgQUFyXAf6YbSOKJ4Bfv%2BYDSD6LkByF5EhxCy6kBxB%2FBGickSI8YmQtRzMLhFitOAsnBcQ4qIB1nxnDZFzEC0B8HuxJTc8%2FNpziC%2Fc%2BMLPShZZyVYt%2FAvz4gA4E%2Bi74dYzuGnCB2i2TuDMPCsiTTU5II0adOscgWZ2CTR5C2Yb0B0AmlyA2QZ13QbwVQf09UuwfHsBwLXk89fXB%2FU3ul32lT9mRNlMZ9MRpQq1KSuxbjoIAud9q8I8nmqFWz3vzNisghHQJYIDJuprBDtYt75sWYT2JV%2B8p7VBts6NVvYDE7EKm1Ga9VwKC0k5Av4k4WoWXjJUXNgawtwTEw%2BNB1tDpXVrhqlHResaBn9al%2BoRefIU3dpPFo%2FY2H4OHn59f7y5nl%2B%2BhZePL2%2FD18jmRGnVtZ8KqTGGXmoPyfq6Vm4%2FDbNZfdkqfE%2FR3jIYSSrkW4i7b9dAVqSM2mYxAIcXBPs86BiqiGr6ERYRfUUwjBYBECelPSuE4qRmtSG1SJykyGVCcZKyxUtqNAd48itMVqTvFScrRWPzvvT8B2lHzEc%2FfWnK%2FNAF0daMtHQYygGAO4LzEBxWfiecJ7lAz3AVjxOnGJQSp6tFFNhFToYHJUOVl2rxxEAniQUV9VI1qWPXmaK2sP5%2FHS%2F6S4PZ3IPPEMSTyzx8gi4WMZPu0ihFwoITi7%2BqKOXVGZl7%2BoConRjwPcZYrm2M98%2BFeOo80%2BRIlonJi3Vg8kJYP6L%2BAbJo39sEUEWlitQCV3SLllugvoAujGJUN4H34bVrAt6aMN%2BkMLIj9FHpNo2DiR6pZxKwSgziPGV86yMfJCVXMJZ5rfjN7sJEaOQaVAk9zAuorKsXx6hfLcT%2FvPTL6jTsqpZINEWzp0XYFiWt6js2t3w6oBrCbK7BExPWn46JqjqvdqrzlegzrLBRUZA03Q%2BjAL2AIfJQsLEDz9gIEEWOh0MQfDvGbwS4%2FDyGBBw73iB9MIOTCWW8dwGln%2F9AXpRsronjHf2CDWOUlCO5CDKdCGxkXdCAaFwDG7sTkHFbwzlGEqkSi3oKgLnBABCImD4x1VLFbRLiyVOpnSyVVlR97bh4KrWFFasBFiNyY%2BGgwjR2iHyssyFEPpMC12aq8r2i%2FJkqxu1bpRpyHEwVrxCprc1YpSJtI6maC01TX7ctUdGMznUa3S0LWzNHkyUftK0IiI2pJbLuNbucqSXry3pJmslua2JZXCfDhz3bxHY7suifIYDyvbcsLVj9HgbX34wrU3Kvwu8%2F%2B0qqtenZAc5TpruVViNdrL%2FzghpzpBYofC651cIk8jh47LSgiqnSXqRSAW%2FbD%2ForurEfnVIOdEG0tQOjdBiqDyyvlZFHB8aG4Xm97%2FmLP1%2BI2vdctDjkGhM%2FSVZJUmmImQ%2B4ra9EazvDDCVjuj5mWCLTLz6MoOPFIyUUK%2FxFVoWtbgiOE9yWIgYcTdcFm400ZYLWDjiyaRu7Lzm8pE5Gr8KcSRUWrSFeuqGjjw8v%2BzSjJbxQKOx28DLCklmnmMW98MJLPmXheV4CXR5VmLpmEKElpB45RBrvXRUTbzFxHFnWILGWvpdbkOlr71Xr23UYEV0hN2OLS14r1c0u7AZW5CZm4%2FBedwEnSlCzLhlzKMoyOE91dbeUHeg4LdUkVi%2BJPXJ16zdOUisb%2FxPLVzLIQ%2BGMnQ3b3PbQ1tnFczoet3FQWnbsHWfgcTv%2F7XBH5NSInzssk9ep7yZSCcvFI2WbenZFJUKG4vqonX1AKl%2FIgSCNRrTmZobjoB9lqRj4aTZ5yBGP2I%2BOAJMjAv74nPKKCGjr6MmyQRC5naewaAV5LlrJUj6jzLFgnZGr9qbCIzqjHxHFEw8fcKGKLtS2DqAsG4U2cqXax0K%2BE4m%2FJ%2BWJhI7PmVS2oSBVhEJTLuH4XEMLB958m6%2FPlMQl%2BMekx0JO4Ft2KuRfAYqcKD7rZZYcYCKNPTR%2BWcIQ%2FL11iuRWCyY06bszfgqayH%2BGwCOdlg4lxmxwamcdL%2FCaDFBqTMcfH5TaSMD1UAhqYcnxI9jvDlC6Tk5bBEKqzp6kjqCiFrFyZpuKkCgs7uQOBBBLNt6KUwdDnQZmSjV%2FdGxksa4Sa16SsBCM8cSnUmmf0BHEgmYjNlVTuLPKOrGlQc3WIOuyyoZkl1tVfqxyqcBOcn%2FhPZxlfvAZraW6%2BWbjdYGyB%2F1wrcIDXEGW56t1V9nzzHXGvhZfO7P4l6SuFQ%2FSxs0mb2jgZynTQIuwPjtOVuWRf0W3Pzzp8W7tj3Q89idzH8LtD%2BmnWO2PZsud2h%2B1EoPzMexPanz8pzD%2B07tUepbdG%2Bjt2yHyjHOBVsjmaIXUT072CCL%2FjHnh41g%2BYArvfk6i7awkMjhVyw6%2FO%2BwR8O3mPwMn1Tf%2FYFm9%2FB8%3D%3C%2Fdiagram%3E%3C%2Fmxfile%3E)

![Software Design](../image/Team201SoftwareProposal.png)

**Figure 1:** Software Diagram


## Conclusions
There are many prospective issues with this proposal that we wish to address. Since this is a project for the EGR 304 class, we need to maintain the class project requirements and build our system so that it can be demonstrated in a lab setting. However, for an actual product, we would ideally make several changes. First, the light sensor would not alert the second it receives low light, but instead measure the readings over a day's time and report its findings to the user the next day, so they could consider moving their plant to receive more sunlight. Then, the buzzer subsystem would most likely be replaced with a connection to an app, where, instead of audio alerts, the app would send push notifications to the user so they know the status of their plant without being annoyed by constant sounds coming from the device.

## Top 5 Changes to Design
1. At the time of testing the components for the moisture sensor had not been received so the code was designed to simulate changing moisture levels so the data transmision to different subsystems could be observed.
2. The software design originally featured a buzzer, but after we were told that did not satisfy the complexity requirements of the project, it was switched back to a speaker subsystem.
3. The light sensor subsystem originally featured a transistor, but this would have given a digital signal, not an analog signal. Therefore, the system changed to featuring just the op-amp amplified signal straight to the microcontroller.
4. .
5. .

## Version 2.0
- **Light Sensor:**
- **Moisture Sensor:**
   The next version of this moisture sensing subsystem will be powered by a lithium potassium battery to allow for testing outside. An LCD display will be added to allow the testing team to easily check the readings the micro controller is recieving. A plastic housing will be 3d printed to protect the internal components from water and soil durning testing. The code will be reworked to allow full fuctionallity of the sensing, data display and data transmission.
- **Motor:**
- **Speaker:**


