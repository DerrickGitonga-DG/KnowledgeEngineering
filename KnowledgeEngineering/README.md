# KnowledgeEngineering — ICS 3202 Practical Exercise 4

A knowledge-based self-driving trailer **educational simulation** based on Practical Exercise 3 route data.

## Run
1. Open `Autonomous_Trailer.ipynb` in Jupyter Notebook, JupyterLab, VS Code or Google Colab.
2. Select a Python 3 kernel and choose **Run All**.
3. Review the route (Nairobi → Kisumu, **352.0 km within the supplied graph**), inference explanations, demo scenarios and passing tests.
4. Edit the example `user_scenario` percept values to test a different situation.

No third-party Python packages or online access are required to execute the notebook.

## Project artifacts
- `Autonomous_Trailer.ipynb`: final notebook (facts, inference, rules, UCS, demo, tests)
- `TEAM_MINUTES_TEMPLATE.md`: blank group meeting notes template; complete truthfully and export to PDF, **or upload an actual group photo**

## Important accuracy note
This is **not** a real self-driving implementation. The source Exercise 3 graph has one directed Nairobi–Kisumu path, so 352 km is the optimal path only **within that graph**; no alternate detour can be calculated without adding verified road segments. Simulated traffic, roadblocks and sensor readings are not live data.

## Group submission checklist
- [ ] One team member creates a **public** GitHub repo named exactly `KnowledgeEngineering`.
- [ ] Push `Autonomous_Trailer.ipynb`, this README, and valid teamwork evidence.
- [ ] Include **all contributing members** and their student numbers in the notebook heading.
- [ ] Every other group member **forks the original public repo** to their own GitHub account.
- [ ] Confirm all members' forks are visible; include the fork URLs in the final README if desired.
- [ ] Only one member submits the **original** repository URL to e-learning before the deadline.

### Source materials
User-provided `UCS_Trailer.ipynb`, `design(1).md`, and the Exercise 4 assignment brief.
