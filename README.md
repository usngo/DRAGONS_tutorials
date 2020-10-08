---
# DRAGONS data reduction (Jupyter Notebooks)

This repository has Jupyter Notebook examples of data reduction for the Gemini Observatory instruments. The procedures were written using the [DRAGONS' Application Program Interface (API)](https://gmosimg-drtutorial.readthedocs.io/en/v2.1.1/03_api_reduction.html) for Python.

---
## Before you try the notebooks:

- [x] Install DRAGONS by creating a anaconda environment. Detailed instructions can be found on the [Gemini Data Processing Software](https://www.gemini.edu//observing/phase-iii/understanding-and-processing-data/Data-Processing-Software) webpage.

- [x] Add the Conda DRAGONS environment to your Jupyter notebook by installing the following packages:

   ```
   conda install -n dragons nb_conda_kernels ipykernel
   ```
   
- [x] The notebooks will download the raw (public) data directly from the [Gemini Observatory Archive](https://archive.gemini.edu/searchform). For that, you'll need the `wget` python package:

   ```
   conda install -n dragons wget
   ```

- [x] Once you've downloaded one of the notebooks, on your terminal:

   ```
   conda activate dragons
   jupyter notebook [name].ipynb
   ```

---
## Current notebooks available:

### GMOS_IM_FIELD.ipynb

GMOS imaging (i-band) of a stellar field. This is extracted from the Gemini/DRAGONS GMOS tutorial, Section 3. Dataset includes Biases, Twilight Flats, and Science frames. Link to the [Jupyter notebook](GMOS_IM_FIELD.ipynb) or [direct download](https://raw.githubusercontent.com/usngo/DRAGONS/main/GMOS_IM_FIELD.ipynb).

### GMOS_IM_NGC5018.ipynb

GMOS imaging (g-band) of the elliptical galaxy NGC5018.  Dataset includes Biases, Twilight Flats, and Science frames. Link to the [Jupyter notebook](GMOS_IM_NGC5018.ipynb) or [direct download](https://raw.githubusercontent.com/usngo/DRAGONS/main/GMOS_IM_NGC5018.ipynb).

### GSAOI_NGC5128.ipynb

GSAOI imaging (K-short) of a field around NGC5128. This is extracted from the Gemini/DRAGONS GSAOI tutorial, Section 3. Dataset includes Flats, Standard Star, and Science frames. Link to the [Jupyter notebook](GSAOI_NGC5128.ipynb) or [direct download](https://raw.githubusercontent.com/usngo/DRAGONS/main/GSAOI_NGC5128.ipynb).

---
## Additional resources

- **DRAGONS Documentation:** Data reduction with DRAGONS is currently available for all imaging data from current Gemini instruments. New modes and instruments are being added. Detailed instructions on the current stable version can be found on the [documentation page](https://dragons.readthedocs.io/en/stable/).

- **Gemini DR Forum:** The Gemini Observatory maintains a [Data Reduction User Forum](http://drforum.gemini.edu/) with materials on data reduction, software installation, and much more!

---
## Need help?

Problems, comments, suggestions, and/or need help with any of the above? You can contact the US NGO members via our [Portal](http://ast.noao.edu/csdc/usngo), [Twitter](https://twitter.com/usngo), or submit a pull request on github.

Follow us on Twitter! <a href="https://twitter.com/usngo" target="_blank"><img src="https://badgen.net/twitter/follow/usngo"></a>

---
