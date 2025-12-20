---
layout: project
title: Heat Exchanger Analysis
description: Class Assignment
technologies: [GitHub]
image: /assets/images/thermo-portfolio-0.jpg
---
**Heat Exchanger**
Group Members: Monna Li and Stephanie Cheng

**Photos and schematics of the device or system:**
(we forgot to take photos so our photos are from a friend who went on a different day)
![Photo]({{ "/assets/images/thermo-portfolio-1.jpg" | relative_url }}){: style="width: 600px"}

**A qualitative description of the device or system:**

The device we chose to look at was a heat exchanger. It has four ports, labeled 1, 2, 3, and 4, where 1 flows to 2 (and vice versa) and 3 flows to 4 (and vice versa). There is one cold water reservoir, consisting of a bucket with ice water placed inside styrofoam insulation, and one hot water reservoir, consisting of a bucket with water and an attached immersion heater.
![Photo]({{ "/assets/images/thermo-portfolio-2.jpg" | relative_url }}){: style="width: 600px"}

**A system diagram of the device or system operating (either CV or CM), showing work and heat transfer interactions as well as any relevant mass flows:**

![Photo]({{ "/assets/images/thermo-portfolio-3.jpg" | relative_url }}){: style="width: 600px"}

**Mass balance, energy balance, and entropy balance equations (as relevant) capturing the physics more central to the device or system operation:**

![Photo]({{ "/assets/images/thermo-portfolio-4.jpg" | relative_url }}){: style="width: 450px"}
![Photo]({{ "/assets/images/thermo-portfolio-5.jpg" | relative_url }}){: style="width: 600px"}

**Describe a change to device or system design or operating conditions and then how that change influences device performance:**

![Photo]({{ "/assets/images/thermo-portfolio-6.jpg" | relative_url }}){: style="width: 300px"}

We started by running the system in parallel flow, then changed the set up to run it again in counter flow. In parallel flow, the two pumps and reservoirs are put on the same side of the heat exchanger so that water from the cold and hot reservoirs flow in the same direction. In counter flow, one of the reservoirs is put on the other side of the heat exchanger, pumping the water such that it flows in the opposite direction of the other reservoir. This change influences device performance because in parallel flow, both lines start with a large temperature difference and approach the same mean temperature in which there isn’t a lot of heat exchange. Meanwhile in counter flow, the gradient of hot to mean versus cold to mean occurs in opposite directions such that there will be a more consistent large temperature difference and thus more heat exchange occurring.

**Where might you find a heat exchanger used in the real world?**

Heat exchangers are used in the real world in fridges, during which cold refrigerant acts as the cold reservoir while the air in the fridge represents the hot reservoir. As the hot and cold substances flow alongside each other the heat energy from the air transfers into the refrigerant thus making the air inside the fridge cold and keeping our food fresh.

**Is the heat exchanger actually operating in an adiabatic manner (following our typical assumption)? How does this feature (or lack of this feature) influence function in the real world application you’re considering?**

![Photo]({{ "/assets/images/thermo-portfolio-7.jpg" | relative_url }}){: style="width: 300px"}

The heat exchanger is not operating in an adiabatic manner because if you compare the amount of heat energy entering the cold water to the amount of heat energy leaving the hot water, you find that its efficiency is not 100%, meaning that all of the heat leaving the hot water didn’t actually go into the cold water but rather also into the environment. Additionally, while our data didn’t reflect this, if the efficiency is over 100%, it means that heat is entering from the environment and heating up the cold water which similarly means the system is not adiabatic. The lack of this adiabatic feature influences function in the real world because we would need to over-compensate for the heat that is both entering and exiting out into the environment. This means that we would actually need more refrigerant flow to cool the fridge since some of it is lost to cooling the nearby environment rather than entirely going towards cooling the inside of the fridge.

**Are you achieving steady state operation? Can you make adjustments to get there? Are the kinetic energy changes in the flow from input to output on each line?**

We are not actually achieving steady state operation because nothing is perfect in real life and there will always be slight fluctuations. For example, the temperatures of the hot and cold reservoirs were not perfectly constant since the insulation was not perfect (there was some heat transfer between the water and the environment). Also, the pump actually sucks up and releases water in pulses rather than as a continuous, smooth stream. This would cause fluctuations in the mass flow rate, meaning it’s not actually perfectly constant like we assumed. While we cannot really make adjustments to improve the pump, we can use better insulating materials for the hot and cold reservoirs or try to maintain a constant room temperature by carrying out the experiment in a carefully monitored room.
