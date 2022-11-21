## CO2-Dasboard
This project is to get started with python dashboard. I follow Thu-Vu's repositories to build this project by myself in WSL2./

# Install environment
This repo is for CO2-dasboard project./
I use poetry package to create environment by following step:
* First, go to root directory of project
* Use ```poetry init``` command to create virtual env
* Simply use ```poetry add hvplot jupyterlab panel``` to install dependencies.

Ref: 
* https://python-poetry.org/docs/

To serve the dashboard locally, use the command:
``` shell script 
panel serve ./CO2_dashboard/Interactive_dashboard.ipynb
```