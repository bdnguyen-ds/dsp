# Jupyter Notebook:  Getting Started
The Jupyter notebook is an interactive computational environment, in which you can combine code, execution, rich text, mathematics, plots and rich media. 

---

### [Install the Notebook](http://jupyter.readthedocs.io/en/latest/install.html)
Installing Jupyter using Anaconda and conda:  
For new users, we highly recommend [installing Anaconda](https://www.continuum.io/downloads). Anaconda conveniently installs Python, the Jupyter Notebook, and other commonly used packages for scientific computing and data science.  (Prereq: Python is installed.)

Once anaconda is installed, you can launch the notebook by typing
```{bash}
$ jupyter notebook
```

### Upgrade all libraries/packages
We will now update all the packages/libraries installed by anaconda to ensure you have the latest version of everything!

```{bash}
$ conda update --all
```

### Run the Notebook at Terminal Prompt  
Note:  The notebook will open at the directory in which you launch the notebook on your terminal.  
```
$ jupyter notebook
```
>[BDN]my example
```console
reshama$ jupyter notebook
[I 11:41:22.769 NotebookApp] Serving notebooks from local directory: /Users/reshamashaikh/_ds/metis
[I 11:41:22.769 NotebookApp] 0 active kernels 
[I 11:41:22.769 NotebookApp] The Jupyter Notebook is running at: http://localhost:8888/
[I 11:41:22.769 NotebookApp] Use Control-C to stop this server and shut down all kernels (twice to skip confirmation).
```

### Shut Down the Juypter Notebook App
At terminal prompt:  
 * control + c
 * type:  `y`
 
>[I 16:25:06.371 NotebookApp] JupyterLab extension loaded from C:\ProgramData\Anaconda3\lib\site-packages\jupyterlab
[I 16:25:06.371 NotebookApp] JupyterLab application directory is C:\ProgramData\Anaconda3\share\jupyter\lab
[I 16:25:06.372 NotebookApp] Serving notebooks from local directory: D:\Users\huahuashishi
[I 16:25:06.372 NotebookApp] The Jupyter Notebook is running at:
[I 16:25:06.372 NotebookApp] http://localhost:8888/?token=c6c010c799b879a333e1d6310ae7e30c971362461c2dabbf
[I 16:25:06.373 NotebookApp]  or http://127.0.0.1:8888/?token=c6c010c799b879a333e1d6310ae7e30c971362461c2dabbf
[I 16:25:06.373 NotebookApp] Use Control-C to stop this server and shut down all kernels (twice to skip confirmation).
[C 16:25:06.423 NotebookApp]

    To access the notebook, open this file in a browser:
        file:///C:/Users/huahuashishi/AppData/Roaming/jupyter/runtime/nbserver-51076-open.html
    Or copy and paste one of these URLs:
        http://localhost:8888/?token=c6c010c799b879a333e1d6310ae7e30c971362461c2dabbf
     or http://127.0.0.1:8888/?token=c6c010c799b879a333e1d6310ae7e30c971362461c2dabbf
[E 16:25:07.657 NotebookApp] Could not open static file ''
[W 16:25:07.702 NotebookApp] 404 GET /static/components/react/react-dom.production.min.js (::1) 5.98ms referer=http://localhost:8888/tree?token=c6c010c799b879a333e1d6310ae7e30c971362461c2dabbf
[W 16:25:07.706 NotebookApp] 404 GET /static/components/react/react-dom.production.min.js (::1) 1.00ms referer=http://localhost:8888/tree?token=c6c010c799b879a333e1d6310ae7e30c971362461c2dabbf
[I 16:25:16.423 NotebookApp] Interrupted...
[I 16:25:16.423 NotebookApp] Shutting down 0 kernels
```console
^C[I 11:43:35.486 NotebookApp] interrupted
Serving notebooks from local directory: /Users/reshamashaikh/_ds/metis
0 active kernels 
The Jupyter Notebook is running at: http://localhost:8888/
Shutdown this notebook server (y/[n])? y
[C 11:43:37.782 NotebookApp] Shutdown confirmed
[I 11:43:37.783 NotebookApp] Shutting down kernels
reshama$ 
```

---

### Getting to Know Jupyter

You can try out Jupyter on a browser without installing it.  
https://try.jupyter.org/

