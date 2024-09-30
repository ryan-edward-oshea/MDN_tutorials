Provides tutorials for using MDNs with in situ measurements and satellite imagery<br/> 
Requirements:<br/>
	-**Conda** or **pip** to create a virtual environment | https://github.com/conda-forge/miniforge or https://docs.anaconda.com/miniconda/ <br/> 
	-**(if not using Conda) Python V3.8** (preferably 3.8.19 or 3.8.10)  <br/> 
	-**git**     | https://github.com/git-guides/install-git <br/> 
	-**git-lfs** | https://docs.github.com/en/repositories/working-with-files/managing-large-files/installing-git-large-file-storage <br/> 
	
	
Installation steps to be run in in Terminal (or Command Prompt for Windows):<br/> 
1. Clone tutorials repo: <br/> 
	**git clone https://github.com/ryan-edward-oshea/MDN_tutorials.git**<br/> 
2. Skip if using conda: Install Python 3.8 (preferably 3.8.19 or 3.8.10) <br/> 
3. Create a virtual environment: <br/> 
	**python3.8 -m venv MDN_env_09_30_24**<br/> 
	or with conda: **conda create -n MDN_env python=3.8.10**<br/> 
4. Activate the environment:<br/> 
	Mac/Linux:**source MDN_env/bin/activate**<br/>
	Windows:**MDN_env/Scripts/activate**<br/> 
	or with conda: **conda activate MDN_env**<br/>
5. Update pip
	**python -m pip install --upgrade pip** 
6. Install the MDN into the python environment and update dependencies:<br/> 
	**pip install git+https://github.com/ryan-edward-oshea/MDN.git@MDN_V3**<br/> 
7. Start JupyterHub notebook in command line with: <br/> 
	**jupyter-notebook** <br/> 
8. Open the tutorials: <br/> 
	./MDN_tutorials/SC_1_.... <br/> 
	
Common issues:
1. Unable to install Latex --> add "mpl.rcParams['text.usetex']=False" before generating plots. 
2. Do not install in Box/Onedrive folder

