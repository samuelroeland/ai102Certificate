# AI-102 Questions and Answers

## Question 1

**You have an Azure AI Search solution and a collection of blog posts that include a category field.**

You need to index the posts. The solution must meet the following requirements:

- Include the category field in the search results.
- Ensure that users can search for words in the category field.
- Ensure that users can perform drill down filtering based on category.

Which index attributes should you configure for the category field?

**Answer:** searchable, facetable, and retrievable

---

## Question 2

**You are building an app that will process scanned expense claims and extract and label the following data:**

- Merchant information
- Time of transaction
- Date of transaction
- Taxes paid
- Total cost

You need to recommend an Azure AI Document Intelligence model for the app. The solution must minimize development effort.

**Answer:** the prebuilt receipt model

---

## Question 3

**You are building an internet-based training solution. The solution requires that a user's camera and microphone remain enabled.**

You need to monitor a video stream of the user and verify that the user is alone and is not collaborating with another user. The solution must minimize development effort.

**Answer:** Spatial Analysis in Azure AI Vision

---

## Question 4

**You have an Azure subscription. You plan to build a solution that will analyze scanned documents and export relevant fields to a database.**

You need to recommend an Azure AI Document Intelligence model for the following type of document:

- Expenditure request authorization forms

The solution must minimize development effort and costs.

**Answer:** Custom template

---

## Question 5

**You have a chatbot that uses Azure OpenAI to generate responses.**

You need to upload company data by using Chat playground. The solution must ensure that the chatbot uses the data to answer user questions.

Which value should you choose for Placeholder 1 in the code?

**Answer:** ChatCompletionsOptions()

---

## Question 6

**Which value should you choose for Placeholder 2 in the code?**

**Answer:** AzureCognitiveSearchChatExtensionConfiguration

---

## Question 7

**You have an Azure subscription that contains an Azure OpenAI resource named AI1.**

You build a chatbot that uses AI1 to provide generative answers to specific questions.

You need to ensure that the chatbot checks all input and output for objectionable content.

Which type of resource should you create first?

**Answer:** Azure AI Content Safety

---

## Question 8

**What is the maximum size of each file that can be uploaded to the Azure AI Agent Service?**

**Answer:** 512 MB

---

## Question 9

**What is the maximum size of all files that can be uploaded to the Azure AI Agent Service?**

**Answer:** 200 GB

---

## Question 10

**When running a cURL command to Azure Text-to-Speech with three different `<voice>` tags, does the output contain three sentences in different voices?**

**Answer:** Yes

---

## Question 11

**Do the three sentences use different accents?**

**Answer:** Yes

---

## Question 12

**Do the three sentences have a neutral tone?**

**Answer:** No

---

## Question 13

**You have a question answering project in Azure Cognitive Service for Language.**

You need to move the project to a Language service instance in a different Azure region. Which three actions should you perform in sequence?

**Answer:**

1. Export the existing project from the original Language service.
2. Import the project into the new Language service instance.
3. Train and publish the project in the new Language service instance.

---

Question 14
You are building a chatbot. You need to configure the bot to guide users through a product setup process. Which type of dialog should you use?

A) component

B) action

C) waterfall ✅

D) adaptive

Correct Answer: C) waterfall

Explanation:
Waterfall dialogs are ideal for guiding users through a series of steps, where each step depends on the input from the previous one.

Question 15
\*\*You are building a customer support chatbot. You need to configure the bot to identify the following:

Code names for internal product development
The solution must minimize development effort. Which Azure Cognitive Service for Language feature should you use for the above requirement?\*\*

A) Key phrase extraction

B) Language detection

C) Named Entity Recognition (NER)

D) Custom Named Entity Recognition (NER) ✅

Correct Answer: D) Custom Named Entity Recognition (NER)

Explanation:
Custom NER allows training the model to recognize specific entities such as internal code names.

Question 16
\*\*You are building a customer support chatbot. You need to configure the bot to identify the following:

Messages that include credit card numbers
The solution must minimize development effort. Which Azure Cognitive Service for Language feature should you use for the above requirement?\*\*

A) Key phrase extraction

B) Language detection

C) Named Entity Recognition (NER)

D) Personally Identifiable Information (PII) detection ✅

Correct Answer: D) Personally Identifiable Information (PII) detection

Explanation:
PII detection identifies sensitive personal information like credit card numbers, social security numbers, etc.

Question 17
You are building a model to detect objects in images. The percentage of false positives is **\_\_**.

A) 0 ✅

B) 25

C) 30

D) 50

E) 100

Correct Answer: A) 0

Question 18
You are building a model to detect objects in images. The value for the number of true positives by the total number of true positives and false negatives is **\_\_**.

A) 0

B) 25 ✅

C) 30

D) 50

E) 100

Correct Answer: B) 25

Question 19
You are creating a chatbot. You need to ensure that the bot conversation resets if a user fails to respond for 10 minutes. You need to complete the following code:

python
Copy
Edit
if now_seconds != last_access and (now_seconds - last_access >= self.expire_after_seconds):
await turn_context.<Placeholder 1>(
"Welcome back! Let's start over from the beginning."
)
await self.conversation_state.<Placeholder 2>(turn_context)
Which value should you choose for Placeholder 1?

A) on_send_activities

B) send_activity ✅

C) send_trace_activity

D) update_activity

Correct Answer: B) send_activity

Which value should you choose for Placeholder 2?

A) Delete_property_value

B) clear_state ✅

C) Save_changes

D) Set_property_value

Correct Answer: B) clear_state

Question 20
You are building a chatbot. You need to configure the chatbot to query a knowledge base. Which dialog class should you use?

A) QnAMakerDialog ✅

B) AdaptiveDialog

C) SkillDialog

D) ComponentDialog

Correct Answer: A) QnAMakerDialog

Question 21
\*\*You are building a call handling system that will receive calls from French-speaking and German-speaking callers. The system must perform the following tasks:

Capture inbound voice messages as text.
Which Azure Cognitive Services service should you use?\*\*

A) Speaker Recognition

B) Speech-to-text ✅

C) Text-to-speech

D) Translator

Correct Answer: B) Speech-to-text

Question 22
\*\*You are building a call handling system that will receive calls from French-speaking and German-speaking callers. The system must perform the following tasks:

Replay messages in English on demand.
Which Azure Cognitive Services service should you use?\*\*

A) Speech-to-text only

B) Speech-to-text and Language

C) Speaker Recognition and Language

D) Text-to-speech and Translator ✅

Correct Answer: D) Text-to-speech and Translator

Question 23
You have an Azure Cognitive Search solution that stores data in a JSON format. You need to ensure that the search solution can handle multiple languages. What should you configure?

A) Indexers

B) Analyzers ✅

C) Synonym maps

D) Skillsets

Correct Answer: B) Analyzers

Question 24
You are creating an Azure AI solution. You need to ensure that sensitive data is masked or removed from the output. Which feature should you use?

A) Content filtering

B) Profanity filtering ✅

C) Prompt shields

D) Sentiment analysis

Correct Answer: B) Profanity filtering

Question 25
You are building an AI solution using Azure OpenAI Service.
You need to ensure the solution does not return potentially harmful content in the generated responses.
Which feature should you use?

A) Prompt shields ✅

B) Content filtering

C) Data masking

D) Synonym mapping

Correct Answer: A) Prompt shields

Explanation:
Prompt shields help prevent the generation of harmful or inappropriate content by filtering prompts before processing.

Question 26
You have a chatbot project that uses Azure AI Language Studio.
You need to configure the project to use knowledge base articles and user manuals stored in a PDF format.
Which feature should you enable?

A) Custom Question Answering ✅

B) Conversational Language Understanding

C) Entity Linking

D) Key Phrase Extraction

Correct Answer: A) Custom Question Answering

Question 27
You are using Azure AI Document Intelligence to process scanned invoices.
You need to extract specific fields like invoice number, due date, and total amount.
Which model should you use?

A) Prebuilt Layout

B) Prebuilt Invoice ✅

C) Custom Model

D) Entity Recognition

Correct Answer: B) Prebuilt Invoice

Question 28
You are building a document processing pipeline that includes multiple stages, such as text extraction, language detection, and entity recognition.
Which Azure AI service allows you to build such a multi-step pipeline?

A) Azure AI Vision

B) Azure AI Document Intelligence

C) Azure AI Language Service with Orchestrator flow

D) Azure AI Language Service with Skillset ✅

Correct Answer: D) Azure AI Language Service with Skillset

Question 29
You are developing an AI solution using Azure AI Search.
You need to allow users to filter search results by category and also enable full-text search within the category field.
Which attributes should you configure for the category field?

A) Searchable and Retrievable

B) Facetable and Retrievable

C) Searchable, Facetable, and Retrievable ✅

D) Retrievable only

Correct Answer: C) Searchable, Facetable, and Retrievable

Question 30
You are creating a custom vision model to detect objects in images.
You want to evaluate model performance using a confusion matrix.
Which metric indicates the proportion of actual positives that are correctly identified?

A) Precision

B) Recall ✅

C) Accuracy

D) F1 Score

Correct Answer: B) Recall

Question 31
You are using the Azure AI Speech SDK to convert text into spoken audio.
Which method should you use to synthesize speech?

A) FromTextAsync ✅

B) StartSpeaking

C) GenerateSpeech

D) SynthesizeText

Correct Answer: A) FromTextAsync

Question 32
You are building an AI solution that detects key information in customer emails, such as names, locations, and organizations.
Which Azure AI Language feature should you use?

A) Key Phrase Extraction

B) Sentiment Analysis

C) Entity Linking

D) Named Entity Recognition (NER) ✅

Correct Answer: D) Named Entity Recognition (NER)

Question 33
You are using the Azure Translator service.
Which feature allows you to automatically remove profanities from translations?

A) Profanity filtering ✅

B) Content shielding

C) Sentiment filtering

D) Text masking

Correct Answer: A) Profanity filtering

Question 34
You are building a chatbot with Azure AI services.
The chatbot must answer questions from a set of product FAQs.
Which feature should you use?

A) Conversational Language Understanding

B) Custom Question Answering ✅

C) Key Phrase Extraction

D) Summarization

Correct Answer: B) Custom Question Answering

Question 35
You are building a virtual agent that can answer natural language questions.
The solution must support multi-turn conversations and follow-up questions.
Which feature should you use?

A) Custom Text Classification

B) Conversational Language Understanding (CLU) ✅

C) Sentiment Analysis

D) Document Translation

Correct Answer: B) Conversational Language Understanding (CLU)

Question 36
You are using Azure AI Vision to analyze images.
Which feature allows you to detect and identify objects within an image?

A) Spatial Analysis

B) Object Detection ✅

C) OCR

D) Image Classification

Correct Answer: B) Object Detection

Question 37
You need to analyze sentiment in a large collection of text documents.
Which Azure AI Language feature should you use?

A) Key Phrase Extraction

B) Entity Recognition

C) Sentiment Analysis ✅

D) Summarization

Correct Answer: C) Sentiment Analysis

Question 38
You are using Azure AI Document Intelligence.
You need to extract data from forms with varying layouts.
Which model should you use?

A) Prebuilt Invoice

B) Prebuilt Receipt

C) Custom Model ✅

D) Layout Model

Correct Answer: C) Custom Model

Question 39
You are building an AI solution that needs to generate summaries of news articles.
Which Azure AI Language feature should you use?

A) Key Phrase Extraction

B) Summarization ✅

C) Text Classification

D) Entity Linking

Correct Answer: B) Summarization

Question 40
You need to extract key phrases from a document to understand the main topics.
Which Azure AI Language feature should you use?

A) Key Phrase Extraction ✅

B) Entity Linking

C) Sentiment Analysis

D) Summarization

Correct Answer: A) Key Phrase Extraction

Question 41
You are building an AI-powered search application.
You need to ensure that users can filter results by multiple criteria, such as product type and price range.
Which feature should you configure in Azure AI Search?

A) Searchable Fields

B) Facets ✅

C) Scoring Profiles

D) Cognitive Skills

Correct Answer: B) Facets

Question 42
You are building a content moderation solution using Azure AI Content Safety.
Which feature detects offensive, violent, or adult content?

A) PII Detection

B) Content Filtering

C) Harmful Content Detection ✅

D) Sentiment Analysis

Correct Answer: C) Harmful Content Detection

Question 43
You are using Azure AI Language for document processing.
You need to classify documents into predefined categories.
Which feature should you use?

A) Key Phrase Extraction

B) Custom Text Classification ✅

C) Entity Linking

D) Summarization

Correct Answer: B) Custom Text Classification

Question 44
You are using Azure AI Search.
Which feature allows you to assign importance to specific fields during ranking?

A) Scoring Profiles ✅

B) Synonym Maps

C) Indexers

D) Facets

Correct Answer: A) Scoring Profiles

Question 45
You need to build an AI solution that can translate text from one language to another.
Which Azure AI service should you use?

A) Language Studio

B) Translator ✅

C) Speech-to-Text

D) Content Safety

Correct Answer: B) Translator

Question 46
You are using Azure AI Vision.
Which feature allows you to analyze video feeds to detect people entering or exiting an area?

A) Object Detection

B) Image Analysis

C) Spatial Analysis ✅

D) OCR

Correct Answer: C) Spatial Analysis

Question 47
You are using Azure AI services.
Which feature allows you to recognize a person's voice for authentication?

A) Speech-to-Text

B) Text-to-Speech

C) Speaker Recognition ✅

D) Profanity Filtering

Correct Answer: C) Speaker Recognition

Question 48
You need to detect offensive or inappropriate content in generated text.
Which Azure AI service feature should you use?

A) Prompt Shields ✅

B) Profanity Filtering

C) Named Entity Recognition

D) Sentiment Analysis

Correct Answer: A) Prompt Shields

Question 49
You are using Azure AI Document Intelligence.
Which model extracts the structure and text of a document without predefined fields?

A) Prebuilt Invoice

B) Custom Model

C) Layout Model ✅

D) Prebuilt Receipt

Correct Answer: C) Layout Model

Question 50
You are developing a chatbot that answers FAQs.
Which Azure AI Language feature should you use?

A) Summarization

B) Custom Question Answering ✅

C) Sentiment Analysis

D) Language Detection

Correct Answer: B) Custom Question Answering

Question 51
You need to ensure that your AI system does not store customer data.
Which Azure AI feature supports this requirement?

A) Zero Retention Policy ✅

B) Encryption at Rest

C) Content Filtering

D) Data Masking

Correct Answer: A) Zero Retention Policy

Question 52
You are developing a solution that must support 20 languages in a single AI model.
Which Azure AI Language feature should you use?

A) Multi-language Support in Custom Text Classification ✅

B) Key Phrase Extraction

C) Entity Linking

D) PII Detection

Correct Answer: A) Multi-language Support in Custom Text Classification

Question 53
Which Azure AI feature ensures content safety by filtering out harmful prompts before processing?

A) Prompt Shields ✅

B) Profanity Filtering

C) Sentiment Analysis

D) Named Entity Recognition

Correct Answer: A) Prompt Shields

Question 54
Which Azure AI feature allows you to convert written text into spoken audio?

A) Speech-to-Text

B) Text-to-Speech ✅

C) Voice Authentication

D) Language Detection

Correct Answer: B) Text-to-Speech

Question 55
Which Azure AI feature allows you to identify locations mentioned in a text?

A) Entity Linking ✅

B) Sentiment Analysis

C) PII Detection

D) Key Phrase Extraction

Correct Answer: A) Entity Linking

Question 56
Which Azure AI service can generate a summary of a legal document?

A) Key Phrase Extraction

B) Summarization ✅

C) Sentiment Analysis

D) Entity Recognition

Correct Answer: B) Summarization

Question 57
Which Azure AI Vision feature allows you to analyze the spatial layout of a scanned document?

A) Layout Model ✅

B) Object Detection

C) OCR

D) Spatial Analysis

Correct Answer: A) Layout Model

Question 58
Which Azure AI service is designed for extracting data from forms like invoices and receipts?

A) Document Intelligence ✅

B) Custom Vision

C) Language Understanding

D) Speech Service

Correct Answer: A) Document Intelligence

Question 59
Which Azure AI feature allows users to query documents in natural language?

A) Custom Question Answering ✅

B) Sentiment Analysis

C) Entity Linking

D) Text Classification

Correct Answer: A) Custom Question Answering

Question 60
Which Azure AI Language feature allows you to identify relationships between people, places, and organizations in text?

A) Entity Linking ✅

B) Sentiment Analysis

C) Summarization

D) Key Phrase Extraction

Correct Answer: A) Entity Linking
