This is a repo containing the dataset from the paper "Smart Home Privacy Policies Demystified: A Study of Availability, Content, and Coverage"

### Content_Labels:
The `content_label` directory contains the annotated jsonl files for 284 privacy policies. More details on content_labels can be found in Table 3 of the paper.

### Document Labels:
The `document_label` directory contains the JSON file, which includes document labels as well as additional statistics used in our paper (e.g., amazon ratings).

### NER Model:
In addition to content and document labels, we annotated a set of 600 statements for NER evaluation. The model and train/test data can be found here: [NER Download](https://drive.google.com/drive/folders/1Dqxi3T_TARNRXVct1UWOCzxKiKfWWBkB?usp=sharing)

### Initial_Vendor_List.tsv:
This contains initial list of smart home vendors. Note that the "None" value is used for vendors for which we were not always able to locate the privacy policy links.
