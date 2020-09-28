1) Create an enviorement to install and use scikit-hep using anaconda:
$conda create conda create -n Scikit-HEP python=3.6 numpy matplotlib

2) after creating the enviorement just run the command to activate it:
$conda activate Scikit-HEP

2-a)now we can run pip to install scikit-hep tools in our enviorement, from the website https://pypi.org/project/scikit-hep/:
(Scikit-HEP)$pip install scikit-hep

3) to install the kernel and use jupyter lab (fancy jupyter notebook):
(Scikit-HEP)$conda install jupyter ipython

3-a) installing the kernel on the jupyter kernel list:
(Scikit-HEP)$python -m ipykernel install --user --name=Scikit-HEP --display-name="SciKit-HEP"

4) install h5py to open the datasets:
(Scikit-HEP)$conda install h5py

5) install pyjet:
(Scikit-HEP)$pip install --user pyjet

extras*) install pytables to use pandas to read the h5 files:
(Scikit-HEP)$conda install pytables

extras**) install tqdm to have a nice progress bar:
(Scikit-HEP)$conda install tqdm 
_________________________________________
alternatively just run:
$conda env create -f Scikit-HEP.yml
with the enviorement .yml file in this folder. just copy the file into your home folder and run the command above.