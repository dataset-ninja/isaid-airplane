Dataset **iSAID Airplane Grayscale** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/V/L/u8/04JYEt14GNftDPJFDbFET2EG92ovJ5b3pj6pvE07bZqAPfoEwd568bIGMKBFVbIHJkS6oLHGFnEe1IMLWQyYIp8ee4YqkKGNYFfqgUTyHsRAp0wf8iHvjz8ahb15.tar)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='iSAID Airplane Grayscale', dst_dir='~/dataset-ninja/')
```
Make sure not to overlook the [python code example](https://developer.supervisely.com/getting-started/python-sdk-tutorials/iterate-over-a-local-project) available on the Supervisely Developer Portal. It will give you a clear idea of how to effortlessly work with the downloaded dataset.

The data in original format can be [downloaded here](https://www.kaggle.com/datasets/romanrybalko/isaid-plane-gray/download?datasetVersionNumber=1).