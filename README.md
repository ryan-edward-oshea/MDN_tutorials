Provides tutorials for using MDNs with in situ measurements and satellite imagery<br/> 
Requirements:<br/>
	-**Conda** or **pip** to create a virtual environment | https://github.com/conda-forge/miniforge or https://docs.anaconda.com/miniconda/ <br/> 
	-**(if not using Conda) Python V3.8.10** (preferably 3.8.10 or 3.8.19)  <br/> 
	-**git**     | https://github.com/git-guides/install-git <br/> 
	-**git-lfs** | https://docs.github.com/en/repositories/working-with-files/managing-large-files/installing-git-large-file-storage <br/> 
	
	
Installation steps to be run in in Terminal (or Command Prompt for Windows):<br/> 
1. Create directory to hold tutorials and environment:<br/> 
	**mkdir Aquaverse**<br/> 
2. Navigate to directory:<br/> 
	**cd Aquaverse**<br/> 
3. Clone tutorials repo: <br/> 
	**git clone https://github.com/ryan-edward-oshea/MDN_tutorials.git**<br/> 
4. Skip if using conda: Install Python 3.8 (preferably 3.8.10 or 3.8.19) <br/> 
5. Create a virtual environment: <br/> 
	**python3.8 -m venv AQV_env_09_30_24**<br/> 
	or with conda: **conda create -n AQV_env_09_30_24 python=3.8.10**<br/> 
6. Activate the environment:<br/> 
	Mac/Linux:**source AQV_env_09_30_24/bin/activate**<br/>
	Windows:**AQV_env_09_30_24/Scripts/activate**<br/> 
	or with conda: **conda activate AQV_env_09_30_24**<br/>
7. Update pip: <br/>
	**python -m pip install --upgrade pip** <br/>
8. Install the MDN into the python environment and update dependencies:<br/> 
	**pip install git+https://github.com/ryan-edward-oshea/MDN.git@MDN_V3**<br/> 
9. Start JupyterHub notebook in command line with: <br/> 
	**jupyter-notebook** <br/> 
10. Open the tutorials: <br/> 
	./MDN_tutorials/SC_1_.... <br/> 
	
Common issues:<br/>
1. Unable to install Latex --> add "mpl.rcParams['text.usetex']=False" before generating plots. <br/>
2. Do not install MDN wihin Box/Onedrive folder.<br/>

