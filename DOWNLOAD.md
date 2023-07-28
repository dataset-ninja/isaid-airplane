Dataset **iSAID Airplane Grayscale** can be downloaded in Supervisely format:

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/3/P/rf/Zxgort8MxLShf6pd2KgFGKGJT6iCqYGiByQWTfOVhJj8qmLKewASNb9OGAKKfRTOWkOZoCxMCWztLjolWsEpidkvWIjb4x7u2e06MHYtWnwIuSLNylauTPjieSRv.tar)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='iSAID Airplane Grayscale', dst_path='~/dtools/datasets/iSAID Airplane Grayscale.tar')
```
The data in original format can be 🔗[downloaded here](https://www.kaggle.com/datasets/romanrybalko/isaid-plane-gray/download?datasetVersionNumber=1)