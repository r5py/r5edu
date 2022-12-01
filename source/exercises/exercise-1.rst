Exercises 1-4
=============

**Objectives:** These exercises help you to get a hands-on experience in using the open source spatial accessibility tools in Python and/or R.
You should do the Exercise 1 first, but after that you can pick an exercise that interests you the most.

Exerise 1 - Run the tutorial
----------------------------

Run the first tutorial that demonstrates how to calculate travel time matrices in Brighton by public transport and cycling.
The tutorial will teach you the basics of using R5 with:

- ``r5py``: if you prefer using Python for programming -> :doc:`Go to the tutorial <../notebooks/r5py_intro>`
- ``r5r``: if you prefer using R for programming -> :doc:`Go to the tutorial <../notebooks/r5r_intro>`

Exerise 2 - Inspect accessibility of locations of your own interest
-------------------------------------------------------------------

In the Exercise 1 (i.e. first tutorial), you familiarized yourself with calculating accessibility to schools in Brighton area.
In this exercise, the idea is to apply these same techniques to e.g. services / or locations of your own interest (e.g. health-care, bars, restaurants, what-ever-you-like).
To do this:

- Create a new Notebook where you run these codes (alternatively add new cells under the tutorial)
- Download the points of interest for yourself from OpenStreetMap using ``omsnx`` (Python) or ``osmdata`` (R). You can get inspiration from :doc:`this short tutorial <../notebooks/extra_materials/download_poi_data_for_Brighton>` in the Extra materials
- Repeat the travel time analyses for these locations and explore the patterns with maps and other graphics.
- If you are using Binder: **Download the Notebook** to your own computer if you wish to store your work permanently

Exercise 3 - Shortest path analysis in Python
---------------------------------------------

Exerises 1 and 2 focused on computing travel time matrices that show regional patterns of access, but we did not conduct any individual shortest path analysis.
If you are interested there is a separate tutorial that shows how to conduct individual shortest path analyses using Python.

Task:

- Familiarized yourself with :doc:`this tutorial <../notebooks/spatial_network_analysis>` to network analysis and shortest path analysis using ``networkx`` and ``pyrosm``  libraries.

Exercise 4 - Go adventurous and repeat the analyses in some other city!
-----------------------------------------------------------------------

Advanced: If you feel that the previous exercises weren't enough challenge for you, here, you should **conduct accessibility analyses in some other city.**
You should find appropriate data for yourself (at least GTFS and OSM data), build the networks, and run the travel time analyses for the locations that interest you.