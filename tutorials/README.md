# Getting Started
This is a quick start guide to use basic functionality of the  LifeWatch VRE Platform as a Service (PaaSVRE) 
and Notebook as a Virtual Research Environment (NaaVRE).

## Platform as A Service VRE (PaaSVRE)
Navigate to the LifeWatch VRE Platform as a Service (VRE PaaS) and click on the 'Sign in' button.
![Sign in](images/sign_in_vre_1.png)
Click on the 'Sign in with Keycloak' button.
![Sign in](images/sign_in_with_keycloak_1.png)
Enter your credentials and click on the 'Sign in' button.
![Sign in](images/sign_in_with_keycloak_2.png)
On the mai panel you will see several Virtual Labs (VLs). Select one of them. When in the VL you can see:
* A decryption of the VL
* The number instances currently running by other users 
* A lunch button to take you to your instance of Notebook as a Virtual Research Environment (NaaVRE)
* Assets that are available to you:
  * Workflow runs 
  * Data products
  * Geographical data products
![VL](images/vl_1.png)

To lunch your instance of NaaVRE click on the 'Lunch my instance' button. where you will be redirected to the 
NaaVRE.

## Notebook as a Virtual Research Environment (NaaVRE)
In the new page click on the 'Sign in' button. 
![VL](images/n-a-a-vre_1.png)
Next you will see the JupiterLab environment. If the Launcher page is not open it by clicking 'File->New->New Launcher'.
![Launcher](images/n-a-a-vre_launcher_1.png)

### Create a new Python Notebook

Click on the 'Python 3' icon to create a new Python Notebook and in the first cell type the following code:
```python
# input list
a = ['a','b','c']
```
![Python Notebook](images/n-a-a-vre_python_notebook_1.png)

Add a new cell and type the following code:
```python
# process the list
for elem in a:
    res = elem + '_processed'
    print(res)
```
![Python Notebook](images/n-a-a-vre_python_notebook_2.png)

### Containerize Cells 
To containerize the cells select the first cell and on the left column click on the 'LifeWatch Panel' button.
![LifeWatch Panel](images/lifeWatch_panel1.png)
On the left panel you will see a preview of the containerized cell with any inputs, outputs and dependencies 
![LifeWatch Panel](images/lifeWatch_panel2.png)
To containerize the cell select the type of the 'a' output as a 'List', the base image as miniconda3 and click on 
the 'Create' button.
![containerize](images/containerize_1.png)
If the containerization is successful you will see a pop-up message.
![containerize](images/containerize_2.png)





# Add Custom Module Names