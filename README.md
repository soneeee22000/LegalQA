# LegalQA
This repository contains a system being built for my Special Studies requirement at AIT with the help of the Langchain framework!

1. The Few-Shot-fine-tuned llama v2 ipynb file showcases how the dataset generation works and how I train it on the llama v2 sharded model. All the steps, starting from sample generation , creating dataframes, setting up train parameters, running inference, and merging and storing the model in Google Drive,
   ![image](https://github.com/soneeee22000/LegalQA/assets/109932809/a3133a4c-33ae-428f-b87b-e9807e70f9bf)
   ![image](https://github.com/soneeee22000/LegalQA/assets/109932809/2ed56ff3-afc3-4c88-a0bf-a2f478fd8949)
Okay , Now that we have our model! let's upload it on Huggingface so that I can use it easily and will make it opensource since others can,also
 
   https://huggingface.co/PyaeSoneK/LlamaV2LegalFineTuned?text=My+name+is+Merve+and+my+favorite

  2. Everything is fine and all.But,now that you have your finetuned model, you have to figure out how you would use it in your application. The problem with llama model is most of the people who started out fine with the model( like me customized dataset, train the model, inference and everything) the model weights ended up occupying most of the space left in your drive! Even seniors in my Brainlab like Sir. Amanda is facing this problem i heard. I spend hours and hours on the same problem as well. Trying and failing .But, Data Science is all about that from the start! Trails and ERRORS! There are so many steps I can still try to take and I shall!

Note: I found out that in langchain you can run the quantized version of llama models locally via TheBloke/Llama-2-7B-Chat-GGML you can see all sort of llama models and their performance based on the different format of quant method. But, that's not what i want ! I want something easy for everyone to use! I also found out that there aren't any llama models on huggingface hub that you can test it out in the inference api right away since almost every models are way too big for their sizes! May be this is my opportunity to contribute something back to the community! I must make it my mission ! 

I will either prune or use quant methods to reduce the model size down ! afterwards, I will take Abhinav's advice to further train the model again on much more data! this time I might introduce very recent datasets to solve data freshness problem in llms! 

   
