# DRAGONS data reduction examples (using Jupyter Notebooks)

This repository has Jupyter Notebook examples of data reduction for the Gemini Observatory instruments. The procedures were written using the [DRAGONS' Application Program Interface (API)](https://gmosimg-drtutorial.readthedocs.io/en/v2.1.1/03_api_reduction.html) for Python.

## Before you try the notebooks:

- [x] Install DRAGONS by creating a anaconda environment. Details can be found on the [Gemini Data Processing Software](https://www.gemini.edu//observing/phase-iii/understanding-and-processing-data/Data-Processing-Software) webpage.
- [x] Add the Conda DRAGONS environment to your Jupyter notebook. The following commands were tested and worked:

   `conda install -n dragons nb_conda_kernels ipykernel`
   
- [x] The notebooks will download the raw (public) data directly from the [Gemini Observatory Archive](https://archive.gemini.edu/searchform). For that, you'll need the `wget` python package:

   `conda install -n dragons wget`

- [x] Once you've downloaded one of the notebooks, on your terminal:

   ```
   conda activate dragons
   jupyter notebook [name].ipynb
   ```

## Current examples available and tested:

- [GMOS_IM_FIELD.ipynb](GMOS_IM_FIELD.ipynb): GMOS imaging (i-band) of a stellar field. This is extracted from the Gemini/DRAGONS tutorial, Section 3. Link to [direct download](https://raw.githubusercontent.com/usngo/DRAGONS/main/GMOS_IM_FIELD.ipynb).
- [GMOS_IM_NGC5018.ipynb](GMOS_IM_NGC5018.ipynb): GMOS imaging (g-band) of the elliptical galaxy NGC5018. Link to [direct download](https://raw.githubusercontent.com/usngo/DRAGONS/main/GMOS_IM_NGC5018.ipynb).

---
Problems, comments, and/or suggestions? You can contact the US NGO members via our [Portal](http://ast.noao.edu/csdc/usngo), [Twitter](https://twitter.com/usngo), or submit a pull request.
