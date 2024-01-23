FROM python:3.11

RUN apt-get update

RUN pip install --upgrade pip

RUN python -m pip install --upgrade pip \
&&  pip install --no-cache-dir \
    black \
    jupyterlab \
    jupyterlab_code_formatter \
    jupyterlab-git \
    lckr-jupyterlab-variableinspector \
    jupyterlab_widgets \
    ipywidgets \
    import-ipynb

RUN pip install --no-cache-dir \
    numpy \
    pandas \
    scipy \
    scikit-learn \
    pycaret \
    matplotlib \
    japanize_matplotlib \
    mlxtend \
    seaborn \
    plotly \
    requests \
    beautifulsoup4 \
    Pillow \
    opencv-python

RUN pip install --no-cache-dir \
    openpyxl
