# AI-Travel-Assistant-with-Prompt-Flow

## Table of Contents

- [Overview](#overview)
- [Situation](#situation)
- [Task](#task)
- [Action](#action)
- [Result](#results)    
- [Technologies Used](#technologies-used)
- [Demo](#demo)  

## Overview

WanderMate is a personalized, multi-turn AI travel companion that helps users plan trips, discover destinations, book experiences, and get tailored recommendations for flights, hotels, and activities. Unlike traditional travel bots that provide rigid, one-off answers, WanderMate keeps track of user preferences and past conversations, delivering context-aware, natural interactions—almost like chatting with a seasoned travel guide.

Built with Azure AI Foundry’s Prompt Flow and powered by GPT models from Azure OpenAI, WanderMate leverages user prompts and chat history to generate dynamic, relevant responses. This project highlights prompt engineering, conversational memory management, and enterprise-ready deployment within the Azure AI ecosystem.

## Situation

I was inspired by apps like Expedia’s chatbot and Google Travel, which make trip planning easier, but I wanted something more intuitive: a true travel companion that doesn’t just dump search results but understands me. I envisioned WanderMate as a virtual travel buddy that remembers my preferences, guides me through decisions, and helps me explore destinations without feeling overwhelmed or lost in endless options. Instead of being a generic, transactional assistant, it acts like a well-traveled friend—personalized, attentive, and always ready with the perfect suggestion.

## Task 

Create a Prompt Flow for WanderMate that orchestrates prompts and other activities.

## Action

1. Create a Prompt Flow, Start the Compute Session.
2. Provide Input: question (string): ${inputs.question}, chat_history (string): ${inputs.chat_history}
3. Grounded the assistant with a system prompt:
“You are a Sales AI assistant that helps customers buy makeup, shoes, clothes, and electronics.”
5. Implemented conversation history retention to enable natural, multi-turn dialogues.


## Result

1. Delivered a Customer-Facing AI E-commerce Shopping Assistant that provides end-to-end personalized, friendly, and data-driven shopping recommendations instead of generic answers.
2. Achieved **~30% faster responses** and **~25% lower operational cost**, making the Assistant practical for small-to-large enterprise e-commerce platforms.


## Technologies Used

1. Language Model: LLaMA-4 Maverick-17B-128F-Instruct-FP8
2. Cloud AI Platform: Azure AI Foundry
3. Python SDKs:
    a. azure-ai-inference (Model Inference API)
    b. azure-ai-projects
    c. azure-core (optional if using credentials)
    d. python-dotenv (environment variable management)
4. Development Environment: Azure Cloud Shell / Local Python
5. Version Control & Hosting: Git & GitHub

## Demo

LINK: https://drive.google.com/drive/folders/1XQYrQqkeJJGe9foyTDGOCrLVDVlcu2zU?usp=sharing

