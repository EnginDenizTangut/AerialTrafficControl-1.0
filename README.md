Aerial Traffic Control

This project main goal is tracking and counting the cars, from the satellite camera with custom pretrained model.

The model right now just for the first version, it can track and count cars, buses.

Please work on the jupyter notebook or google colab

#
Work On Your PC

Download the files

```bash
  git clone https://github.com/EnginDenizTangut/AerialTrafficControl-1.0.git
```

Go to directory

```bash
  cd my-project
```

Install requirements

```bash
  !pip install -q ultralytics supervision==0.18.0
```

Install libraries

```bash
    import numpy as np
    import supervision as sv
    import os
    from ultralytics import YOLO
    from supervision.assets import download_assets, VideoAssets
```

  
