Dataset **iSAID Airplane Grayscale** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/k/L/2V/oIcnRLbBd4hmMFmBFpcC2qGZKlHDcTY4A6EWuLwbbRs4tu9YJ1wRIOJu7Ht1xq4kanEfoFOmHIHddVxDZvs7f5vtTLTfpuFmVHBWvAoDDXK6o0MRaEQ1oqI7HU0l.tar)

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