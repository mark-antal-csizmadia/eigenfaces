# eigenfaces
Eigenfaces exercise.

# Get it running by following the steps below:
1. Make sure you have Anaconda and Git installed on your machine.
2. Go to your desired directory, open your terminal of choice and clone the directory to your local machine: git clone https://github.com/mark-antal-csizmadia/eigenfaces.git
3. Open the Anaconda prompt in the eigenfaces directory, and recreate the eigenfaces_env virtual environment: conda env create -f eigenfaces_env.yml
5. Still in the Anaconda prompt, make sure that the eigenfaces_env virtual environment has been created: conda info --envs
6. Still in the Anaconda prompt, make the eigenfaces_env virtual environment available for 
Jupyter Notebook as a kernel: python -m ipykernel install --user --name eigenfaces_env --display-name "Python (eigenfaces_env)"
7. Still in the Anaconda prompt, open up the eigenfaces.ipynb: jupyter notebook eigenfaces.ipynb
8. Make sure that the kernel is set to the eigenfaces_env kernel via selecting Kernel>Change kernel...>Python (eigenfaces_env)
9. Happy playing!

# Issues.
1. Issue with reading PGM files.
