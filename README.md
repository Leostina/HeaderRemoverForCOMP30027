# HeaderRemover for COMP30027
a very simple header remover , designed only for slides COMP30027ML, UOM 2022-SEM1

### use:
-> Place COMP30027 PDFs which you want to remove headers into the ```.\in``` folder ->\
-> Check and install the dependencies ->\
-> Run ```headerRemover.py```,\
 Alternatively, you may specify customised input and output folder, preceded by ```-ipath``` and ```-opath``` flags:\
 e.g. ```headerRemover.py -ipath myInputFolder -opath myOutputFolder``` ->\
-> Wait till the program finishes ->\
-> Locate the postprocess PDFs in ```.\out ``` or output folder you specified.

### workflow:
-> Convert PDF to images \
-> Traverse hard-coded image area px by px \
-> Replace the ones of specified color to blank \
-> Combine processed images into new PDF.

### dependencies:
please install the following dependencies before use:\
Pillow, pathlib, pdf2image
```
pip install pillow
pip install pathlib
pip install pdf2image
```

### update:
May dev a much cleverer CNN-based InkSaver in the future or when I am free.
For enquiries or other ideas please contact
```xinqiy@student.unimelb.edu.au```

by Léo Xinqi Yu
