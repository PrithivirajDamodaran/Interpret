# Interpret

The PyTorch implementation the [Smooth Grad](https://arxiv.org/pdf/1706.03825.pdf) and [Integrated Gradients](https://arxiv.org/pdf/1703.01365.pdf) for NLP Models.

This repository based on the [Allen NLP Interpret Module](https://github.com/allenai/allennlp/tree/master/allennlp/interpret) but for HuggingFace.


### The example of the output:
<!-- ![](https://miro.medium.com/max/1056/1*w0f8xVbGBZHF7U04OINrVw.png) -->

### Integrate your own task-specific model

To integrate your model simply override the [forward_step](https://github.com/koren-v/Interpret/blob/master/saliency_interpreter.py#L89) and [update_output](https://github.com/koren-v/Interpret/blob/master/saliency_interpreter.py#L102) methods of base class SaliencyInterpreter.
