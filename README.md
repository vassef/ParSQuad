# ParSQuad
ParSQuAD is a Persian Question Answering Dataset based on Machine Translation of SQuAD 2.
Since the implementation of this dataset hasn't been yet implemented in the hugging face, I have prepared the essential set ups in the hugging face to enable using this data set using the load_dataset library :

from datasets import load_dataset
dataset = load_dataset("Shayanvsf/ParSQuAD")

By running the above command, you'll be able to switch between two modes(manual, Automatic), and the output will be a Dataset Dict that is compatible with the available Transformer models in hugging face.




