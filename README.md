# LegalQA
This repository contains a system being built for my Special Studies requirement at AIT with the help of the Langchain framework!

1. The Few-Shot-fine-tuned llama v2 ipynb file showcases how the dataset generation works and how I train it on the llama v2 sharded model. All the steps, starting from sample generation , creating dataframes, setting up train parameters, running inference, and merging and storing the model in Google Drive,
   ![image](https://github.com/soneeee22000/LegalQA/assets/109932809/a3133a4c-33ae-428f-b87b-e9807e70f9bf)
   ![image](https://github.com/soneeee22000/LegalQA/assets/109932809/2ed56ff3-afc3-4c88-a0bf-a2f478fd8949)
Okay , Now that we have our model! let's upload it on Huggingface so that I can use it easily and will make it opensource since others can,also
 
   https://huggingface.co/PyaeSoneK/LlamaV2LegalFineTuned?text=My+name+is+Merve+and+my+favorite

  2. Everything is fine and all.But,now that you have your finetuned model, you have to figure out how you would use it in your application. The problem with llama model is most of the people who started out fine with the model( like me customized dataset, train the model, inference and everything) the model weights ended up occupying most of the space left in your drive! Even seniors in my Brainlab like Sir. Amanda is facing this problem i heard. I spend hours and hours on the same problem as well. Trying and failing .But, Data Science is all about that from the start! Trails and ERRORS! There are so many steps I can still try to take and I shall!

Note: I found out that in langchain you can run the quantized version of llama models locally via TheBloke/Llama-2-7B-Chat-GGML you can see all sort of llama models and their performance based on the different format of quant method. But, that's not what i want ! I want something easy for everyone to use! I also found out that there aren't any llama models on huggingface hub that you can test it out in the inference api right away since almost every models are way too big for their sizes! May be this is my opportunity to contribute something back to the community! I will make it my mission ! 

I will either prune or use quant methods to reduce the model size down ! afterwards, I will take my friend, Abhinav's advice to further train the model again on much more data! this time I might introduce very recent datasets to solve data freshness problem in llms, just like RAG+ ! I can also perfect my web scraping with langchain code to custom more fresh datasets! 

For now, Behold my finetuned model on Huggingface ! I can finally load it and run ! after hours and hours of code debugging and trails and errors! sometimes if we miss even a minute details then our code will end up in choas and we could spend hours before a screen finding out what went wrong and that led to spending time on different alternatives and eventually end up fixing the first mistake that we started out with! Nevertheless, Voila my model is alive and well on the net and ohh there's already one download already! 

![image](https://github.com/soneeee22000/LegalQA/assets/109932809/069b7b33-8764-4b13-bfa8-cf95793d7cd3)

put in the best system-prompt that describes your model ! and voila with the help of langchain we can test it out like this , Perfect answer:
![image](https://github.com/soneeee22000/LegalQA/assets/109932809/88cd3bed-94d9-4b97-b9a1-c5c9f06253cf)







   
