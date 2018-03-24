# Data Analysis with R (using Jupyter Notebook)

If you are using Jupyter through Anaconda distribution, to install R via conda manager, just do:

```
conda install -c r r-essentials
```

After that, you may find this sort of error: 

```
from jupyter_core.utils import ensure_dir_exists
ImportError: cannot import name 'ensure_dir_exists'
```

If so, update jupyter_core and jupyter_client manually:

```
conda update jupyter_core jupyter_client
```

Done!
