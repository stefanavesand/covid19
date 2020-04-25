# voila-covid19-viewer
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/stefanavesand/covid19/master?urlpath=voila%2Frender%2Findex.ipynb)

Experimental web app built with Jupyter, ipywidgets, ipyleaflet, plot.ly and voila for visualization of COVID-19 trends.

![image](https://user-images.githubusercontent.com/6136323/80289963-382e3400-8710-11ea-9589-3af7c1f018c9.png)

## Usage

```bash
voila index.ipynb
```

To automatically cull idle kernels:

```bash
voila --MappingKernelManager.cull_interval=10 --MappingKernelManager.cull_idle_timeout=10 app.ipynb
```
