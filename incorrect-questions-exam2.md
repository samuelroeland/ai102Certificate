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
