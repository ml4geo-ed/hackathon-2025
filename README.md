# hackathon-2025

Welcome to ML4GEO's inaugaral Ideathon/Hackathon for Geospatial Foundation Models (GFM). 

Below we've collated a list of helpful links and tutorials to get you started:

## Foundation Models / Tutorials

  * **TerraTorch**: Built on PyTorch, enables access to multiple vision (TerraMind, Clay, SSL4EO,...) and weather foundation models (Pritvi). Many examples of image classification, downscaling @
    * https://github.com/IBM/terratorch/tree/main/examples/notebooks
   
  * **TerraMind**: The latest GFM from ESA, can be applied for classical deep learning tasks, as well as generative tasks (e.g. S1 from S2 data)
    *  https://github.com/IBM/ML4EO-workshop-2025
      * Examples of disaster response with S1 and S2; multi-temporal data crop segmentation 

  * **Google Satellite v1 Embeddings**:
    * https://developers.google.com/earth-engine/datasets/catalog/GOOGLE_SATELLITE_EMBEDDING_V1_ANNUAL
    * We have scripts to help download rasters of embeddings with python API

  * **SatCLIP:** Predict location coordinates given satellite imagery
    * https://github.com/microsoft/satclip/tree/main/notebooks   


## Challenges

 * [ESA Phi Lab - AI4EO challenges](https://platform.ai4eo.eu/)
 * [Terramind Blue Sky challenge](https://www.fast-eo.eu/news/terramind-blue-sky-challenge)
 * [Zindi - Amini GeoFM Decoding the Field Challenge](https://zindi.africa/competitions/amini-geofm-decoding-the-field-challenge)


## ML-ready datasets

### Unlabelled

* [ESA's MajorTOM dataset](https://github.com/ESA-PhiLab/Major-TOM) - 50+TB of Sentinel-1 and -2 data and DEMs.

### Labelled

* [Torchgeo DataModules](https://torchgeo.readthedocs.io/en/latest/api/datamodules.html) - torchgeo has a number of datasets readily available to import prepped in a format read for ML. If you are using the TerraTorch, this is particularly useful as it is built on top of TorchGeo so can be used off-the-shelf.
* [PhilEO](https://huggingface.co/datasets/PhilEO-community/PhilEO-downstream) - 400GB Sentinel-2 dataset of the PhilEO Bench containing labels for the three downstream tasks of building density estimation, road segmentation, and land cover classification.
