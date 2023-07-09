Dataset **iSAID Airplane** can be downloaded in Supervisely format:

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/H/x/m9/uKsrSxJZdQtMD9PBbsfdATJkkxo1E6FmoN56cLOnQ8bo3D1F0nl59xsUNKhJOM1JwLQufVwT0ybMEpbhp2LhgCAfU56aahJRHyQ3D7FlE9Jbee4pAjVGlYgXqiB5.tar)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='iSAID Airplane', dst_path='~/dtools/datasets/iSAID Airplane.tar')
```
The data in original format can be 🔗[downloaded here](https://www.kaggle.com/datasets/romanrybalko/isaid-plane-gray/download?datasetVersionNumber=1)