# KnowledgeEngineering  Practical Exercise 4

A knowledge-based self-driving trailer **educational simulation** based on Practical Exercise 3 route data.

## Run
1. Open `Autonomous_Trailer.ipynb` in Jupyter Notebook, JupyterLab, VS Code or Google Colab.
2. Select a Python 3 kernel and choose **Run All**.
3. Review the route (Nairobi → Kisumu, **352.0 km within the supplied graph**), inference explanations, demo scenarios and passing tests.
4. Edit the example `user_scenario` percept values to test a different situation.

No third-party Python packages or online access are required to execute the notebook.


## Important accuracy note
This is **not** a real self-driving implementation. The source Exercise 3 graph has one directed Nairobi–Kisumu path, so 352 km is the optimal path only **within that graph**; no alternate detour can be calculated without adding verified road segments. Simulated traffic, roadblocks and sensor readings are not live data.


### Source materials
User-provided `UCS_Trailer.ipynb`, `design(1).md`, and the Exercise 4 assignment brief.
