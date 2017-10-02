# Uploading multiple user SBML files to a Jupyter notebook

Demonstration of uploading multiple user SBML (or indeed any) files to a Jupyter notebook

This notebook is aimed at a niche bit of Computational Biology, but if you ignore all the bio bits it also explains how to do multiple user file uploads within a Jupyter notebook.

Uploads rely upon peteut's excellent IPython widget at https://github.com/peteut/ipython-file-upload.

tldr: You must write the file content into a global in order to access it elsewhere in the notebook.

Reading SBML via libSBML within a Jupyter notebook is easy enough from a local file on the host, but much harder for files uploaded by the user. As it took me a whole day to sort out a solution I thought I'd share.
