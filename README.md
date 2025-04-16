# ClinicaDL tutorials

To run the tutorials, you need a [Python environment with ClinicaDL](https://clinicadl.readthedocs.io/en/latest/installation.html).
You will also need some additional dependencies to run the notebooks (`matplotlib`, `notebook`, etc.), that you can install
with the following command:

```
poetry install --extras tutorials
````

> **_NOTE:_** In the future, extra dependencies will be downloaded via: ```pip install clinicadl[tutorials]```

You can then run the tutorials, either:

- by **opening the notebook in your IDE**, and selecting the right kernel (your `ClinicaDL` environment),

or:

- by activating your `ClinicaDL` environment, and **opening the notebook in your browser** using:

    ```
    jupyter notebook
    ```