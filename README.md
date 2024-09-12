# MDN_tutorials<br/> 
Provides tutorials for using MDNs with in situ measurements and satellite imagery<br/> 
Requirements:<br/> 
	-git     | https://github.com/git-guides/install-git <br/> 
	-git-lfs | https://docs.github.com/en/repositories/working-with-files/managing-large-files/installing-git-large-file-storage <br/> 
	
	
Installation steps:<br/> 
1. Clone tutorials repo: <br/> 
	-git clone https://github.com/ryan-edward-oshea/MDN_tutorials.git<br/> 
2. Install Python 3.8 (preferably 3.8.19 or 3.8.10) if not available<br/> 
3. Create a virtual environment: <br/> 
	-python3.8 -m venv MDN_env<br/> 
	or with conda: conda create -n MDN_env python=3.8.10<br/> 
4. Activate the environment:<br/> 
	-source MDN_env/bin/activate<br/> 
	or with conda: conda activate MDN_env<br/> 
5. Install the MDN into the python environment and update dependencies:<br/> 
	-pip install git+https://github.com/ryan-edward-oshea/MDN.git@MDN_V3<br/> 
6. Start JupyterHub notebook in command line with: <br/> 
	-jupyter-notebook <br/> 
7. Open the tutorials: <br/> 
	-./MDN_tutorials/SC_1_.... <br/> 
