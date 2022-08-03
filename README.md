# Spotify Project

## Building the module

First, create and activate a virtual environment to prevent versioning conflicts.
```bashmhfhsgdkaf
virtualenv spot_venv
source spot_venv/bin/activate
```

Now you can build and install the module.
```bash
python setup.py build
pip install .
```

Build and train the model with 
```bash
python -m spotify_module.create_model
```

## Testing

Write tests in the `tests` folder, following the `test_*.py` naming convention. Run them with
```bash
python -m unittest
```