# 2021-2022-UROP-Marsh-Research

My name is Andy, and I a Civil Engineering student at UC Berkeley. During my third year, I had the opportunity to work in research. I helped Lukas WinklerPrins, a PhD student, and Mark Stacey, the Civil Engineering department chair, with their research at Whale's Tail Marsh studying wave attenuation in coastal marshes. This research was apart of a bigger research project of the USGS Pacific Coastal and Marine Science Center in Santa Cruz, CA, with data collected in summer 2021 during some of the highest tides of the year.

My work was to look at data from various sensors at the marsh. The main sensors I dealt with were pressure sensors on the marsh top. There were 6 sensors in total each going more inland: one on the mudflats near the marsh (BT0) and five on the marsh top (BT1-5). In my analysis, however, I did not use BT0 as that would have complicated the understanding of wave attenuation (traveling over a marsh scarp instead of just over marsh-top vegetation). These pressure sensors were able to extrapolate other metrics as well. The metrics I analyzed were significant wave height and depth.
Another sensor that I briefly looked at was the velocity sensor. This sensor records the velocity of the incoming waves in the three dimensions.
Unfortunately, the data could not be publicly published due to USGS protocol.

My research can be summarized with three Jupyter Notebooks I have created: "BT Sensors.ipynb" , "Velocity Sensor.ibynb", and Wave Heights Decay.ipynb".

"BT Sensors.ipynb" was the firs notebook I created, and it was mainly me exploring and understanding the data. In this notebook, I plotted depth and wave height against time for all five sensors just to get a feel of what was happening on the marsh. I also explored plotting significant wave height against depth to look for patterns. Through this we also stumbled upon a cutoff depth of 0.1m where the sensors were giving us zeros for wave height when the depth was below the cutoff.

"Velocity Sensor.ipynb" was the next notebook, and this was me exploring the velocity data. I didn't do much here except plotted veloctiy in the three dimensions against time. I also plotted velocity in the first dimension against the second dimension.

Lastly, "Wave Heights Decay.ipynb" was the notebook where we wanted to find out what wave attenuation would fit the best for our marsh and if the K constant in those models, which dictating how fast the wave attenuates, changes over time. The models I compared was an exponential one from Kobayashi Et al. and an inverse one from Lei and Nepf Et al. For the first question, I looked at the average wave height on all sensors during innundation periods and use curve fitting to fit those models to the data points. An exponential function worked best for our marsh. For the next question, I fitted the exponential model to wave heights of many time periods and took the K value from each curve fit. I then plotted it and discovered that it had an inverse relationship with depth.


All this was made possible because of Lukas who put in an incredible amount of time to mentor me and guide me through everything I was doing. He really taught me a lot and made it very fulfilling for me as I completed the research this year. Thank you!

Finally, here are the references we used: 

Dalrymple, R. A., Kirby, J. T. & Hwang, P. A. Wave Diffraction Due to Areas of Energy Dissipation. Journal of Waterway, Port, Coastal, and Ocean Engineering 110, 67–79 (1984).

Foster-Martinez, M. R., Lacy, J. R., Ferner, M. C. & Variano, E. A. Wave attenuation across a tidal marsh in San Francisco Bay. Coastal Engineering 136, 26–40 (2018).

Kobayashi, N., Raichle, A. W. & Asano, T. Wave Attenuation by Vegetation. Journal of Waterway, Port, Coastal, and Ocean Engineering 119, 30–48 (1993).

Lei, J. & Nepf, H. Wave damping by flexible vegetation: Connecting individual blade dynamics to the meadow scale. Coastal Engineering 147, 138–148 (2019).

Mendez, F. J. & Losada, I. J. An empirical model to estimate the propagation of random breaking and nonbreaking waves over vegetation fields. Coastal Engineering 51, 103–118 (2004).

Möller, I. et al. Wave attenuation over coastal salt marshes under storm surge conditions. Nature Geosci 7, 727–731 (2014).




