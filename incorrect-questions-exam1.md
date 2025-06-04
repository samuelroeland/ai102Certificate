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
