# AutoCert

AutoCert is a commandline program that automates the process of generating certificates in bulk given a pptx template. It replaces all the instances of the placeholder with the names given in the input file, written in pure python, by Kinshuk Dua


## Installation

Download or clone this repository and then install it's dependencies with:
```python
pip install -r requirements.txt
```
## Features

- Keeps the original formatting as the pptx file.
- Does ***not*** use image processing, text detection or ML giving the best performance possible, even with a huge number of input names.
- Supports custom csv delimiter and input file names.
- All dependencies and the program itself is written in pure python.
- Files are saved in a pptx format for high resolution printing.

## Usage


```cmd
python AutoCert.py <template.pptx> <names.txt/csv> -d <"place holder text" (optional)> -dem <csv delimiter (optional)>
```
By default the placeholder is ```"Jane Smith"```

and the delimiter is newline ```"\n"```
## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

