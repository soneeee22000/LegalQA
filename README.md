# LegalQA
This repository contains a system being built for my Special Studies requirement at AIT with the help of the Langchain framework!

Few-Shot-fine-tuned llama v2 ipynb file showcases how the dataset generation works and how I train it on the llama v2 hf version. All the steps, starting from sample generation , creating dataframes, setting up train parameters, running inference, and merging and storing the model in Google Drive,
   ![image](https://github.com/soneeee22000/LegalQA/assets/109932809/a3133a4c-33ae-428f-b87b-e9807e70f9bf)

Okay , Now that we have our model! let's upload it on Huggingface so that I can use it easily and will make it opensource since others can,also
 
   https://huggingface.co/PyaeSoneK/LlamaV2LegalFineTuned?text=My+name+is+Merve+and+my+favorite

put in the best system-prompt that describes your model ! and voila with the help of langchain we can test it out like this , Perfect answer:
![image](https://github.com/soneeee22000/LegalQA/assets/109932809/88cd3bed-94d9-4b97-b9a1-c5c9f06253cf)

----

llama is good! It's the best but it's also very expensive!
![image](https://github.com/soneeee22000/LegalQA/assets/109932809/05082c8f-26e6-4c4e-881f-76cd6ce470d0)

   I spent weeks trying to deploy the model on huggingface spaces but encountered so many errors and it takes too long to run since the model is too big for personal use ! it's meant for commerical use! me running on just only cpu exhuast every compute units i have in store! so i have to unfortunately give up on this approach .( i will come back around solving this problem in my Masters' Thesis )

   Now i have looked for smallest to medium sized models so that i can deploy on huggingface spaces! Since now my goal is not getting the best model and outcome anymore! my goal is to deploy ! i can always get back to making it better!

   as a recap! here is a quick look at the dataset that i am using to finetune llms with! ( peft : parameter efficient fine-tuning)
   ![image](https://github.com/soneeee22000/LegalQA/assets/109932809/15fcb4b6-6b9b-4b6a-8915-aeab076c768a)

with this dataset I have finetuned different sizes and versions of EleutherAI/pythia 70m, 410m ,2.8b and so on! as usual 









   
