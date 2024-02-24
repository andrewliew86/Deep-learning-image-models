# Image classifier using image transformer model
Background:
Image classifiers allow a user to quickly label food items from provided images. In this proof of concept study, I fine-tuned a pretrained encoder vision transformer model from the open access libraries (HuggingFace) using a labelled food dataset (food101 from Hugging Face). 

Results:
I did some preliminary testing with and it does a decent job at identifying common food types but struggles with images that are not food (e.g. cat). Further fine-tuning will be needed to improve performance and reduce false positives. 

Python libraries/tools: 🤗 transformers, PyTorch. 
