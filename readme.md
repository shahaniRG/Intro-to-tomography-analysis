# Codes for tomography analysis

Made for the Shahani Research Group (http://www.ashwinshahani.com/).  
University of Michigan, Department of Materials Science and Engineering. 

## Description

Some codes for the group. Please add notes and documents to improve this repo for other students who will do beamline experiments.

**Radiography processing and exporting in notebook**
![Radiography example](https://user-images.githubusercontent.com/1335424/171718559-0bea267b-3464-4659-9f0a-aa81c839e925.png)

**Tomography reconstruction in notebook**
![forGithub](https://user-images.githubusercontent.com/1335424/171723376-5ca2baa6-e502-4b72-8d5b-a9738cf4423e.png)

## Getting Started

### Dependencies

* use enviroment_pc.yml with anaconda to set up a conda env

### Installing

For sake of installation time, start by installing [miniconda](https://docs.conda.io/projects/conda/en/latest/user-guide/install/windows.html) 

Open Anaconda Prompt and create a new environment named tomopy for the [tomopy](https://tomopy.readthedocs.io/en/latest/) package and various dependencies. Use the yml file in this repo to start.
```
conda env create --file environment_pc.yml
```

Start playing around in [JupyterLab](https://jupyterlab.readthedocs.io/en/stable/getting_started/overview.html) and open the jupyter notebooks to guide you as you begin reconstructions.
```
conda activate tomopy_analysis
jupyter lab
```

* See the jupyter notebook and other files with comments
* See tomopy_prep.ipynb to get started

### Executing program

* How to run the program
* Step-by-step bullets
```
code blocks for commands
```

## Authors

Updated Jan 14, 2022: Paul Chao; pchao [at] umich.edu  
Updated Feb 15, 2022: Paul Chao and Kiran
Updated June 2, 2022: Paul Chao; pchao [at] umich.edu 

## Version History

* 0.1
    * Initial Release

## License

MIT License

Copyright (c) 2022 Paul Chao

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

## Acknowledgments

* [tomopy](https://tomopy.readthedocs.io/en/latest/)
