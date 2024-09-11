# MDN_tutorials
Provides tutorials for using MDNs with in situ measurements and satellite imagery

Installation steps:
1. Clone tutorials repo: 
	-git clone https://github.com/ryan-edward-oshea/MDN_tutorials.git
2. Install Python 3.8 (preferably 3.8.19 or 3.8.10) if not available
3. Create a virtual environment: 
	-python3.8 -m venv MDN_env
	or with conda: conda create -n MDN_env python=3.8.10
4. Activate the environment:
	-source MDN_env/bin/activate
	or with conda: conda activate MDN_env
5. Install the MDN into the python environment and update dependencies:
	-pip install git+https://github.com/ryan-edward-oshea/MDN.git@MDN_V3
6. Start JupyterHub notebook in command line with: j
	-jupyter-notebook
