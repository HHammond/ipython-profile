# IPython Profile

This repo is a clone of my local IPython profile which adds a features to
IPython such as importing Matplotlib, Numpy and Pandas as well as setting inline
plotting by default.

I use this profile with my D3 inspired [Matplotlibrc](https://github.com/HHammond/Matplotlibrc).

To use this IPython profile just use the following bash commands:

```bash
cd $(ipython locate)
mv profile_default profile_default.bk
git clone git@github.com:HHammond/ipython-profile.git profile_default
```

## Features:

* Pretty Tables and Notebook

* DataFrame Summary Row and Column:

    ```
    summarize(df)
    ```

    Function information [here](https://github.com/HHammond/ipython-profile/blame/master/startup/01_init_formatting.py#L7-L37).

* Percentage Formatting:

    ```
    as_percent(0.5)
    ```
    
    Function information [here](https://github.com/HHammond/ipython-profile/blame/master/startup/01_init_formatting.py#L40-L55).

* Automatic Imports:
    * Numpy as `np`
    * Pandas as `pd`
    * PyPlot as `plt`

## Preview

##### Main Interface
![](http://i.imgur.com/2VmQyZh.png)

##### Typography
![](http://i.imgur.com/ZMTginu.png)
![](http://i.imgur.com/f7wSnyz.png)

##### Tables
![](http://i.imgur.com/JCgBgYq.png)

