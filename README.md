# Fine-tuning LLama2-7b on Financial Data using AWS SageMaker:

## Project Description
- Utilize Amazon Sagemaker and s3 bucket AWS tools to **fine-tune the Meta Llama 2 7B foundation model**.
- This model has been trained for text-generation tasks. The goal is to adapt this model to your selected domain, enhancing its ability to understand and generate domain-specific text.
### Steps:
* Upload the Domain Data to s3 bucket
* Create AWS SageMaker role and attach the required persmission specially the **Fulls3bucketAcceess**
  ![image](https://github.com/sidahmed-faisal/Finetune-Llama2-7B-on-Financial-data-with-Sagemaker/assets/83870963/a287366a-1ba0-4de1-95be-394acc639989)
  ![image](https://github.com/sidahmed-faisal/Finetune-Llama2-7B-on-Financial-data-with-Sagemaker/assets/83870963/c0d8fb3f-8081-40b8-bd8d-bdbe1271a306)
* Create Sakemaker notebook instance with the role created in the previous step
  ![image](https://github.com/sidahmed-faisal/Finetune-Llama2-7B-on-Financial-data-with-Sagemaker/assets/83870963/f251122a-956a-41ca-b933-e280a97c61ab)
* Fine-tune the model on your chosen dataset using training notebook
* Test and evaluate the model for its responses to domain knowledge and text-generation tasks using evaluation notebook
* Deploy the fine-tuned model
* Test the fine-tuned model on domain-specific knowledge and text generation tasks relevant to your dataset.




