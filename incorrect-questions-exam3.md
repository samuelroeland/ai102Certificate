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
