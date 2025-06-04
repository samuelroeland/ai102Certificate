---

## Question 13

**Q:** You have an Azure subscription with an Azure AI Service resource named CSAccount1 and a virtual network named VNet1.
You need to:
- Prevent external access to CSAccount1
- Minimize administrative effort

**Which two actions should you perform?**

- A. In VNet1, enable a service endpoint for CSAccount1 ✅
- B. In CSAccount1, configure the Access control (IAM) settings
- C. In VNet1, modify the virtual network settings
- D. In VNet1, create a virtual subnet
- E. In CSAccount1, modify the virtual network settings ✅

**Answers:** A and E
**Explanation:** Enabling a service endpoint and modifying network settings in CSAccount1 ensures internal-only access and meets the requirements without extensive IAM configuration.
[Service Endpoints](https://learn.microsoft.com/en-us/azure/virtual-network/virtual-network-service-endpoints-overview)
[Virtual Network Settings](https://learn.microsoft.com/en-us/azure/virtual-network/virtual-networks-overview)
[IAM Access Control](https://learn.microsoft.com/en-us/azure/role-based-access-control/overview)

---

## Question 14

**Q:** You are building an Azure AI Language Understanding solution.
You notice many utterances vary only slightly (e.g. full airport names vs. codes).
**Which custom entity should you use to minimize training utterances?**

- A. Pattern.any ✅
- B. machine-learning
- C. regular expression
- D. list

**Answer:** A
**Explanation:** `Pattern.any` identifies multiple variations like “JFK” and “John F. Kennedy International Airport” as the same entity with minimal utterances.
[Pattern.any Docs](https://learn.microsoft.com/en-us/azure/ai-services/luis/concepts/patterns-features#pattern-any-entity)

---

## Question 15

**Q:** You need to test and optimize content filter configurations for an AI chatbot using Azure Content Safety.
**You use the Monitor online activity feature to run tests.**
Does this meet the requirement?

- A. Yes
- B. No ✅

**Answer:** B
**Explanation:** The Monitor feature is for live analysis, not testing. Use “Test” or “Analyze” tools for sample testing in Content Safety Studio.
[Content Safety Features](https://learn.microsoft.com/en-us/azure/ai-services/content-safety/overview#content-safety-studio-features)

---

## Question 16

**Q:** You use the Protected Material Detection feature in Content Safety Studio to test content filters on sample questions.
**Does this meet the requirement?**

- A. Yes
- B. No ✅

**Answer:** B
**Explanation:** Protected material detection is for identifying sensitive data like PII, not for tuning content filters for toxicity or harm. Use “Moderate” or “Life Safety” features.
[Protected Material Detection](https://learn.microsoft.com/en-us/azure/ai-services/content-safety/quickstart-protected-material/)

---

## Question 17

**Q:** You need to deploy a Language Understanding container to a host computer.
**What is the correct sequence of steps?**

- A. 5-4-3 ✅
- B. 5-4-1
- C. 5-3-2

**Answer:** A
**Explanation:**

1. Export the model from LUIS portal (Action 5)
2. Move the package to Docker input directory (Action 4)
3. Run the container (Action 3)
   [How to use LUIS containers](https://learn.microsoft.com/en-us/azure/ai-services/luis/luis-container-howto?tabs=3#how-to-use-the-container)

---

## Question 18

**Q:** You need to translate Microsoft Word and PowerPoint files from German to French.
You must:

- Preserve formatting
- Use a custom glossary

**What is the correct sequence of actions?**

- A. 1-4-6
- B. 1-6-3
- C. 1-3-2
- D. 1-3-6 ✅

**Answer:** D
**Explanation:**

1. Define translation specification (Action 1)
2. Upload glossary for German (Action 3)
3. Perform async translation (Action 6)
   [Document Translation Workflow](https://learn.microsoft.com/en-us/azure/ai-services/translator/document-translation/overview)

---

## Question 19

**Q:** You have an Azure subscription that contains an Azure AI Document Intelligence resource named Adoce1.
App1 uses the business card model v2.1.
You need to enable QR code reading while minimizing administrative effort.
**What should you do first?**

- A. Upgrade the business card model to v3.0
- B. Implement the read model ✅
- C. Deploy a custom model
- D. Implement the contract model

**Answer:** B
**Explanation:** The read model supports extracting QR codes, while the business card model does not. This is the lowest-effort path to QR code support.
[Read More](https://learn.microsoft.com/en-us/azure/ai-services/document-intelligence/concept/add-on-capabilities?view=doc-intel-3.1.0)

---

## Question 20

**Q:** You want User1 to upload datasets and fine-tune existing models in Azure OpenAI.
**Which role should you assign to follow the principle of least privilege?**

- A. Cognitive Services OpenAI Contributor ✅
- B. Cognitive Services Contributor
- C. Cognitive Services OpenAI User
- D. Contributor

**Answer:** A
**Explanation:** This role grants exactly the permissions required for dataset upload and model tuning without unnecessary access.
[OpenAI RBAC Roles](https://learn.microsoft.com/en-us/azure/ai-services/openai/how-to/role-based-access-control)

---

## Question 21

**Q:** You trained an Azure Custom Vision model to identify products using the Retail domain.
You plan to export the model for a mobile app.
**Which actions should you perform in sequence?**

- A. 3-2-1
- B. 1-3-2
- C. 1-2-3 ✅
- D. 2-3-4

**Answer:** C
**Explanation:**

1. Change domain to compact (e.g., Retail-compact)
2. Retrain the model
3. Export for mobile app deployment
   [Export Custom Vision Models](https://learn.microsoft.com/en-us/azure/ai-services/custom-vision-service/export-your-model)

---

## Question 22

**Q:** You are building a chatbot using custom question answering in Azure AI Language.
The bot answers "What is the price of Product1?" correctly but fails on "Which colors of Product1 are available?"
**What should you do to improve accuracy?**

- A. Add alternative phrasing to the question and response pair
- B. Add a new question and response pair ✅
- C. Modify the system prompt
- D. Modify the original documents and retrain the model

**Answer:** B
**Explanation:** A new question and answer pair is needed if the knowledge base doesn’t include that specific data, even if semantically similar to an existing one.
[Custom QA Overview](https://learn.microsoft.com/en-us/azure/ai-services/language-service/question-answering/overview)

# AI-102 Exam Questions and Answers (Complete with All Options)

---

## Question 1: Provision a Standard Tier Cognitive Service for Receipt Scanning

**Task:** Use `provision_resource` to create a Standard-tier Form Recognizer resource for scanned receipts.

```csharp
provision_resource("res1", kind, tier, location);
```

**Kind Options:**

- [ ] ComputerVision
- [ ] CustomVision.Prediction
- [ ] CustomVision.Training
- [x] FormRecognizer ✅

**Tier & Location Options:**

- [ ] "eastus", "S1"
- [ ] "useast", "S1"
- [x] "S0", "eastus" ✅
- [ ] "S0", "useast"

---

## Question 2: Update Custom Vision Classifier

**Correct Sequence:**

- [ ] 2-6-1-5-3
- [x] 4-6-1-5-3 ✅
- [ ] 2-6-5-1-3

**Steps:**

1. Label the sample images
2. From Vision Studio, open the project
3. Publish the model
4. From the Custom Vision portal, open the project
5. Retrain the model
6. Upload sample images of the new products
7. From Azure Machine Learning studio, open the workspace

---

## Question 3: Deploy Anomaly Detector on Offline Server

**Correct Sequence:**

- [ ] 6-5-3-1
- [ ] 1-5-3-6
- [x] 3-6-5-1 ✅

**Steps:**

1. Query the prediction endpoint on Server1
2. From Server1, run the docker push command
3. Install the Docker Engine on Server1 ✅
4. Query the prediction endpoint of Azure AI Anomaly Detector in Azure
5. From Server1, run the docker run command ✅
6. From Server1, run the docker pull command ✅

---

## Question 4: Deploy GPT-3.5 Model in Azure OpenAI Studio

**Correct Sequence:**

- [ ] 2-4-5
- [x] 4-2-5 ✅
- [ ] 5-4-2
- [ ] 4-3-5

**Steps:**

1. Create a deployment with text-embedding-ada-002
2. Apply Marketing Writing Assistant system message template ✅
3. Apply Default system message template
4. Create a deployment with GPT-3.5 Turbo ✅
5. Deploy the solution to a new web app ✅

---

## Question 5: Optimize Speech Output for Cars

**SSML Attribute Options:**

- [ ] style attribute of the mstts:express-as element
- [x] effect attribute of the voice element ✅
- [ ] pitch attribute of the prosody element
- [ ] level attribute of the emphasis element

---

## Question 6: Enable Speech Capabilities in Chatbot

**Options (Select 3):**

- [x] Enable WebSockets for the chatbot app ✅
- [x] Create a Speech service ✅
- [x] Register a Direct Line Speech channel ✅
- [ ] Register a Cortana channel
- [ ] Enable CORS for the chatbot app
- [ ] Create a Language Understanding service

---

## Question 7: Cognitive Search Autocompletion

**Options (Select 3):**

- [x] Make API queries to the autocomplete endpoint and include suggesterName ✅
- [x] Add a suggester that has the three product name fields as source fields ✅
- [ ] Make API queries to the search endpoint using searchFields
- [ ] Add a suggester for each of the three product name fields
- [ ] Set the searchAnalyzer property
- [x] Set the analyzer property for the three product name variants ✅

---

## Question 8: Custom Vision Project for Defects

**Project Type Options:**

- [ ] Food
- [ ] General
- [ ] General (compact)
- [ ] Image classification
- [ ] Logo
- [x] Object detection ✅

---

## Question 9: Files for Azure Document Intelligence (S0 Tier)

**Options:**

- [ ] File1.pdf only
- [ ] File2.jpg only
- [x] File3.tiff only ✅
- [ ] File2.jpg and File3.tiff only
- [ ] File1.pdf, File2.jpg, and File3.tiff

---

## Question 10: Categorize and Caption Images

**Options (Select 2):**

- [ ] Object detection in Azure AI Vision
- [x] Image descriptions in Azure AI Vision ✅
- [x] Image type detection in Azure AI Vision ✅
- [ ] Content tags in Azure AI Vision
- [ ] Image classification in Azure Custom Vision

---

## Question 11: Analyze Text for Hate (Dropdown 1)

**Options:**

- [ ] BlocklistMatch
- [x] CategoriesAnalysis ✅
- [ ] Equals

---

## Question 12: Read Hate Severity (Dropdown 2)

**Options:**

- [ ] BlocklistItemId ?? 0);
- [ ] BlocklistItemText ?? 0);
- [ ] Category ?? 0);
- [x] Severity ?? 0); ✅

---

## Question 13: Supported Files in Azure Content Understanding

**Options:**

- [ ] File1.pdf and File3.docx only
- [x] File1.pdf, File2.jpg, and File5.png only ✅
- [ ] File1.pdf, File2.jpg, and File3.docx only
- [ ] All files

---

## Question 14: Remove Entry from Blocklist (Dropdown 1)

**Options:**

- [ ] AddOrUpdateBlocklistItems
- [ ] CreateOrUpdateTextBlocklist
- [ ] DeleteTextBlocklist
- [x] RemoveBlocklistItems ✅

---

## Question 15: Parameter Class for Blocklist Deletion (Dropdown 2)

**Options:**

- [x] RemoveTextBlocklistItemsOptions ✅
- [ ] AddOrUpdateTextBlocklistItemsOptions
- [ ] BlocklistClient
- [ ] ContentSafetyClient

# AI-102 Exam Practice Questions

---

### Question 1

**You are building a chatbot. You need to use the Content Moderator API to identify aggressive and sexually explicit language.
Which three settings should you configure?**

- [ ] autocorrect
- [ ] PII
- [ ] listId
- [x] Resource Name ✅
- [x] classify ✅
- [ ] language
- [ ] Content-Type
- [x] Ocp-Apim-Subscription-Key ✅

---

### Question 2

**You plan to deploy an Azure OpenAI resource using an ARM template to handle 600 requests/minute.
Which value should you choose for Placeholder 2?**

- [ ] 1
- [ ] 60
- [x] 100 ✅
- [ ] 600

---

### Question 3

**You are building an app to share user images. Which service should you use for profane language detection?**

- [ ] Azure AI Language
- [ ] Azure AI Vision
- [x] Azure AI Content Safety ✅
- [ ] Azure AI Custom Vision
- [ ] Azure AI Document Intelligence

---

### Question 4

**You want to extract text from one million scanned magazine articles stored as images. What should you use?**

- [ ] Azure AI Document Intelligence
- [ ] Azure AI Language
- [ ] Azure AI Vision Image Analysis
- [x] the Read API in Azure AI Vision ✅

---

### Question 5

**You are translating speech from French to German with the Speech SDK. What should you use for Placeholder 2?**

- [x] AddTargetLanguage ✅
- [ ] SpeechRecognitionLanguage
- [ ] SpeechSynthesisLanguage
- [ ] TargetLanguages
- [ ] VoiceName

---

### Question 6

**You are building a containerized app to scan confidential documents with the Language service. What actions do you perform in sequence?**

**Available actions:**

1. Run container with App ID and Secret
2. Provision isolated on-prem Kubernetes cluster
3. Pull image from Microsoft Container Registry
4. Run container with API key and endpoint
5. Provision on-prem cluster with internet
6. Pull from Docker Hub
7. Provision AKS

**Correct Sequence:** 2 → 3 → 4 ✅

---

### Question 7

**You want to run a custom speech-to-text model on a Docker host. What steps do you perform in order?**

**Available actions:**

1. Retrain the model
2. Request approval
3. Export model to Host1
4. Run container
5. Configure disk logging

**Correct Sequence:** 2 → 3 → 4 ✅

---

### Question 8

**You need to enable active learning in a QnA Maker app. What actions do you perform in sequence?**

**Available actions:**

1. Add a task to the Azure resource
2. Approve and reject suggestions
3. Publish the knowledge base
4. Modify automation task logic
5. Show active learning suggestions
6. Save and train the knowledge base
7. Select Azure Cognitive Services properties

**Correct Sequence:** 5 → 2 → 6 → 3 ✅

---

### Question 9

**You are translating HTML content into Greek with transliteration to Latin. Which parameters do you include?**

- [x] textType=html ✅
- [x] to=el ✅
- [ ] from=el
- [ ] textType=plain
- [x] toScript=Latn ✅
- [ ] toScript=Cyrl

---

### Question 10

**You need a PPE compliance monitoring solution for a food factory. What service should you use?**

- [ ] Face
- [x] Azure AI Vision ✅
- [ ] Azure Video Analyzer for Media (formerly Video Indexer)

---

### Question 11

**You want to upload local video files to Azure Video Indexer. Which files are allowed?**

| File  | Format | Length (mins) | Size (MB) |
| ----- | ------ | ------------- | --------- |
| File1 | WMV    | 34            | 400       |
| File2 | AVI    | 90            | 1,200     |
| File3 | MOV    | 300           | 980       |
| File4 | MP4    | 80            | 1,800     |

- [x] File1, File2, File3 and File4 ✅
- [ ] File1 and File3 only
- [ ] File1, File2, and File3 only
- [ ] File1, File2, and File4 only

---

### Question 12

**You want to import Q&A pairs into Azure AI Language. Which two formats can you use?**

- [ ] JSON
- [x] TSV ✅
- [x] Excel ✅
- [ ] LU
- [ ] CSV

---

### Question 13

**You want to index a 20-GB video on a local drive using Azure AI Video Indexer. What should you do first?**

- [x] Upload File1.avi to Microsoft OneDrive ✅
- [ ] Upload File1.avi to www.youtube.com
- [ ] Upload File1.avi to an Azure Storage queue
- [ ] Upload File1.avi to the Azure AI Video Indexer website

---

### Question 14

**You want to use Azure AI Content Safety to detect violence in blob-stored images. What endpoint should you use?**

- [ ] /contentmoderator
- [x] /contentsafety ✅
- [ ] /vision

---

### Question 15

**You want to analyze an image using Azure OpenAI Studio to generate a text description. What sequence should you follow?**

**Available actions:**

1. Create text-embedding deployment
2. Enter prompt + upload image
3. Create DALL-E deployment
4. Add system message
5. Open Chat playground
6. Open Completions playground
7. Create GPT-4 deployment with `vision-preview`

**Correct Sequence:** 7 → 5 → 4 → 2 ✅

---

### Question 16

**You need to provide consistent Q&A from PDF documents with minimal effort. What should you use?**

- [ ] Azure AI Document Intelligence
- [x] Azure AI Language ✅
- [ ] Azure Machine Learning
- [ ] Azure OpenAI

### Screenshot 2025-06-04 at 19.37.40

**Question:**

MES ITT Se You are building an Azure web app named App! that will translate text from English to Spanish. You need to use the Text Translation REST API to perform the translation. The solution must ensure that you have data sovereignty in the United States. You need to complete the following URI. https: // Placeholder 1 i Placeholder 2 ?api-version=3 .@&to=es Which value should you choose for Placeholder 1?

**Options:**

- api.cognitive.microsofttranslator.com
- nam.cognitive.microsofttranslator.com
- Your answer is incorrect ✅
- a
- nam.cognitiveservices.azure.com
- . eastus.api
- ognitive.microsoft.com

**Explanation:**

Overall explanation api-nam.cognitive.microsofttranslator.com is CORRECT because it ensures that the data and operations are handled within the North America region, adhering to data sovereignty requirements for the United States. Seven endpoint aquest processing data center, Global (recommended) Closest available data center api.copnitive.nicrosofttranslator.com Americas: East US 2 + West US 2 ‘pi-nan.cognitive.nicrosofttrans Asia Pacific: Japan East + Southeast Asia ‘api-ape.cognitive.alcrosofttranslater.com Europe (except Switzerland): France Central « West Europe ‘api-eur.cognitive.nicrosofttranslator.com Switzeriand: ‘Switzerland North Switzerland West For more information see Switzerland service endpoints api.cognitive.microsofttranslator.com is INCORRECT because it does not specify a particular region and may not ensure data sovereignty within the United States. api-nam.cognitiveservices.azure.com is INCORRECT because it is not the correct endpoint for the Text Translation REST API. eastus.api.cognitive.microsoft.com is INCORRECT because while it specifies the East US region, it is not the correct endpoint for the Text Translation REST API. Read More: https://learn.microsoft.com/en-us/azure/cognitive-services/Translator/reference/v3-0- reference#base-urls Domain Implement natural language processing solutions

---

### Screenshot 2025-06-04 at 19.39.04

**Question:**

You develop a Conversational Language Understanding model by using Language Studio. During testing, users receive incorrect responses to requests that do NOT relate to the capabilities of the model. You need to ensure that the model identifies spurious requests. What should you do?

**Options:**

- Enable active learning.
- . Add entities.
- Add examples to the None intent.
- . Add examples to the custom intents.

**Explanation:**

Overall explanation Add examples to the None intent is CORRECT because the None intent is used to handle spurious or irrelevant requests that do not relate to the capabilities of the model. By adding examples of irrelevant requests to the None intent, you train the model to recognize and correctly categorize these types of queries, thereby improving the model's ability to identify spurious requests. Adding examples to the None intent The None intent is also treated like any other intent in your project. If there are utterances that you want predicted as None, consider adding similar examples to them in your training data. For example, if you would like to categorize utterances that are not important to your project as None, such as greetings, yes and no answers, responses to questions such as providing a number, then add those utterances to your intent. You should also consider adding false positive examples to the None intent. For example, in a flight booking project it is likely that the utterance "I want to buy a book" could be confused with a Book Flight intent. Adding "I want to buy a book" or "| love reading books" as None training utterances helps Be alter the predictions of those types of utterances towards the None intent

---

### Screenshot 2025-06-04 at 19.46.26

**Question:**

You have an Azure subscription that contains a Language service resource named tal and a virtual network named vnett. You need to ensure that only resources in vnett can access tal. What should you configure?

**Options:**

- . anetwork security group (NSG) for vnet1
- Your answer is incorrect ✅
- Azure Firewall for vnet1
- \_ the virtual network settings for tal
- . aLanguage service container for ta1

**Explanation:**

Overall explanation the virtual network settings for ta1 is CORRECT because configuring the virtual network settings for the Language service resource ta1 will ensure that it can only be accessed by resources within vnett. This setup restricts access to the service based on the virtual network, providing a secure way to limit access. anetwork security group (NSG) for vnet1 is INCORRECT because while an NSG can control inbound and outbound traffic at the network interface level, it is not used directly to restrict access to Azure resources like the Language service. NSGs are used to filter network traffic but don't inherently control resource-specific access. Azure Firewall for vnet1 is INCORRECT because although Azure Firewall can provide centralized network security, it is more complex and might be unnecessary for just limiting access to a single Language service resource. It's used for broader network security purposes. a Language service container for ta1 is INCORRECT because containers are used for deploying instances of services but do not configure network access restrictions by themselves.

---

### Screenshot 2025-06-04 at 19.49.07

**Question:**

You need to develop an automated call handling system that can respond to callers in their own language. The system will support only French and English. Which Azure Cognitive Services service should you for the following requirement? "Detect the incoming language." Your answer is incorrect

**Options:**

- Speaker Recognition
- \_ Speech to Text
- . Text Analytics
- . Text to Speech
- . Translator

**Explanation:**

Overall explanation Speech to Text is CORRECT because it includes the capability to detect the language of the spoken content using the AutoDetectSourceLanguageConfig configuration. This is suitable for identifying whether the incoming language is French or English, which is essential for routing the call to the appropriate language handling system. Text Analytics is INCORRECT because it processes text data, not audio data. In this scenario, the input is callers' voice, so Text Analytics is not applicable. Speaker Recognition is INCORRECT because it is used to recognize and authenticate speakers based on their voice, not to detect the language of the spoken content. Text to Speech is INCORRECT because it converts text into spoken language but does not detect the language of the input text.

---

### Screenshot 2025-06-04 at 19.51.36

**Question:**

You are using a Language Understanding service to handle natural language input from the users of a web- based customer agent. The users report that the agent frequently responds with the following generic response: "Sorry, | don't understand that" You need to improve the ability of the agent to respond to requests. Which three actions should you perform in sequence? ACTIONS 1. Add prebuilt domain models as required. 2. Validate the utterances logged for review and modify the model. 3. Migrate authoring to an Azure resource authoring key. 4. Enable active learning. 5. Enable log collection by using Log Analytics. 6. Train and republish the Language Understanding model.

**Options:**

- 5-2-6
- 4-2-6
- Your answer is incorrect ✅
- 2-4-6
- 1-2-6

**Explanation:**

Overall explanation 4-2-6 is the CORRECT actions in sequence. (Action 4) Enable active learning is CORRECT. This step allows the Language Understanding service to collect and suggest new utterances that are not well understood. Active learning helps identify gaps in the model. (Action 2) Validate the utterances logged for review and modify the model is CORRECT. Review the utterances that the system flagged as not well understood and use these to improve the model. Modify the intents and entities to better capture the user's queries.

---

### Screenshot 2025-06-04 at 19.53.59

**Question:**

You need to implement a table projection to generate a physical expression of an Azure Al Search index. Which three properties should you specify in the skillset definition JSON configuration table node? tableName

**Options:**

- generatedKeyName
- Your selection is incorrect ✅
- & dataSource
- Your selection is incorrect ✅
- & dataSourceConnection
- 1 source

**Explanation:**

Overall explanation tableName is CORRECT because it specifies the name of the table in the knowledge store where the projected data will be stored. generatedKeyName is CORRECT because it specifies the name of the key that uniquely identifies, each row in the table. source is CORRECT because it specifies the source fields from the enriched documents that are used to populate the table. Define a table projection Table projections are recommended for scenarios that call for data exploration, such as analysis with Power BI or workloads that consume data frames. The tables section of a projections array is a list of tables that you want to project. To define a table projection, use the tables array in the projections property. A table projection has three required properties: Expand table Property Description tableName Determines the name of a new table created in Azure Table Storage. generatedKeyName Column name for the key that uniquely identifies each row. The value is system-generated. If you omit this property, a column will be created automatically that uses the table name and "key" as the naming convention. source A path to a node in an enrichment tree. The node should be a

---

### Screenshot 2025-06-04 at 22.41.41

**Question:**

You are building an app that will use Azure Al Language to extract meaning from text messages. You need to provide additional context by adding references to supporting articles in Wikipedia. What should you use?

**Options:**

- entity linking
- Your answer is incorrect ✅
- custom entity extraction recognition (NER)
- Azure Al Content Safety
- ) key phrase extraction

**Explanation:**

Overall explanation entity linking is CORRECT because it identifies and disambiguates entities in text by mapping them to their corresponding entries in external knowledge bases like Wikipedia. This allows the app to provide contextually relevant references to supporting articles, enhancing the understanding of extracted entities. custom entity extraction recognition (NER) is INCORRECT because it identifies custom entities based on predefined patterns or training but does not link those entities to external knowledge bases like Wikipedia. Azure Al Content Safety is INCORRECT because it focuses on detecting and filtering harmful or inappropriate content and does not provide capabilities for linking text entities to external references. key phrase extraction is INCORRECT because it identifies important phrases from text but does not link those phrases to knowledge bases like Wikipedia. Read More:

---

### Screenshot 2025-06-04 at 22.41.46

**Question:**

You are building an app that will use the Azure Al Speech service. You need to ensure that the app can authenticate to the service by using a Microsoft Entra ID token. Which two actions should you perform? ‘Your selection is incorrect & Enable a virtual network service endpoint. itional Access policy.

**Options:**

- Create a private endpoint.
- (Request an X.509 certificate.
- C1 Configure a custom subdomain.
- Il explanation

**Explanation:**

Create a private endpoint is CORRECT because it allows secure communication between your Azure Al Speech service and your virtual network using a private IP address. This ensures that traffic remains private and controlled while supporting Microsoft Entra ID authentication. Configure a custom subdomain is CORRECT because Azure Al services, including Speech, often require a custom subdomain for Entra ID authentication. This enables token-based authentication to the Speech service via the subdomain. Enable a virtual network service endpoint is INCORRECT because service endpoints are primarily used for secure access to Azure services via virtual networks but do not directly support Entra ID authentication tokens. Create a Conditional Access policy is INCORRECT because Conditional Access policies are used to enforce access controls and not for directly enabling authentication to the Speech service via Entra ID. Request an X.509 certificate is INCORRECT because Azure Al Speech authentication with Entra ID relies on token-based authentication, not certificate-based authentication. Read More: https://learn.microsoft.com/en-us/azure/ai-services/speech-service/overview https://learn.microsoft.com/en-us/azure/ai-services/speech-service/role-based-access- control#authentication-with-keys-and-tokens

---

### Screenshot 2025-06-04 at 22.41.51

**Question:**

You are building a call handling system that will perform the following action: ¢ Convert voicemails from French to English. Which Azure Al Speech SDK class should you use for the above action?

**Options:**

- SpeechSynthesizer
- . TextTranslationClient
- . TranslationRecognitionResult
- TranslationRecognizer

**Explanation:**

Overall explanation TranslationRecognizer is CORRECT because it is specifically designed to perform real-time speech-to-text translation. It can process spoken content in one language (e.g., French) and output the recognized text in another language (e.g., English). This makes it ideal for converting voicemails from French to English in a call-handling system. SpeechSynthesizer is INCORRECT because it is used for text-to-speech conversion, not for recognizing and translating spoken content from one language to another. TextTranslationClient is INCORRECT because it is used for translating text from one language to another, not for handling audio-based speech recognition and translation tasks. Beta Share fe

---

### Screenshot 2025-06-04 at 22.51.52

**Question:**

You are building an app that will translate input from English to French and Simplified Chinese by using the Microsoft Translator service. You need to verify that when profane words are identified, they are marked in the following XML format: <profanity></profanity>. You need to complete the below cURL statement. curl -X POST \*https://api cognitive.microsofttranslator.com/translate?api-version=3.0&fro1 n&to=fr&eto=zh-Hans profanity Action= Dropdown 1%) &profanityMarker= Dropdown 2 -H "Ocp-Apim-Subscription-Key: <client-seeret>” -H "Content-Type: application/json; charset TF -d"[{(Text!’This is an <insert-profane-word> good i What should you choose for Dropdown 1?

**Options:**

- Asterisk
- Deleted
- Marked
- NoAction
- Tag

**Explanation:**

Overall explanation Marked is CORRECT. When profanityAction=Marked is set, the system processes the text to identify profanity and allows it to be further marked using a value from profanityMarker, such as Asterisk or Tag. This is required to trigger profanity tagging behavior. Accepted ProfanityMarker Action Example: Source Example: Target - English ProfanityAction value = Spanish value NoAetion Default. Same as not setting the Que coche de What a <insert-profane- ‘option. Profanity passes from <insert-profane-_word> car source to target. word> Marked Asterisk Asterisks replace profane words Que cache de = What a\*\*\* car (defautt). <insert-profane- word> Marked Tag Profane words are surrounded by Que coche de What a <profanity> XML tags <profanity> <insert-profane-_<insert-profane-word> </profanity> word> </profanity> car Deleted Profane words are removed from Que coche de © What acar the output without replacement. \_<insert-profane- word> Asterisk is INCORRECT because it is not a valid accepted value for Dropdown 4 (profanityAction). Deleted is INCORRECT because it removes the profane words entirely from the output. na marldine ar mackina

---

### Screenshot 2025-06-04 at 22.52.58

**Question:**

You are building an app that will translate input from English to French and Simplified Chinese by using the Microsoft Translator service. You need to verify that when profane words are identified, they are marked in the following XML format: <profanity></profanity>. You need to complete the below cURL statement. curl -X POST “hit pi.cognitive.microsofitranslator.comvtr pi-version=3.08from=endeto=fr&to=zh-Hans profanity Action= Dropdown | ¥ | &profanityMarker Dropdown2 -H "Ocp-Apim-Subscription-Key: <client-secret>” -H "Conte ‘ype: application/json; charset= UTE-8" -d"[{(Text!’This is an <insert-profane-word> good idea.’}]” What should you choose for Dropdown 2?

**Options:**

- Asterisk"
- Deleted"
- Marke
- Tag"

**Explanation:**

Overall explanation Tag" is CORRECT. When used with profanityAction=Marked, setting profanityMarker=Tag ensures that any profane words in the translated output are surrounded by <profanity>...</profanity> XML tags, as required in the question. Accepted ProfanityMarker Action Example: Source Example: Target - English ProfanityAction value + Spanish value NoAction Default. Same as not setting the Que eoche de What a <insert-profane- option, Profanity passes from <insert-profane-_ word> car source to target word> Marked Asterisk Asterisks replace profane words Que cache de Whata“\*\* car (default). <insert-profane- word> Marked tag Profane words are surrounded by Que coche de What a <profanity> XML tage <profanity>. <insertprofane-_<inser-profane-word> </profanity> word> </profanity> car Deleted Profane words are removed from Que coche de What acar the output without replacement. <insert-profane- word> Asterisk" is INCORRECT because although it is a valid profanityMarker value, it replaces profane words with \*\*\*, not XML tags, which does not meet the requirement. Deleted’, Marked" and NoAction" profanityMarker; these are valid values only for profanityAction. re INCORRECT because these are not valid values for

---

### Screenshot 2025-06-04 at 22.53.34

**Question:**

You plan to build an agent that will combine and process multiple files uploaded by users. You are evaluating whether to use the Azure Al Agent Service to develop the agent. What is the maximum size of all the files that can be uploaded to the service?

**Options:**

- 16B
- Your answer is incorrect ✅
- 10GB
- 100GB
- 118
- 20068

**Explanation:**

Overall explanation 200 GB is CORRECT because the Azure Al Agent Service currently supports a maximum combined file upload size of 200 GB per agent session. This includes all files uploaded by users for use in grounding, context augmentation, or processing during interactions with the agent. Limit Name Limit Value Max files per agent/thread 10,000 Max file size for agents & fine-tuning 512 MB Max size forall uploaded files for agents 20068 agents token limit 2,000,000 token limit, NOTE: The max size for all uploaded files was 100GB earlier. If in the exam, 200GB is not an available option, please choose 100GB instead. Read More: https://learn.microsoft.com/en-us/azure/ai-services/agents/quotas-limits Domain Implement an agentic solution
