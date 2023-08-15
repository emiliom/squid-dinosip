# DINOSIP2023 - A Comparative Assessment Between Two Depth-Profiling Systems on Ocean Salinity, Temperature, and Velocity off Hawaiian Coast
By Elizabeth Pawelka, Mentored by Emilio Mayorga

## Quick Introduction to the Program and Author
During the Summer of 2023 I completed a 9-week program titled the Diverse and Inclusive Naval Oceanographic (DINO) Summer Internship Program (SIP) at the Applied Physics Laboratory (APL) at the University of Washington. At the time of the program I was going into my third year as a physics/astronomy major at UW, and was looking forward to learning more about the physical properties of the ocean, python coding, autonomous vehicles, and big data management in anticipation of overlap with future research on subglobal icy worlds in our Solar System and beyond in the field of Astronomy.

## What is the Abstract of the Project?
Argo and APL’s (Applied Physics Laboratory) EM-APEX (ElectroMagnetic Autonomous Profiling Explorer) floats are deployed to collect vertical samples of publicly available ocean data to improve general understanding of processes largely related to climate change ramifications, currents, and atmospheric-sea interactions. The global Argo network operates 3000 floats that dive every 10 days, capturing baseline CTD (conductivity, temperature, depth) measurements down to 2000m and velocity estimations based on distance displacement and time between float emergence at the surface. Comparatively, EM-APEX floats specialize in direct measurements of velocity using electrodes and rapid CTD sampling at a shorter 5–7 day interval, providing complementary higher resolution data. Our project will assess means of comparing and integrating trajectory, CTD, and velocity data from EM-APEX and Argo floats, focusing on a region between Hawaii and California from 2017-2019. We are using the programming language, Python, to navigate the Argo and APL database for broadly coincident floats, to distinguish the mixed (upper) layer from the lower layer of the water column via CTD graphs, and to graphically compare low- and high-resolution velocities. We expect standard ocean conditions will remain prominent (velocity and temperature decrease with depth, while salinity increases), uncertainties due to inexact float matches will arise, and more insight will be gained on differences between datasets. The next steps to consider are analyzing other APL floats to provide a more global representation of connection with Argo, and to compare Argo’s historical data in similar temporal bounds to better distinguish between natural and resurfacing-time variability.

## What were the main goals of this project?
This project mainly focused on understanding the similarities and differences between two sets of big autonomous float data, Argo and EM-APEX, in addition to making direct comparisons between salinity, temperature, depth, and velocity data in order to portray the complimentary nature of both systems. Specific objectives included:
1. Complete necessary conceptual research to understand what the mechanics of vertical profiling floats were, what both systems measured and how the measurements occured, ocean properties centered around objectives (i.e. eddies, internal waves, ocean topography, the mixed layer), and how Argo vs EM-APEX cycles compared.
2. Complete necessary background research on figuring out how to access Argo and EM-APEX data, reorganize it in a way to better visualize via Python in JupyterLab, and understand how this data has been processed and managed.
3. Develop plots using Python packages available in mamba forge such as pandas, argopy, seawater, matplotlib, and so forth to make graphs and sort through data.
4. Finally, do a precursory visual analysis focusing on three main questions; _When does the mixed layer shift from shrinking to growing seasonally in 2017_, _Are there any interesting cases of a phenomenon called "salt fingers"_, and _Does ANDRO calulated velocities from Argo data with higher error bounds suggest a factoring out of shorter-scale phenomena that EM-APEX floats have picked up on?_

## What is the purpose of this repo?
The purpose of this repository is to share insight into the code development and processing behind the scenes of this project and to provide insight as to what I have learned about cross referencing Argo and EM-APEX data.

There will be some insight to results integrated in the code, but the conceptual background research and explicit results are better explained in the following resources I have included here:
1. A PowerPoint Slideshow of all Concepts Learned + Some Highlights of the DINO SIP Programing itself...
2. A Poster summarizing the project process that can be seen below or can be downloaded via this file...
3. A technical paper giving a more detailed layout of further insights and the project itself meant to compliment the poster that can be accessed here...

## Credits
I would ultimately like to recognize
