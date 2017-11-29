# How to add kernels to Jupyter notebooks
## IPython kernels
The following steps show how to make an IPython kernel (even if it is in a conda/virtualenv environment) available to an existing jupyter installation:

1. Enable the environment whose IPython kernel you want to use from Jupyter. For a conda environment, you need to do:

   ```
   activate <env_name>
   ```
  
2. Install the IPython Kernel for Jupyter package (a.k.a. `ipykernel`):

   ```
   pip install ipykernel
   ```
   
3. Create your kernel. Assign it a `<name>` and, optionally, a `<display_name>` to be shown in the Jupyter Notebook menu:

   ```
   python -m ipykernel install --user --name <name> --display_name <display_name>
   ```
   
   **Note:** Since we have passed the `--user` option, this will create a user-specific kernelspec directory describing the kernel so that it is locatable by every Jupyter installation. Non-user kernels can be also available. You can list the kernels available to any Jupyter executable as follows:
   
   ```
   jupyter kernelspec list
   ```

## Other kernels
The specific steps will depend on the particular kernel. Check the corresponding documentation for details.
