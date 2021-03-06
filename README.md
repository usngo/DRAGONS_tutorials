---
# DRAGONS data reduction (Jupyter Notebooks)

This repository has Jupyter Notebook examples of data reduction for the Gemini Observatory instruments. They were written using the [DRAGONS' Application Program Interface (API)](https://dragons-recipe-system-users-manual.readthedocs.io/en/v2.1.1/appendices/full_api_example.html) for Python.

---
## Before you try the notebooks:

- [x] Install the Python-based DRAGONS platform by creating an anaconda environment. Detailed instructions can be found on the [Gemini Data Processing Software](https://www.gemini.edu//observing/phase-iii/understanding-and-processing-data/Data-Processing-Software) webpage.

- [x] At this point, you will have DRAGONS installed. To run the notebooks in the US NGO repository, you will have to allow the Jupyter notebooks to run on your Conda DRAGONS environment. You can do that by installing the packages listed below. From your bash terminal:

   ```
   conda install -n dragons nb_conda_kernels ipykernel
   ```
   
- [x] The Jupyter Notebooks are configured to download the raw (public) data directly from the [Gemini Observatory Archive](https://archive.gemini.edu/searchform). For that, you'll need the `wget` python package installed. From your bash terminal:

   ```
   conda install -n dragons wget
   ```

- [x] Download one of the files listed on the [Current notebooks available](#current-notebooks-available) section. Once the download is completed, start a bash terminal, go to the folder where you have downloaded the file, and type:

   ```
   conda activate dragons
   jupyter notebook [name].ipynb
   ```
   
*Note: at this stage, a browser window will open and the Jupyter notebook will be loaded. On the top right part of the window, you should see* `Python [conda env:dragons]` *or something similar, ensuring that the correct DRAGONS environment is loaded.*

---
## Current notebooks available:

### F2_IM_WISEJ0413-4750.ipynb

Flamingos-2 imaging (Y-band) of the brown dwarf WISE J041358.14-475039.3. This is extracted from the Gemini/DRAGONS F2 tutorial, Section 3. Dataset includes Flats, Darks, and Science frames. Link to the [Jupyter notebook](F2_IM_WISEJ0413-4750.ipynb) or [direct download](https://raw.githubusercontent.com/usngo/DRAGONS/main/F2_IM_WISEJ0413-4750.ipynb) (right-click &#8594; Save Link As...).

### GMOS_IM_FIELD.ipynb

GMOS imaging (i-band) of a stellar field. This is extracted from the Gemini/DRAGONS GMOS tutorial, Section 3. Dataset includes Biases, Twilight Flats, and Science frames. Link to the [Jupyter notebook](GMOS_IM_FIELD.ipynb) or [direct download](https://raw.githubusercontent.com/usngo/DRAGONS/main/GMOS_IM_FIELD.ipynb) (right-click &#8594; Save Link As...).

### GMOS_IM_NGC5018.ipynb

GMOS imaging (g-band) of the elliptical galaxy NGC5018.  Dataset includes Biases, Twilight Flats, and Science frames. Link to the [Jupyter notebook](GMOS_IM_NGC5018.ipynb) or [direct download](https://raw.githubusercontent.com/usngo/DRAGONS/main/GMOS_IM_NGC5018.ipynb) (right-click &#8594; Save Link As...).

### GNIRS_IM_GRB120116A.ipynb

GNIRS imaging (J-band - point source through keyhole) of GRB120116A. This is extracted from the Gemini/DRAGONS GNIRS tutorial, Example 1-B. Dataset includes Flats, Darks, and Science frames. Link to the [Jupyter notebook](GNIRS_IM_GRB120116A.ipynb) or [direct download](https://raw.githubusercontent.com/usngo/DRAGONS/main/GNIRS_IM_GRB120116A.ipynb) (right-click &#8594; Save Link As...).

### GSAOI_NGC5128.ipynb

GSAOI imaging (K-short) of a field around NGC5128. This is extracted from the Gemini/DRAGONS GSAOI tutorial, Section 3. Dataset includes Flats, Standard Star, and Science frames. Link to the [Jupyter notebook](GSAOI_NGC5128.ipynb) or [direct download](https://raw.githubusercontent.com/usngo/DRAGONS/main/GSAOI_NGC5128.ipynb) (right-click &#8594; Save Link As...).

### NIRI_SN2014J.ipynb

NIRI imaging (K-prime) of SN2014J. This is extracted from the Gemini/DRAGONS NIRI tutorial, Section 4. Dataset includes Flats, Standard Star, Darks, and Science frames. Link to the [Jupyter notebook](NIRI_SN2014J.ipynb) or [direct download](https://raw.githubusercontent.com/usngo/DRAGONS/main/NIRI_SN2014J.ipynb) (right-click &#8594; Save Link As...).

---
## Additional resources

- **DRAGONS Documentation:** Data reduction with DRAGONS is currently available for all imaging data from current Gemini instruments. New modes and instruments are being added. Detailed instructions on the current stable version can be found on the [documentation page](https://dragons.readthedocs.io/en/stable/).

- **Gemini DR Forum:** The Gemini Observatory maintains a [Data Reduction User Forum](http://drforum.gemini.edu/) with materials on data reduction, software installation, and much more!

---
## Need help?

Problems, comments, suggestions, and/or need help with setting up and running the Jupyter notebooks? You can contact the US NGO members via our [Portal](http://ast.noao.edu/csdc/usngo), [Twitter](https://twitter.com/usngo), or submit a *New issue* through github.

For assistance with DRAGONS installation and procedures, please submit a ticket to the [Gemini Helpdesk](https://www.gemini.edu/observing/helpdesk/submit-general-helpdesk-request) (Partner Country: US; Topic: DRAGONS).

Follow us on Twitter! <a href="https://twitter.com/usngo" target="_blank"><img src="https://badgen.net/twitter/follow/usngo"></a>

---
