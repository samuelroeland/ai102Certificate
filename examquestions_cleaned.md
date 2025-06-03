### 51.

You have a knowledge base that contains semi-structured data.
You need to build a bot that will use the knowledge base as part of user conversations.
Which service should you use?

- **Custom question answering**

---

### 52.

You have a website that allows users to upload images.
You need to ensure that the uploaded images do not contain adult content. The solution must minimize development effort.
Which service should you use?

- **Azure AI Vision Image Analysis**

---

### 53.

You build an app that enables users to upload scans of invoices.
You need to extract text and key/value pairs from the scanned invoices.
Which service should you use?

- **Azure AI Document Intelligence**

---

### 54.

You are building a mobile app that will enable users to scan street signs and will read out the text on the sign.
You need to recommend a service to use. The solution must minimize development effort.
Which service should you recommend?

- **Azure AI Vision**

---

### 55.

You are building an app that will extract text from scanned receipts.
You need to recommend which service to use. The solution must minimize development effort.
What should you recommend?

- **Azure AI Document Intelligence**

---

### 56.

You are building an app that will use an Azure AI Services resource.
You need to identify the endpoint for the resource.
From the Azure CLI, which command should you run?

- **az cognitiveservices account show --name myresource --resource-group cognitive-services-resource-group**

---

### 57.

You plan to build an app that will use Azure AI Services.
You need to identify the methods that can be used to authenticate to Azure AI Services.
Which two methods can you use? Each correct answer presents a complete solution.

- **a subscription key**
- **Microsoft Entra ID**

---

### 58.

You are building an app that will use Azure AI Custom Vision. The app will be deployed to an internet host.
You enable firewall rules for your Azure AI Services account.
You need to ensure that the app can access the Azure AI Custom Vision service over the internet.
What should you do?

- **Grant access to an internet IP range.**

---

### 59.

You are developing a containerized optical character recognition (OCR)-capable application by using Azure AI Services containers.
While developing the solution, you retrieve a status message of “Mismatch”, and the connection to the AI Services resource fails.
You need to ensure that the solution can connect to the AI Services resource.
What should you do?

- **Confirm that the API key is for the correct resource type.**

---

### 60.

You are building an app named App1 that uses the Image Analysis API.
You are evaluating analyzing images by using the following request:
https://*.cognitiveservices.azure.com/computervision/imageanalysis:analyze?features=read,description
Which results will the request return?

- **the visible text in the image and a description of the image content**

---

### 61.

You build an app named App1 that uses the Azure AI Face service.
You need to optimize the app for images that contain blurry faces.
What should you do?

- **Set the detection model to detection_02.**

---

### 62.

You are building an app that will detect the color scheme of uploaded images.
You are evaluating using the Image Analysis API to detect the dominant background color of an image.
Which color can the API return as a dominant background color?

- **teal**

---

### 63.

You are building an app that will use Azure AI Vision to extract text from scanned images of handwritten text.
Which Azure AI Vision feature should you use?

- **optical character recognition (OCR)**

---

### 64.

You have an app named App1 that extracts invoice data from PDF files by using an S0 instance of Azure AI Document Intelligence. The PDF files are up to 2 MB each and contain up to 10 pages.
Users report that App1 is unable to process some invoices.
You need to troubleshoot the issue.
What is a possible cause of the issue?

- **Some of the files are password protected.**

---

### 65.

You are building an app that will be deployed to an edge device and will use Azure AI Custom Vision to analyze images of fruits.
You need to select a model domain for the app. The solution must support running the app without internet connectivity.
Which model should you use?

- **Compact domain**

---

### 66.

You are building an app that will use Azure AI Vision to analyze and classify images to build an image library of animals.
You need to configure the classification type for the Azure AI Vision project. The solution must ensure that the images selected only include a single animal.
Which type of classification should you use?

- **multiclass**

---

### 67.

You are using a custom Language content model in an Azure AI Video Indexer solution.
During testing, you upload a text file that includes the following sentence: “Kubernetes is a new feature in Azure & the cloud.”
The sentence is discarded.
You need to ensure that the model retains the sentence.
What should you do?

- **Remove the “&” character from the text file.**

---

### 68.

You are building a video processing app that will use Azure AI Video Indexer to extract insights from videos that contain multi-language content.
You need to configure the API calls to enable multilingual identification.
Which value should you set for the sourceLanguage parameter?

- **multi-language detection**

---

### 69.

You are building an app that will analyze resumes and remove names and addresses.
You need to configure the Azure AI Language Personally Identifiable Information (PII) detection feature for the app.
Which categories should you specify in the request?

- **Person and Address only**

---

### 70.

You are building an app that will analyze the sentiment of user feedback by using Azure AI Language.
You have a test document named Test.docx that contains one positive sentence and multiple neutral sentences.
You need to validate the app by analyzing Test.docx.
Which label will the app return for Test.docx?

- **positive**

---

### 71.

You are building an app that will flag documents that contain the names of staff members by using the Azure AI Language Personally Identifiable Information (PII) detection feature.
You need to configure the PII detection feature.
Which category should you use?

- **Person**

---

### 72.

You need to build an app that will summarize text documents into key phrases.
Which Azure AI Language feature should you recommend?

- **key phrase extraction**

---

### 73.

You have an app that sends audio recordings from a call center to the speech-to-text feature of Azure AI Services.
During testing, you notice that the Word Error Rate (WER) is high and there are a lot of substitution errors.
You need to improve the model and reduce the WER.
What should you add to the training data?

- **custom product and people names**

---

### 74.

You are building an app that will analyze meeting recordings and identify who is speaking at which moment in time.
You need to configure a voice profile for the app.
Which type of voice profile should you use?

- **Speaker identification**

---

### 75.

You plan to build an app that will transcribe large quantities of audio files by using the Azure AI Speech service batch transcription feature.
You need to recommend a storage solution for the audio files. The solution must minimize development effort.
What should you recommend?

- **Azure Storage**

---

### 76.

You are building an app that will recognize the intent and entities of user utterances in real-time.
You are evaluating the use of intent recognition with the Azure AI Speech and Azure AI Language services or simple pattern matching.
When should you use pattern matching?

- **You are only interested in matching strictly what the user said.**

---

### 77.

You are building a custom translation model.
You need to use bilingual training documents to teach the model your terminology and style.
Which rule should you follow?

- **Be liberal.**

---

### 78.

You are building a custom translation model.
You need to evaluate the precision of the text that you translated by using a Bilingual Evaluation Understudy (BLEU) score.
Which scale is used for the score?

- **between 0 and 100**

---

### 79.

You are using Azure AI Translator to translate documents from one language to another.
You need to extend the capabilities of an application by using the Azure AI Translator service.
Which three features are available in the Translator service? Each correct answer presents a complete solution.

- **Detect language**
- **Dictionary lookup**
- **Transliterate**

---

### 80.

You are building an Azure AI Translator custom model.
You need to ensure that the translation accuracy for the model has a Bilingual Evaluation Understudy (BLEU) score that indicates high quality.
What is the minimum score range required?

- **40 to 59**

---

### 81.

You are building a model that uses Conversational Language Understanding (CLU).
You need to train the model.
Which training methods can you use?

- **standard and advanced only**

---

### 82.

You are creating an orchestration workflow for Language Understanding.
You need to configure workflows for multiple languages. The solution must minimize administrative effort.
What should you create for each language?

- **separate workflow projects**

---

### 83.

You are building a model that uses Conversational Language Understanding (CLU).
You need to measure how accurate the model is by using the ratio between the correctly identified positives (true positives) and all identified positives.
Which metric should you use?

- **precision**

---

### 84.

You are building an orchestration workflow to orchestrate and connect multiple Language Understanding models and question answering projects for use in a bot.
Which two operations can you perform in an orchestration workflow based on Azure AI Language service? Each correct answer presents a complete solution.

- **Connect to Language Understanding applications that are owned by the same resource as the orchestration workflow.**
- **Connect to question answering projects that are in the same Azure AI Language service resource as your orchestration workflow.**

---

### 85.

You are building a multilingual conversational app by using Conversational Language Understanding (CLU), part of Azure AI Language service.
You create a CLU model that will serve multiple languages.
You need to optimize the performance of the model. The solution must minimize development effort.
What should you do?

- **Add utterances for languages that are performing poorly in the model.**

---

### 86.

You plan to build a chatbot that will help users answer FAQs.
You need to identify which scenarios are suitable for use with the Azure AI Language question answering service.
Which three scenarios should you identify? Each correct answer presents a complete solution.

- **when you have a bot conversation that includes static information**
- **when you have static information in a knowledge base of answers**
- **when you need to provide the same answer to a request, question, or command**

---

### 87.

You are building a solution that uses Azure AI Search.
You need to execute the initial run of the indexer.
Which stages will be included during the initial run?

- **document cracking, field mapping, skillset execution, and output field mapping**

---

### 88.

You are building a solution that uses Azure AI Search.
You need to save normalized binary files as projections.
Which type of projection should you use?

- **files**

---

### 89.

You are building a knowledge mining solution by using Azure AI Search.
You need to ensure that the solution supports wildcard queries in search requests.
What should you include in the REST API request?

- **“queryType”: “full”**

---

### 90.

You are building an app will use Azure AI Search.
You need to index a collection of documents.
What is the first stage of the indexing process?

- **document cracking**

---

### 91.

You are building a solution that uses Azure AI Search.
You need to create a skillset definition.
What are minimum sections you should include in the definition?

- **name, description, and skills**

---

### 92.

You are building a knowledge mining solution that will use AI enrichment and Azure AI Search.
You need to create a data structure that will be used to store the enriched and indexed output for downstream apps.
What should you create?

- **a knowledge store**

---

### 93.

You are creating an application that references the Azure OpenAI REST API for a DALL-E model.
You plan to use thumbnails of the images that DALL-E generates and display them in a table on a webpage.
You need to find the image URLs in the JSON response.
Which element should you review?

- **the result element**

---

### 94.

You are building a web app that will generate images based on user prompts. The app will use the DALL-E 3 Azure OpenAI model.
You need to ensure that HTTP requests against the Azure OpenAI API successfully generate images.
Which three HTTP header properties should you include? Each correct answer presents part of the solution.

- **the API version used in this operation**
- **the name of the Azure OpenAI service resource**
- **the name of the DALL-E 3 model deployment**

---

### 95.

You are building a web app that will generate images based on user prompts. The app will use the DALL-E 3 Azure OpenAI model.
You need to ensure that HTTP requests against the Azure OpenAI API successfully generate images.
Which HTTP body property should you include?

- **the prompt**

---

### 96.

You are deploying an Azure OpenAI service.
You plan to use your own data in the models you will deploy.
You need to ensure that the model can index your data sources.
Which additional Azure service should you deploy?

- **Azure AI Search**

---

### 97.

You are building a GPT-based chat application that will answer questions about your company.
You plan to use the Using your data feature in Azure OpenAI to ground the model with company data.
Which four types of files can you use to ground the model? Each correct answer presents a complete solution.

- **HTML**
- **MD**
- **PDF**
- **TXT**

---

### 98.

You are building a GPT-based chat application that will answer questions about your company.
You plan to use the Using your data feature in Azure OpenAI to ground the model with your company data.
While testing, you discover that some responses are not accurate enough.
You need to configure the Azure OpenAI resource to filter out less-relevant documents for responses.
Which parameter should you configure?

- **Strictness**

---

### 99.

You are building a GPT-based chat application that will answer questions about your company.
You plan to test the application by using strategies defined by Microsoft best practices.
Which three prompt engineering strategies should you consider while testing the application? Each correct answer presents a complete solution.

- **Be Descriptive**
- **Be Specific**
- **Order Matters**

---

### 100.

You are creating an application that will use Azure OpenAI REST API services. The application uses a REST call to a DALL-E model to generate images. The three parameters in the REST call are prompt, n, and size.
What does the size parameter indicate?

- **the size of the images in pixel resolution**

---

# Microsoft AI-102 Practice Questions

Below is a comprehensive list of your practice questions, each with scenario, question, choices, and correct answer.

---

## 1. Azure AI Search custom skill (Web API call)

**Scenario:**
You are building an Azure AI Search custom skill.
You have the following custom skill schema definition:

```json
{
  "@odata.type": "#Microsoft.Skills.Custom.WebApiSkill",
  "description": "My custom skill description",
  "uri": "https://contoso-webskill.azurewebsites.net/api/process",
  "context": "/document/organizations/*",
  "inputs": [
    {
      "name": "companyName",
      "source": "/document/organizations/*"
    }
  ],
  "outputs": [
    {
      "name": "companyDescription"
    }
  ]
}
```

**Question:**
The definition calls a web API as part of the enrichment process.
A) Yes
B) No
_Correct Answer: Yes_

---

## 2. Azure AI Search custom skill (enrichment step context)

**Scenario:**
(Same custom skill schema as above.)

**Question:**
The enrichment step is called only for the first organization under /document/organizations.
A) Yes
B) No
_Correct Answer: No_

---

## 3. Azure AI Service resource access via VNet

**Scenario:**
You have an Azure subscription that contains an Azure AI Service resource named CSAaccount1 and a virtual network named VNet1. CSAaccount1 is connected to VNet1.
You need to ensure that only specific resources can access CSAaccount1.
The solution must meet the following requirements:

- Prevent external access to CSAaccount1.
- Minimize administrative effort.

**Question:**
Which two actions should you perform?

- In VNet1, enable a service endpoint for CSAaccount1.
- In CSAaccount1, configure the Access control (IAM) settings.
- In VNet1, modify the virtual network settings.
- In VNet1, create a virtual subnet.
- In CSAaccount1, modify the virtual network settings.

_Correct Answers:_

- In VNet1, enable a service endpoint for CSAaccount1.
- In CSAaccount1, modify the virtual network settings.

---

## 4. Azure AI Language Understanding (LUIS) custom entity

**Scenario:**
You are building an Azure AI Language Understanding solution.
You discover that many intents have similar utterances containing airport names or airport codes.
You need to minimize the number of utterances used to train the model.

**Question:**
Which type of custom entity should you use?

- Pattern.any
- machine-learning
- regular expression
- list

_Correct Answer: Pattern.any_

---

## 5. Azure Content Safety Studio – Monitor online activity feature

**Scenario:**
You have an Azure subscription that contains an Azure OpenAI resource named AI1 and an Azure AI Content Safety resource named CS1.
You build a chatbot that uses AI1 to provide generative answers and CS1 to check input and output for objectionable content.
You need to optimize the content filter configurations by running tests on sample questions.

**Question:**
Solution: From Content Safety Studio, you use the Monitor online activity feature to run the tests.
Does this meet the requirement?
A) Yes
B) No
_Correct Answer: No_

---

## 6. Azure Content Safety Studio – Safety metaprompt feature

**Scenario:**
(Same as above)

**Question:**
Solution: From Content Safety Studio, you use the Safety metaprompt feature to run the tests.
Does this meet the requirement?
A) Yes
B) No
_Correct Answer: No_

---

## 7. Azure Content Safety Studio – Protected material detection feature

**Scenario:**
(Same as above)

**Question:**
Solution: From Content Safety Studio, you use the Protected material detection feature to run the tests.
Does this meet the requirement?
A) Yes
B) No
_Correct Answer: No_

---

## 8. Language Understanding (LUIS) container deployment sequence

**Scenario:**
You have a Language Understanding solution that runs in a Docker container.
You download the Language Understanding container image from the Microsoft Container Registry (MCR).
You need to deploy the container image to a host computer.

**Question:**
Which three actions should you perform in sequence?

ACTIONS

1. From the host computer, build the container and specify the output directory.
2. From the Language Understanding portal, retrain the model.
3. From the host computer, run the container and specify the input directory.
4. From the host computer, move the package file to the Docker input directory.
5. From the Language Understanding portal, export the solution as a package file.

Options:

- 5-4-3 (Correct)
- 5-4-1
- 5-3-2

_Correct Sequence: 5-4-3_

---

## 9. Azure AI Search – Compromised Query Key Rotation Sequence

**Scenario:**
You have a web app that uses Azure AI Search. You see greater than expected search query volumes and suspect the query key is compromised.
You need to prevent unauthorized access to the search endpoint and ensure users only have read-only access. The solution must minimize app downtime.

**Question:**
Which three actions should you perform in sequence?

ACTIONS

1. Delete the compromised key
2. Change the app to use the secondary admin key
3. Add a new query key
4. Regenerate the secondary admin key
5. Change the app to use the new key
6. Regenerate the primary admin key

Options:

- 3-5-1 (Correct)
- 2-5-1
- 5-1-3

_Correct Sequence: 3-5-1_

---

## 10. Document Translation – Custom Glossary and Formatting

**Scenario:**
You have Microsoft Word and PowerPoint presentations in German. You need to translate the files to French, preserving formatting and supporting the use of a custom glossary.
You have blob containers for German files and for French files.

**Question:**
Which three actions should you perform in sequence to complete the solution?

ACTIONS

1. Define a document translation specification that has a French target.
2. Perform an asynchronous translation by using the list of files to be translated.
3. Upload a glossary file to the container for German files.
4. Upload a glossary file to the container for French files.
5. Generate a list of files to be translated.
6. Perform an asynchronous translation by using the document translation specification.

Options:

- 1-3-6 (Correct)
- 1-4-6
- 1-6-3

_Correct Sequence: 1-3-6_

---

## 11. Azure DevOps Pipeline – Identify Created AI Services Account

**Scenario:**
You have an Azure DevOps pipeline that is used to deploy an app and will create an Azure AI services account.
You need to add a step to identify the created Azure AI services account, minimizing development effort.

**Question:**
Which Azure Command-Line Interface (CLI) command should you run?

- az resource link
- az cognitiveservices account network-rule
- az cognitiveservices account show (Correct)
- az account list

_Correct Answer: az cognitiveservices account show_

---

## 12. Text Analytics – Entity Recognition Output

**Scenario:**
You are developing a text processing solution.
You have the following function:

```csharp
static void GetKeyWords(TextAnalyticsClient textAnalyticsClient, string text)
{
    var response = textAnalyticsClient.RecognizeEntities(text);
    Console.WriteLine("Key words:");
    foreach (CategorizedEntity entity in response.Value)
    {
        Console.WriteLine($"\t{entity.Text}");
    }
}
```

You call the function and use the following string as the second argument:
Our tour of London included a visit to Buckingham Palace

**Question:**
What will the function return?

- London and Buckingham Palace only (Correct)
- Tour and visit only
- London and Tour only
- Our tour of London included visit to Buckingham Palace

_Correct Answer: London and Buckingham Palace only_

---

## 13. Document Intelligence Studio – Image Upload Target

**Scenario:**
You have 1,000 scanned images of handwritten surveys (no consistent layout). Need to extract data with minimal development effort.

**Question:**
Where should you upload the images?

- Azure Cosmos DB account
- Azure Files share
- Azure Storage account (Correct)

_Correct Answer: Azure Storage account_

---

## 14. Document Intelligence Studio – Model Type for Inconsistent Layout

**Scenario:**
Same as above.

**Question:**
Which type of model should you use?

- Custom neural (Correct)
- Custom template
- Identity document (ID)

_Correct Answer: Custom neural_

---

## 15. Document Intelligence Studio – QR Code Extraction

**Scenario:**
Update an app to interpret QR codes (minimize admin effort). What should you do first?

- Upgrade business card model to v3.0
- Implement the read model (Correct)
- Deploy a custom model
- Implement the contract model

_Correct Answer: Implement the read model_

---

## 16. Azure OpenAI Resource – Least Privilege Role for Fine-tuning

**Scenario:**
Assign a role to allow a user to upload datasets and fine-tune models on OpenAI1, following least privilege.

- Cognitive Services OpenAI Contributor (Correct)
- Cognitive Services Contributor
- Cognitive Services OpenAI User
- Contributor

_Correct Answer: Cognitive Services OpenAI Contributor_

---

## 17. Azure OpenAI GPT-4 Grounding Data Resources

**Scenario:**
You deploy the GPT-4 model to the resource and need to upload files for grounding data.

**Question:**
Which two types of resources should you create?

- Azure AI Document Intelligence
- Azure Blob Storage (Correct)
- Azure AI Bot Service
- Azure AI Search (Correct)
- Azure SQL

_Correct Answers: Azure Blob Storage, Azure AI Search_

---

## 18. Azure AI Language – Masking PII (Dropdown 1)

**Scenario:**
App to mask telephone numbers and email details using Azure AI Language service.

**Question:**
What should you choose for Dropdown 1?

- RecognizeLinkedEntities
- RecognizePiiEntities (Correct)
- SingleLabelClassify

_Correct Answer: RecognizePiiEntities_

---

## 19. Azure AI Language – Masking PII (Dropdown 2)

**Scenario:**
Same as above.

**Question:**
What should you choose for Dropdown 2?

- RedactedText (Correct)
- Statistics
- Warnings

_Correct Answer: RedactedText_

---

## 20. Azure SDK for Real-Time Language Identification

**Scenario:**
Social media messaging app, need to identify language in real time.

**Question:**
Which SDK package should you install?

- Azure.AI.Translation.Text (Correct)
- Microsoft.CognitiveServices.Speech
- Azure.AI.Translation.Speech
- Azure.AI.Translation.Document

_Correct Answer: Azure.AI.Translation.Text_

---

## 21. Azure Custom Vision Model Deployment Sequence

**Scenario:**
Deploying a Custom Vision object detection model for mobile (Android), using Retail domain.

ACTIONS:

1. Change the model domain.
2. Retrain the model.
3. Export the model.
4. Test the model.

**Question:**
Which three actions should you perform in sequence?

- 1-2-3 (Correct)
- 3-2-1
- 1-3-2
- 2-3-4
- 1-2-4

_Correct Sequence: 1-2-3_

---

## 22. Azure AI Speech: Synthesize Audio (File Exists)

**Scenario:**
Azure AI Speech service, C# code writes to file path/to/file.wav.

**Question:**
Will the function fail if there is an existing file named File.wav?

- Yes
- No (Correct)

_Correct Answer: No_

---

## 23. Azure AI Speech: Synthesize Audio (Voice Sampling)

**Scenario:**
Same C# code as above.

**Question:**
Will the function sample File.wav to use as a synthesized voice?

- Yes
- No (Correct)

_Correct Answer: No_

---

## 24. Azure AI Speech: Synthesize Audio (Output Generation)

**Scenario:**
Same C# code as above.

**Question:**
Will the function generate an audio file based on the input text?

- Yes (Correct)
- No

_Correct Answer: Yes_

---

## 25. Azure AI Language – Custom Question Answering Chatbot Improvement

**Scenario:**
Chatbot answers a price question correctly, but fails to answer a question about available colors for a product. You need to improve chatbot accuracy.

**Question:**
What should you do?

- Add alternative phrasing to the question and response pair
- Add a new question and response pair (Correct)
- Modify the system prompt
- Modify the original documents and retrain the model

_Correct Answer: Add a new question and response pair_

# Recent AI-102 Practice Questions

Below are your most recent practice questions, including scenario, question, choices, and correct answer.

---

## 1. Provision Cognitive Services for Receipt Recognition (Dropdown 1)

**Scenario:**
You plan to provision Azure Cognitive Services resources using a method that takes resource kind, tier, and location.
You need to create a Standard tier resource that will convert scanned receipts into text.

**Question:**
What should you choose for Dropdown 1?

- ComputerVision
- CustomVision.Prediction
- CustomVision.Training
- **FormRecognizer** (Correct)

---

## 2. Provision Cognitive Services for Receipt Recognition (Dropdown 2)

**Scenario:**
You plan to provision Azure Cognitive Services resources using a method that takes resource kind, tier, and location.
You need to create a Standard tier resource that will convert scanned receipts into text.

**Question:**
What should you choose for Dropdown 2?

- "eastus","S1"
- "useast","S1"
- **"S0","eastus"** (Correct)
- "S0","useast"

---

## 3. Provisioning for Speech + Language APIs

**Scenario:**
You are developing an app that will use the Speech and Language APIs.
You need to provision resources for the app. The solution must ensure that each service is accessed by using a single endpoint and credential.

**Question:**
Which type of resource should you create?

- Azure AI Language
- Azure AI Speech
- **Azure AI Service** (Correct)
- Azure AI Content Safety

---

## 4. Azure AI Vision Client Library – Face Recognition

**Scenario:**
You are developing an application that will use the Azure AI Vision client library.
You have Python code that analyzes image tags and descriptions.

**Question:**
Will the code perform face recognition?

- Yes
- **No** (Correct)

---

# AI-102 Practice Exam Questions and Answers

Below is a summary list of all your stored AI-102 practice questions (images 1–40), including the question, correct answer, and a brief explanation.

---

## 1. Will the code list tags and their associated confidence?

**Answer:** Yes
**Explanation:** The code includes `VisualFeatureTypes.tags` and iterates over `image_analysis.tags`, printing each tag's name and associated confidence.

---

## 2. Will the code read an image file from the local file system?

**Answer:** Yes
**Explanation:** The code reads the image as a binary stream from the local file system.

---

## 3. Sequence to add new products to a custom vision classifier

**Answer:** 4-6-1-5-3
**Explanation:** Open project → Upload new samples → Label images → Retrain model → Publish model.

---

## 4. Will the call output key phrases from the input string to the console?

**Answer:** Yes
**Explanation:** The function iterates over `response.key_phrases` and prints each one.

---

## 5. Will the output contain these words: the, cat, sat, on, and mat?

**Answer:** No
**Explanation:** Key phrase extraction omits common words like "the" and "on"; output is likely "cat" and "mat".

---

## 6. Will the output contain the confidence level for key phrases?

**Answer:** No
**Explanation:** The function only outputs key phrases, not confidence scores.

---

## 7. Which API call for completions in Azure OpenAI .NET SDK?

**Answer:** GetCompletions
**Explanation:** This calls the completions endpoint for text generation.

---

## 8. Which property outputs the completion text?

**Answer:** (response.Value.Choices[0].Text);
**Explanation:** This property contains the actual model response text.

---

## 9. ARM template: What value for Placeholder 1 to deploy Document Intelligence?

**Answer:** Microsoft.CognitiveServices
**Explanation:** Document Intelligence resources are under Cognitive Services.

---

## 10. ARM template: What value for Placeholder 2 to deploy Document Intelligence?

**Answer:** FormRecognizer
**Explanation:** Form Recognizer is the correct kind for Document Intelligence.

---

## 11. Two ways to improve chatbot quality with minimal dev effort

**Answer:**

- Provide grounding content.
- Add sample request/response pairs.
  **Explanation:** Grounding content and sample pairs improve quality without retraining or fine-tuning.

---

## 12. Sequence to deploy Azure AI Anomaly Detector on a server

**Answer:** 3-6-5-1
**Explanation:** Install Docker → pull the image → run container → query prediction endpoint.

---

## 13. Which model for extracting invoice fields?

**Answer:** invoice
**Explanation:** The invoice prebuilt model extracts these fields with minimal effort.

---

## 14. Which service to extract invoice items, sales, customer details from scanned invoices?

**Answer:** Azure AI Document Intelligence
**Explanation:** This service is optimized for extracting structured data from documents like invoices.

---

## 15. Which kind for OpenAI resource in az CLI?

**Answer:** OpenAI
**Explanation:** The OpenAI kind enables generative text capabilities.

---

## 16. Which flag for customer-managed key in az CLI?

**Answer:** --encryption
**Explanation:** Use `--encryption` to specify customer-managed key settings.

---

## 17. Which image to use for containerized sentiment analysis?

**Answer:** mcr.microsoft.com/azure-cognitive-services/textanalytics/sentiment
**Explanation:** This is the container image for sentiment analysis.

---

## 18. What to use for Billing in docker run for sentiment analysis?

**Answer:** https://contoso.cognitiveservices.azure.com
**Explanation:** Use the endpoint URI for the resource as the billing identifier.

---

## 19. How to configure App1 for Azure Cognitive Services with minimal effort?

**Answer:** the endpoint URI and subscription key
**Explanation:** This is the simplest, lowest-effort way to configure access.

---

## 20. Which Language service for recognizing product/codename entities?

**Answer:** custom Named Entity Recognition (NER)
**Explanation:** Custom NER allows recognition and categorization of specific entities with minimal development effort.

---

## 21. Which Azure service to optimize reading for users with learning differences?

**Answer:** Azure AI Immersive Reader
**Explanation:** Immersive Reader improves reading comprehension with accessibility features.

---

## 22. Sequence to deploy Azure OpenAI GPT-3.5 Turbo for writing press releases

**Answer:** 4-2-5
**Explanation:** Deploy GPT-3.5 Turbo → Apply Marketing Writing Assistant template → Deploy to new web app.

---

## 23. What does 'Weather.Historic' entity represent in the CLU JSON sample?

**Answer:** by month
**Explanation:** The entity's start and end positions correspond to "by month" in the sample utterance.

---

## 24. Which SSML attribute to optimize synthesized voice for vehicles?

**Answer:** the effect attribute of the voice element
**Explanation:** This attribute applies audio effects to optimize speech for specific environments such as car interiors.

---

## 25. Solution for query throttling: add replicas?

**Answer:** Yes
**Explanation:** Adding replicas increases query throughput and reduces throttling.

---

## 26. Solution for query throttling: enable CMK encryption?

**Answer:** No
**Explanation:** CMK encryption addresses security, not query capacity or throttling.

---

## 27. Solution for query throttling: add indexes?

**Answer:** No
**Explanation:** Adding indexes organizes data but does not improve query throughput or reduce throttling.

---

## 28. Solution for query throttling: migrate to higher tier?

**Answer:** Yes
**Explanation:** A higher tier provides more resources, handling more queries and reducing throttling.

---

## 29. Increase face detection for blurs/sideways faces?

**Answer:** Change the detection model.
**Explanation:** Using a different detection model increases robustness for blurs and rotated faces.

---

## 30. Enable speech for chatbot: three actions?

**Answer:**

- Enable WebSockets for the chatbot app.
- Create a Speech service.
- Register a Direct Line Speech channel.
  **Explanation:** These steps enable speech input/output for the chatbot.

---

## 31. Improve QnA Maker chatbot accuracy: three actions sequence?

**Answer:** 5-2-4
**Explanation:** Add alternative phrasing → Retrain model → Republish model.

---

## 32. Custom Vision fault detection: three action sequence?

**Answer:** 5-2-1
**Explanation:** Create project → Upload & tag images → Train classifier.

---

## 33. Cognitive Search autocomplete: three actions?

**Answer:**

- Make API queries to the autocomplete endpoint and include suggesterName in the body.
- Add a suggester that has the three product name fields as source fields.
- Set the analyzer property for the three product name variants.
  **Explanation:** These enable efficient autocomplete on product names.

---

## 34. Azure AI Vision API request: which HTTP method?

**Answer:** POST
**Explanation:** The API requires a POST to submit image data for analysis.

---

## 35. Azure AI Vision API: visual feature to detect clipart/line drawing?

**Answer:** imageType
**Explanation:** The `imageType` visual feature identifies whether an image is clipart or a line drawing.

---

## 36. Custom Vision retraining: action sequence to minimize effort?

**Answer:** 6-5-2
**Explanation:** Upload all images → Get suggested tags → Review and confirm tags.

---

## 37. Custom Vision project type for defect/package completeness?

**Answer:** Object detection
**Explanation:** Object detection identifies defects and verifies presence of all products in a package.

---

## 38. Custom Vision domain for intermittent connectivity?

**Answer:** General (compact)
**Explanation:** The compact domain is optimized for edge/offline use.

---

## 39. Document Intelligence: model for handwritten content?

**Answer:** "prebuilt-read"
**Explanation:** The prebuilt-read model detects handwritten content in documents.

---

## 40. Document Intelligence: minimum confidence threshold?

**Answer:** 0.75
**Explanation:** A confidence threshold of 0.75 ensures reliable detection of handwritten content.

---

# AI-102 Exam Questions and Answers

---

## Question 1 ![image1](image1)

**Scenario:**
You have an Azure subscription that contains an Azure OpenAI resource named AI1 and a user named User1.
You need to ensure that User1 can perform the following actions in Azure AI Studio:

- Identify resource endpoints.
- View models that are available for deployment.
- Generate text and images by using deployed models.
  The solution must follow the principle of least privilege.
  **Question:** Which role should you assign to User1?

**Correct Answer:**

- Cognitive Services OpenAI User

**Explanation:**
This role grants users the minimum permissions needed to view and interact with Azure OpenAI resources, following the principle of least privilege.

---

## Question 2 ![image2](image2)

**Scenario:**
You have an Azure subscription that contains an Azure AI Content Safety resource named CS1.
You need to call CS1 to identify whether a user request contains hateful language.
**Question:** What should you choose for Dropdown 1 in the API endpoint?

**Correct Answer:**

- contentsafety/

**Explanation:**
You should use the contentsafety/ endpoint to access content safety features for identifying harmful or hateful language.

---

## Question 3 ![image3](image3)

**Scenario:**
You have an Azure subscription that contains an Azure AI Content Safety resource named CS1.
You need to call CS1 to identify whether a user request contains hateful language.
**Question:** What should you choose for Dropdown 2 in the API endpoint?

**Correct Answer:**

- text:analyze

**Explanation:**
The text:analyze API operation is used to analyze the text for content safety.

---

## Question 4 ![image4](image4)

**Scenario:**
You are building an app that will provide users with definitions of common AI terms using Python and OpenAI API.
**Question:** Will the response contain an explanation of large language models (LLMs) that has a high degree of certainty?

**Correct Answer:**

- No

**Explanation:**
The response is not guaranteed to have a high degree of certainty, as LLMs can generate varied outputs.

---

## Question 5 ![image5](image5)

**Scenario:**
You are building an app that will provide users with definitions of common AI terms using Python and OpenAI API.
**Question:** Changing "What is an LLM?" to "What is an LLM in the context of AI models?" will produce the intended response.

**Correct Answer:**

- Yes

**Explanation:**
Clarifying the prompt improves the chance for a relevant and accurate response.

---

## Question 6 ![image6](image6)

**Scenario:**
You are building an app that will provide users with definitions of common AI terms using Python and OpenAI API.
**Question:** Changing "You are a helpful assistant." to "You must answer only within the context of AI language models." will produce the intended response.

**Correct Answer:**

- Yes

**Explanation:**
Refining the system prompt focuses the assistant's responses within the specified context.

---

## Question 7 ![image7](image7)

**Scenario:**
You have an Azure subscription that contains an Azure AI Document Intelligence resource named DI1 using Standard S0 tier.
You have the files: File1.pdf (800MB), File2.jpg (1KB), File3.tiff (5MB).
**Question:** Which files can you analyze by using DI1?

**Correct Answer:**

- File3.tiff only

**Explanation:**
File3.tiff is the only file supported by the service and within supported size and format limits.

---

## Question 8 ![image8](image8)

**Scenario:**
You have an Azure subscription that contains an Azure AI Content Safety resource named CS1. You plan to build an app that will analyze user-generated documents and identify offensive terms that are specific to the local language dialect.
**Question:** You need to create a dictionary that will contain the offensive terms. The solution must minimize development effort. What should you use?

**Correct Answer:**

- a blocklist

**Explanation:**
A blocklist allows you to define custom lists of offensive terms, minimizing development effort.

---

## Question 9 ![image9](image9)

**Scenario:**
You have an Azure subscription that contains an Azure AI Search resource named AS1. You implement a custom skill in AS1 that performs language and sentiment analysis of documents.
**Question:** In which order will AS1 index the documents?

**Correct Answer:**

- 3-4-2-1-5 (document cracking, field mappings, skillset execution, output field mappings, push to index)

**Explanation:**
This is the correct order for document processing in Azure AI Search.

---

## Question 10 ![image10](image10)

**Scenario:**
You are building a chatbot that will use an Azure OpenAI model.
**Question:** Which three actions should you perform in sequence to deploy the model?

**Correct Answer:**

- 6-3-5 (Apply for access to Azure OpenAI, Provision an Azure OpenAI resource, Deploy the GPT model)

**Explanation:**
You must first get access, provision the resource, then deploy the model.

---

## Question 11 ![image11](image11)

**Scenario:**
You plan to build an app that will use the Azure OpenAI DALL-E model.
**Question:** What should you use to deploy the model?

**Correct Answer:**

- Azure AI Studio and Azure Command-Line Interface (CLI)

**Explanation:**
These tools are required to provision and deploy DALL-E within Azure OpenAI.

---

## Question 12 ![image12](image12)

**Scenario:**
You are building an app that will share user images.
You need to configure the app to categorize the image as either a photograph or a drawing, and generate a caption for the image.
**Question:** Which two services in Azure AI Vision should you include?

**Correct Answer:**

- image descriptions in Azure AI Vision
- image type detection in Azure AI Vision

**Explanation:**
These services minimize development effort and provide the required capabilities.

---

## Question 13 ![image13](image13)

**Scenario:**
You are building an app that will analyze text by using Azure AI Content Safety.
You need to identify text that contains hateful content.
**Question:** What should you choose for Dropdown 1 in the code?

**Correct Answer:**

- CategoriesAnalysis

**Explanation:**
This analyzes text for categories such as hate, violence, etc.

---

## Question 14 ![image14](image14)

**Scenario:**
You are building an app that will analyze text by using Azure AI Content Safety.
You need to identify text that contains hateful content.
**Question:** What should you choose for Dropdown 2 in the code?

**Correct Answer:**

- Severity ?? 0);

**Explanation:**
This extracts the severity of hateful content from the analysis response.

---

## Question 15 ![image15](image15)

**Scenario:**
You have the files: File1.pdf, File2.jpg, File3.docx, File4.webp, File5.png.
**Question:** Which files can you analyze by using Azure AI Content Understanding?

**Correct Answer:**

- File1.pdf, File2.jpg, and File5.png only

**Explanation:**
Azure AI Content Understanding supports PDF, JPG, and PNG files.

---

## Question 16 ![image16](image16)

**Scenario:**
You have a blog that allows users to append feedback comments. Some comments contain harmful content.
**Question:** Which two actions should you perform to detect harmful content with minimal development effort?

**Correct Answer:**

- From the Azure portal, create an Azure AI Content Safety resource.
- Sign in to Content Safety Studio and select Moderate text content.

**Explanation:**
These steps will allow you to quickly prototype content moderation.

---

## Question 17 ![image17](image17)

**Scenario:**
You have an app that uses an Azure AI Content Safety blocklist.
You need to remove an entry from the blocklist, minimizing impact on existing entries.
**Question:** What should you choose for Dropdown 1?

**Correct Answer:**

- RemoveBlocklistItems

**Explanation:**
This method removes specific entries without impacting the rest of the blocklist.

---

## Question 18 ![image18](image18)

**Scenario:**
You have an app that uses an Azure AI Content Safety blocklist.
You need to remove an entry from the blocklist, minimizing impact on existing entries.
**Question:** What should you choose for Dropdown 2?

**Correct Answer:**

- RemoveTextBlocklistItemsOptions

**Explanation:**
This class specifies options for removing blocklist items by ID.

---

# AI-102 Practice Questions and Answers

---

## Question 18

You are building a chatbot that will use question answering in Azure Cognitive Service for Language.
You have a PDF named Doc1.pdf that contains a product catalogue and a price list.
You upload Doc1.pdf and train the model.
During testing, users report that the chatbot responds correctly to the following question: What is the price of ?
The chatbot fails to respond to the following question: How much does cost?
You need to ensure that the chatbot responds correctly to both questions.

**Solution:** From Language Studio, you add alternative phrasing to the question and answer pair, and then retrain and republish the model.
Does this meet the goal?

**Answer Options:**

- Yes (Correct)
- No

**Explanation:**
Yes is CORRECT because adding alternative phrasing to the question and answer pair in Language Studio can help the model recognize different ways users might ask the same question. By providing alternative phrasings, you are effectively training the model to understand and respond to variations of the question, ensuring that it can handle both "What is the price of?" and "How much does cost?".

---

## Question 19

You are building an app that will scan confidential documents and use the Language service to analyze the contents.
You provision an Azure Cognitive Services resource.
You need to ensure that the app can make requests to the Language service endpoint. The solution must ensure that confidential documents remain on-premises.
Which three actions should you perform in sequence?

**ACTIONS:**

1. Run the container and specify an App ID and Client Secret.
2. Provision an on-premises Kubernetes cluster that is isolated from the internet.
3. Pull an image from the Microsoft Container Registry (MCR).
4. Run the container and specify an API key and the Endpoint URL of the Cognitive Services resource.
5. Provision an on-premises Kubernetes cluster that has internet connectivity.
6. Pull an image from Docker Hub.
7. Provision an Azure Kubernetes Service (AKS) resource.

**Answer Options:**

- 3-2-1
- 1-3-2
- 2-1-3
- 5-3-1
- 2-3-4 (Correct)

**Explanation:**
2-3-4 is the CORRECT sequence of actions:

1. Provision an on-premises Kubernetes cluster that is isolated from the internet.
2. Pull an image from the Microsoft Container Registry (MCR).
3. Run the container and specify an API key and the Endpoint URL of the Cognitive Services resource.

---

## Question 20

You are building a transcription service for technical podcasts.
Testing reveals that the service fails to transcribe technical terms accurately.
You need to improve the accuracy of the service.
Which five actions should you perform in sequence?

**ACTIONS:**

1. Deploy the model.
2. Create a Custom Speech project.
3. Upload training datasets.
4. Create a speech-to-text model.
5. Create a Speaker Recognition model.
6. Train the model.
7. Create a Conversational Language Understanding model.

**Answer Options:**

- 2-3-4-6-1 (Correct)
- 2-4-6-3-1
- 3-4-2-6-1

**Explanation:**
2-4-3-6-1 is the CORRECT sequence of actions:

1. Create a Custom Speech project.
2. Create a speech-to-text model.
3. Upload training datasets.
4. Train the model.
5. Deploy the model.

---

## Question 21

You have a Docker host named Host1 that contains a container base image.
You have an Azure subscription that contains a custom speech-to-text model named model1.
You need to run model1 on Host1.
Which three actions should you perform in sequence?

**ACTIONS:**

1. Retrain the model.
2. Request approval to run the container.
3. Export model1 to Host1.
4. Run the container.
5. Configure disk logging.

**Answer Options:**

- 2-4-2
- 3-2-4
- 2-3-4 (Correct)
- 2-1-3

**Explanation:**
2-3-4 is the CORRECT sequence of actions:

1. Request approval to run the container.
2. Export model1 to Host1.
3. Run the container.

---

# AI-102 Exam Q&A Collection (with Multiple Choice Options)

This file contains a collection of AI-102 exam questions with all answer options, the correct answer clearly indicated, and explanations when available.

---

## 1. Accessing Microsoft Word documents in Azure Storage for AI Search

**Question:**
You want to find information in Microsoft Word documents that are stored in an Azure Storage blob container. What should you do to ensure Azure AI Search can access the files?

**Options:**

- Add a JSON file that defines an Azure AI Search index to the blob container
- Enable anonymous access for the blob container
- **In an Azure AI Services resource, add a data source that references the container where the files are stored** (Correct)

---

## 2. Making a field available in search results

**Question:**
You're creating an index that includes a field named modified_date. You want to ensure that the modified_date field can be included in search results. Which attribute must you apply to the modified_date field in the index definition?

**Options:**

- searchable
- filterable
- **retrievable** (Correct)

---

## 3. Mapping data values from source to index

**Question:**
You created a data source and an index. What must you create to map the data values in the data source to the fields in the index?

**Options:**

- A synonym map
- **An indexer** (Correct)
- A suggester

---

## 4. Enriching the index with detected language

**Question:**
You want to create a search solution that uses a built-in AI skill to determine the language in which each indexed document is written, and enrich the index with a field indicating the language. Which kind of Azure AI Search object must you create?

**Options:**

- Synonym map
- **Skillset** (Correct)
- Scoring Profile

---

## 5. Ordering search results by file size

**Question:**
You want your search solution to show results in descending order of the file_size field value. What is the simplest way to accomplish this goal?

**Options:**

- Create a scoring profile that boosts results based on the file_size field
- Make the file_size field facetable, and include a facet parameter that specifies the file_size field in queries
- **Make the file_size field sortable, and include an orderby parameter that specifies the file_size field in queries** (Correct)

---

## 6. Implementing autocomplete in search UI

**Question:**
You created a search solution. Users want to be able to enter a partial search expression and have the user interface automatically complete the input. What should you add to the index?

**Options:**

- **A suggester** (Correct)
- A synonym map
- A scoring profile

---

## 7. Integrating user input into QnA Maker (Active Learning)

**Question:**
You have a chatbot that uses a QnA Maker application.
You enable active learning for the knowledge base used by the QnA Maker application.
You need to integrate user input into the model.
Which four actions should you perform in sequence?

**Options:**

1. Add a task to the Azure resource
2. Approve and reject suggestions
3. Publish the knowledge base
4. Modify the automation task logic app to run an Azure Resource Manager template that creates the Azure Cognitive Services resource
5. For the knowledge base, select Show active learning suggestions
6. Save and train the knowledge base
7. Select the properties of the Azure Cognitive Services resource

**Correct Sequence:**
5 → 2 → 6 → 3

---

## 8. Translator API – URI parameters for webpage translation

**Question:**
You are developing a method for an application that uses the Translator API.
The method will receive the content of a webpage, then translate it into Greek (el), and include a transliteration using the Roman alphabet.
You need to create the URI for the call to the Translator API.
Which three additional query parameters should you include?

**Options:**

- textType=html
- to=el
- toScript=Latn
  (**All 3 above are correct**)

---

## 9. Uploading speech samples to Speech Studio

**Question:**
You need to upload speech samples to a Speech Studio project for use in training. How should you upload the samples?

**Options:**

- Upload a .zip file that contains a collection of audio files in the .mp3 format and a corresponding text transcript file.
- Upload individual .wav files, one by one.
- **Upload a .zip file that contains a collection of audio files in the .wav format and a corresponding text transcript file.** (Correct)
- Upload a .csv file with links to audio samples.

---

## 10. Azure AI Search: Data source compatibility

**Question:**
You have the following data sources:

- Finance: On-premises Microsoft SQL Server database
- Sales: Azure Cosmos DB using the Core (SQL) API
- Logs: Azure Table storage
- HR: Azure SQL database

You need to ensure that you can search all the data by using the Azure AI Search REST API. What should you do?

**Options:**

- Mirror Finance to an Azure SQL database **(Correct)**
- Mirror Finance to Azure Table storage
- Use Azure Data Factory to create Linked Services for each source
- Use Azure Synapse to create a serverless view

---

## 11. Extracting information from receipts with minimal development effort

**Question:**
Your company wants to reduce how long it takes for employees to log receipts in expense reports. All the receipts are in English.
You need to extract top-level information from the receipts, such as the vendor and the transaction total. The solution must minimize development effort.
Which Azure service should you use?

**Options:**

- Custom Vision
- Personalizer
- **Azure AI Document Intelligence** (Correct)
- Computer Vision

---

## 12. Recognizing "Paris" as an entity in LUIS

**Question:**
You are building a Language Understanding model for purchasing tickets.
You have the following utterance for an intent named PurchaseAndSendTickets:
Purchase [2 audit business] tickets to [Paris][next monday] and send tickets to [email@domain.com]
You need to select the entity types.
The solution must use built-in entity types to minimize training data whenever possible.
Which entity type should you use for the label "Paris"?

**Options:**

- Email
- List
- Regex
- **GeographyV2** (Correct)
- Machine learned

---

## 13. Recognizing "email@domain.com" as an entity in LUIS

**Question:**
You are building a Language Understanding model for purchasing tickets.
You have the following utterance for an intent named PurchaseAndSendTickets:
Purchase [2 audit business] tickets to [Paris][next monday] and send tickets to [email@domain.com]
You need to select the entity types.
The solution must use built-in entity types to minimize training data whenever possible.
Which entity type should you use for the label "email@domain.com"?

**Options:**

- **Email** (Correct)
- List
- Regex
- GeographyV2
- Machine learned

---

## 14. Recognizing "2 audit business" as an entity in LUIS

**Question:**
You are building a Language Understanding model for purchasing tickets.
You have the following utterance for an intent named PurchaseAndSendTickets:
Purchase [2 audit business] tickets to [Paris][next monday] and send tickets to [email@domain.com]
You need to select the entity types.
The solution must use built-in entity types to minimize training data whenever possible.
Which entity type should you use for the label "2 audit business"?

**Options:**

- Email
- List
- Regex
- GeographyV2
- **Machine learned** (Correct)

---

## 15. Moving a Custom Vision object detection model between environments

**Question:**
You have a Custom Vision resource named acvdev in a development environment.
You have a Custom Vision resource named acvprod in a production environment.
In acvdev, you build an object detection model named obj1 in a project named proj1.
You need to move obj1 to acvprod.
Which three actions should you perform in sequence?

**Options:**

- 2-3-1
- 2-5-1
- 2-1-4
- **2-1-3** (Correct)

---

## 16. LUDown: Identifying an intent

**Question:**
You are building a bot that will use Language Understanding.
You have a LUDown file that contains the following content with several sections, including `## SelectItem`.
Based on the information presented, select the answer choice that completes the following statement correctly:

"SelectItem is **\*\***\_\_**\*\***."

**Options:**

- a domain
- an entity
- **an intent** (Correct)
- an utterance

---

## 17. LUDown: Identifying an utterance

**Question:**
You are building a bot that will use Language Understanding.
You have a LUDown file that contains the following content with several sections, including `- choose {@DirectionalReference=top right}`.
Based on the information presented, select the answer choice that completes the following statement correctly:

"Choose {@DirectionalReference=top right} is **\*\***\_\_**\*\***."

**Options:**

- a domain
- an entity
- an intent
- **an utterance** (Correct)

---

## 18. Azure OpenAI: Completing code for embeddings

**Question:**
You have an Azure subscription that is linked to a Microsoft Entra tenant.
The subscription contains an Azure OpenAI resource named OpenAI1 with a primary API key of `111a1f1a1fa11aaa1fa1a1a1a1f1a1aa`.
OpenAI1 has a deployment named `embeddings1` that uses the text-embedding-ada-002 model.
You need to query OpenAI and retrieve embeddings for text input.
You need to complete the provided code.

What should you choose for Placeholder 1?

**Options:**

- x1xx1f1x1-x1f1-xxxx-xxxx-x1f11xxx1fx1
- **111a1f1a1fa11aaa1fa1a1a1a1f1a1aa** (Correct)
- 1y1y1yyy-1yy1y-yy1y1-yy1y1f1111y1

---

## 19. Azure OpenAI Deployment Name for Embeddings

**Question:**
You have an Azure subscription that contains an Azure OpenAI resource named OpenAI1 with a primary API key.
OpenAI1 has a deployment named embeddings1 that uses the text-embedding-ada-002 model.
You need to query OpenAI and retrieve embeddings for text input.
You need to complete the code: What should you choose for Placeholder 2?

**Options:**

- **embeddings1** (Correct)
- OpenAI1
- text-embedding-ada-002

---

## 20. Azure AI Vision Service for Workspace Safety Compliance

**Question:**
You are building an app that will use Azure AI to monitor workspaces for safety regulation compliance.
Requirements:

- Generates alerts when employees enter high-risk areas
- Monitors video feeds in real time
- Minimizes development effort
  What should you recommend?

**Options:**

- object detection in Azure AI Custom Vision
- **Azure AI Vision Spatial Analysis** (Correct)
- Azure AI Vision Image Analysis
- Azure AI Video Indexer

---

## 21. Azure OpenAI Model for Cosine Similarity

**Question:**
You have an Azure subscription and 10,000 ASCII files.
You need to identify files that contain specific phrases. The solution must use cosine similarity.
Which Azure OpenAI model should you use?

**Options:**

- GPT-3.5 Turbo
- **text-embedding-ada-002** (Correct)
- GPT-4-32k
- GPT-4

---

## 22. Document Intelligence Studio: File Format and Size Support

**Question:**
You have an Azure subscription that contains an Azure AI Document Intelligence resource named Aldoc1 in the S0 tier.
You have the files shown in the table (JPG, PDF, PNG, XLSX; some password-locked, various sizes).
You need to train a custom extraction model by using Aldoc1. Which files can you upload to Document Intelligence Studio?

**Options:**

- File2, and File5 only
- File2, File4, and File5 only
- File1, File2, File3, File4, and File5
- **File1 and File2 only** (Correct)

---

## 23. Service for Dynamic Text Classification in a Chatbot

**Question:**
You are building a chatbot.
You need to ensure that the chatbot can classify user input into separate categories. The categories must be dynamic and defined at the time of inference.
Which service should you use to classify the input?

**Options:**

- Azure OpenAI text summarization
- Azure AI Language custom text classification
- Azure AI Language custom named entity recognition (NER)
- **Azure OpenAI text classification** (Correct)

---

## 24. Azure AI Vision for PPE Compliance in Factories

**Question:**
You have a factory that produces food products.
You need to build a monitoring solution for staff compliance with personal protective equipment (PPE) requirements.
Solution requirements:

- Identify staff who have removed masks or safety glasses
- Perform a compliance check every 15 minutes
- Minimize development effort
- Minimize costs
  Which service should you use?

**Options:**

- Face
- **Azure AI Vision** (Correct)
- Azure Video Analyzer for Media (formerly Video Indexer)

---

## 25. Azure OpenAI Role Assignment Principle of Least Privilege

**Question:**
You have an Azure subscription that contains an Azure OpenAI resource named AI1 and a user named User1.
You need to ensure that User1 can add custom data sources to AI1. The solution must follow the principle of least privilege.
Which role should you assign to User1?

**Options:**

- **Cognitive Services OpenAI Contributor** (Correct)
- Search Index Data Contributor
- Cognitive Services Contributor
- Search Service Contributor

---

## 26. Custom Skill for Invoice Property Extraction with Azure AI Search

**Question:**
You have an Azure AI Search resource named Search1.
You have an app named App1 that uses Search1 to index content.
You need to add a custom skill to App1 to ensure that the app can recognize and retrieve properties from invoices by using Search1.
What should you include in the solution?

**Options:**

- Azure AI Immersive Reader
- Azure OpenAI
- **Azure AI Document Intelligence** (Correct)
- Azure AI Custom Vision

---

# Azure AI Exam Questions – Questions, Options, and Correct Answers

---

## Question 1

You have 100 chatbots that each has its own Language Understanding model. Frequently, you must add the same phrases to each model.
You need to programmatically update the Language Understanding models to include the new phrases.
How should you complete the code? (Drag and drop the correct values to fill the code blanks.)

**Options to drag:**

- AddPhraseListAsync
- PhraseList
- PhraseListCreateObject
- Phrases
- SavePhraseListAsync
- UploadPhraseListAsync

**Code to complete:**

```csharp
var phraselistId = await client.Features.__________ (appId, versionId, new __________ {
    EnabledForAllModels = false,
    IsExchangeable = true,
    Name = "PL1",
    Phrases = "item1,item2,item3,item4,item5"
});
```

**Correct Drag-and-Drop Sequence:**

- Box 1: AddPhraseListAsync
- Box 2: PhraseListCreateObject

---

## Question 2

You plan to use a Language Understanding application named app1 that is deployed to a container.
App1 has the following versions:

| Version | Trained date | Published date |
| ------- | ------------ | -------------- |
| V1.2    | None         | None           |
| V1.1    | 2020-10-01   | None           |
| V1.0    | 2020-09-01   | 2020-09-15     |

You need to create a container using the latest deployable version of app1.
Which three actions should you perform in sequence?

**Actions:**

- Run a container that has version set as an environment variable.
- Export the model by using the Export as JSON option.
- Select v1.1 of app1.
- Run a container and mount the model file.
- Select v1.0 of app1.
- Export the model by using the Export for containers (GZIP) option.
- Select v1.2 of app1.

**Correct Sequence:**

1. Select v1.1 of app1.
2. Export the model by using the Export for containers (GZIP) option.
3. Run a container and mount the model file.

---

## Question 3

You need to build a chatbot that meets the following requirements:

- Supports chit-chat, knowledge base, and multilingual models
- Performs sentiment analysis on user messages
- Selects the best language model automatically

What should you integrate into the chatbot?

A. QnA Maker, Language Understanding, and Dispatch
B. Translator, Speech, and Dispatch
C. Language Understanding, Text Analytics, and QnA Maker
D. Text Analytics, Translator, and Dispatch

**Correct Answer:** C

---

## Question 4

Your company wants to reduce how long it takes for employees to log receipts in expense reports.
You need to extract top-level information from the receipts, such as the vendor and the transaction total. The solution must minimize development effort.
Which Azure service should you use?

A. Custom Vision
B. Personalizer
C. Form Recognizer
D. Computer Vision

**Correct Answer:** C

---

## Question 5

You need to create a new resource that will be used to perform sentiment analysis and optical character recognition (OCR). The solution must:

- Use a single key and endpoint to access multiple services.
- Consolidate billing for future services.
- Support future use of Computer Vision.

How should you complete the HTTP request to create the new resource? (Select the appropriate options.)

**Options to select:**

- HTTP Verb: PATCH, POST, PUT
- "kind": CognitiveServices, ComputerVision, TextAnalytics

**Correct Selection:**

- HTTP Verb: PUT
- "kind": CognitiveServices

---

## Question 6

You are developing a new sales system that will process video and text from a public-facing website.
You want to monitor the system to ensure equitable results regardless of user location or background.
Which two responsible AI principles provide guidance?

A. transparency
B. fairness
C. inclusiveness
D. reliability and safety
E. privacy and security

**Correct Answer:** B (fairness), C (inclusiveness)

---

## Question 7

You plan to use containerized versions of the Anomaly Detector API on local devices for testing/on-premises datacenters.
You need to ensure deployments meet these requirements:

- Prevent billing and API info from being stored in command-line histories.
- Control container image access using Azure RBAC.

Which four actions should you perform in sequence?

**Actions:**

- Create a custom Dockerfile.
- Pull the Anomaly Detector container image.
- Distribute a docker run script.
- Push the image to an Azure container registry.
- Build the image.
- Push the image to Docker Hub.

**Correct Sequence:**

1. Create a custom Dockerfile.
2. Pull the Anomaly Detector container image.
3. Build the image.
4. Push the image to an Azure container registry.

---

## Question 8

You plan to deploy a containerized Azure Cognitive Services service for text analysis.
You configure https://contoso.cognitiveservices.azure.com as the endpoint.
You need to run the container on an Azure VM using Docker.
How should you compose the command? (Select the appropriate options in the answer area.)

**Correct Command:**

```bash
docker run --rm -it -p 5000:5000 --memory 8g --cpus 1 \
mcr.microsoft.com/azure-cognitive-services/textanalytics/sentiment \
Eula=accept \
Billing=https://contoso.cognitiveservices.azure.com \
ApiKey=xxxxxxxxxxxxxxxxxxxx
```

---

## Question 9

You need to call the method to create a free Azure resource in the West US Azure region. The resource will be used to generate captions of images automatically.
Which code should you use?

A. create_resource(client, "res1", "ComputerVision", "F0", "westus")
B. create_resource(client, "res1", "CustomVision.Prediction", "F0", "westus")
C. create_resource(client, "res1", "ComputerVision", "S0", "westus")
D. create_resource(client, "res1", "CustomVision.Prediction", "S0", "westus")

**Correct Answer:** A

---

## Question 10

You successfully run the following HTTP request to regenerate a key for Azure Cognitive Services.
What is the result of the request?

A. A key for Azure Cognitive Services was generated in Azure Key Vault.
B. A new query key was generated.
C. The primary subscription key and the secondary subscription key were rotated.
D. The secondary subscription key was reset.

**Correct Answer:** D

---

## Question 11

You receive sample files to use for training a custom Form Recognizer model.
Which three files can you use to train the model? (Each correct answer presents a complete solution.)

A. File1 (PDF, 20 MB)
B. File2 (MP4, 100 MB)
C. File3 (JPG, 20 MB)
D. File4 (PDF, 100 MB)
E. File5 (GIF, 1 MB)
F. File6 (JPG, 40 MB)

**Correct Answer:** A, C, F, D

---

## Question 12

A customer uses Azure Cognitive Search and plans to enable server-side encryption with customer-managed keys (CMK) stored in Azure.
What are three implications of the planned change?

A. The index size will increase.
B. Query times will increase.
C. A self-signed X.509 certificate is required.
D. The index size will decrease.
E. Query times will decrease.
F. Azure Key Vault is required.

**Correct Answer:** A, B, F

---

## Question 13

You are developing a new sales system that will process the video and text from a public-facing website.
You plan to notify users that their data has been processed by the sales system.
Which responsible AI principle does this help meet?

A. transparency
B. fairness
C. inclusiveness
D. reliability and safety

**Correct Answer:** A

---

## Question 14

You create a web app named app1 that runs on an Azure virtual machine named vm1, which is on an Azure virtual network named vnet1.
You plan to create a new Azure Cognitive Search service named service1.
You need to ensure that app1 can connect directly to service1 without routing traffic over the public internet.
Solution: You deploy service1 and a public endpoint to a new virtual network, and you configure Azure Private Link.
Does this meet the goal?

A. Yes
B. No

**Correct Answer:** B

---

## Question 15

You create a web app named app1 that runs on an Azure virtual machine named vm1, which is on an Azure virtual network named vnet1.
You plan to create a new Azure Cognitive Search service named service1.
You need to ensure that app1 can connect directly to service1 without routing traffic over the public internet.
Solution: You deploy service1 and a public endpoint, and you configure an IP firewall rule.
Does this meet the goal?

A. Yes
B. No

**Correct Answer:** B

---

## Question 16

You create a web app named app1 that runs on an Azure virtual machine named vm1, which is on an Azure virtual network named vnet1.
You plan to create a new Azure Cognitive Search service named service1.
You need to ensure that app1 can connect directly to service1 without routing traffic over the public internet.
Solution: You deploy service1 and a public endpoint, and you configure a network security group (NSG) for vnet1.
Does this meet the goal?

A. Yes
B. No

**Correct Answer:** B

---

## Question 17

You need to identify unusual values in each time series to help predict machinery failures.
Which Azure service should you use?

A. Anomaly Detector
B. Cognitive Search
C. Form Recognizer
D. Custom Vision

**Correct Answer:** A

---

## Question 18

You are developing a streaming Speech to Text solution that will use the Speech SDK and MP3 encoding.
How should you complete the code? (Select the appropriate options in the answer area.)

**Audio Format Options:**

- AudioConfig.SetProperty
- AudioStreamFormat.GetCompressedFormat
- AudioStreamFormat.GetWaveFormatPCM
- PullAudioInputStream

**Recognizer Options:**

- KeywordRecognizer
- SpeakerRecognizer
- SpeechRecognizer
- SpeechSynthesizer

**Correct Answers:**

- Audio Format: AudioStreamFormat.GetCompressedFormat(AudioStreamContainerFormat.MP3)
- Recognizer: SpeechRecognizer

---

## Question 19

You need to use a video and audio feed from each learner’s computer to detect whether the learner is present and paying attention.

**For each requirement, select the appropriate Azure Cognitive Services service:**

- From a learner’s video feed, verify whether the learner is present: **Face**
- From a learner’s facial expression in the video feed, verify whether the learner is paying attention: **Face**
- From a learner’s audio feed, detect whether the learner is talking: **Speech**

---

## Question 20

Which two Azure resources are automatically created in RG1 when you provision the QnA Maker service?

A. Language Understanding
B. Azure SQL Database
C. Azure Storage
D. Azure Cognitive Search
E. Azure App Service

**Correct Answers:** D, E

---

## Question 21

You are building a language model by using a Language Understanding (classic) service.
You need to add more contributors. What should you use?

A. a conditional access policy in Azure Active Directory (Azure AD)
B. the Access control (IAM) page for the authoring resources in the Azure portal
C. the Access control (IAM) page for the prediction resources in the Azure portal

**Correct Answer:** B

---

## Question 22

You have an Azure Cognitive Search service.
You discover that some search query requests to the Cognitive Search service are being throttled.
You need to reduce the likelihood that search query requests are throttled.
Solution: You migrate to a Cognitive Search service that uses a higher tier.
Does this meet the goal?

A. Yes
B. No

**Correct Answer:** A

---

## Question 23

You need to develop an automated call handling system that can respond to callers in their own language (French and English only).
Which Azure Cognitive Services service should you use to meet each requirement?

- Detect the incoming language:
- Respond in the callers’ own language:

**Services to choose from:**

- Speaker Recognition
- Speech to Text
- Text Analytics
- Text to Speech
- Translator

**Correct Answers:**

- Detect the incoming language: Speech to Text
- Respond in the callers’ own language: Text to Speech

---

## Question 24

You have receipts that are accessible from a URL.
You need to extract data from the receipts by using Form Recognizer and the SDK. The solution must use a prebuilt model.
Which client and method should you use?

A. the FormRecognizerClient client and the StartRecognizeContentFromUri method
B. the FormTrainingClient client and the StartRecognizeContentFromUri method
C. the FormRecognizerClient client and the StartRecognizeReceiptsFromUri method
D. the FormTrainingClient client and the StartRecognizeReceiptsFromUri method

**Correct Answer:** C

---

## Question 25

You have a collection of 50,000 scanned documents that contain text.
You need to configure an enrichment pipeline to perform OCR and text analytics through Azure Cognitive Search while minimizing costs.
What should you attach to the skillset?

A. a new Computer Vision resource
B. a free (Limited enrichments) Cognitive Services resource
C. an Azure Machine Learning Designer pipeline
D. a new Cognitive Services resource that uses the S0 pricing tier

**Correct Answer:** D

---

## Question 26

You have an Azure Cognitive Search service.
You discover that some search query requests to the Cognitive Search service are being throttled.
You need to reduce the likelihood that search query requests are throttled.
Solution: You add indexes.
Does this meet the goal?

A. Yes
B. No

**Correct Answer:** B

---

## Question 27

You have an Azure Cognitive Search service.
You discover that some search query requests to the Cognitive Search service are being throttled.
You need to reduce the likelihood that search query requests are throttled.
Solution: You enable customer-managed key (CMK) encryption.
Does this meet the goal?

A. Yes
B. No

**Correct Answer:** B

---

## Question 28

You create a web app named app1 that runs on an Azure virtual machine named vm1, which is on an Azure virtual network named vnet1.
You plan to create a new Azure Cognitive Search service named service1.
You need to ensure that app1 can connect directly to service1 without routing traffic over the public internet.
Solution: You deploy service1 and a private endpoint to vnet1.
Does this meet the goal?

A. Yes
B. No

**Correct Answer:** A

---

## Question 29

You have a Language Understanding resource named lu1.
You need to ensure that bot1 adheres to the Microsoft responsible AI principle of inclusiveness.
How should you extend bot1?

A. Implement authentication for bot1.
B. Enable active learning for lu1.
C. Host lu1 in a container.
D. Add Direct Line Speech to bot1.

**Correct Answer:** D

---

## Question 30

You are building an app that will process incoming email and direct messages to either French or English language support teams.
Which Azure Cognitive Services API should you use?

**Endpoint:**

- api.cognitive.microsofttranslator.com
- eastus.api.cognitive.microsoft.com
- portal.azure.com

**Path:**

- /text/analytics/v3.1/entities/recognition/general
- /text/analytics/v3.1/languages
- /translator/text/v3.0/translate?to=en
- /translator/text/v3.0/translate?to=fr

**Correct Answer:**

- eastus.api.cognitive.microsoft.com
- /text/analytics/v3.1/languages

---

## Question 31

You have an Azure Cognitive Search instance that indexes purchase orders by using Form Recognizer.
You need to analyze the extracted information by using Microsoft Power BI.
What should you add to the indexer?

A. a projection group
B. a table projection
C. a file projection
D. an object projection

**Correct Answer:** B

---

## Question 32

You discover that some search query requests to the Cognitive Search service are being throttled.
You need to reduce the likelihood that search query requests are throttled.
Solution: You add replicas.
Does this meet the goal?

A. Yes
B. No

**Correct Answer:** A

---

## Question 33

You have an Azure Cognitive Search solution and a collection of blog posts that include a category field.
You need to index the posts. The solution must meet the following requirements:

- Include the category field in the search results.
- Ensure that users can search for words in the category field.
- Ensure that users can perform drill down filtering based on category.

Which index attributes should you configure for the category field?

A. searchable, sortable, and retrievable
B. searchable, facetable, and retrievable
C. retrievable, filterable, and sortable
D. retrievable, facetable, and key

**Correct Answer:** B

---

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
