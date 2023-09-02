# FInetuning-Falcon-7b-Midjourneyprompt
Finetuning Falcbon-7b with PEFT, QLORA technique on Midjourney prompts got improved results

Covers from loading base pre-trained model to finetuning it with our custom dataset using QLORA and then inferencing our fine-tuned model.

Dataset - Our Dataset consists of user prompts and their results, the results consist of mid-journey prompts with, Some Examples are below

Example Training Set - 

![image](https://github.com/ArjunPrasadSarkhel/FInetuning-Falcon-7b-Midjourneyprompt/assets/49405291/3e12a232-336f-4496-9cb3-f669e28c31f3)

![image](https://github.com/ArjunPrasadSarkhel/FInetuning-Falcon-7b-Midjourneyprompt/assets/49405291/e10ec7c5-d917-4882-8542-622c7c7491d7)

![image](https://github.com/ArjunPrasadSarkhel/FInetuning-Falcon-7b-Midjourneyprompt/assets/49405291/32e935b3-1505-482a-b5c0-39081f8ffa2a)

Note: --ar is a parameter which stands for aspect ratio

Before Training Falcon-7b Model Output - 

![image](https://github.com/ArjunPrasadSarkhel/FInetuning-Falcon-7b-Midjourneyprompt/assets/49405291/16192c8b-85d5-44a4-abd0-18989a395026)

After Training on our Custom dataset - 

![image](https://github.com/ArjunPrasadSarkhel/FInetuning-Falcon-7b-Midjourneyprompt/assets/49405291/a39753ac-9cae-4088-95c7-0d38961f61bb)

Model upload on HuggingFace Hub

HugginFace Hub Saved Model - https://huggingface.co/ArjunPrSarkhel/Falcon-7b-MidjourneyPrompts
