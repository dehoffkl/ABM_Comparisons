# ABM_Comparisons
This repository is for comparisons between different ABM frameworks

For speed purposes, I tested the 2D Wealth Distribution, where agents first move to a new grid space, then if they have any money, they pass off $1 to a random agent in the same space.

|Parameter|Value|
|---------|-------|
|Grid size|100x100|
|Number of agents|10,000|
|Number of steps|200|
|CPU|Ryzen 3 2200G|
|RAM|8GB|

|ABM Library|Run Time|
|---------|--------|
|Mesa|~46 seconds|
|Julia Agents.jl|1.75 seconds|
