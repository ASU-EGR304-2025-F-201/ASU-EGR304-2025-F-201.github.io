---
title: Team Software Design
---

## Introduction
To showcase our our subsystems will communicate and function together, we created the following software diagram, using the UML format. Below in **Figure 1**, each of our subsystems' pseudo-code is laid out to give an understanding of the process each system will complete, and how they will communicate with each other. A brief summary is that both the light and moisture sensors will take their readings, and send outputs when needed to then control the motor and buzzer subsystems, to water the plant and alert the user, respectively.

## Team Software Diagram

Our software diagram in draw.io can be found ["here"](https://viewer.diagrams.net/?tags=%7B%7D&lightbox=1&highlight=0000ff&edit=_blank&layers=1&nav=1&title=EGR304%20Software%20Design.drawio&dark=auto#R%3Cmxfile%3E%3Cdiagram%20name%3D%22Page-1%22%20id%3D%22XCvLQIIv3M2afVEnnrfr%22%3E7V3fd6I6EP5rPOfeB3uAAMKjtb%2F23O7Z3rXd7j5STTFbJBaw2vvX3yCgEiNCSEC3fWklJGAn881MvpmkHTCYLq8DZzb5isfQ62jKeNkBFx1N0wCwya%2B45T1pUS0DJC1ugMZp26ZhiP6DaaOSts7RGIa5jhHGXoRm%2BcYR9n04inJtThDgRb7bM%2Fbyb505LtxpGI4cb7f1EY2jSdJqGcqm%2FQYid5K9WVXSO1Mn65w2hBNnjBdbTeCyAwYBxlHyabocQC%2BWXiaXZNzVnrvrLxZAPyoz4F%2FL8v8Z4VcceHdjxzu%2Fs3uTLuMpaVMYvWcyCPDcH8P4MUoHnC8mKILDmTOK7y7ItJO2STT1yJVKPiaj3xxvno5OG2AQweXWG9IveQ3xFEbBO%2Bky2ZKjmUltsRH6WpKpLunppZNOsbt%2B1EYK5EMqiApC0U5RKMuGhaSfsJB0XbyQkILcGxejp4elsrz6Nwxvuz%2B6mRWD4x0rsys2PA9GsOhhO%2BKNHztML3EQTbCLfce73LSe5ydg0%2BcW41kq9t8wit5Tw%2BvMI5yfFLhE0c94%2BJmRXv3aunOxTJ%2B8unjPLnwiu61B8eWv7XubYaurbFxq3p3AhVGBHHS2EgTQcyL0lpez%2BBmtpvYqh9oPoR%2FigLR9hyERBA8IwC4GbMpOWHkIqIYsDNh8EOjdXfUX5g%2F84LrGoO945uRtllnmDw%2BBPSpQGgLp0DuMyAysdQJoRl4nFEonkvlJR1Fqsf4aNbClCrSW%2BqeqrORgtGktKwYJPNbyPnBGL6RpMIklQT7coynkMpp6ZaO5jivEuxlNIBSMTyis5GC2CQVDPhQGE8iCguK4DvLDaBVRPEPy%2FhEfQIxdgKxdRIaQXt6FrBEkHiFAIELMT4Ss5NBrEyFmA87CeYEhaeoTzXdWEDmH0QJCvxNbctMjrz1H5IMbf%2FCzlnnWstWL%2FIXr5gA6Y%2BS74dY9tBkiBmi2QeGsd5ZHGugJQBoz6DYEAq3XJtDULZhtQHcAaGoOZhvUtRvAl53Q1y%2FB4u0FQtdSz19fH8BvfLvoan%2FMjPKZzrozyhRqXVZiNbQfBM77VodZvNQKt568s2KzckbAUCgOmOqvA6VWf9WyKO1LvvGe0SY9em20sj8wEau0FWWvmkvhISmH0B8nXM3cS6ZKCFtDmXtq4aGLYGuYtG7FMPWoaF3TFE%2FrMj2iSJ6iXfvJ4xFr28%2F%2Bw6%2FvjzfXs8u38PLx5W3wGtmCKK2q9lOjNcY0Cu0h3d%2FQi%2B2n2avXX7Vy3ydvbzmMJBPyDcTdtysga0pGbfMYgMMJwa4IOoYpoop%2BhEdEXzEKo3kA5UlpT4ZQntSsJqQWyZMUnSaUJylbvqSGM0gWv9JkRfteebLSdD7vy65%2FUHbEfPTLl7rMD1sQTa1IC6ehGADkQWgWwsPK74SzpBboGS3jeRIUgzLidJBHgZ3nZERQMkx5AUskBlopLCipl6DHnLvWFLWB%2FP91nPRX7gPHD0lIsKoEGCKXyJZLaVlcImW6qawvkKW1Bidlz54J0Irl3mOF1cpWeP8iSKSyc62KVJVatVgHVi2U2aP6H2CJ9r1NAkdUqEgNkES3eBH%2FzBZD%2FKA%2BnKqmQK1Lc0UaJxnCnot2qza42JBqhoAoQj8uSyaXPvZh0nKFYplXCtfsNgyDTqecCthgUfDkTVYco341EO6L0i%2Br1SirXN3QBE%2Bf5mFTDDQwdmxucfQPTGk21xSJCetPx0RZnQet6nwptowobJQXJEv3wyjAL3CAPbJ4WNuBZ2IEqCbHIyEIuRyRN0LSfh5DAo0cr5%2FemKLxmDHfu4Ayzn9gL0r20sRRjnHBhzFGhZGaB5lBBTaqIWlCdKGBjd0KyISlbI6RMypFmp4CYG4IACQipkstsIC8PUEiaSnQSma0pOrrx0VLgQYSVH0iRuzGwsHkxwVyURSvXpUB9onOhgj7XApcmZ9abw0Vz09x7tYq1JDj4KdEhUhN7b0qFGkTNdQb%2FW6Se9UsWdGMIXQZ3S73WrEkk6f8s6kIiI%2BfpYrsdbuYn6X7q0ZBVcnuaCoLbtDhw55dYbsPsthfQwLRe29ZerD8PQiuv5lXPcW9Cr%2F%2F7Gqp1qZHBThPme6WSj66RH9nOTUWSC0w%2BFx6Z0WPKtsQsbGCKaZSW48KBbxtP9ivaMd%2BtEo5sAXR1IaLwmkoP7Gi8iGPDooNw%2FMqufnFn81lbXPOWxw6syROkmVqUmpi5gPu4ivQ2tYwwyiQro4Znsj0i48i5HjxTEnFiniRlWGra4LjBHehyAFH3bxgvZlmLNCaAUe2bOP3JYdT6nT0Ks2ZlGHRauKlHTr6%2BPCyTzMawguDwm4GL0MimVUNSvwUUXhZL1lEHo%2FAlkcZpq4eRFj1p0cOkdpbVeXEW1wcR1YrSOXS93ILKjv3Xra%2FXYURMTR677W8krVC3WzDbhBFrmM2Dm9tl3CABLPWkrOGoqhus%2B1UVeEqv%2FlUVZGoTqy0x6SPSzN3tjIL211aZX%2FL6Tin2vFb0YFwggumhZ2MdvhB9CpCnOcoktep77MBVEmDiOpm5qkOpbgLhpdgPuwDst5SjsqoNaMVq%2F2Pg6lTlXyMpNv08T8iwiQ2AnoCEfDHl1%2BXREBThzIWTYLM%2FS65%2FA4Smd9RlfXia40F64xOcPc0EdEZ%2B%2FAkkXj4gDkdtlCbOpqxaBaaKCtqHgvrTTviPalIJLR8AqO2DQWlJBTq0m3H5xoaOArm22x12iJpIX9MemDiGL1l5yX%2BFeDIieJTUKbJ0R7KyMOjlwUK4d9b5ytujeBCk7G74megif43ASIqT9lQ4iycZj6s5VxojwNKtZnr44NSE7WqHg5hJSw5foS67QHKMOhli0RIVdm%2B0xJUQB4rZ3ZPkxKFxQ%2B5gwEiko13rVTBUKuBmVbOHx0bWWwAKj2kSAvBOM9CKpT2CR3OK2k1YjM1RTirbFDV%2FyBL11VllU3FLraq4ljlQoGd5Fa8ezTN%2FOAzXkl1853N1znObnTDlQr3SQdVnS1Xj8ruZ64z9rXkszON%2F5LUtZJJ2rjZ5A01%2FCxjGWhR1mfHyQIRpUps%2ByOSHm%2FX%2FijHY38y9yHd%2FtB%2Bitf%2B6Lbaqv0BpRicj2F%2FUuPjP4Xxr86l1rHsTt9o3g7Rp39LtEK2QCsEPjnZI4j8M%2BZFjGP5gNWu%2BzmJpiv56OAUFJ0Od9gjkMvN%2F8xNum%2F%2B9TC4%2FB8%3D%3C%2Fdiagram%3E%3C%2Fmxfile%3E)

![Software Design](../image/Team201SoftwareProposal.png)

**Figure 1:** Software Diagram


## Conclusions
There are many prospective issues with this proposal that we wish to address. Since this is a project for the EGR 304 class, we need to maintain the class project requirements and build our system so that it can be demonstrated in a lab setting. However, for an actual product, we would ideally make several changes. First, the light sensor would not alert the second it receives low light, but instead measure the readings over a day's time and report its findings to the user the next day, so they could consider moving their plant to receive more sunlight. Then, the buzzer subsystem would most likely be replaced with a connection to an app, where, instead of audio alerts, the app would send push notifications to the user so they know the status of their plant without being annoyed by constant sounds coming from the device.

## Top 5 Changes to Design
1. At the time of testing the components for the moisture sensor had not been received so the code was designed to simulate changing moisture levels so the data transmision to different subsystems could be observed.
2. .
3. .
4. .
5. .

## Version 2.0
- **Light Sensor:**
- **Moisture Sensor:**
   The next version of this moisture sensing subsystem will be powered by a lithium potassium battery to allow for testing outside. An LCD display will be added to allow the testing team to easily check the readings the micro controller is recieving. A plastic housing will be 3d printed to protect the internal components from water and soil durning testing. The code will be reworked to allow full fuctionallity of the sensing, data display and data transmission.
- **Motor:**
- **Speaker:**


