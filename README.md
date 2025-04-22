Beer Carbonation Calculator for Pressure-Fermented Lagers

This project was born out of challenges encountered during the carbonation of pressure-fermented lagers. The goal is to calculate the amount of CO2 in beer that was naturally produced by yeast during fermentation, and determine how much additional CO2 is needed to reach a desired carbonation level. The calculator leverages principles such as Henry's law to estimate CO2 content based on pressure and temperature.

Background

Inspired by the concept of fully spunding (using only CO2 produced by yeast during fermentation to carbonate the beer), I experimented with setting the spunding pressure to the maximum limit of my container (2.5 bar) for the last few points of gravity. This resulted in beer with carbonation levels around 1.8-2.0 volumes of CO2, or less. While this method can carbonate beer to a degree, it often requires additional CO2 to reach higher carbonation levels, especially as blindly force carbonating beer that’s already at 1.8 volumes can be risky.

Most available resources on carbonation focus on flat beer, offering quick methods with vague details on pressure, time, or equilibrium. Larger breweries tend to use weight (CO2 transferred from a tank to the beer) instead of the temperature-pressure-time methods, allowing for faster CO2 dispersion at much higher pressures.

Objective

This calculator aims to determine the existing weight of CO2 in a fermentation vessel based on the current pressure and temperature of the beer, and then estimate the additional CO2 required to achieve the target carbonation level. The calculator doesn’t include CO2 in the headspace for now and assumes the beer is cold crashed, with the CO2 content calculated at equilibrium temperature before being converted to standard conditions (0°C, 1 atmosphere).

Theory

The carbonation process is governed by Henry's Law, which describes how much CO2 can dissolve in beer at a given pressure and temperature. The calculator estimates the CO2 content in the beer, and based on the pressure set by the spunding valve, determines how much external CO2 (if any) needs to be added to reach the desired carbonation level.

This approach uses a simplified CO2 calculation for standard temperature and pressure (STP).

Some of the reading and resources i've used for the project so far:

https://www.youtube.com/watch?v=VBYhYXIBR1c&ab_channel=FlaminGalahBrewingCo

https://en.wikipedia.org/wiki/Henry%27s_law

https://www.morebeer.com/articles/Spunding?srsltid=AfmBOorU-IDInq5HOttrdcPpWxOextuxopVTmRgh_V-XzhTe2oLN-HDC
