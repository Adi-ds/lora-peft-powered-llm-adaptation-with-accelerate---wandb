# LORA-PEFT-powered-LLM-adaptation-with-Accelerate-WandB

<img src="https://i.imgur.com/vnejHGh.png">

<img src="https://www.jardiradio.com/blog/assets/96_hf_bitsandbytes_integration/Thumbnail_blue.png">

<p align="center">
  <img src="https://cdn4.iconfinder.com/data/icons/logos-and-brands/512/189_Kaggle_logo_logos-512.png" width=240> <img src="https://www.altoros.com/blog/wp-content/uploads/2016/01/tensorflow-logo-cropped.png" width=300> <img src="https://miro.medium.com/v2/resize:fit:691/1*VSQ0XEywxSgZBwW05GsZtw.png" width=344>
</p>

<p align="center">
  <img src="https://images.squarespace-cdn.com/content/v1/593e7428a5790aa6651c2a84/1533737043262-9AXTD8RHTIJOICBI1OHS/Jupyter.png" height=400>
</p>



Welcome to the repository containing code to fine-tune a Large Language Model (LLM) for the task of answering multiple-choice-questions, specifically using the LLM Science Exam dataset from a [<img src="https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=Kaggle&logoColor=white" width=60>](https://www.kaggle.com/competitions/kaggle-llm-science-exam) competition. The primary objective of this project is to finetune a language model and adapt them to accurately predict the correct answers to a set of questions.

This has three Jupyter Notebooks focussed for three parts of the project:

1. **Crafting a Delectable Mix of Data and Prompts!**: Setting up an ideal learning environment for Large Language Models (LLMs) is akin to creating a recipe for success. Imagine LLMs as eager learners, ready to absorb a mix of various information. It's not just about throwing words together randomly; we carefully design prompts, like clear instructions, to help LLMs tackle different language tasks – from simple summaries to more intricate challenges. After curating this diverse mix of data, we split it into training and validation sets. The training set acts as the main course, allowing LLMs to grasp language patterns, while the validation set ensures they genuinely comprehend the information. This [<img src="https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=Kaggle&logoColor=white" width=60>](https://www.kaggle.com/code/adityadawn/preparing-data-for-science-llm-exam) notebook contains the code for data processing.

2. **Training Large Language Models Made as Delightful as Cooking a Gourmet Meal!**: Have you ever thought about the detailed steps involved in training a big language model? It's a bit like getting ready to cook a fancy meal! Each part needs careful consideration and accurate actions, starting with collecting the best ingredients and becoming a pro at cooking methods. So, just as a chef creates a masterpiece by paying attention to every detail, crafting a well-trained language model involves precision and dedication at every stage! This [<img src="https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=Kaggle&logoColor=white" width=60>](https://www.kaggle.com/code/adityadawn/training-llm-using-accelerate-and-w-b) notebook contains the code for training the LLM. I am adding this flowchart for better understanding of the training process.

<p align="center">
  <img src="https://github.com/Adi-ds/lora-peft-powered-llm-adaptation-with-accelerate---wandb/assets/78504100/3e055ad9-7869-413a-ab01-ef8a34c6a379">
</p>

The fine-tuned model has been uploaded to :hugs: hub. Click [🤗](https://huggingface.co/Adi-ds/Kaggle-Science-LLM) to land on the model space. You can also see [<img src="https://seeklogo.com/images/T/tensorflow-logo-02FCED4F98-seeklogo.com.png" width=15> board](https://huggingface.co/Adi-ds/Kaggle-Science-LLM/tensorboard). Also, I have made the [<img src="https://i0.wp.com/neptune.ai/wp-content/uploads/2022/11/Weights-Biases.png?fit=400%2C400&ssl=1" width=20>](https://wandb.ai/adityadawn98/Kaggle-LLM-Science/runs/s9m1tnpr) board public.

3. **The Grand AI Buffet Opens**: It's finally time to indulge! This [<img src="https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=Kaggle&logoColor=white" width=60>](https://www.kaggle.com/code/adityadawn/llm-inference) notebook throws open the doors, unleashing the PEFT model on real-world data. It's the grand reveal, the moment to witness the culmination of all the efforts – the AI creation, ready to serve up a feast of insights and solutions.


### Please UPVOTE my notebooks in <img src="https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=Kaggle&logoColor=white" width=60>. You can also connect me on [<img src="https://freelogopng.com/images/all_img/1656958733linkedin-logo-png.png" width=75>](https://www.linkedin.com/in/adityadawn-ds/)

 [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
