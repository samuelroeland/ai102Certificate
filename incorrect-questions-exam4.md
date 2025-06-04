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
