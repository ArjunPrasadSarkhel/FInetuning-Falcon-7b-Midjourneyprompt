# Finetuning Falcon-7b on Midjourney Prompts

Finetuning Falcon-7b with PEFT and QLORA techniques on Midjourney prompts resulted in significant improvements.

It covers the entire process, from loading the base pre-trained model to finetuning it with our custom dataset using QLORA, and then performing inference with our fine-tuned model.

## Dataset

Our dataset consists of user prompts and their results, with a focus on mid-journey prompts. Here are some examples:

### Example Training Set

- ![Example 1](https://github.com/ArjunPrasadSarkhel/FInetuning-Falcon-7b-Midjourneyprompt/assets/49405291/3e12a232-336f-4496-9cb3-f669e28c31f3)
- ![Example 2](https://github.com/ArjunPrasadSarkhel/FInetuning-Falcon-7b-Midjourneyprompt/assets/49405291/e10ec7c5-d917-4882-8542-622c7c7491d7)
- ![Example 3](https://github.com/ArjunPrasadSarkhel/FInetuning-Falcon-7b-Midjourneyprompt/assets/49405291/32e935b3-1505-482a-b5c0-39081f8ffa2a)

**Note:** The `--ar` parameter represents the aspect ratio.

## Before Training Falcon-7b Model Output

![Before Training](https://github.com/ArjunPrasadSarkhel/FInetuning-Falcon-7b-Midjourneyprompt/assets/49405291/16192c8b-85d5-44a4-abd0-18989a395026)

## After Training on Our Custom Dataset

![After Training](https://github.com/ArjunPrasadSarkhel/FInetuning-Falcon-7b-Midjourneyprompt/assets/49405291/a39753ac-9cae-4088-95c7-0d38961f61bb)

## Model Upload on HuggingFace Hub

You can find the saved model on the HuggingFace Hub at the following link:

[HuggingFace Hub Saved Model](https://huggingface.co/ArjunPrSarkhel/Falcon-7b-MidjourneyPrompts)

Feel free to explore and use this fine-tuned model for your tasks and applications.
