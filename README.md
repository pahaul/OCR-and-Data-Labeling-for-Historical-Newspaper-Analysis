OCR-and-Data-Labeling-for-Historical-Newspaper-Analysis

This repository documents a Proof-of-Concept (POC) for training a custom neural network to perform OCR on historical newspaper images of the historical Nazi-era newspaper "[Der Freiheitskampf](https://hait.tu-dresden.de/ext/forschung/der-freiheitskampf.asp)". The project showcases the completed upstream data pipeline required for supervised learning, including manual data annotation (Ground Truth creation) and the low-level PyTorch transformation of image and label data into Tensors. The focus is placed on establishing a robust and production-ready data flow (MLOps readiness) rather than the final model performance.


This project's value lies in its demonstration of the initial, high-effort MLOps steps required to prepare custom data for model training:

Custom Data Labeling & Ground Truth: Manual annotation of image sections (specifically, headlines) using a professional labeling tool [LabelStudio](https://labelstud.io) to create the necessary Ground Truth labels for supervised learning.

Deep Learning Framework: Utilized PyTorch (torch, nn.Module) for defining the network architecture and handling complex data structures (Tensors).

CV Data Transformation: Focused heavily on the process of transforming labeled image data and their corresponding labels into PyTorch Tensors, including handling multiple data channels (tensors/images).
