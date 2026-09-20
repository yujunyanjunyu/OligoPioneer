# OligoPioneer

OligoPioneer is a deep learning model for tandem mass spectrometry (MS/MS) prediction, focusing on oligopeptides analyzed under quadrupole time-of-flight collision-induced dissociation (QTOF-CID) conditions.

## Model Weights

The trained OligoPioneer model weights are hosted on Hugging Face:

[Download OligoPioneer model weights](https://huggingface.co/yujunyanjunyu/OligoPioneer/tree/main)

## Note

OligoPioneer incorporates oligopeptide sequence representations generated using the pretrained ESM Cambrian protein language model (ESMC).

The pretrained ESMC-600M weights are available from the official Hugging Face repository:

[ESMC-600M pretrained weights](https://huggingface.co/biohub/ESMC-600M)

[Official ESM code repository](https://github.com/Biohub/esm)

The ESMC weights are not redistributed in this repository. Users should obtain them from the official source and comply with the corresponding license and citation requirements.
