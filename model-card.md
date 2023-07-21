# thesven/whisper-tiny-bn-thesven

  

## Model Description

  
This is the `openai/whisper-tiny` model fine-tuned on the OOD-Speech Bengali dataset. The fine-tuning was performed to enhance the model's performance on Bengali speech recognition tasks, especially for out-of-distribution samples.

  

## Model Details

  

-  **Original Model:** [openai/whisper-tiny on Hugging Face](https://huggingface.co/openai/whisper-tiny)

-  **Fine-tuned Model:** [thesven/whisper-tiny-bn-thesven on Hugging Face](https://huggingface.co/thesven/whisper-tiny-bn-thesven)

-  **Model Architecture:** Whisper ASR

  

## Intended Use

  

This model is intended for automatic speech recognition (ASR) tasks in the Bengali language, especially for scenarios that involve out-of-distribution samples.

  

## Performance

  

[Provide details on the model's performance metrics after fine-tuning, such as Word Error Rate (WER), accuracy, etc.]

  

## Training Data

  

The model was fine-tuned using the OOD-Speech Bengali dataset:

  

-  **Training Samples:** 10,000

-  **Validation Samples:** 1,000

-  **Dataset Source:** [OOD-Speech: A Large Bengali Speech Recognition Dataset for Out-of-Distribution Benchmarking](https://arxiv.org/abs/2305.09688)

  

## Evaluation Data

  

[Provide details about the evaluation dataset used, if different from the validation set of the training data.]

  

## Fine-tuning Procedure

  

The model was fine-tuned using the OOD-Speech Bengali dataset with [specific hyperparameters, optimizer, learning rate, epochs, etc. if available].

  

## Licensing

  

This model is released under the MIT License. You are free to use, modify, distribute, or sell it under the terms of the license.

  

```

MIT License

  

Copyright (c) 2023 thesven

  

Permission is hereby granted, free of charge, to any person obtaining a copy

of this software and associated documentation files (the "Software"), to deal

in the Software without restriction, including without limitation the rights

to use, copy, modify, merge, publish, distribute, sublicense, and/or sell

copies of the Software, and to permit persons to whom the Software is

furnished to do so, subject to the following conditions:

  

The above copyright notice and this permission notice shall be included in all

copies or substantial portions of the Software.

  

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR

IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,

FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE

AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER

LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,

OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE

SOFTWARE.

```

  
  

## Citation

  

```

@article{OOD-Speech2023,

title={OOD-Speech: A Large Bengali Speech Recognition Dataset for Out-of-Distribution Benchmarking},

author={Authors of the OOD-Speech paper},

journal={arXiv preprint arXiv:2305.09688},

year={2023}

}

```