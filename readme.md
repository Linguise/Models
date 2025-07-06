## Linguise Models
This repository is a collection of some of my pretrained llms for my Project [Linguise](https://github.com/c4vxl/Linguise/).

#### Overview of the models:
1. `pretrained-lstm-100.mdl`: This is just a pretrained version of an lstm model. Use this for finetuning.

URL: https://cdn.c4vxl.de/Linguise-models/pretrained-lstm-100.mdl

2. `eliza-lstm-50.mdl`: This is a finetuned version of `pretrained-lstm.mdl`. It has been finetuned to act as the popular model [Eliza](https://en.wikipedia.org/wiki/ELIZA). The dataset can be found [here](https://huggingface.co/datasets/MIND-INTERFACES/ELIZA-EVOL-INSTRUCT)

URL: https://cdn.c4vxl.de/Linguise-models/eliza-lstm-50.mdl

1. `not.mdl`: This model just answers with the opposite word of what you prompted it with
URL: https://cdn.c4vxl.de/Linguise-models/not.mdl


_Note that you can actually finetune or even train your own models using the [jNN-python library](https://github.com/c4vxl/jNN-python/)_
