📽️ Dynamic Visualization of the Legislative Network
This repository contains code and output for a dynamic visualization of the New Zealand legislative network, with a focus on the Mental Health (Compulsory Assessment and Treatment) Act 1992.

The notebook Dynamic_visualization_MentalHealthAct.ipynb generates an animated representation of how the structure and relationships between Acts evolve over time. Using preprocessed CSV files containing legal network and centrality data, the animation reflects monthly changes across 20 act versions.

The animation captures:

Node additions and removals

Legal relationship evolution (citations, amendments, repeals)

Temporal dynamics of the legislative environment

⚙️ Requirements
To run the visualization script, ensure you have the following:

Python 3.8+

Jupyter Notebook

Manim Community Edition

pandas

networkx

matplotlib

The animation is rendered using Manim’s OpenGL engine for smooth and high-quality transitions.

🎞️ Output
MentalHealthAct_Network_Animation.mp4
This is the final video output illustrating the monthly evolution of the legislative network. It shows the dynamic interplay of legal relationships and structural changes around the core act over time.
