# Capstone Deloyment

This Capstone project was created in Jupiter Notebook locally. Bound and built library dependency package using API provided by https://mybinder.org/. Docker image was uploaded onto Jupiter server automatically using webservice as link below:

https://hub.gke2.mybinder.org/user/juliepone-capstone-ls63vtsp/notebooks/JP_Capstone_Final.ipynb

This Notebook application can be executed directly from server by Run Cells or Run All. The output tables and plots will be displayed. Different datasets could be applied using same model algorithms. Different DataFrame and plots will be generated accordingly.

Original codes are stored in github repository.
https://github.com/JuliePone/Capstone

If encounter http error due to github repository changed, please rebuild image as following:
1. Go to https://mybinder.org/. Enter https://github.com/JuliePone/Capstone in GitHub repository name or URL field.
2. Copy the URL below and share your Binder with others, e.g. https://hub.gke2.mybinder.org/user/juliepone-capstone-ao122czl
3. The docker image will be push onto server again and then Jupiter Notebook will be launched automatically. 
4. Click JP_Capstone_Final.ipynb under Files folder. 
5. Copy and store the URL for use later.
6. Select Cell>Run All. The output tables and plot results will be populated.

Below are the web service offered by www.mybinder.org:
1. Enter your repository information
Provide in the above form a URL or a GitHub repository that contains Jupyter notebooks, as well as a branch, tag, or commit hash. Launch will build your Binder repository. If you specify a path to a notebook file, the notebook will be opened in your browser after building.
2. We build a Docker image of your repository
Binder will search for a dependency file, such as requirements.txt or environment.yml, in the repository's root directory (more details on more complex dependencies in documentation). The dependency files will be used to build a Docker image. If an image has already been built for the given repository, it will not be rebuilt. If a new commit has been made, the image will automatically be rebuilt.
3. Interact with your notebooks in a live environment!
A JupyterHub server will host your repository's contents. We offer you a reusable link and badge to your live repository that you can easily share with others.


