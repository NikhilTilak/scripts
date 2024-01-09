This repo contains scripts to acquire voltage waveforms from a Keysight EDUX1052A oscilloscope and a Rigol DHO 1102 oscilloscope.

Another script calculates the power spectral density (PSD) of these signals for noise analysis.

## Resources : 

[Programming manual keysight](https://www.keysight.com/us/en/assets/9018-07747/programming-guides/9018-07747.pdf)

[Programming manual Rigol](https://tw.rigol.com/tw/Images/DHO10004000_ProgrammingGuide_EN_tcm17-5395.pdf)

[Pyvisa documentation](https://pyvisa.readthedocs.io/en/latest/)

## Python packages used:

Numpy, Scipy, Matplotlib, pandas, scikit-learn, Pyvisa

## Using venv

On MacOS :

- Add venevdir/ to .gitignore file.

- Initialize a virtual environment : python3 -m venv venvdir

- Activate the virtua enviroment using : source venvdir/bin/activate

- Install required packages listed in requirements.txt using : pip3 install -r requirements.txt




