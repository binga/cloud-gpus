# Cloud GPU Vendors

This repository contains information about service providers who host GPUs in
the cloud for on-demand use for Machine Learning practitioners. This guide is
also designed to help enthusiasts, new-comers to this field and also experienced
folks to keep a track of new updates made by all these vendors and keep their
costs low when deciding to choose their preferred platform.

## Cloud GPU Vendors

- "-" means not available
- "???" means maybe available
- GPU prices are per hour
- Storage prices are per GB/month

| GPU Cloud Provider                                                                                    | K80 Price | V100 Price | Storage Price  | Last Updated |
| ----------------------------------------------------------------------------------------------------- | --------- | ---------- | -------------- | ------------ |
| [Google Colaboratory](https://colab.research.google.com/)                                            | Free      | -          | 15GB max       | 8-Sep-18     |
| [Kaggle Kernels](https://www.kaggle.com/dansbecker/running-kaggle-kernels-with-a-gpu)                 | Free      | -          | 8GB max        | 8-Sep-18     |
| [Salamander](https://salamander.ai/)                                                                  | $0.36     | $1.17      | $0.10          | 8-Sep-18     |
| [Paperspace](https://www.paperspace.com/)                                                             | $0.59     | $2.30      | $0.10          | 8-Sep-18     |
| [Vast.AI](https://vast.ai/)                                                                           | $0.64     | $2.30      | -              | 19-Sep-18    |
| [Oracle Cloud](https://cloud.oracle.com/compute/gpu/features)                                         | -         | $2.25      | $0.04          | 8-Sep-18     |
| [Spell](https://spell.run/)                                                                           | $0.27     | $3.06      | ???            | 8-Sep-18     |
| [Crestle](https://www.crestle.com/)                                                                   | $0.59     | -          | $0.42          | 8-Sep-18     |
| [Neptune ML](https://neptune.ml/)                                                                     | $0.64     | -          | $0.28          | 8-Sep-18     |
| [Microsoft Azure](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/sizes-gpu)          | $0.87     | $2.95      | $0.10          | 8-Sep-18     |
| [LeaderGPU](https://www.leadergpu.com/)                                                               | -         | $3.00      | $0.13          | 8-Sep-18     |
| [Amazon Web Services (AWS)](https://aws.amazon.com/ec2/instance-types/p2/)                            | $0.90     | $3.06      | $0.10          | 8-Sep-18     |
| [DeepCognition](https://deepcognition.ai/)                                                            | $0.90     | $3.06      | ???            | 8-Sep-18     |
| [Google Cloud Platform (GCP)](https://cloud.google.com/gpu/)                                          | $1.21     | $3.24      | $0.03          | 8-Sep-18     |
| [FloydHub](https://www.floydhub.com/)                                                                 | $1.20     | $4.20      | 100GB included | 8-Sep-18     |
| [IBM Cloud](https://www.ibm.com/cloud/gpu)                                                            | $2.65     | -          | ???            | 8-Sep-18     |
| [Alibaba Cloud](https://www.alibabacloud.com/product/gpu?spm=a3c0i.11728334.1144220.1.23794a1clKeiCs) | -         | ???        | ???            | 8-Sep-18     |
| [Lambda Labs](https://lambdalabs.com/)                                                                | -         | ???        | ???            | 8-Sep-18     |
| [Nvidia Cloud](https://www.nvidia.com/en-us/data-center/gpu-cloud-computing/)                         | ???       | ???        | ???            | 8-Sep-18     |
| [Riseml](https://riseml.com/)                                                                         | -         | ???        | ???            | 8-Sep-18     |
| [Valohai](https://valohai.com/)                                                                       | ???       | ???        | ???            | 8-Sep-18     |
| [VScaler](https://www.vscaler.com/)                                                                   | ???       | ???        | ???            | 8-Sep-18     |

### Other GPUs

| GPU Cloud Provider                                                                                    | P100 Price | GTX 1080 Price | Storage Price | Last Updated |
| ----------------------------------------------------------------------------------------------------- | ---------- | -------------- | ------------- | ------------ |
| [Snark AI](https://snark.ai/)                                                                         | $0.10      | -              | ???           | 8-Sep-18     |
| [Vast.AI](https://vast.ai/)                                                                           | $1.65      | $0.10          | -             | 8-Sep-18     |
| [Oracle Cloud](https://cloud.oracle.com/compute/gpu/features)                                         | $1.28      | -              | $0.04         | 8-Sep-18     |
| [Vector Dash](https://vectordash.com/)                                                                | -          | $0.51          | ???           | 8-Sep-18     |
| [LeaderGPU](https://www.leadergpu.com/)                                                               | $1.50      | $0.75          | $0.13         | 8-Sep-18     |
| [Paperspace](https://www.paperspace.com/)                                                             | $1.72      | -              | $0.10         | 8-Sep-18     |
| [Microsoft Azure](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/sizes-gpu)          | $2.00      | -              | $0.13         | 8-Sep-18     |
| [Ovh](https://www.ovh.com/world/public-cloud/instances/prices/)                                       | -          | $1.15          | $0.09         | 8-Sep-18     |
| [Neptune ML](https://neptune.ml/)                                                                     | $2.15      | -              | $0.28         | 8-Sep-18     |
| [Google Cloud Platform (GCP)](https://cloud.google.com/gpu/)                                          | $2.22      | -              | $0.03         | 8-Sep-18     |
| [Alibaba Cloud](https://www.alibabacloud.com/product/gpu?spm=a3c0i.11728334.1144220.1.23794a1clKeiCs) | ???        | -              | ???           | 8-Sep-18     |
| [Exoscale](https://exoscale.com/)                                                                     | ???        | -              | ???           | 8-Sep-18     |
| [IBM Cloud](https://www.ibm.com/cloud/gpu)                                                            | ???        | -              | ???           | 8-Sep-18     |

## Notes

- Google Cloud Platform gives you
[$300 free compute credits](https://cloud.google.com/free/)

- Azure gives
[$100 free compute credits](https://azure.microsoft.com/en-in/free/students/)
to students

- Google Colaboratory, Kaggle Kernels & Crestle are only for Jupyter Notebooks
and limited to 6/12/24 hour sessions

- The prices for Google Cloud Platform assume you've attached the GPUs to a
"n1-standard-16" instance.

- 250GB Paperspace volumes are $0.04 per GB; larger or smaller volumes cost more

### Cloud Credits

For the benefit of beginners, we included a cloud credits section which will help beginners try these platforms for their hobby project, take it for a spin and choose the platform of their choice.

Update (August 17, 2018):
- 20$ of credit (~100 hours of GPU compute) for fastai students by Vast.ai. Check their announcement here.

Update (August 12, 2018):
- 2 hours of free trial on DeepCognition.

Update (August 10, 2018):
- 75-150$ AWS credits for students with [GitHub Education Pack](https://education.github.com/pack). You would need a .edu student email address.

Update (August 2, 2018):
- 42 hours of 1080 GPU credits by Snark AI for fastai students. Promo Code available on fastai forums.

Update (July 6, 2018):
- 100 hours of GPU give away by FloydHub to the folks at RemoteML. Check out their tweet to participate.

Update (May 8, 2018):
- 15$ credit in PaperSpace for fastai students. Credit Code available here.


## GPU Datasheets

Nvidia manufactures all the GPUs listed here

| GPU                                                                                                                        | TFlops (double / single precision) |
| -------------------------------------------------------------------------------------------------------------------------- | ---------------------------------- |
| [K80](https://www.nvidia.com/content/dam/en-zz/Solutions/Data-Center/tesla-product-literature/TeslaK80-datasheet.pdf)      | 1.9 / 5.6                          |
| [V100](https://images.nvidia.com/content/technologies/volta/pdf/tesla-volta-v100-datasheet-letter-fnl-web.pdf)             | 7.8 / 125.0                        |
| [P100](https://images.nvidia.com/content/tesla/pdf/nvidia-tesla-p100-datasheet.pdf)                                        | 5.3 / 10.6                         |
| [GTX 1080](https://international.download.nvidia.com/geforce-com/international/pdfs/GeForce_GTX_1080_Whitepaper_FINAL.pdf) | 8.8 / 8.8                          |
