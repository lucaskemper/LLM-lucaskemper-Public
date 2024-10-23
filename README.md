## Code is currently private for security reasons
# LLM Framework (Customized Fork)
**By Lucas Kemper, HEC Lausanne MSc Finance Student**

I'm developping  (started 20.10.2024) a customized version of **Lobe Chat**, an open-source ChatGPT/LLMs UI/Framework, by leveraging various open-source projects from GitHub and tailoring them to meet my specific needs. Using **Lobe Chat** as a foundation, I integrated several features that enhanced the overall functionality and user experience for my personal project.

## Key Features of the Customized Version

### 1. File Upload & Knowledge Base (need to fix upload of file, error: stuck on "preparing to upload file"
I utilized existing features from the Lobe Chat repository to enable file uploads and create a personalized knowledge base. This allows me to manage and search through various types of files, adapting the functionality for my specific use case.

### 2. Multi-Model Service Provider Support
I configured the framework to support multiple model service providers, such as **OpenAI** and **Anthropic's Claude**, enabling more flexibility and diversity in AI-driven conversations.

### 3. Local Large Language Model (LLLM) Support
I took advantage of the local LLM capabilities provided by the original project and modified the integration to work more efficiently for my specific needs. 

### 4. Optimizations
I implemented several optimizations to enhance the performance, security, and scalability of the framework:
- **Vercel**: Used **Vercel** for fast front-end hosting and seamless deployment workflows.
- **Cloudflare**: Added **Cloudflare** for enhanced DNS management and security features like DDoS protection and CDN.
- **MongoDB**: Integrated **MongoDB** for managing data storage and retrieval efficiently across the system. ---- Switch to AWS?????
- **Clerk**: Used **Clerk** for secure user authentication and login via GitHub or Google.
- Better integration for Ios (using Webkit)
 

### 5. Issues
1. Can't Upload files (Error: please check your network connection and ensure that the file storage service's cross-origin configuration is correct)
2. High API usage (OpenAI), not important at this point


### 6. RoadMap (in order of priority):
1. Implement pdf generator / python code runtime into UI.
2. Implement OpenBB Integration
3. Tailor the models to my needs (Financial Analysis, among other needs)
4. Create / Implement local LLM 
5. Reduce Cost

   

Through these modifications, I created a customized, private chatbot tailored to my unique requirements, while still benefiting from the robustness of the original open-source tools.




## Contact
Feel free to connect with me on LinkedIn: [Lucas Kemper](https://www.linkedin.com/in/lucas-kemper)
