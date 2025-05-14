# Brain-Tumor-Segmentation

Utilized the BraTS 2020 dataset that was also specifically designed with the
Brain Tumor Segmentation Challenge 2020 to help develop and benchmark algorithms of
interest for segmentation tasks of brain tumors within MRI scans. It comprises multimodal
MRI scans of clinically diagnosed patients with gliomas, both of LGG and HGG types. The
dataset provides four types of MRI modalities:
1. T1-weighted (T1): Provides high-resolution anatomical images of the brain.
2. T1-contrast-enhanced (T1ce): Highlights the active tumor regions by enhancing the
contrast of tumor tissue.
3. T2-weighted (T2): Captures detailed images of the tumor and surrounding edema.
4. FLAIR (Fluid Attenuated Inversion Recovery): Visualizes the presence of edema
and helps in identifying tumor boundaries.
The BraTS 2020 dataset also includes manual segmentations of four main tumor sub-regions:
 Enhancing Tumor (ET): Enhancing section of the tumor indicating active growth.
 Tumor Core (TC): This is the area consisting of the enhancing tumor and its necrotic
components, leaving behind any edema.
 Whole Tumor (WT): The entire extent of the tumor itself, enhancing and nonenhancing
regions, as well as edema.
 Edema: The visible swelling around the tumor, often found in FLAIR imaging mode.
The dataset includes 369 training samples with ground truth annotations for these tumor
regions. This dataset has become a benchmark for evaluating segmentation methods in the field
of medical image analysis, particularly for glioma segmentation.
This multimodal and annotated dataset allows for the development of deep learning
models that can handle complex segmentation tasks, improving tumor diagnosis and treatment
planning. The various MRI sequences provide complementary information, enabling
comprehensive tumor characterization and segmentation.
