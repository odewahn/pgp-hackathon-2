# Install conda

wget https://repo.anaconda.com/archive/Anaconda3-5.2.0-Linux-x86_64.sh

# Install conda

sudo bash Anaconda-latest-Linux-x86_64.sh

# Install Jupyter Lab

conda install jupyterlab


# Start jupyter

```
jupyter lab --port 9999 --ip 0.0.0.0
```

Be sure that you bind to port `0.0.0.0`

It will provide a lin with it's local environment:

```
$ jupyter lab --port 9999 --ip 0.0.0.0
[I 19:31:06.238 LabApp] JupyterLab beta preview extension loaded from /home/ubuntu/anaconda3/lib/python3.6/site-packages/jupyterlab
[I 19:31:06.238 LabApp] JupyterLab application directory is /home/ubuntu/anaconda3/share/jupyter/lab
[I 19:31:06.242 LabApp] Serving notebooks from local directory: /home/ubuntu/team12
[I 19:31:06.242 LabApp] 0 active kernels
[I 19:31:06.242 LabApp] The Jupyter Notebook is running at:
[I 19:31:06.242 LabApp] http://ip-10-0-0-48:9999/?token=4b086322c216fd7bf87c1a537ff5ad9c199b29de91be3698
[I 19:31:06.242 LabApp] Use Control-C to stop this server and shut down all kernels (twice to skip confirmation).
[W 19:31:06.242 LabApp] No web browser found: could not locate runnable browser.
[C 19:31:06.242 LabApp] 
    
    Copy/paste this URL into your browser when you connect for the first time,
    to login with a token:
        http://ip-10-0-0-48:9999/?token=4b086322c216fd7bf87c1a537ff5ad9c199b29de91be3698&token=4b086322c216fd7bf87c1a537ff5ad9c199b29de91be3698
```

# Access the notebook through its public IP address

http://54.174.176.236:9999/lab

Use the token you got in the main link as the auth token:

```
4b086322c216fd7bf87c1a537ff5ad9c199b29de91be3698
```




