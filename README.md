**Important Information**

Before running this code, you need to create a virtual environment (kernel) to run this Jupyter Notebook file. Follow these steps in the Anaconda prompt (ensure that Anaconda Navigator is installed):

1. Create a new virtual environment (kernel) by running the following command, replacing "IM" with the desired name for your kernel:  
   'python -m venv IM'

2. Activate the virtual environment by running:  
   '.\IM\Scripts\activate'

3. Install the 'ipykernel' package by running:  
   'pip install ipykernel'

4. Register the virtual environment as a Jupyter kernel by running:  
   'python -m ipykernel install --name=IM'

After creating the kernel, open a new Jupyter notebook and run the code inside the '.ipynb' file. 
Ensure that you have added the dataset to the path where you created the kernel.
Also in the code,if you didn't installed cuda toolkit(if you have nvida graphic card please install otherwise don't install) please intstall it(make sure that you installed cuda 11.8 version otherwise it will not work,
beacause pytorch only hase 12.1 version and 11.8 version) and run this code in the anaconda prompt "pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu118"
