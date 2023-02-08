# CRF-Based-Malayalam-Chunker
CRF-Based-Malayalam-Chunker
# This is a CRF based Chunker. Please install CRF++ toolkit. All the necessary details can be accesed from the below website:
https://taku910.github.io/crfpp/
# How to run the chunker
crf_test -m model_path input_file > output_file
## model_path: Chunker Model Path
## input_file: Contains token and pos separated by a tab in conll format. Sentences are separated by a blank line
## output_file: Contains token, pos, chunk separated by a tab in conll format. Sentences are separated by a blank line
# Here, you can use the following command
crf_test -m malayalam-chunk-model.m malayalam_chunker_input.txt > malayalam_chunker_output.txt
