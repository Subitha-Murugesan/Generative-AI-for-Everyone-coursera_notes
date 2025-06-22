# Generative-AI-for-Everyone-coursera_notes
Generative AI for Everyone coursera course notes and learnings
# Generative AI for Everyone

## Week 1:  
### What is Generative AI:
---------------------------------------------------------------------------------------------------------------

**Welcome Video:**  
The rise of GenAI: from 2022 November to 2023-December is tremendous  

Generative AI could:  
- Add $2.6 - $4.4 Trillion annually to the economy  
- Raise global GDP by 7% in next 10 years  
- Impact 10% of the tasks carried daily by 80% of the workers  

And there are some fears as well like job loss through automation.  

**Generative AI** - AI system that can produce high quality content, specifically text, image, and audio  
GenAI application examples: chatgpt, gemini, Bard, Bing chat - It generates response based on the user prompt.  

And Generative AI as a developer tool like lang chain compatibility and API support.  

AI is already pervasive in our lives: like web search AI, Fraud detection, Recommender systems  

Generative AI can build other AI tools easily  

**Image, Audio and Video Generation:**  
Prompt -> image generation  
Prompt -> Audio generation  
Prompt -> Video + Audio generation  

### What you’ll learn:
- How Gen AI tech works  
    - What it can and can’t do  
    - Common use cases  
- Generative AI projects  
    - Identify and build GenAI user cases  
    - Technology options  
- Impact on Business and society  
    - How teams can take advantage of Gen AI  
    - AI risks and responsible AI  

----------------------------------------------------------------------------------------------------------------------

### How Generative AI Works
![et of tools](https://github.com/user-attachments/assets/800538d9-f78a-494e-ac9d-572cc351906f)

**Supervised Learning (labelling things)**  
Input A ——> Input B | Application  
![Supervised learning (labeling things)](https://github.com/user-attachments/assets/d5e1f0fb-7d8e-4a61-b404-c96aed318144)

Performance is better when we train the large AI models than small AI models  

**Generating Text using LLMs**  
Text generation process:  

`I love eating` — prompt  
LLM generates - idli, meat  
![How Large Language Models (LMs) work](https://github.com/user-attachments/assets/a0bfffd1-22e5-4c17-a824-ac3c2d669795)

----------------------------------------------------------------------------------------------------------------------

### LLMs as a Thought Partner:

LLM is giving a new way to find information.  
Sometimes hallucinations  

1. As a writing partner  
Web search or using an LLM?  
- For medical matters use web search and check trustworthy sources.  
- Bake a pineapple pie - many websites - in that case use LLM to get precise answers  
- Coffee-infused pineapple pie - it is challenging one so no website will be there, here we can use LLM.  

----------------------------------------------------------------------------------------------------------------------

### AI is a General Purpose Technology  

Similar to electricity AI is useful for many tasks - general purpose tech  

Examples of tasks LLMs can carry out:  
1. Writing - brainstorming partner, can ask questions  
2. Reading - summary of long para, checking the classification like yes or no  
3. Chatting - general purpose chatbot, special purpose chatbot also like taking online pizza order  

**Software-based LLMs and Web-based LLMs**  
- Web based Interface Application EG: ChatGPT, Bard and Bing chat  
- Software based applications eg: email routing, document search  

----------------------------------------------------------------------------------------------------------------------


### GEN AI APPLICATIONS:  
**Writing:**  

Short prompts to generate large texts  
Examples:  
1. Brainstorming product names - cookie brand name  
2. Brainstorming to develop the sales strategy - increasing cookie sales in Q4  
3. Writing a press release - press release announcing the hire of a new COO  
    - Using the improved prompt we get a detailed and precise info about the COO joining  
4. Translation  

----------------------------------------------------------------------------------------------------------------------


**Reading:**  

Large para to summary  
1. Proofreading - check out the mistakes and fix it  
2. Summarising an article  
3. Summarising call center conversations  
    - Call —> transcript —> LLM (summarise the conversations) or tabular column about the crisp info  
4. Customer email analysis  
    - Prompt -> Indicate which dept to route the following email —> Department: complaints  
    - Detailed look at email routing prompt  
5. Reputation Monitoring - Dashboard to track customer sentiment over time  

----------------------------------------------------------------------------------------------------------------------

**Chatting:**  

Special purpose chatbot - many companies looking to develop that  

- Customer service chatbot - general purpose  
- Trip Planner chatbot - Specialized chatbots  
- Career coach, Recipe Ideas  
- IT service Chatbot - reduce manual efforts  

The rise of chatbots in customer service  
Focus on text-based chatbots  

![reley choosoburgor for](https://github.com/user-attachments/assets/71984dd9-692a-4d86-ae6e-fbf43ec4e57f)


**Advice for Deploying Chatbot:**  
1. Start with an internal facing chatbot  
    - Work with staff to assess behaviour of chatbot  
    - Avoid public mistakes  
2. Deploy with human in the loop to check for mistakes  
3. Only after the deemed safe allow bot to communicate directly with customers  

----------------------------------------------------------------------------------------------------------------------


### What LLMs Can and Cannot Do:

**Specific Limitations:**  

**What prompting an LLM can do:**  
Fresh college graduate thumb rule - Imperfect thumb rule  
If a fresh college grad can do LLM can do and vice versa  
![What prompting an LLM can do](https://github.com/user-attachments/assets/23c5ebf8-4f24-41ff-9a83-805cdc8b4598)


**Limitations:**  
- Knowledge cut-off: if the LLM knowledge is only there till some year e.g. 2022, when we ask a question about 2025 - it will not answer.  
- Making things up: Hallucinations:  
    - Example: Give me three quotes the Shakespeare about singer Beyonce.  
    - Hallucinations have had serious consequences.  
- The input and output length is limited:  
    - LLM can accept a prompt up to certain limit  
    - Some LLM have longer context limits - up to 100,000 words  
    - LLM context length = limit on total input + output  
- Not currently work with structured tabular data (now working)  
    - Gen AI works best with unstructured data  
- Bias and Toxicity outputs:  
    - Gender bias  
    - Harmful speech  

----------------------------------------------------------------------------------------------------------------------

### Tips for Prompting:

1. Be detailed and specific  
    - Give sufficient context for LLM to complete the task  
    - Describe the desired task in detail  
2. Guide the model to think through its answer  
    - Step-by-step instructions  
3. Experiment and iterate  
    - Iteratively improving your prompt  

**Prompting process:**  
1. Be clear and specific in prompt  
2. Think about why result is giving desired output  
3. Refine your prompt  
4. Repeat  

----------------------------------------------------------------------------------------------------------------------


### Image Generation:

Today image generation can be done using diffusion model.  
Heart of diffusion model is supervised learning  
![Image generation (diffusion model)](https://github.com/user-attachments/assets/a6b05dfb-5966-4abf-b4ec-f80036115975)
![Image generation](https://github.com/user-attachments/assets/da21f751-ff52-4818-a9be-54c9b0334f8d)


Using text prompt:  
![Adding text](https://github.com/user-attachments/assets/cc7ceff2-4f25-4c85-bbfa-1256ce303964)

**Image generation from Text**

![Image generation from text](https://github.com/user-attachments/assets/08ce8e71-d1dd-4dd3-85e5-591fd37f358a)

----------------------------------------------------------------------------------------------------------------------


## Week 2:

### Software Application  
Using Generative AI in software applications  

**Examples of Software Applications:**  
1. Writing, reading and chatbot  
    - Reading:  
        - Old method for restaurant review classification
          ![Supervised learning for restaurant reputation](https://github.com/user-attachments/assets/1b50ecfa-7b6b-4e73-bca8-c82439b7da44)
 
        - New method using prompt
          ![Prompt-based development](https://github.com/user-attachments/assets/a573375f-ab6c-481b-b36a-a9206121731e)


**Workflow using Gen AI:**  
![Workflow using Generative Al](https://github.com/user-attachments/assets/9529ca25-8140-4b88-bebd-4374fc9bba96)

----------------------------------------------------------------------------------------------------------------------

### Lifecycle of a GEN AI Project:
![Lifecycle of a generative Al project](https://github.com/user-attachments/assets/6fc87700-b9ef-47c1-a7f6-df654a36b63e)
![Lifecycle of a generative Al project](https://github.com/user-attachments/assets/352a9544-9189-40da-a8f1-1254e37d81cc)

One more example: Food ordering system  

**Tools to improve performance:**  
Building Gen AI is experimental process - we repeatedly find and fix mistakes  
1. Prompting - idea -> prompt -> LLM response -> idea loop  
2. RAG  
    - Give LLM access to external data sources  
3. Fine tune models  
    - Adapt LLM for a task  
4. Pre-train models  
    - Train LLM from scratch  

---

### Cost Intuition:
![How much does it cost](https://github.com/user-attachments/assets/a15df137-75a2-45ca-a89c-61fbb0232af8)


**What is a token?**  
Examples:  
- The = 1 token  
- Andrew = 1 token  
- Translate = 2 tokens  
- Programming = program + ing = 2 tokens  

Roughly 1 token = 3/4 words  
33% more than the count of words  
300 words = 400 tokens  

**Estimating cost**
![Estimating Cost](https://github.com/user-attachments/assets/41c786d9-5685-49b4-b4b3-55976f12ebae)

---

### Advanced Technology Beyond Prompting:

**RAG (Retrieval Augmented Generation):**  
![Retrieval Augmented Generation (RAG) example](https://github.com/user-attachments/assets/6ca19e92-068e-4eeb-857f-c88ce7d49a4e)
![Retrieval Augmented Generation (RAG) example](https://github.com/user-attachments/assets/c3b9eacc-c7f3-4185-b92a-ac08aeac5ff1)
![promptin andro on hone](https://github.com/user-attachments/assets/fc6c58a5-3d9a-4e6f-ae70-1a0447a3cf18)



Examples of RAG:  
- Chat with PDF files
  ![Examples of RAG applications](https://github.com/user-attachments/assets/0c103c55-5d46-4063-bf1d-2558d65e2b42)
  ![Examples of RAG applications](https://github.com/user-attachments/assets/e2edd60a-72aa-43f1-b6da-16df86675d8c)


- New form of web search - Bing, Google Search  

**Big Idea: LLM as reasoning engine**  
1. LLMs have a lot of general knowledge but they don’t know everything  
2. By providing relevant context in the prompt, we ask LLM to read a piece of text then process it to get an answer  
3. We are using it as a reasoning engine to process information rather than using it as a source of information - LLM isn’t a database  

---

### Fine Tuning:

If LLM has reached the token limit we can achieve the task by doing the fine tuning  
Implementation of Fine tuning is difficult compared to the RAG  
![Pretraining and Fine-tuning](https://github.com/user-attachments/assets/b28c53bb-be56-4a8a-b48f-e3a2d0d75eb5)

**Pretraining:** LLM learns with 100B of data to predict the response  
**Fine tuning:** Take the pretrained LLM and train with set of particular 1000 to 10000 words dataset along with the pretrained dataset, create a new dataset and train the LLM  

Examples:  
- Shift LLM response to positive optimistic attitude  
- Fine-tune model that mimics how Andrew speaks  
- Help LLM understand medical notes, legal documents, financial documents  
- Get a smaller model to perform tasks previously done by larger models  

Pretraining is expensive, only large techs are trying out  

**Instead of training from scratch, use open source models**

---

### Choosing a Model:

Many LLMs are out there  

When choosing a model there are few guidelines:  
1. Model Size  
2. Closed or Open Source  

---

### How LLMs Follow Instructions:

**Instruction Tuning and RLHF:**  

How do chat systems learn to follow instructions?  
- By pretraining the LLM to predict the next word with the help of user prompt  

**Instruction Tuning:**  
- Fine-tune a dataset of prompts with good answers and bad answers  
- LLM not only predicts the next word, it can follow the user instructions  

**Reinforcement Learning from Human Feedback (RLHF):**  
- HHH (Helpful, Honest, Harmless)  
- Response and score dataset u
