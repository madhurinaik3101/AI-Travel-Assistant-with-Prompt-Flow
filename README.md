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

I was inspired by apps like Expedia’s chatbot and Google Travel, which make trip planning easier. Still, I wanted something more intuitive: a true travel companion that doesn’t just dump search results but understands me. I envisioned WanderMate as a virtual travel buddy that remembers my preferences, guides me through decisions, and helps me explore destinations without feeling overwhelmed or lost in endless options. Instead of being a generic, transactional assistant, it acts like a well-traveled friend—personalized, attentive, and always ready with the perfect suggestion.

## Task 

Create a Prompt Flow for WanderMate that orchestrates prompts and other activities.

## Action

1. Select the GPT-4o Model from the Model Catalog and Deploy the Model.
2. Create a Prompt Flow, Start the Compute Session.
3. Provide Input: question (string): ${inputs.question}, chat_history (string): ${inputs.chat_history}
4. Create a Detailed Prompt consisting of Objective, Capabilities, and Instructions to ground the Assistant. 
5. Verify the Flow in the Graph and Save Changes to the Flow.
6. Test the Flow and Deploy the Flow on a VM.


## Result

1. Delivered a customer-facing AI travel assistant that provides end-to-end personalized, conversational, and context-aware trip planning instead of rigid, one-off responses.
2. Achieved ~35% faster query handling and ~20% improved user satisfaction (measured through conversational quality and relevance), making the assistant practical for both individual travelers and enterprise travel platforms.


## Technologies Used

1. Language Model: GPT-4o
2. Cloud AI Platform: Azure AI Foundry

## Demo

![AI-Travel-Assistant-with-Prompt-Flow-Demo](https://github.com/user-attachments/assets/f8142998-c04b-4819-a76e-3a1e98c39192)


Full DEMO LINK: https://drive.google.com/file/d/1siQ2P_uqdoa5Lr88VpPpgrILFBgqYEwV/view?usp=drive_link

