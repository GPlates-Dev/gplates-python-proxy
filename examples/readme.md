Use the following commands to create a running environment

    `conda create --name gplates-ws-example -c conda-forge cartopy matplotlib moviepy shapely jupyter requests`

    `conda activate gplates-ws-example`

    `pip install gplates-ws-proxy`

You may use the environment.yml to create the conda env as well.

    `conda env create -f environment.yml`

### Reconstruct locations

👉 [reconstruct locations](reconstruct_shapely_points.py)

The red dots are present-day locations. The blue dots are paleo-locations at 100Ma.

![reconstruct_shapely_points](https://github.com/michaelchin/gplates-python-proxy/assets/2688316/382818ab-3742-4660-9602-6579c39dc737)

### Plot paleo-coastlines

👉 [paleo-coastlines movie](paleo-coastlines.ipynb)

![paleo-coastlines movie](https://github.com/michaelchin/gplates-python-proxy/assets/2688316/11113728-967a-445c-9941-7b82523138ea)

### Plot paleo-labels

👉 [paleo-labels](plot_paleo_labels.py)

![plot_paleo_labels](https://github.com/michaelchin/gplates-python-proxy/assets/2688316/5e3a1f6b-e1d7-4d9f-b2f8-967e530d3a8e)

### Plot subduction zones

👉 [plot_subduction_zones.py](plot_subduction_zones.py)

![plot_subduction_zones](https://github.com/michaelchin/gplates-python-proxy/assets/2688316/5b491f47-38df-4dd4-80c6-ded0e17fe965)

