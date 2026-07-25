# Medical Imaging Projects

# Optic Disc and Cup Segmentation for Glaucoma Detection:

The repository contains weights for the pretrained model which can segment the optic disc and optic cup from retinal scans. It has then been used to calculate the Cup to Disc Ratio(CDR), which is used as a marker for glaucoma detection.

## Dataset:
Drishti-GS - RETINA DATASET FOR ONH SEGMENTATION
```
https://www.kaggle.com/datasets/lokeshsaipureddi/drishtigs-retina-dataset-for-onh-segmentation
```

## Models:
model_od.pth : Optic Disc Segmentation Model
model_cuo.pth : Optic Cup Segmentation Model

## Framework:
PyTorch

## References:
```
https://cdn.iiit.ac.in/cdn/cvit.iiit.ac.in/images/ConferencePapers/2014/MadhulikaUjjwal2013Drishti.pdf
https://cvit.iiit.ac.in/mip/datasets.html
```

## Hugging Face repository:
```
https://huggingface.co/Yashu13/od-cup-segmentation-glaucoma-detection
```
\\


# Medical Text Extraction using Retrieval Augmented Generation:

The notebook uses a basic RAG pipeline for revision flashcard generation, utilising:

## Features
```
Text extraction from pdf using PyMuPDF
Text chunking
Semantic Embeddings via BAAI/bge-base-en-v1.5
Similarity search via FAISS
Flashcard generation using Qwen2.5-3B-Instruct
```

## Dataset:
ICMR: Definition_of_terms_used_in_limitation_of_treatment_and_providing_palliative_care_at_end_of_life.pdf
```
https://www.icmr.gov.in/icmrobject/custom_data/pdf/downloadable-books/Definition_of_terms_used_in_limitation_of_treatment_and_providing_palliative_care_at_end_of_life.pdf
```

## Reference:
```
https://www.youtube.com/watch?v=0jOlZpFFxCE
https://huggingface.co/BAAI/bge-base-en-v1.5
```
