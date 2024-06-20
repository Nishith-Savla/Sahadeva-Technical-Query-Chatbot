# Sahadeva Technical Query Bot

## Overview
Sahadeva is a sophisticated virtual assistant designed to handle user technical queries via text input. This chatbot leverages Langchain & GPT-3.5 to provide accurate and efficient responses by extracting information from the company's PDF documents, YouTube videos, and images. The aim is to resolve customer queries quickly and effectively, enhancing user experience and reducing support costs.

## Business Problem
When customers cannot resolve their technical queries through calls or websites, businesses face several significant issues, including:
- Increased customer dissatisfaction
- Competitive disadvantage and reduced efficiency
- Lost revenue
- Higher support costs
- Negative word-of-mouth
- Overloaded support teams
- Missed opportunities for data collection
- Compliance and legal risks

## Existing Solutions
Traditional solutions like call centers, FAQ sections, and email/social media support have limitations:
- **Call Centers:** Often slow and unhelpful
- **FAQ Sections:** Limited to general knowledge about the product or service
- **Email/Social Media Support:** Unreliable and unpredictable

## Our Solution
Sahadeva addresses these issues by offering a more robust and efficient approach to handling technical queries:
- **Advanced Query Handling:** Utilizes Langchain & GPT-3.5 for understanding and generating human-like text
- **Multimedia Support:** Extracts information from PDFs, YouTube videos, and images

### Admin Workflow
1. **Admin Uploads Documents:** Admin can upload company documents in PDF, URL, or image format.
2. **Data Processing:** Documents are split into data chunks and stored in a vector database.

### User Workflow
1. **User Inputs a Query:** Users input their technical queries.
2. **Query Handling:** The system uses a QA chain and vector similarity search to find relevant information.
3. **AI Model Response:** The AI model generates a response based on the search results.

## Tech Stack
- **Foundation Model:** GPT-3.5
- **Data Processing:** Splitting data chunks, embedding them into a vector database
- **Infrastructure:** OCR Space for text recognition, ChromaDB for embedding storage

## Benefits and Value Proposition

### Tangible Benefits
- **Instant Response:** Provides quick answers to user queries.
- **Scalability:** Can handle a large number of queries simultaneously.
- **Data Accuracy:** Ensures accurate information retrieval.
- **Cost Savings:** Reduces support costs by automating query handling.

### Intangible Benefits
- **Enhanced User Experience:** Improves overall customer satisfaction.
- **Negligible Human Error:** Minimizes errors in responses.
- **Empowering Self-Sufficiency:** Enables users to resolve their own queries.

## Future Scope
- **Video Input:** Adding support for video (mp4) input.
- **Feature Extraction from Images:** Enhancing the capability to extract and process information from images.
- **Multimedia Output:** Providing responses in various multimedia formats.
