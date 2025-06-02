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
