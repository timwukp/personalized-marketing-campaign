# personalized-marketing-campaign
For personalized marketing campaign hands-on workshop
Use case
Assuming you are a marketing campaign manager, you're going to promote the flight ticket for Airline. At first, AI system will help you find out the target users segment; and then generate marketing promotion template for thoes target users. There has two AI engines

1. Recommendation engine - Amazon Personalize service

2. Content Generative engine - Amazon Bedrock service

The pipeline -

Marketing request-->Personalize-->retrive medata-->combine with PromptTemplate--> Langchain-->Amazon Bedrock & LLM--> Generate content -->save in JSON

Step1: to run the notebook - airline_ticket_user_segmentation_09212023_github.ipynb

Step2: to run the notebook - personalized_marketing_campaign_09212023_github.ipynb

If you're running notebook in AWS SageMaker Studio, for the IAM assume role requirements are,
1. AmazonPersonalizeFullAccess
2. AmazonS3FullAccess
3. bedrock_full_access_policy
4. IAMFullAccess
5. AmazonSageMakerFullAccess
