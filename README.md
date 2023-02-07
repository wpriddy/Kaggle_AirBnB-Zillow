## Version Requirements

Python >= 3.8.5

## Installation

I used an Anaconda environment and Windows OS. It is recommended to set up a virtual environment within the conda environment. 

```bash
>> conda create -n "YOUR ENVIRONMENT NAME" python=3.9


>> conda activate "YOUR ENVIRONMENT NAME"
```

Change directories into the /wyatt_priddy_data_challenge folder

You will need to install the appropriate packages which are stored in the requirements.txt

```bash
>> pip install -r requirements.txt
```

Activate jupyter notebooks for the data_challenge.ipynb file

```bash
>> jupyter-notebook data_challenge.ipynb
```

If the kernel is not starting and you come into an error similar to:

```bash
ImportError: DLL load failed while importing win32api: The specified module could not be found.
```

You may need to install the win32api module to the conda environment:

```bash
>> conda install pywin32
```

Note: installation on pywin32 is not included in the requirements.txt in case another operating system or windows version. 

In order to view interactive graphs, the environment must be set up and the code needs to be run. For basic visual analysis, static shots of the interactive graphs are previewable in the /static_graphs folder. 
