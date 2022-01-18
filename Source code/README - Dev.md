# MUltiple tests corrections and FOrmatted tables Software (MUFOS)

## For developers - General notes
Information about the software development, its architecture, quality control and reuse potential (i.e. how it can be built upon), please see the this preprint (link coming soon).

For additional information about underlying procedures and calculations, see the [MUFOS Help Guide and Documentation document](../MUFOS%20Help%20Guide%20and%20Documentation_1.0.docx).

## Run instructions
1. Make sure you have Python 3.8 installed.
2. Navigate to the source code and run `pip install -r requirements.txt` in your shell in order to install all of the required packages.
3. Run the `_ROOT.py` file.

## Build instructions
1. Make sure you have Python 3.8 installed as well as the latest version of `pyinstaller` (get it by running `pip install pyinstaller`).
2. Navigate to the source code.
3. Run `pip install -r requirements.txt`
4. Run `pyinstaller mufosWindowsSpec.spec` (or `pyinstaller mufosMacSpec.spec`)

This procedure will yield a `dist` folder, which contains a MUFOS executable file.

**Note: when packaging for MacOs**, there is a known issue with tkinter (see [here](https://github.com/pyinstaller/pyinstaller/issues/3820)).
The solution used is copying the [msgcat-1.6.1.tm](https://github.com/nikbpetrov/mufos/blob/master/Source%20code/msgcat-1.6.1.tm) into one of the tk folders - see [here](https://github.com/pyinstaller/pyinstaller/issues/3820#issuecomment-515673901).

## Support
In case of any problems, questions or feedback, please contact the leading developer at [nikbpetrov@gmail.com](mailto:nikbpetrov@gmail.com).

Copyright (C) 2022  Nikolay Petrov, Vasil Atanasov, & Trevor Thompson
