# Virtual Research Environments

Virtual research environments (VREs) provide user-centric support in the lifecycle of research activities, for example, 
discovering and accessing research assets or composing and executing application workflows. The LifeWatch VRE platform 
provides a workflow management system, a data management framework, and tools for enabling collaboration among users. 



# Tutorials

This section of the documentation contains step-by-step tutorials that help outline the capabilities of Virtual Research 
Environments (VRE) and how you can achieve specific aims. The tutorials are recommended if you do not have much 
experience with VRE.

* [Tutorials](tutorials/README.md)
  * [Getting Started](tutorials/README.md#getting-started)
  * [Add Custom Module Names](tutorials/README.md#add-custom-module-names)



## Platform as A Service VRE (PaaSVRE)


The LifeWatch VRE platform is a Platform as a Service (PaaS) that provides a set of tools and services to support custom 
VREs.

### Main Features

* A user-friendly interface to the LifeWatch VRE platform
* Overview of the running Virtual Labs (VLs)
* Overview of executed workflows
* Community based data products catalog
* Community based geographical data products catalog
* Collaboration tools
  * Video conferencing with [jupyter-videochat](https://jupyter-videochat.readthedocs.io/en/latest/)
  * Git integration with [jupyterlab-git](https://pypi.org/project/jupyterlab-git/) 


## Notebook as a Virtual Research Environment (NaaVRE)

The Notebook as a Virtual Research Environment (NaaVRE) is a set of tool build on top of JupiterLab that provides a
user-friendly interface to the LifeWatch VRE platform. 

### Main Features
* Containerization of cells 
* Workflow composition based on containerized cells
* Execution of containerized cells on a workflow engine
* Search for notebooks

### Supported Kernels
* Python 
* Rscript 