[![Launch Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/tuftsdatalab/python-data-analysis/main?urlpath=lab/tree/python-data-analysis.ipynb){:target="_blank"}&nbsp;
[![View on Github](https://tuftsdatalab.github.io/badges/github.svg)](https://github.com/tuftsdatalab/python-data-analysis)&nbsp;
[![Download Zip](https://tuftsdatalab.github.io/badges/zip.svg)](https://github.com/tuftsdatalab/python-data-analysis/zipball/main)&nbsp;
[![Download TarGz](https://tuftsdatalab.github.io/badges/tgz.svg)](https://github.com/tuftsdatalab/python-data-analysis/tarball/main)&nbsp;
![download size](https://img.shields.io/github/repo-size/tuftsdatalab/python-data-analysis?label=download%20size)&nbsp;
![last updated](https://img.shields.io/github/last-commit/tuftsdatalab/python-data-analysis?label=last%20updated)

**A Tufts University Data Lab Workshop**\
Written by Uku-Kaspar Uustalu

[![datalab.tufts.edu](https://tuftsdatalab.github.io/badges/datalab.svg)](https://sites.tufts.edu/datalab)&nbsp;
[![@TuftsDataLab](https://tuftsdatalab.github.io/badges/twitter.svg)](https://twitter.com/intent/follow?screen_name=tuftsdatalab)

Python resources: [go.tufts.edu/python](https://sites.tufts.edu/datalab/python/)\
Questions: <datalab-support@elist.tufts.edu>\
Feedback: <uku-kaspar.uustalu@tufts.edu>

Workshop slides: [tufts.box.com/v/python-data-analysis](https://tufts.box.com/v/python-data-analysis)\
Live offerings: [go.tufts.edu/workshops](https://sites.tufts.edu/datalab/workshops/)

---
## Running the Workshop using Binder (virtual JupyterLab) {#binder}
[![Launch Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/tuftsdatalab/python-data-analysis/main?urlpath=lab/tree/python-data-analysis.ipynb){:target="_blank"}

You can launch an online [Binder](https://mybinder.org/) instance with a [JupyterLab](https://jupyterlab.readthedocs.io/en/stable/) interface pre-configured for this workshop as follows:

1. Click on the [**Launch Binder**](https://mybinder.org/v2/gh/tuftsdatalab/python-data-analysis/main?urlpath=lab/tree/python-data-analysis.ipynb){:target="_blank"} button above.
2. A Binder instance will launch in a new tab with the message *Starting Repository*.
3. Wait patiently and do not close the Binder tab.
4. After a few minutes, the notebook will launch in a JupyterLab instance.

---
## Running the Workshop Locally on your Computer {#local}
[![Download Zip](https://tuftsdatalab.github.io/badges/zip.svg)](https://github.com/tuftsdatalab/python-data-analysis/zipball/main)&nbsp;
[![Download TarGz](https://tuftsdatalab.github.io/badges/tgz.svg)](https://github.com/tuftsdatalab/python-data-analysis/tarball/main)

If you have Anaconda or Miniconda installed, you can launch the workshop notebook locally as follows:

1. Click on the [**Download Zip**](https://github.com/tuftsdatalab/python-data-analysis/zipball/main) or [**Download TarGz**](https://github.com/tuftsdatalab/python-data-analysis/tarball/main) button above to download an archive containing the workshop materials.
2. Extract the contents of the downloaded archive to a suitable location and rename the extracted folder if desired.
3. Launch JupyterLab either from the **command line** or via **Anaconda Navigator**.
    - From the **command line**:
        1. Launch **Terminal** (*macOS/Linux*) or the **Anaconda PowerShell Prompt** (*Windows*).
            - **Windows**: *Start > Anaconda3 > Anaconda PowerShell Prompt*
            - **macOS**: *Applications > Utilities > Terminal*
        2. *Optional:* If you are using Miniconda or have modified your base Anaconda environment, create and activate a new environment for this workshop using the included **environment.yml** file as follows:
            1. Navigate to the folder containing the extracted workshop materials from within the console.
            2. Create a new environment for the workshop: `conda env create -f binder/environment.yml`
            3. Activate the workshop environment: `conda activate python-data-analysis`
        3. Type `jupyter lab` and press **Enter/Return** to launch JupyterLab.
    - Using **Anaconda Navigator**:
        1. Launch Anaconda Navigator via the Start Menu (*Windows*) or from Applications (*macOS*).
            - **Windows**: *Start > Anaconda3 > Anaconda Navigator*
            - **macOS**: *Applications > Utilities > Terminal*
        2. Launch **JupyterLab** using the corresponding *Launch* button.
4. JupyterLab will open in a web browser. (A new tab will be generated if a browser is already open.)
5. Within the JupyterLab file explorer on the left, navigate to the location of the extracted folder containing the workshop materials.
6. Once you are in the correct directory, *double-click* on **python-data-analysis.ipynb** in the file browser to open the workshop notebook.