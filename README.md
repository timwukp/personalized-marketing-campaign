# personalized-marketing-campaign
For personalized marketing campaign hands-on workshop
Use case
Assuming you are a marketing campaign manager, you're going to promote the flight ticket for Airline. At first, AI system will help you find out the target users segment; and then generate marketing promotion template for thoes target users. There has two AI engines

Recommendation engine - Amazon Personalize service
Content Generative engine - Amazon Bedrock service
The pipeline -

Marketing request-->Personalize-->retrive medata-->combine with PromptTemplate--> Langchain-->Amazon Bedrock & LLM--> Generate content -->save in JSON
