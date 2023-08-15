# LegalQA
This repository contains a system being built for my Special Studies requirement at AIT with the help of the Langchain framework!

1. The Few-Shot-fine-tuned llama v2 ipynb file showcases how the dataset generation works and how I train it on the llama v2 sharded model. All the steps, starting from sample generation , creating dataframes, setting up train parameters, running inference, and merging and storing the model in Google Drive,
   ![image](https://github.com/soneeee22000/LegalQA/assets/109932809/a3133a4c-33ae-428f-b87b-e9807e70f9bf)
   ![image](https://github.com/soneeee22000/LegalQA/assets/109932809/2ed56ff3-afc3-4c88-a0bf-a2f478fd8949)

2. Now that we have our model we will solve the big issue of LLMS, which is the data freshness problem ( to simply put) most of the llms are cut off from the following years that they were trained and cut off from. So, I don't want my model to have the same problem! To solve the issues , langchain offers retriveal QA which will allow us to chat with documents (text, pdf,..) .But, this has too many limitations. First of all, it's hard to collect articles and documents .Most of the well-esatablished sites don't offer their articles as open-soruced . So, I will take the next step called : web scrapping. We will take what we need from the most recent ,fresh data possible ! sounds good? follow along!

   
