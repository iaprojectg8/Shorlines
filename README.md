# Shorelines notebook

This notebook is from the [Digital Earth Africa website](https://docs.digitalearthafrica.org/en/latest/sandbox/notebooks/Datasets/Coastlines.html). We have just changed the area of interest.


## Environment

First, you need to create and activate an environment as usual
1. **Create a virtual environement**:
Open a command prompt or a terminal and create a virtual environment:
```
python -m venv yourenvname
```

2. **Activate it**:
```
yourenvname\Scripts\activate
```

## Dependancies

Second, you need to install GDAL because without it you will not be able to install the other packages needed. In this repository, you have a wheel directory that allows you to build GDAL from it. You need to be in the root of this repo and run this command:
```
pip install .\wheel\GDAL-3.8.4-cp311-cp311-win_amd64.whl
```

Then you will have to install the rest of the modules, with the file `requirements.txt`:

```
pip install -r requirements.txt
```

## Run

To run the `shorlines.ipynb` you need to have a code editor that supports that kind of file like **Visual Studio Code** or **Jupyter**

Finally you can run everything or run cell by cell with the play button.
