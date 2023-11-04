# segmind/SSD-1B LoRA inference Cog model

This is an implementation of the [segmind/SSD-1B](https://huggingface.co/segmind/SSD-1B) as a Cog model. [Cog packages machine learning models as standard containers.](https://github.com/replicate/cog)

First, download the pre-trained weights:

    cog run script/download-weights

Then, you can run predictions:

    cog predict -i lora_url=@trained_model.tar -i prompt="a photo of TOK"

## Example:

"a photo of TOK"

![alt text](output.png)